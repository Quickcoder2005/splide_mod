# splide_mod

#### This is a slight modification of the splide library css part.
#### This makes it easier to change the colors of the slider arrows and pagination.

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
