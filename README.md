# Paper Framework
## Usage
To include in your project, place this in your `<head></head>` section.

```css
<link rel="stylesheet" type="text/css" href="paper.css" />
```

To ensure this works properly, you will need to also include Normalize.css.

```css
<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.0/normalize.min.css" />
```

## Modification
The following CSS variables can be modified. This includes font import.

```css
/* Include Google Fonts */
@import url('https://fonts.googleapis.com/css?family=Lato:100,100i,300,300i,400,400i,700,700i,900,900i');

/* Global Variables */
:root {
    --font: 'Lato', sans-serif;
    --main: #9B4DCA;
    --lightaccent: #D14BE1;
    --accent: #D747AA;
    --darkaccent: #7F4BE1;
    --dark: #1F1F1F;
    --grey: #CECECE;
    --lightgrey: #EAEAEA;
    --light: #FAFAFA;
}
```

