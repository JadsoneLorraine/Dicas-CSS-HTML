# Centralizando uma div:
##  HTML

```<div class="minhaClasse">
    <p>
        Texto de exemplo
    </p>
</div>```
```


## CSS

.minhaClasse {

width: 200px;

padding: center;

margin: auto;

background-color: red

}

p{
font-size: 48px;
}
@media screen and (max-width: 768px) {
p{
font-siza: 20px;
    }
}

O trecho a cima de CSS, só vai ser carregado se a resolução
for menos que 768.

##  HTML



 <section>
<div class="minhaClasse">
<p>Texto de exemplo</p>
</div>
<div class="minhaClasse">
<p>Texto de exemplo</p>
</div>
<div class="minhaClasse">
<p>Texto de exemplo</p>
</div>
</section> 

css
section{
display: flex;
flex-direction: row;
}
.minhaClasse {
width: 200px;
text-align: center;
margin: auto;
background-color: burlywood;
border-radius: 10px 0px 10px 0px;
border:solid 1px dashed;
}