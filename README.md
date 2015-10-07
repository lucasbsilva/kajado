# Biblioteca Kajado 1.6

Cada projeto é único, todos com suas diferenças e similaridades, e a ideia do **Kajado** é dar a possibilidade de total personalização dos componentes, muito além das bibliotecas atuais, com o kajado você é quem cria os componentes que necessita.

Estilo Fluente
-----------------

Utilizando o conceito de estilo fluente, voce carrega apenas o css que realmente vai usar, e isso evita importar uma folha de estilo enorme por causa de apenas um estilo, Alem de deixar sua folha de estilo muito mais descritivel, personalizada e reutilizavel

Sem Estilo fluente
```css
    <style>
        .component {
            text-align: center;
            font-size: 14px;
        }
    </style>

    <div class="component">
    </div>
```

Com Estilo fluente
```css
    <style>
        .text-center {
            text-align: center;
        }
        
        .font-size-14 {
            font-size: 14px;
        }
    </style>

    <div class="text-center font-size-14">
    </div>
```


Iniciando
-----------------

Para começar a usar o Kajado, acesse <http://kajado.github.io/> e obtenha a documentação completa e exemplos que precisa.


Compatibilidade
-----------------

O Kajado foi testado nos navegadores:

* IE 8+
* Firefox, Chrome, Safari, opera
* Android 2.x


Licença
-----------------

Você pode usar para fins pessoais e comerciais, modificar e melhorar, pedimos apenas a gentileza de divulgar, quanto mais desenvolvedores utilizando, mais contribuições teremos! 
Leia a licença completa [clicando aqui](https://github.com/kajado/kajado/blob/master/LICENSE)

