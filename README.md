# AMPSPER

Casper Ghost theme modified to use [Google AMP](https://github.com/ampproject/amphtml)

Version: 0

# Installation

Create a new directory called ampsper, under /themes of your Ghost installation.

Activate theme from your settings.

# Adding custom style to your Ghost blog

Add the following section within your Ghost custom Header with the necessary format.

```html
<style amp-custom> </style>
```

and remove ref to the screen.css file.

# Future

0. In order to have amp-img and other custom tags, we may need to modify how Ghost outputs the .hbs files!
1. Skeleton theme for Arabic Content using custom fonts and RTL styling
