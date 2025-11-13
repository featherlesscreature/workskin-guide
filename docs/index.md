# Workskin Guide
This guide seeks to explain the basics of ao3 Workskins, and provide guides for specific formatting techniques, with a heavy focus on formatting used for Undertale/Deltarune fics.
<br>
Archive of Our Own formats works with [HTML](https://www.w3schools.com/html/default.asp). As a part of this, it allows users to use [CSS](https://www.w3schools.com/css/default.asp) to add custom styles using workskins.
## Creating a workskin
To create a workskin, click on the 'skins' button on the sidebar. Then, click on the 'My Work Skins' button and click 'Create Work Skin'. From here, you can add your very own CSS rules. To attach a workskin to a work, scroll down to 'Associations' in the Fic creation/edit menu. There will be a box called 'Select work skin'. Click on it, then select your desired skin from the drop down.

## Basic Formatting
CSS rules are added as classes, like so:
```css
#workskin .your-class {
   /* Rule Goes here */
}
```

To apply the rule to your work, simply set the class of any of the tags you wish to be formatted to 'your class'.

```html
<p class="your-class">Text formatted with your class!</p>
```

### Text Highlighting
Highlighting text is one of the most common techniques used. It can be done quite easily.

```css
#workskin .red {
 color: #ff0033ff;
}
```

Then, within the HTML of your work, simply wrap the text you wish to highlight in a 'span' tag.

```html
<span class="red">Highlighted Text</span>
```

<p style="color: #ff0033ff;">Highlighted Text</p>

## Types of spacing.
CSS provides several distinct types of spacing.
<table>
 <tr>
   <th>Name</th>
   <th>Explanation</th>
 </tr>
 <tr>
   <th>Pixel (px)</th>
   <th>Represents one single pixel on the screen.</th>
 </tr>
 <tr>
   <th>Percentage (%)</th>
   <th>Relative to the size of the parent element</th>
 </tr>
 <tr>
   <th>em</th>
   <th>Relative to font size</th>
 </tr>
 <tr>
   <th>rem</th>
   <th>Relative to the font size of the root html element</th>
 </tr>
</table>

## Note on Compatibility and Accessibility
While it is not possible to make your formatting work for every single person, it is still important to consider accessibility. A large number of people read on mobile phones, so your fic should almost always be tested on mobile. Also try to consider site skins, as these can affect the readability of certain elements, such as coloured text. All guides listed should work on all major platforms and browsers, unless otherwise specified.

## Testing your Formatting
If you are on a computer, you can check how your Work Skin will look on mobile by pressing `ctrl+shift+m` on most browsers.
<br><br>
Often, you will want to view how your formatting looks, without dealing with ao3. The simplest way to do this is to test within a draft, however this is both inconvenient and inelegant.
It is possible to create a [sandbox](./local-testing.md), which allows you to see how your formatting will look locally.
