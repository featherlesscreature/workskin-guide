# Depths Formatting Guide
A commonly used formatting trick is using the 'linear-gradient' rule to transition to a black screen.
```css
#workskin .descent {
 width: 100%;
 background-image: linear-gradient(#f0f0f000, #000000ff);
 margin: 0;
 padding-bottom: 30%;
}
```
<div style="width: 100%; background-image: linear-gradient(#f0f0f000, #000000ff); margin: 0; padding-bottom: 30%;"></div>
This rule has a fair amount going on. The core of this effect is the `linear-gradient`, which renders a gradient between two colours.
Note that the transition is done from a transparent colour `#f0f0f000`, to black. This allows the gradient to transition from any colour. The second notable part of the effect is the padding. This can be made as large, or as small as appropriate.
<br><br>
Reversing the effect is as simple as changing the gradient to fade to transparent.


```css
#workskin .ascent {
 width: 100%;
 background-image: linear-gradient(#000000ff, #f0f0f000);
 margin: 0;
 padding-top: 30%;
}
```
<div style="width: 100%; background-image: linear-gradient(#000000ff, #f0f0f000); margin: 0; padding-bottom: 30%;"></div>
Combining the two gradients with an additional rule allows for a fade to black effect. Note that 1px of `padding-top` and `padding-bottom` is added. This prevents an ugly gap between the divs. A margin is also added to the `<p>` tag, as this stops the white text from melting into the white margin around it.
```css
#workskin .depths {
  width: 100%;
  background-color: #000;
  margin: 0;
  padding-top: 1px;
  padding-bottom: 1px;
  color: #ffffff;
}
#workskin .depths p {
  margin-left: 2px;
}
```

<div style="width: 100%; background-image: linear-gradient(#f0f0f000, #000000ff); margin: 0; padding-bottom: 30%;"></div>
<div style="width: 100%; background-color: #000; margin: 0; padding-top: 1px; padding-bottom: 1px; color: #ffffff;"> 
    <p style="margin-left: 2px;">Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos.</p>
</div>
<div style="width: 100%; background-image: linear-gradient(#000000ff, #f0f0f000); margin: 0; padding-bottom: 30%;"></div>