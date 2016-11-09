Website Performance Optimization portfolio project by Alex Twomey

Visit here to go to the homepage: https://alexanderwolf.github.io

and here to go to the pizzeria: https://alexanderwolf.github.io/views/pizza.html

to run locally, open index.html and views/pizza.html

Change Log

index.html

- Moved main CSS to minified internal style sheet
- Made print CSS style sheet only load when media is 'print'
- Made Google Analytics async and moved to top of body tag (as suggested by GA implementation docs)
- Image optimisation

pizza.html

- Converted main and bootstrap CSS to minified internal style sheet
- Image optimisation

main.js

- Dynamically calculating number of background pizzas using window.innerHeight
- Refactored the changePizzaSizes() function to reduce number of iterations made when executed and removed unnecessary functions and DOM manipulation