## viewport - adjust the width for different devides
```html
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

## box-sizing
When we add the padding or margin to the element, it makes the whole element bigger.
It also happens if we set with percentage, like 100%. The div will stretch out of the viewport. 
**Always set the box-sizing in the universal selector using an asterisk.** It works throughout the page.
```css
*, *::before, *::after {
    box-sizing: border-box;    
}
```

```css
.promo-card {
    width: 400px;
    height: 400px;
    padding: 25px;
    border: solid 5px #5035ff;
}
```
Once we add the box-sizing, the height and weight is set for the whole div.
```css
.promo-card {
    width: 400px;
    height: 400px;
    padding: 25px;
    border: solid 5px #5035ff;
    box-sizing: border-box;
}
```


