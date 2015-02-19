![ps](http://thiagohata.com.br/imgs_md/psd/photoshop_logo.jpg)


Alguns podem falar que é besteira, mas todas vezes seja um trabalho freelance ou um novo job sempre tem uma discussão como enviar o PSD. Organizar o .psd ajuda no trabalho em equipe e principalmente na agilidade.

Por isso criei esse guia, espero que me ajude como ajude outros profissionais.



#Como me enviar um PSD:


##Medidas:

Geralmente a primeira pergunta é qual a medida do arquivo .PSD

Depende

**Vai ser fluído (Responsive Design)?**

Você vai precisar criar um psd com diversas medidas diferentes layouts se adequando a cada resolução. Vou usar medidas padrões achadas em muitos frameworks.
	

Dispositivos 				| Tamanho |
-----------------------		| --------| 
iPhone 						| 320 px  | 
Extra Small Devices			| 480 px  | 	
Small Devices, Tablets		| 768 px  |
Medium Devices, Desktops	| 992 px  |
Large Devices, Wide Screens| 1200 px |

São medidas que o mercado encontrou. Mas não significa que precisa criar  se achar que precisa criar mais uma medida fique a vontade.

Muitas pessoas que trabalhei criam layouts maiores que 1200px, para simular os respiros laterais do site. 

Se vai trabalhar em paralelo com o FrontEnd ou seja em quanto desenvolve o layout o Front já vai desenvolvendo as interfaces prontas. Comece pelas medidas Mobiles assim fica mais fácil(A dificuldade está em diminuir o conteúdo e não em aumentar). E o seu FrontEnd vai ficar feliz, pois vai economizar boas linhas. 

**Não é  fluído(resposive design)?**

Pode ser 1200 px para monitores modernos ou 992px para monitores menores. 

## Nomes intuitivos as layers:


Nada mais chato você precisar identificar algo no PSD e se deparar com isso:

![bagunca](http://thiagohata.com.br/imgs_md/psd/layers_baguncadas.jpg)



Coloque nomes intuitivos nas layers:

![layers organziadas](http://thiagohata.com.br/imgs_md/psd/layers__organizadas.jpg)




## Organizar conceitualmente as layers em pastas:

O PSD começa a crescer e centenas de novas layers começam a aparecer, organize as layers do projeto em pastas:

![Layers pastas](http://thiagohata.com.br/imgs_md/psd/pastas_layers.jpg) 

**As vezes é preciso colorir. **



## Merge Layers

Pow, você é um DA um assistente o que seja, "Manja dos paranauê" criar aquele mega efeito, para o Front isso não importa. 

![merge exemplo](http://thiagohata.com.br/imgs_md/psd/merge.jpg)

Poucas as vezes o front vai precisar disso. 


De merge nas layers, ajuda com o peso do PSD e a organização das layer, o exemplo anterior ficaria assim:


![merge](http://thiagohata.com.br/imgs_md/psd/botao.jpg)  




##Padronize espaços

Padronizar espaços é  bom para o conforto das telas como aproximações de objetos baseados em Gestalt e facilitam muito a medição para o CSS.

Existe diversas formas para padronizar espaços os mais comuns são sistema de grids.

![grid 12](http://thiagohata.com.br/imgs_md/psd/grid__12.jpg)

Existem grids de 12 colunas, 24 colunas entre outros, você pode montar o grid conforme o projeto.

Existe um plugin para Photoshop que ajuda muito nessa tarefa [GuideGuide](http://guideguide.me/)

## Crie um guia de UI ELEMENTS

Se o projeto é pequeno ou um "pastel" bem provável que você não vai criar ou não vai ter tempo.

Caso o projeto seja grande e você trabalhe com uma equipe grande de desenvolvedores CRIE UI ELEMENTS

Se você fizer um guia de UI-ELEMETS nem precisa se atentar tanto aos próximos tópicos.

![ui elements](http://thiagohata.com.br/imgs_md/psd/ui.jpg)

UI elements(Elementos de interface) podem conter:

- Grids usados    
- Paleta de cores 
- Títulos H1 à H6 
- Links 
- Elementos da Interface (essencial)
- Interação Mouse Over, Active, Focus
- Botões
- 

 
 Um bom UI Elements deve evoluir para um bom [style guide](http://tableless.com.br/guia-de-estilos/)
  

## Fontes que não são do Sistema

Não existe nada mais chato que abrir um psd com erro de fontes, ae parar tudo que está fazendo e ter que ir atrás da fonte. 

Depois de um tempo você descobre que o Diretor de Arte usou uma fonte de uma biblioteca particular dele que é mega rara. 

Junto com o projeto crie uma pasta fonts.

![fonts](http://thiagohata.com.br/imgs_md/psd/fonts.jpg)

E coloque as fontes que foram usadas no projeto. 

Caso esteja usando [google fonts](https://www.google.com/fonts/), não esqueça de enviar o link da fonte usada.


**Caso não seja google fonts:** 

Na web não usamos a fonte apenas um formato. Usamos quatro formatos .ttf .otf .woff e .svg

Existe programas e sites que ajudam muito nessa tarefa de converter fontes para outros formatos.

**Mac OSX:**

[Font Prep:](https://github.com/briangonzalez/fontprep) Basta arrastar e soltar que ele faz o resto.


**Online:**

[Fontsquirrel](http://www.fontsquirrel.com/tools/webfont-generator)




## Interações do Layout

Caso tenha feito um UI ELEMENT pode ser inserido nele.

Muito chato quando não existe um ui elements e abro o psd e está organizado mas não possui nenhum tipo de interação. Você vai conversar com o D.A e as vezes o cara está alocado em outra tarefa e vai te dar uma resposta do tipo: "Ahh faz um efeito lá mudando de cor".


Você ajuda o cara muda e em determinada etapa do projeto o D.A vê e te olha torto e pede pra mudar, e lá vai você mudar.

Caso o projeto seja pequeno o rápido crie no própio .PSD


![hover](http://thiagohata.com.br/imgs_md/psd/btn_hover.jpg)

**Usei uma cor diferente para destacar e usei :hover para mostrar o efeito**


##Fundos grandes e repetitivos

Evite usar backgrounds grandes e pesados, quando não tiver outra opção salve o arquivo separadamente e envie separado do .psd 

Viu que o **pattern** se repete então salve apenas o pattern como o fundo separadamente.


## Ícones

**O ícone pode ser mais genérico e não precisa ficar exato em todos os browsers?**

Infelizmente usar ícones como fontes optimiza o site mas ele pode ficar diferente 
dependendo do navegador 1px pra direita em um, um 1px a esquerda em outro.

Use um serviço de fontes para ícones.
[icomoon:](https://icomoon.io/)


**Não tem como usar ícone com fonte**

Ok. Sem problemas. Mas ter que sair caçando ícone pelo .PSD pode ser uma tarefa demorada. Todo ícone utilizado guarde em uma pasta junto com o projeto **ICONES**
e salve os ícones já cortados. Evite o .png caso necessite de um fundo transparente e tenha poucas cores use .png8 


## Plugins Legais Photoshop

[LAYRS CONTROL:](http://madebyvadim.com/layrs/) Ajuda a organizar as layers do seu projeto. Como Merge e cortar.

[Velositey:](http://dandkagency.com/extensions/velositey/)Muito bom para prototipação.

[GuideGuide](http://guideguide.me/) Criar Guides de forma fácil.

[Specctr:](https://www.specctr.com/products.php) Muito bom para mostrar informações de espaço, tamanho de fontes, cores... 