# splide_mod

#### This is a slight modification of the splide library css part.
#### This makes it easier to change the colors of the slider arrows and pagination.

# cdn_links

//splide-mod-css

> <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Quickcoder2005/splide_mod@main/splide-mod.css"/>

//original-css

> <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@2.4.21/dist/css/themes/splide-sea-green.min.css"/>

# usage

#### Add these 2 lines of code in before mounting splide.
#### This set s the primary and secondary colors to your desired color.

> document.documentElement.style.setProperty('--primary', 'pink');
    document.documentElement.style.setProperty('--secondary', 'red');

# example

> window.onload = function(){
    document.documentElement.style.setProperty('--primary', 'pink');
    document.documentElement.style.setProperty('--secondary', 'red');
    new Splide( '.splide', {type: 'loop'}).mount();
    });
}
