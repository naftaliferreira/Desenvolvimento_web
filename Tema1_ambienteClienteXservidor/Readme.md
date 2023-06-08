<h1>O ambiente web Cliente X Servidor e as tecnologias</h1>

<em>Este módulo resume as tecnologias html, css, Javascript e PHP de forma prática, ou seja, as tecnologias básicas que compõem o ambiente web</em>

<p>O modelo Cliente X Servidor, foi criado pela Xerox, como forma de separar dados e recursos de processamento. Tomando como exemplo uma rede de computadores de uma empresa, em que temos máquinas exercendo a função de servidores, provendo serviços como armazenamento de arquivos ou dados, impressão, email etc. E máquinas exercendo o papel de clientes, consumindo os recursos oferecidos pelos servidores.</p> 

<strong>Exemplo:</strong>
</br>

<p><img alt="Exemplo para cliente x servidor usando rede interna" 
src="/midia/rede_interna.png" /></p>

<h2>Aplicações no modelo Cliente X Servidor</h2>

<p>Através desse modelo foi possível o desenvolvimento de aplicações que fizessem uso de sua <strong>arquitetura distribuida</strong>. Estas aplicações foram desenvolvidas tendo como base o conceito de desenvolvimento em camadas. Logo surgiram os modelos de duas, três e quatro (ou N) camadas.</p>
</br>
<h3>Modelo de duas camadas</h3>

Neste modelo temos as camadas cliente e servidor, sendo função da primeira tratar da lógica do negócio e fazer a interface com o usuário, enquanto a segunda é responsável por tratar os dados. Normalmente fazendo uso de <strong>Sistemas Gerenciadores de bancos de Dados</strong>. 
*São exemplos desse modelo as aplicações desktop instaladas em cada computador cliente que se comunica com um servidor na mesma rede.*

<strong>Exemplo:</strong>
</br>
<p><img alt="Modelo de duas camadas" src="/midia/modelo_duas_camadas.png" /></p>
</br>

<h2>Modelo de três camadas</h2>

<p>Esse modelo foi criado para resolver alguns problemas do modelo anterior, entre eles a necessidade de reinstalação/atualização da aplicação nos clientes a cada mudança de regra ou lógica.Logo, foi incluída uma camada a mais. a <strong>camada de aplicação</strong> com isso, a responsabilidade de cada camada ficaram assim divididas:</p>
</br>
<ul>
    <li>Camadas de apresentação</li>
        <ul>Representado pela aplicação instalada na máquina do cliente. É responsável pela interface com o usuário e passou a acessar o servidor de aplicação, perdendo acesso direto ao servidor de dados.</ul>
    <li>Camadas de aplicação</li>
        <ul>Representado por um servidor responsável pela lógica e pelas regras de negócio, assim como pelo controle de acesso ao servidor de dados</ul>
    <li>Camada de dados</li>
        <ul>Representado pelo servidor responsável pelo armazenamento dos dados</ul>
<u/l>

</br>
<strong>Exemplo:</strong>
</br>
<p><img alt="Modelo de tres camadas" src="/midia/modelo_tres_camadas.png" /></p>
</br>

<h2>Modelo de quatro camadas</h2>

<p>Outro grande avanço obtido nesse modelo foi <strong>tirar da máquina cliente a responsabilidade pela interface com o usuário,</strong> passando a centralizá-las em um único ponto, normalmente em um servidor web. Com isso, no lugar de aplicações instaladas em cada máquina cliente, passamos a ter os clientes acessando as aplicações hospedadas em servidores web a partir de navegadores. Neste modelo; a divisão de responsabilidades ficou da seguinte forma:</p>

<ul>
    <li>Cliente</li>
        <ul>Passou a precisar apenas de um navegador para ter acesso à aplicação.</ul>
    <li>Servidor</li>
        <ul>Composto pode três servidores, o de aplicações, o de dados e o web, sendo este o último responsável pela apresentação/interface com o usuário cliente.</ul>
</ul>
</br>
<strong>Exemplo:</strong>
</br>
<p><img alt="Modelo de quatro camadas" src="/midia/modelo_quatro_camadas.png" /></p>
</br>

<h2>Ambiente web</h2>

<p>Inicialmente as aplicações ficavam hospedadas dentro de uma rede interna, onde estavam tanto os clientes quanto os servidores. Posteriormente, eles migraram para a internet, surgindo então o <strong>ambiente web</strong>, cuja base é justamente prover aos clientes, usuários, o acesso a várias aplicações a partir de diversos dispositivos, como navegadores desktop e smartphones ou apartir de aplicações mobile.</p>

<h2>Comunicação no ambiente web</h2>

<p>A comunicação neste ambiente, é feita sobre a internet, com o uso dos seus protocolos de comunicação, sendo o principal o protocolo <strong>HTTP</strong>(HyperText Transfer Protocol), que é um protocolo para transferência de hipertexto. Na imagem seguinte, podemos ver um exemplo de comunicação no ambiente web.</p>

<p><img alt="Exemplo comunicação em ambiente web" src="/midia/comunicacao_ambiente_web.png" /></p>

<h2>Ambiente Cliente X Servidor</h2>

<h3>Solicitação e resposta</h3>

<p>O processo de comunicação no ambiente web é conhecido como solicitação (request) e resposta (response). Normalmente a solicitação é iniciada pelo cliente, mas também é possível que o servidor a inicie, como em serviços PUSH</p>
<i>Serviços que disparam notificações/mensagens para os clientes que fizeram opção de recebê-las.</i>

<p><img alt="Processo solicitação (request) e resposta (response)" src="/midia/request_response.png" /></p>

<h2>Conceito de interface</h2>

<p>O conceito de interface pode ser resumido como o estudo da interação entre humanos e computadores. Neste contexto, a interface, muitas vezes chamada de interface do utilizador, é quem provê a interação entre o ser humano e o computador.</p>

<h2>A interface do lado cliente</h2>

<p>A evolução tecnológica levou a uma crescente utilização de dispositivos móveis que possuem os mais <strong> variados tamanhos de tela e funcionalidades.</strong>Sobre essa variedade nas características dos dispositivos utilizados na interface para o acesso a aplicações no ambiente web, é necessário garantir usabilidade, ou seja, que sejam desenvolvidos sistemas fáceis de usar e aprender, alem de flexíveis.Partindo do ponto de vista da usabilidade, essa deve estar alinhada ao conceito de design responsivo, o qual deverá permitir que as páginas web e consequentemente as aplicações web respondam a qualquer dispositivo sem perda de informações por parte do usuário.</p>
<p>O site <a href = "https://gs.statcounter.com/">StatCounter Global Statistcs </a> mantem ativa uma série de dados e estatísticas sobre dispositivos, tamanhos de tela, além de outras informações relacionadas.Sobre o tamanho das telas.</p>
<h2>O conceito do design responsivo</h2>
<h3>Design responsivo</h3>
<p>O <strong>Design responsivo</strong> é a abordagem que sugere que o design e o desenvolvimento devam responder ao comportamento e ao ambiente do usuário com base no tamanho da tela, na plataforma e na orientação do dispositivo por ele utilizado</p>

<h3>Design responsivo na prática</h3>
<p>Ao aplicarmos o conceito de design responsivo, fazemos uso de uma combinação de técnicas, como <strong>layouts, media query e scripts</strong></p>

<h3><i>Layouts fluídos</i></h3>

<p>Para entender o conceito de layout fluido, é necessário entender primeiro o que seria o seu oposto, <i>Layout fixo</i>.</p>

<h4>Layout fixo</h4>
<p>As dimensões (Largura x Altura)dos elementos de uma página web são definidos com a utilização de unidades de medidas fixas, como os píxels.Desta forma, tais elementos não se adaptam as alturas no tamanho do campo de visão dos dispositivos que os visualiza.</p>
</br>
<h4>Layout fluído</h4>
<p>Os layouts fluídos fazem uso de unidades flexíveis, no lugar de definir as dimensões com o uso de quantidades fixas são utilizados valores flexíveis. Isso permite, por exemplo, que em vez de definir que o cabeçalho de uma página tenha 1366px de largura, possamos definir que ele ocupe 90% do tamanho da tela do dispositivo que o visualiza. Daí o conceito fluído, ou seja, de adaptabilidade ao campo de visão conforme dimensões do dispositivo que visualiza a página.</p>

<p>Alem dos valores percentuais, as outras medidas flexíveis são:</p>
</br>
<dl>
    <dt><strong>Layout fixo</strong></dt>
        <dl>As dimensões (Largura x altura) dos elementos de uma página web são definidos com a utilização de medidas fixas, como os píxels. Desta forma, os elementos não se adaptam as alterações no tamanho do campo de visão dos dispositivos que os visualiza.</dl>
    <dt><strong>Layout fluído</strong></dt>
        <dl>Fazem uso de unidades flexíveis, no lugar de definir as dimensões com o uso de quantidades fixas são utilizados valores flexíveis. Isso permite, por exemplo, que em vez de definir que o cabeçalho de uma página tenha 1366px de largura, possamos definir que ele ocupe 90% do tamanho da tela do dispositivo. Daí o conceito fluído, a adaptabilidade ao campo de visão conforme as dimensões do dispositivo que visualiza a página.<dl>
</dl>

<p>Alem dos valores percentuais, há outras unidades de medidas flexíveis, por exemplo:</p>

*   EM

    *   Unidade de medida tipográfica, estando relacionada a letra "M".    

*   REM

    *   Enquanto EM está relacionado ao tamanho do elemento em contexto, no REM definimos que o elemento de contexto, o elemento pai, sempre será a tag HTML < body >. Daí a letra "R" de raiz (Root).

<p><i>Mais informações sobre as unidades, fíxas e flexíveis basta acessar o site W3C - CSS Units</i></p>

<h2>Media query</h2>

<p>A função de apresentar, estruturar o layout de uma página no ambiente web, cabe as <strong>folhas de estilo CSS.</strong>Para entender o que media query é importante saber o que é o CSS. Nesse contexto, media query é a utilização de media types (tipos de midia) apartir de uma ou mais expressões para definir formatações para dispositivos diversos.Por exemplo, podemos definir que determinado estilo de um ou mais elementos seja aplicado apenas a dispositivos cuja largura máxima de tela seja igual ou maior a 600px.</p>

<p><strong>Exemplo:</strong></p>

~~~
<style type="text/css">
@media (max-width:360px)
{
    .menu_lateral
    {
        display: none;
    }
}
</style>
~~~
<p>O resultado das expressões utilizadas na media query pode ser True ou False. No caso acima, será verdadeiro sempre que a largura da tela do dispositivo que visualiza a página for inferior a 360px. Do contrário, será False, ou seja, para todos os dispositivos cuja largura de tela seja superior a 360px, o código CSS em questão será ignorado.</p>

<h2>Scripts</h2>

<p>Uma das linguagens de programação mais comuns no ambiente web é os Javascript. Essa linguagem adiciona interação a uma página web, permitindo, por exemplo, a atualização dinâmica de conteúdos, o controle de multimídia, a animação de imagens e muito mais. No contexto de design responsivo, sua faceta mais importante é a de atualização dinâmica de conteúdo, não só do conteúdo, mas também da apresentação dele.</p>

<h2>Design responsivo x design adaptativo</h2>
<p>O conceito de design adaptativo, muitas vezes, é confundido com o design responsivo. Assim como visto anteriormente, consiste na utilização de uma combinação de técnicas para ajustar um site automaticamente em função do tamanho da tela dos dispositivos utilizados pelos usuários, no design adaptativo são usados layout estáticos baseados em pontos de quebra (ou de interrupção), que após o tamanho da tela ser detectado, é carregado um layout apropriado para ele.</p>
<p><i>A aplicação desses dois conceitos na prática acontece da seguinte forma:</i></p> 

<h3>Design responsivo</h3>
	
<p>Media queries são utilizadas, em conjunto com scripts, para criar um layout fluido que se adapte por meio da adequação das dimensões de seus elementos, ao tamanho da tela do dispositivo utilizado pelo visitante.</p> 
	
<h3>Design adaptativo</h3>

<p>Um site é planejado e construido com a definição de seis layouts predefinidos, em que são previstos pontos de quebra para que a página se adapte as seis diferentes dimensões utilizadas.</p> 

<h3>Mobile first</h3>
<p>Uma das abordagens mais utilizadas atualmente, essa abordagem está centrada no crescente uso de dispositivos móveis na navegação no ambiente web e defende que em primeiro lugar, seja pensado o design para telas menores, e postoriormente, para telas maiores. Trata-se de enfoque progressivo <i>(progressive enhancement)</i>, no qual se parte dos recursos e tamanho de tela disponíveis nos dispositivos menores, progredindo com adição de recursos e conteúdo tendo em vista as telas e os dispositivos maiores. A contraponto com o desenvolvimento web tradicional, em que temos o conceito de degradação graciosa <i>(graceful degradation)</i>.</p>

<p>A aplicação prática do mobile first consiste em planejar o desenvolvimento de um site priorizando os recursos e as caracteristicas presentes nos dispositivos móveis, como tamanho de tela, largura de banda disponível e até mesmo recursos específicos, como os de localização, por exemplo.</p>

<h2>Tecnologias do lado cliente</h2>

<h3>HTML</h3>

<p>Considerada a tecnologia fundamental da web, pois sua função é a de definir a estrutura de uma página web. É uma linguagem de marcação simples, composta por elementos, chamados tags, que são relacionados a textos e outros conteúdos a fim de dar-lhes significado.</p> 

<p><i>As tags podem ser agrupadas nos seguintes tipos:</i></p> 

<h3>Estruturais</h3>
<p>Estrutura obrigatória de uma página web:</p>

<p><img alt="estruturais" src="/midia/estruturais.png" /></p>

<h3>De conteúdo</h3>
<p>Tags de conteúdo de uma página web:</p>

<p><img alt="de conteúdo" src="/midia/deconteudo.jpg" /></p>

<h3>Semanticas</h3>
<p>Tags básicas de uma página web:</p>

<p><img alt="semanticas" src="/midia/semanticas.jpg" /></p>

<p>Uma listagem completa de tags e atributos pode ser encontrada no site do W3C.</h3> 

<h2>CSS</h2>

<p>Trata-se de uma declarativa cuja função é a apresentação visual de páginas web. Com isso, tem-se a separação de funções em relação a HTML. A sigla significa Cascading Style Sheets (folhas de estilo em cascata).</p> 

<h3>Sintaxe</h3>

<p>Consiste em uma declaração em que são definidos os elementos e os estilos que desejamos aplicar a eles.</p>

<h3>O seletor</h3>
Um elemento HTML (body, div, p etc) ou o seu identificador (atributo id) ou classe (atributo class). 

<h3>A propriedade</h3>
<p>Caracteristica do elemento (cor, fonte, posição, etc).</p>

<h3>O valor</h3>
<p>Novo parâmetro a ser aplicado a caracteristica do elemento. </p>

<p><img alt="exemplo código CSS" src="/midia/codCSS.png" /></p>

<p>A respeito dos seletores, propriedades existentes e mais detalhes sobre a CSS, é recomendado ler o guia de referencia do próprio W3C.</p>


<h2>Tecnologias lado cliente: HTML5, CSS3 e JavaScript</h2>

<h3>Como inserir o CSS na página web</h3>
<p>Há quatro formas de inserir o CSS em um documento: </p>

*	<strong>Inline</strong>

	* São aplicados com a utilização do atributo "style" seguido de uma ou mais propriedades/valores. 

*	<strong>Interno</strong>

	*	São definidos com a utilização da tag < style > dentro de < head >.

*	<strong>Externo</strong>

	*	Forma preferencial de inserir estilos. É usado de forma externa com arquivo.css, contendo apenas estilos. Para vincular basta usar a tag < link > dentro de < head >. 

*	<strong>Escopo</strong>

	*	Forma introduzida no html5, da mesma forma que inline, entretanto, no lugar de ser declarada no < head >, é declarado dentro da tag a qual se quer aplicar estilos. 


<h3><i>Boas práticas</i></h3>

<p><i>É uma boa prática e fortemente recomendado utilizar a forma extrema para incluir CSS em uma página web. Dessa forma mantem o código organizado, separa o html do estilo. Outra boa prática, tendo em vista o desenpenho do carregamento da página web é compactar o arquivo, usando minificação.</i></p> 

<h2>Javascript</h2>

<p>Trata-se de uma linguagem de programação que, assim como o CSS, é interpretada pelo navegador. Entre suas principais caracteristicas, destaca-se o fato de ser multiparadigma. Sua função é fornecer interatividade a páginas web.</p>

<h3>Sintaxe</h3>

<p>A sintaxe é ao mesmo tempo, amigável, simples e completa. Embora criado para ser leve, uma vez que é interpretado nativamente pelos navegadores, trata-se de uma linguagem de programação completa. Seus códigos podem ser tanto estruturados quanto orientados a objetos. É possível usar bibliotecas, como Jquery, Prototype etc. sejam criadas apartir do seu core, estendendo a sua funcionalidade.</p>

<h3>Jquery</h3>
<p>É uma biblioteca Javascript rápida, pequena e rica em recursos que simplifica processos como a manipulação de documentos HTML, eventos, animação, alem do AJAX (Jquery).</p>

<h3>Prototype</h3>
<p>É um framework Javascript de código aberto, modular e orientado a objetos que provê extensões ao ambiente de script do navegador, fornecendo APIs para manipulação do DOM e Ajax (Prototype.js).</p>

<h3>Como inserir Javascript na página web</h3>

<h4>Diretamente em um arquivo HTML</h4>
<p>Umas das formas mais conhecidas é usando a tag < script >< script >, que deve abranger todo o código JS. O código pode ser adicionado:</p>
* Entre as tags < head >
* Entre as tags < body >

<p>Dependendo de onde você adicionar o código JavaScript no arquivo HTML, o carregamento é diferente. A prática recomendada é inseri-lo na seção <head>, pois ele ficará separado do conteúdo real do arquivo HTML.</p>

<p>Mas saiba que, colocá-lo na seção < body > poderá melhorar a velocidade de carregamento, já que o conteúdo do site atual será carregado mais rapidamente, e somente então o JavaScript será analisado. Para este exemplo, vamos dar uma olhada no arquivo HTML abaixo, usado para mostrar o horário atual.</p>
 
<h2>Tecnologias do lado servidor</h2>

<h3>PHP: uma linguagem de programação server side</h3>

<p>Uma das principais funções das linguagens de programação server side é permitir o acesso a informações armazenadas em bancos de dados. Uma vez que apenas utilizando HTML e Javascript não é possível, faz-se necesária a utilização de uma das linguagens no lado servidor. Entre as diversas linguagens disponiveis no lado servidor estão o Java, o Python, o ASP, o .NET e o PHP.</p> 

<p>PHP (Hypertext Preprocessor) é uma linguagem de programação baseada em script, opensource e destinada, sobretudo, ao desenvolvimento web. Trata-se de uma linguagem criada para ser simples, tendo nascida estruturada e, posteriormente, adotado o paradigma de orientação a objetos, apenas 10 anos depois da sua criação.</p>

<h3>Como o PHP funciona</h3>

<p>O php é uma linguagem interpretada, ou seja, ela precisa "rodar" sobre um servidor web. Com isso, todo o código gerado é interpretado pelo servidor, convertido em formato HTML e então exibido no navegador.</p>

* Etapa 1: O código PHP gerado é interpretado pelo servidor. 
* Etapa 2: Esse código é convertido em formato HTML. 
* Etapa 3: O código é exibido no navegador. 

<p>Logo o código-fonte não pode ser visto no lado cliente, mas apenas o HTML gerado.</p> 

<p>Outra caracteristica importante do PHP é poder ser utilizado na maior parte dos sistemas operacionais, assim como em vários servidores web diferentes, como o Apache, o IIS e o Nginx, entre outros.</p>

<h3>Anatomia de um script PHP</h3>

<p>Um script PHP é composto por código delimitado pelas tags < ?php e ?>. A última, de fechamento não é obrigatória. Devido a sua simplicidade, um mesmo script PHP pode conter tanto código estruturado quanto orientado a objetos. Pode até conter código de marcação HTML. Nesse último caso, o código próprio do PHP deverá ficar entre as tags de abertura e fechamento.</p>

<p><img alt="Exemplo PHP" src="/midia/php1.png" /></p>

<p><img alt="Outro exemplo PHP" src="/midia/php2.png" /></p>

<h3>Sintaxe</h3>

<p>A seguir um resumo sobre a sintaxe do PHP:</p>

<h4>Eventos e manipulação DOM</h4>
<p>Essa linguagem oferece amplo suporte à manipulação de eventos relacionados a elementos HTML. É possível, por exemplo, utilizar um elemento < button > (botão) que, ao ser clicado, exiba uma mensagem na tela. Ou ainda aumentar o tamanho de uma fonte ou diminuí-lo.</p>

<h4>Mensagem e entrada de dados</h4>
<p>O JavaScript possui suporte a funções nativas para a exibição de caixas de diálogo para entrada de dados ou exibição de mensagens, como alertas, por exemplo.</p>

<h3>Variáveis</h3>

<p>No PHP, as variáveis são criadas com a utilização do símbolo de cifrão ($). Além disso, PHP é case
sensitive, ou seja, sensível a letras maiúsculas e minúsculas, pois faz diferença quando utilizamos
uma e outra.</p>

<h3>Tipos de dados</h3>
<p>O PHP é uma linguagem fracamente tipada. Logo, embora possua suporte para isto, não é necessário definir o tipo de uma variável em sua declaração. Os tipos de dados disponíveis em PHP são: booleanos, inteiros, números de ponto flutuante, strings, arrays, interáveis (iterables), objetos, recursos, NULL e call-backs.</p>

<h3>Operadores condicionais</h3>
<p>No PHP, há suporte às condicionais if, else, if e else ternários, if else e switch.</p>

<h3>Laços de repetição</h3>
<p>No PHP estão disponíveis os laços for, foreach, while e do-while.</p>

<h3>Funções e métodos</h3>
<p>O código PHP possui uma grande quantidade de funções e métodos nativos.</p>


<h3>Inclusão de scripts dentro de scripts</h3>

<p>O PHP permite a inclusão de um script dentro de outro script. Isso é muito útil, sobretudo se pensarmos no
paradigma de orientação a objetos, em que temos, em um programa, diversas classes, codificadas em diferentes scripts. Logo, sempre que precisarmos fazer uso de uma dessas classes, de seus métodos ou atributos, basta incluí-la no script desejado. Para incluir um script em outro, o PHP disponibiliza algumas funções:</p>

*   Include
*   Require
*   Include once
*   Require_once

<h3>Acesso ao sistema de arquivos</h3>

<p>Por meio do PHP é possível ter acesso ao sistema de arquivos do servidor web. Com isso, pode-se por
exemplo, manipular arquivos e diretórios, desde a simples listagem à inclusão ou exclusão de dados.</p>

<h2>Páginas dinâmicas e acesso a dados</h2>

<h3>Páginas dinâmicas</h3>

<p>Para entender o que são páginas dinâmicas, é necessário entender o seu antônimo, as páginas estáticas.<p> 

> HTML + JavaScript + CSS, sem conexão com uma linguagem de programação, formam o que podemos chamar de páginas estáticas. 
> Embora seja até possível termos um site inteiro composto por páginas estáticas, isso seria muito trabalhoso e também nada usual.

<h4>Exemplo</h4>
<p>Imagine um site que tenha, por exemplo, dez páginas. Agora imagine que esse site tenha a mesma estrutura
visual, o mesmo cabeçalho, menu, rodapé e outros pontos em comum. Pense em um blog, por exemplo,
onde o que muda são os conteúdos dos posts. No site estático, teríamos que escrever dez diferentes
arquivos HTML, modificando o conteúdo em cada um deles, diretamente nas tags HTML, e só
conseguiríamos reaproveitar os estilos e a interatividade de navegador utilizando CSS e JavaScript externos.
Entretanto, todo o conteúdo precisaria ser digitado e muito código HTML repetido. Todo esse trabalho nos
ajuda a entender o que são páginas estáticas.</p>

<p>Ainda utilizando o exemplo de um blog, imagine que você deseja receber comentários em seus posts,
deseja que seus visitantes possam interagir com você e vice-versa. Como fazer isso? A resposta, como você
já deve imaginar, é: páginas dinâmicas</p>

> A combinação das tecnologias do lado cliente com as tecnologias do lado servidor produzem as páginas dinâmicas.

<p>Nelas, é possível receber as informações provenientes do cliente, processá-las, guardá-las, recuperá-las e
utilizá-las sempre que desejarmos. E não é só isso: podemos guardar todo o conteúdo do nosso blog no
banco de dados. Com isso, teríamos apenas uma página PHP que recuperaria nosso conteúdo no banco e o
exibiria no navegador. A tabela a seguir apresenta um pequeno resumo comparativo entre as páginas
estáticas e dinâmicas.</p>

<p><img alt="Tabela de comparação entre páginas estáticas e páginas dinâmicas" src="/midia/tabela_dinamicas_estaticas.png" /></p>

<p><i>Outra importante característica de um site dinâmico é possibilitar a utilização de ferramentas de gestão de conteúdo (CMS) para manter as informações do site sempre atualizadas. Porém, no site estático, será preciso modificar diretamente o HTML.</i></p>

<h3>Acesso a dados<h3>