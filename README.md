# Owl-carousel-example

## Documentaion officielle

https://github.com/smashingboxes/OwlCarousel2

## Astuce à savoir

- Bien appeler sont jQuery
- créer un fichier script.js indépendant
- remplir script.js avec:
    ```
    $(document).ready(function(){
    $('.owl-carousel').owlCarousel({
      [pleins d'options différentes... et surtout :]
      autoplay:true,
      autoplayTimeout:3000,
      })
    });
    ```