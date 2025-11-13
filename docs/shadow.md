# Text Shadow
The Text shadow CSS rule is exceptionally useful. The primary use is to add a shadow to text:
```css
#workskin .shadow {
 text-shadow: 1px 1px 0 #000000ff;
}
```
<p style="text-shadow: 1px 1px 0 #000000ff">Shadowed Text</p>

`text-shadow` has four settings, the x offset, the y offset, the intensity of the blur, and the color of the shadow. By default, the colour will be set to the colour of the text.
Additional shadows can be added, separated by commas.
```css
#workskin .shadow {
 text-shadow: 1px 1px 0 #000000ff, -1px -1px 0 #ff0000ff;
}
```
<p style="text-shadow: 1px 1px 0 #000000ff, -1px -1px 0 #ff0000ff">Shadowed Text</p>

## Additional Applications
### Glow
`text-shadow` can be used with a very high blur radius to give text the appearance of 'glowing'.
```css
#workskin .shadow {
 color: #ff0000ff;
 text-shadow: 0 0 1.5em;
}
```
<p style="color: #ff0000ff; text-shadow: 0 0 1.5em">Glowing Text</p>
### Outlines
By adding several `text-shadow` effects, text can be outlined.

```css
#workskin .outline {
 text-shadow: -1px -1px 0 #000000ff, 1px -1px 0 #000000ff,
     -1px 1px 0 #000000ff, 1px 1px 0 #000000ff;
 color: white;
}
```
<p style="text-shadow: -1px -1px 0 #000000ff, 1px -1px 0 #000000ff, -1px 1px 0 #000000ff, 1px 1px 0 #000000ff; color: white;">Outlined Text</p>

One small problem with this approach is that there are noticeable gaps in the text. This cannot be fully solved, however adding a small amount of blur helps lessen the issue.

```css
#workskin .outline {
 text-shadow: -1px -1px 1px #000000ff, 1px -1px 1px #000000ff,
     -1px 1px 1px #000000ff, 1px 1px 1px #000000ff;
 color: white;
}
```

<p style="text-shadow: -1px -1px 1px #000000ff, 1px -1px 1px #000000ff, -1px 1px 1px #000000ff, 1px 1px 1px #000000ff; color: white;">Outlined Text</p>