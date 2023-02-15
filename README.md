notas de estudo/ revisão:
HTML:
<!-- A tag DOCTYPE serve para informar ao navegador qual versão do HTML estamos usando. -->
    <!-- A tag <html>, que marca o conteúdo a ser renderizado no navegador -->
    <!-- Se algum usuário que não entende português estiver lendo nossa página, o navegador vai oferecer a opção de traduzir. -->
    <!-- O nome da tag é meta, ela passa informações para o navegador. -->
    <!-- por que é importante utilizar o charset="UTF-8"? É preciso apontar para o navegador que estamos usando um dicionário que tenha acentos e cedilha, sinais gráficos comuns na língua portuguesa. -->
    <!-- qual sera a folha de estilo -->
    <!-- usa a tag link porque é a linkagem com esse arquivo com outro -->
        <!-- O caractere : serve para atribuir um valor a uma propriedade. -->
    <!-- Na estrutura correta do HTML, inserimos as informações que queremos passar para o navegador no head e as tags de conteúdo no body. -->
    <!-- CSS, que em uma tradução seria folha de estilo em cascata. Quando vamos em um elemento anterior, ele reflete para todos os elementos que estão abaixo. -->
    <!-- Tamanho padrao da font do navegador é 16 pixels.  -->

CSS:
    /* Como é uma folha de estilos em cascata, a cascata vai descendo, e o que eu faço no elemento pai reflete para o elemento filho. */
    /* cores em hexadecimal: 0123456789ABCDEF 
    RGB = Red Green Blue
    0 = ausência
    F = maximo
    # _ _ _ _ _ _
    os dois primeiro underlines são para o vermelho, depois para o verde e depois para o azul
    se colocar tudo #FFFFFF a cor vai ser branco
    se colocar tudo #000000 a cor vai ser preto
    
    cores com rgb:
    RGB 0,1,2,3,4...255 
    0 = ausência
    255 = máximo
    rgb(0,255,255)
    
    Como ajustar o espaçamento interno do elemento, através da propriedade padding
    Como ajustar o espaçamento externo do elemento, através da propriedade margin
    
    O comportamento de uma tag ocupar a largura inteira da página é chamado “block”. Ele bloqueia o conteúdo daquela linha. Todos os itens (li) da nossa linha têm o comportamento block. 
    Uma imagem não bloqueia o conteúdo, ela deixa que existam outros na lateral, e esse tipo de conteúdo é considerado inline.
    A diferença entre eles é que mesmo que eu diminua o tamanho, diminua a largura de um elemento block, ele vai sempre ocupar aquela linha, mesmo preenchendo só metade.
    Um elemento inline não me deixa alterar, por exemplo, o espaçamento externo e interno dele.
    Mas existe uma terceira característica, quando o elemento possui as duas condições. Ele é inline e block ao mesmo tempo. Ou seja, ele bloqueia uma largura, mas essa largura é fixa. Sou eu que dou o tamanho. E ele me deixa também mexer na largura e nos espaçamentos interno e externo.
    Ao fazer o comando de inline-block, os elementos são alinhados pela linha de baixo e queremos sejam alinhados pela linha de cima.Para isso, só adicionar a tag “vertical-align: top” (Faz com que os elementos sejam alinhados verticalmente para cima (como se fosse um align-self) ).
    */

No time do Front-end:
   1. Alguém responsável pela usabilidade do site.(A usabilidade é responsável por responder como vai entregar aquelas informações, a forma.)
   2. O time da interface do usuário.( que vai pegar a forma como aquilo vai ser feito e vai dar o visual para aquilo.)
   3.Temos o codificador, aquele desenvolvedor front end. (Que vai pegar o design, a forma como o site foi apresentado com aquele visual e vai transformar em código para web, para um aplicativo ou para algum sistema.)