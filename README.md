# Grid-Caseira com SASS
 Criar um style grid simples e com menos recursos é muito mas funcional para projetos pequenos.
 
### Por quê?
 Sei que muitos desenvolvedores preferem utilizar os frameworks [Bootstrap](http://getbootstrap.com/) e o [Foundation](http://foundation.zurb.com/). Mas existem vantagens e desvantagens.
 Um exemplo de desvantagens é utilizar um desses frameworks em projetos pequenos onde você pode customizar um Grid de acordo com o seu projeto.
 Isso é muito divertido quando estamos falando do [SASS](http://sass-lang.com/).
 
 -----
### Exemplo Simples
É um style grid fluído com 100%. Se o seu layout tiver um grid de 940px, basicamente é inserir o valor na variável "**$container-max**"
e inserir o valor na classe "**container**".
``` 
  $container-max:940px;

   .container{
      width: $container-max;
   }
```
Com HTML é mais simple ainda.
```
<div class="container">
  <div class="column-4">Coluna de 4</div>
  <div class="column-4">Coluna de 4</div>
  <div class="column-4">Coluna de 4</div>
</div>
```


