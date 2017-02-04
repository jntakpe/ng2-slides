# Binding

* Toutes les propriétés du DOM accessibles
* L'interpolation est du sucre syntaxique sur du binding de propriété
* Sensible à la casse
* Fonctionne avec les webcomponents

Par exemple 


``<h1>{{titre}}</h1>`` 


équivaut à  


``<h1 [textContent]="titre"></h1>``
