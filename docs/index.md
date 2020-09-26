# hcw.css

O hcw.css é um microframework css feito com [sass](https://sass-lang.com/documentation/syntax), para baixar clique [aqui](https://gusleaooliveira.github.io/hcw/css/hcw.min.css).


Caso queira usar diretamente coloque esse código no `header`:

```html
<link rel="stylesheet" href="https://gusleaooliveira.github.io/hcw/css/hcw.min.css">
```

---

## Como usar
### Texto
#### Alinhamento de texto
```html
<p class="text-center">Texto alinhado ao centro</p>
<p class="text-left">Texto alinhado a esquerda</p>
<p class="text-right">Texto alinhado a direita</p>
<p class="text-justify">Texto justificado ... Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempore, voluptatem? Exercitationem voluptatem sint laboriosam accusantium laborum provident rerum! Maxime voluptatum necessitatibus sequi nam unde quas repellendus? Earum fuga esse a.</p>
```

<iframe src="examples/alinhamento-texto.html" height="200" width="600" title="Alinhamento de texto"></iframe>

#### Indentação de texto
```html
<p class="text-indent text-justify">Texto identado normal ... Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempore, voluptatem? Exercitationem voluptatem sint laboriosam accusantium laborum provident rerum! Maxime voluptatum necessitatibus sequi nam unde quas repellendus? Earum fuga esse a.</p>
<p class="text-indent-15 text-justify">Texto identado maior  ... Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempore, voluptatem? Exercitationem voluptatem sint laboriosam accusantium laborum provident rerum! Maxime voluptatum necessitatibus sequi nam unde quas repellendus? Earum fuga esse a.</p>
<p class="text-indent-25 text-justify">Texto identado maior ainda ... Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempore, voluptatem? Exercitationem voluptatem sint laboriosam accusantium laborum provident rerum! Maxime voluptatum necessitatibus sequi nam unde quas repellendus? Earum fuga esse a.</p>
```

<iframe src="examples/identacao-texto.html" height="300" width="700" title="Identação de texto"></iframe>

####    

#### Tamanho de texto
```html
<p class="text-tiny">Texto de exemplo <b>tiny</b></p>
<p class="text-small">Texto de exemplo <b>small</b></p>
<p class="text-medium">Texto de exemplo <b>medium</b></p>
<p class="text-large">Texto de exemplo <b>large</b></p>
<p class="text-xlarge">Texto de exemplo <b>xlarge</b></p>
<p class="text-xxlarge">Texto de exemplo <b>xxlarge</b></p>
<p class="text-xxxlarge">Texto de exemplo <b>xxxlarge</b></p>
<p class="text-jumbo">Texto de exemplo <b>jumbo</b></p>
```

<iframe src="examples/tamanho-texto.html" height="310" width="760" title="Tamanho de texto"></iframe>

### Cores

```html
<div class="grid column-3">
    <div class=" padding-10 ecru"><p>Cor: <b>ecru</b></p></div>
    <div class=" padding-10 gray-blue"><p>Cor: <b>gray-blue</b></p></div>
    <div class=" padding-10 white"><p>Cor: <b>white</b></p></div>
    <div class=" padding-10 silver-pink"><p>Cor: <b>silver-pink</b></p></div>
    <div class=" padding-10 baby-blue-eyes"><p>Cor: <b>baby-blue-eyes</b></p></div>
    <div class=" padding-10 light-blue"><p>Cor: <b>light-blue</b></p></div>
    <div class=" padding-10 cyan"><p>Cor: <b>cyan</b></p></div>
    <div class=" padding-10 aqua"><p>Cor: <b>aqua</b></p></div>
    <div class=" padding-10 light-green"><p>Cor: <b>light-green</b></p></div>
    <div class=" padding-10 lime"><p>Cor: <b>lime</b></p></div>
    <div class=" padding-10 khaki"><p>Cor: <b>khaki</b></p></div>
    <div class=" padding-10 amber"><p>Cor: <b>amber</b></p></div>
    <div class=" padding-10 orange"><p>Cor: <b>orange</b></p></div>
    <div class=" padding-10 light-gray"><p>Cor: <b>light-gray</b></p></div>
    <div class=" padding-10 gray"><p>Cor: <b>gray</b></p></div>
    <div class=" padding-10 pale-red"><p>Cor: <b>pale-red</b></p></div>
    <div class=" padding-10 pale-yellow"><p>Cor: <b>pale-yellow</b></p></div>
    <div class=" padding-10 pale-green"><p>Cor: <b>pale-green</b></p></div>
    <div class=" padding-10 pale-blue"><p>Cor: <b>pale-blue</b></p></div>
    <div class=" padding-10 blue-facebook"><p>Cor: <b>blue-facebook</b></p></div>
    <div class=" padding-10 blue-messenger"><p>Cor: <b>blue-messenger</b></p></div>
    <div class=" padding-10 blue-telegram-2"><p>Cor: <b>blue-telegram-2</b></p></div>
    <div class=" padding-10 green-whatsapp"><p>Cor: <b>green-whatsapp</b></p></div>
    <div class=" padding-10 raisin-black"><p>Cor: <b>raisin-black</b></p></div>
    <div class=" padding-10 tumbleweed"><p>Cor: <b>tumbleweed</b></p></div>
    <div class=" padding-10 eggplant"><p>Cor: <b>eggplant</b></p></div>
    <div class=" padding-10 dark-eggplant"><p>Cor: <b>dark-eggplant</b></p></div>
    <div class=" padding-10 indigo"><p>Cor: <b>indigo</b></p></div>
    <div class=" padding-10 blue"><p>Cor: <b>blue</b></p></div>
    <div class=" padding-10 green"><p>Cor: <b>green</b></p></div>
    <div class=" padding-10 deep-purple"><p>Cor: <b>deep-purple</b></p></div>
    <div class=" padding-10 red"><p>Cor: <b>red</b></p></div>
    <div class=" padding-10 pink"><p>Cor: <b>pink</b></p></div>
    <div class=" padding-10 purple"><p>Cor: <b>purple</b></p></div>
    <div class=" padding-10 teal"><p>Cor: <b>teal</b></p></div>
    <div class=" padding-10 deep-orange"><p>Cor: <b>deep-orange</b></p></div>
    <div class=" padding-10 blue-gray"><p>Cor: <b>blue-gray</b></p></div>
    <div class=" padding-10 brown"><p>Cor: <b>brown</b></p></div>
    <div class=" padding-10 dark-gray"><p>Cor: <b>dark-gray</b></p></div>
    <div class=" padding-10 blue-telegram"><p>Cor: <b>blue-telegram</b></p></div>
    <div class=" padding-10 blue-twitter"><p>Cor: <b>blue-twitter</b></p></div>
    <div class=" padding-10 blue-linkedin"><p>Cor: <b>blue-linkedin</b></p></div>
</div>
```

<iframe src="examples/cores.html" height="600" width="700" title="Cores"></iframe>

### 

---

# Criador

Olá me chamo Gustavo, e criei este material, para mais informações, clique nos links abaixo:

* [LinkTree](https://www.linktree.com.br/gusleaooliveira)


* Disponível em : [Repositório de exercícios](https://gusleaooliveira.github.io/posts/)

