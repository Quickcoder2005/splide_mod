# splide_mod

#### This is a slight modification of the splide library css part.
#### This makes it easier to change the colors of the slider arrows and pagination.

# cdn_links

```
//splide-original-js

<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@2.4.21/dist/js/splide.min.js"></script>

//splide-mod-css

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Quickcoder2005/splide_mod@main/splide-mod.css"/>

//splide-original-css

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@2.4.21/dist/css/themes/splide-sea-green.min.css"/>
```

# usage

#### Add these 2 lines of code in before mounting splide.
#### This sets the primary, secondary and tertiary colors to your desired color.
#### If you don't change any of the primary, secondary or tertiary color using the code below, it will have the default color.

> document.documentElement.style.setProperty('--primary', YOUR_DESIRED_COLOR);
    document.documentElement.style.setProperty('--secondary', YOUR_DESIRED_COLOR);

# example

> window.onload = function(){
    document.documentElement.style.setProperty('--primary', YOUR_DESIRED_COLOR);
    document.documentElement.style.setProperty('--secondary', YOUR_DESIRED_COLOR);
    document.documentElement.style.setProperty('--tertiary, YOUR_DESIRED_COLOR);
    new Splide( '.splide', {type: 'loop'}).mount();
    });
}
