# Paper Framework
## Usage
To ensure this works properly, you will need to also include Normalize.css.

```css
<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.0/normalize.min.css" />
```

To include in your project, place this in your `<head></head>` section.

```css
<link rel="stylesheet" type="text/css" href="paper.css" />
```

## Modification
The following CSS variables can be modified. This includes font import.

```css
/* Import Google Fonts */
@import url('https://fonts.googleapis.com/css?family=Lato:100,100i,300,300i,400,400i,700,700i,900,900i');

:root {
    /* Fonts */
    --mainFont: 'Lato', sans-serif;

    /* Colours */
    --mainColour: #9B4DCA;
    --secondaryColour: #D14BE1;
    --accentColour: #D747AA;
    --lightShade: #FAFAFA;
    --neutralShade: #CECECE;
    --darkShade: #1F1F1F;
}
```

