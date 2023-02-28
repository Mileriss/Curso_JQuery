# Como inserir o JQuery na página  
O JQuery não é utilizado dentro do documento de Javascript, ele é utilizado e renderizado diretamente na página HTML
Por conta disso, existem 2 formas de utilizar o JQuery:  
- Inicio do ***body***  
- Final do ***body***  

## Inicio do Body
Para utilizar o JQuery no inicio é necessário utilizar uma função anonima (Arrow Function) ou uma função normal (Function) e inserir o comando ***ready***

***Sintaxe:***
### Arrow Function (Inicio da página)  
<pre>
$(document).ready(()=>{  
    Aqui vai o conteudo JQuery da página  
})
</pre>
    
### Function (Inicio da página)  
<pre>
$(document).ready(funcao)

function funcao(){
    Aqui vai o conteudo JQuery da página
}
</pre>

### Tag Script (Final da página)    
<pre>
< script >
    Aqui vai o conteudo JQuery da página
< / script >

</pre>

