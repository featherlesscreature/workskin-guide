# Adding custom fonts
Adding a custom font is simple, simply add a new css rule to your workskin.
```css
#workskin .my-font {
 font-family: 'Font Name Here'
}
```
## Fallback Fonts
As it is not possible to ensure that a given font is installed on all systems, it is usually a good idea to specify several backup fonts. This can be done by adding additional font families. For example, ao3 itself uses the following fonts as its fallback:
```css
'Lucida Grande', 'Lucida Sans Unicode', Verdana, Helvetica, sans-serif, 'GNU Unifont';
```


### A Cautionary Tale
When specifying fallback fonts, it is generally a good idea to make sure that the fallbacks match the spirit of the original font. However, please make sure that your fonts are readable. The official undertale workskin uses the following rule:
```css
#workskin .comicsans {
 font-family: 'comic sans ms', 'comic sans', 'chalkboard se', 'chalkboard', cursive;
}
```
As you can see, cursive is set as the final fallback. None of the fonts except cursive are commonly installed on all devices, which means cursive is often used.
<p style="font-family: 'Cursive'">Cursive looks like this.</p>
This tends to make text difficult to read, especially on phones, where most fonts are unlikely to be installed. Ultimately, while being fancy with formatting is fun, in situations like these, where there isn't a good solution, it is usually best to fall back to the default.


A rule that only changes the font if a suitable candidate is found, and otherwise looks identical to the default:
```css
#workskin .comicsans {
 font-family: 'comic sans ms', 'comic sans',
 'chalkboard se', 'Lucida Grande', 'Lucida Sans Unicode',
 'Verdana', 'Helvetica', 'sans-serif', 'GNU Unifont';
}
```
