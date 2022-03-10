# Objetivos

1-`Apresentar o conceito de prototipos e cadeia de protótipos`

2-`Apresentar a estrutura de classes em Javascript`


## Protótipos (Protype)
São basicamento o esqueleto dos objetos.
`Todos os objetos Javascript herdam propriedades e métodos de um prototype.`
`O objeto Object.prototype está no topo desta cadeia.`

Para visualizar os metodos do prototype basta entrar no devtools do navegador e chamar um objeto ou array.


[CADEIA-DE-PROTOTIPOS] (Prototype Chain)
A cadeia de prototipos vai percorrer todo o proto ate o prototype chegar a null caso nao ache o metodo.

Crow->Bird->Animal.Constructor->Function->Function.prototype.constructor->Object(){}->Object.prototype =null;


## Classes

Classes nao existem nativamente
Oquer ocorre é que sempre usamos objetos.E qualquer herança sera tratado nativamente como objeto.

`Syntatic Sugar`: Uma sintaxe feita para facilitar a escrita


Javascript não possui classes nativamente.Todas as classes são objetos e a herança se dá por prototipos.