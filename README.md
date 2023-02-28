notas de estudo/ revisão:
HTML:
<!-- A tag DOCTYPE serve para informar ao navegador qual versão do HTML estamos usando. -->
    <!-- A tag <html>, que marca o conteúdo a ser renderizado no navegador -->
    A tag <!DOCTYPE> serve para informarmos para o navegador qual a versão do HTML estamos usando.
    A tag <head> serve para informarmos para o navegador que informações ele deve ler. E A tag <body> serve para informarmos ao navegador quais informações ele deve exibir.

    tags semânticas fazem com que o navegador entenda melhor o nosso conteúdo,
    A tag <html> serve para informarmos para o navegador onde começa e termina o nosso código.
    
    sempre criar um h1 para colocar o titulo da página, mesmo se ele for uma logo.
    <!-- Se algum usuário que não entende português estiver lendo nossa página, o navegador vai oferecer a opção de traduzir. -->
    <!-- O nome da tag é meta, ela passa informações para o navegador. -->
    <!-- por que é importante utilizar o charset="UTF-8"? É preciso apontar para o navegador que estamos usando um dicionário que tenha acentos e cedilha, sinais gráficos comuns na língua portuguesa. -->
    <!-- qual sera a folha de estilo -->
    <!-- usa a tag link porque é a linkagem com esse arquivo com outro -->
        <!-- O caractere : serve para atribuir um valor a uma propriedade. -->
    <!-- Na estrutura correta do HTML, inserimos as informações que queremos passar para o navegador no head e as tags de conteúdo no body. -->
    <!-- CSS, que em uma tradução seria folha de estilo em cascata. Quando vamos em um elemento anterior, ele reflete para todos os elementos que estão abaixo. -->
    <!-- Tamanho padrao da font do navegador é 16 pixels.  -->

    É errado adicionar as palavras todas em maisculo no html, por isso exite uma tag chamada text-transform que faz alterações com o tipo da palavra (maiusculi,minusculo)
    A melhor maneira de centralizarmos o vídeo é criar uma <div> que envolverá todo o <iframe>, isto é, será a mãe desse conteúdo e terá a classe video.

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
    
    Para deixar uma lista na horizontal basta usar o display inline. E usar um espaçamento com margin
    position static = padrão
    position relative = possivel alterar sua posição (com top, bottom, left, right) 
    position absolute = faz que o elemente seja "independente" e ele pode sai de ordem de onde ele permanecia, e foi para frente, e onde ele estava foi para atrás.
    info: quando a tag não permacer na ordem que foi inserido na html, é recomendado utilizar a tag absolute.
    !quando se utiliza o absolute, lembra que ele nn vai respeitar nada de seu pais como o pading e a margin, 
    por isso que seu pai precisa ser tranquilo com seu filho, que seja relativo, dai o filho vai obdecer as medidas do pai!
    
    */


No time do Front-end:
   1. Alguém responsável pela usabilidade do site.(A usabilidade é responsável por responder como vai entregar aquelas informações, a forma.)
   2. O time da interface do usuário.( que vai pegar a forma como aquilo vai ser feito e vai dar o visual para aquilo.)
   3.Temos o codificador, aquele desenvolvedor front end. (Que vai pegar o design, a forma como o site foi apresentado com aquele visual e vai transformar em código para web, para um aplicativo ou para algum sistema.)


   resumo do que vimos na aula
   A criar um formulário HTML
    A tag que o representa é a <form>
    A tag <input>, para a entrada de dados do usuário
    A criar uma etiqueta para o input, com a tag <label>
    A conectar um input com o seu label
    Colocamos um id para o input e associamos esse id ao atributo for do label
    Alguns tipos de input, como text e submit
    Que label possui o display inline e o input possui display inline-block

    O textarea, para entradas de texto de mais de uma linha
    O input do tipo radio
    Como agrupar vários input do tipo radio, impedindo que mais de um input seja selecionado
    O input do tipo checkbox
    Que podemos criar um input dentro de um label, assim associando-os
    Mais estilizações para a nossa página
    Como funciona a hierarquia no CSS
    O select, que é seletor, um campo de seleção de um item, e o option, que representa cada opção do seletor

    Alguns tipos de inputs para celular: email, tel, number, password, date, datetime, month e search
    Como não permitir que um campo não seja preenchido, através do atributo required
    Como exibir uma sugestão de preenchimento para os campos, através do atributo placeholder
    Como deixar uma opção marcada por padrão nos nossos input radio e checkbox, através do atributo checked
    Como estruturar melhor o nosso código com fieldset (
        A primeira é a divisão, quando temos um campo e um texto, ou vários campos referentes a alguma coisa, não usamos a tag div, usamos a tag fieldset. Ela é referente à configuração de um ou mais campos referentes a um assunto específico.Quando, por exemplo, eu tenho o preenchimento dos dados de um cartão de crédito. Todos os dados referentes àquele cartão podem estar dentro de um fieldset.
    ) e legend (
        . E dentro de um fieldset não temos parágrafos, nós temos o título, e o título de um fildset é chamado de legend.
    )
    Como adicionar uma alternativa à imagem, descrevendo-a, com o atributo alt


    Utilizamos a propriedade transform: scale() para aumentar um elemento proporcionalmente.

    Utilizamos a tag <tr> para marcar uma linha de uma tabela Table row.
    As tags <thead>, <tbody> e <tfoot> ajudam a deixar o conteúdo da tabela mais bem dividido e mais semântico.
    propriedade colspan=X, onde X é o número de células que você quer agrupar.

Portanto, em uma tabela de 5 colunas, para ter uma célula única na linha, usamos um código assim:

        A criar uma tabela HTML
        A tag table, que representa a tabela
        A tag tr, que representa a linha da tabela
        A tag td, que representa a célula da tabela
        A tag thead, que representa o cabeçalho da tabela
        A tag tbody, que representa o corpo da tabela
        A tag th, que representa a célula do cabeçalho da tabela
        A tag tfoot, que representa o rodapé da tabela

        A diferença entre <div> e <section> é que no primeiro caso, trata-se apenas de uma divisão visual. Já no caso da <section> teremos uma divisão por conteúdo complexo, semanticamente homogêneo.
        Só devemos usar <section> quando o bloco for semântico.Para um bloco onde o conteúdo tenha o mesmo significado, o mesmo sentido, usamos uma <section>.

        class e id:  No universo HTML e CSS, ao falarmos de estilo, usamos uma classe, quando falamos de comportamento, usamos o identificador. A força da classe não é tão grande, então ela pode ser sobrescrita e seu estilo alterado, por isso é importante em CSS sempre utilizarmos classes, assim criamos um padrão em nosso código, o que é fundamental.

    Se quisermos que a fonte de titulo-principal seja o dobro da fonte padrão, independe do tamanho dessa fonte padrão, utilizamos a medida em, a media proporcional para pixels. Se quisermos duas vezes o tamanho base (15 pixels), basta escrever 2em.
        Incluiremos uma margem de 0 0 1em. É sempre interessante inserir um espaçamento que seja proporcional ao tamanho da fonte, o que facilita a leitura do usuário.

         uma forma de posicionar e tratar elementos: o float, em tradução livre "flutuação". Quando utilizamos este recurso,o elemento "descola" da página mas o que seria a sua sombra, continua sendo ocupada virtualmente, isto é, o texto respeita esse espaço ocupado.
         O float é um recurso que altera completamente a estrutura da página, todos os elementos abaixo do float passam a ser afetados por ele. Podemos criar uma "barreira" que delimitará seu alcance na página.
         De volta a style.css em titulo-principal, adicionaremos a propriedade clear que "limpa" o float que está posicionado à esquerda.
         Tanto o float:left quanto o float: right servem para que o elemento se destaque na tela, deixe de ocupar o espaço em que estava, para que os outros elementos possam se posicionar ao redor dele