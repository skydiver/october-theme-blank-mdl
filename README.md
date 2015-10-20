# Blank-Material-Design-Lite
A blank theme for [OctoberCMS](https://octobercms.com/) with [Material Design Lite](http://www.getmdl.io/) framework.


## Installation
`$ php artisan theme:install martin.blank-mdl <theme>`

Replace `<theme>` with the name of your theme.


## Using the theme
`$ php artisan theme:use <name>`

Where `<name>` is whatever you specified in `theme:install`.


## Framework Documentation
First, you can check the available [components](http://www.getmdl.io/components/index.html) and [styles](http://www.getmdl.io/styles/index.html).

## Customize
You can customize the colors palette with the [Theme Builder](http://www.getmdl.io/customize/index.html).

Open template file and replace the next line with the new css:

```html
<link rel="stylesheet" href="{{ ['assets/css/material.teal-red.min.css', 'assets/css/styles.css']|theme }}">
```

Alternatively, you can point to the generated CSS file hosted on Material Design Lite CDN:
```html
 <link rel="stylesheet" href="https://storage.googleapis.com/code.getmdl.io/1.0.5/material.indigo-purple.min.css" /> 
```
