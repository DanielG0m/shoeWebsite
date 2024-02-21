# Video de referencia

<iframe width="560" height="315" src="https://www.youtube.com/embed/oWmOqxIanjk?si=5-d7lzG1Y7dDdOUq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# form
Contenedor de varias etiquetas de ingreso de datos tales como:
<input type="text">	 Displays a single-line text input field


<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable button 


# nth-child
Seleccionar varios elementos hijos de la clase indicando su posición, según un argumento o fórmula.

ejemplo en listas

 ul li:nth-child (3) { color: red; }


# >
Combinadores
El último grupo de selectores combina otros selectores con el fin de delimitar elementos de nuestros documentos. El ejemplo siguiente selecciona los párrafos que son hijos directos del elemento <article> utilizando el operador de combinación hijo (>):

CSS

article > p {
}


# json

const menu = document.querySelector(".menu");
const menuBtn = document.querySelector(".menu-btn")

//Open|Close menu functionality
menuBtn.addEventListener("click", () => {
    menu.classList.toggle('nav-toggle');
});