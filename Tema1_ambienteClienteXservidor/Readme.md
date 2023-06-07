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
  <p><i>Além dos valores percentuais, há outras unidades de medidas flexíveis.</i></p>

<h2>Media query</h2>
<p>Função de apresentação, de estruturar o layout de uma página, no ambiente web, cabe as <strong>folhas de estilo (CSS)</strong>. Media query é a utilização de media types (tipos de mídia) apartir de uma ou mais expressões para definir formatações para dispositivos diversos. Com o seu uso podemos, por exemplo, definir que determinado estilo de um ou mais elementos seja aplicado apenas a dispositivos cuja largura máxima de tela seja menor ou igual a 600px.</p> 

<p>Exemplo de fragmento de código em que uma média query é utilizada para impedir que um menu lateral seja exibido caso a largura da tela do dispositivo seja menor que 360px</p>

~~~
<style type="text/css">
@media (max-width: 360px)
{
 .menu_lateral
  {
   display: nome;
   }
}

~~~
<p>O resultado das expressões utilizadas na media query pode ser True ou False. No caso acima, será True sempre que a largura da tela do dispositivo for inferior a 360px. Do contário será False, e o código CSS em questão será ignorado.</p>

<h2>Scripts</h2>

<p>Quando se trata de scripts no lado cliente, no ambiente web, uma das linguagens mais utilizadas é o <strong>JavaScript</strong>.A linguagem adiciona interação a uma página web, permitindo por exemplo, atualização dinâmica de conteúdos, o controle de multimídia, a animação de imagens e muito mais.No contexto design responsivo, sua faceta mais importante é a de atualização dinâmica de conteúdo, e não só do conteúdo, mas também da apresentação dele.</p>

<h3>Design responsivo X design adaptativo</h3>
<p>A aplicação desses dois conceitos acontece da seguinte forma:</p>

| Design responsivo | Design adaptativo |
|-----|--------|
| Medias queries são utilizadas, em conjunto com script para criar um layout fluido que se adapte a adequação de seus elementos. |  Um site é planejado e construido com a definição de seis layouts predefinidos, em que são previstos pontos de quebra em que uma página se adapte as seis diferentes dimensões utilizadas.|

<h3>Mobile first</h3>
<p>Uma das abordagens de design responsivo mais utilizado atualmente é a mobile first. Tal abordagem está centrada no crescente uso de dispositivos móveis na navegação no ambiente web e defende que em primeiro lugar seja pensado o design para telas menores e, posteriormente para telas maiores.</p>
<p>Tal conceito é conhecido como <i>Progressive enhacement</i> "enfoque progressivo" diferente do desenvolvimento web tradicional que temos o conceito <i>Graceful defradation</i> "degradação graciosa":</p>

<h2>Tecnologias do lado cliente</h2>

| HTML | CSS | Javascript |
|---|---|---|
| Linguagem de marcacao de hypertexto | Cascading Style Sheets "folhas de estilo em cascata" | Linguagem de programação multiparadigma |
| Responsável por definir a estruytura a página web | linguagem declarativa responsável por controlar a apresentação visual de páginas web | fornece interatividade  |


<h2>Tecnologias do lado Servidor</h2>

<h3>PHP<h3>
<p>PHP é uma linguagem de programação server side, uma das principais funções destas linguagens é de permitir o acesso  informações armazenadas em bancos de dados.Existem diversas linguagens disponíveis no mercado para o lado servidor como Java, Python, ASP, .NET e o PHP.</p>
<p><strong>PHP</strong> é uma linguagem de programação baseada em script, opensource e destinada sobreturo ao desenvolvimento web.</p>

<h3>Como o PHP funciona?</h3>
<p>O PHP é uma <strong>linguagem interpretada</strong>, ou seja, precisa "rodar" sobre um servidor web. Com isso, todo o código gerado é interpretado pelo servidor, convertido em formato html e então exibido no navegador.</p>

1. Etapa 1: O código PHP gerado é interpretado pelo navegador.
2. Etapa 2: Esse código é convertido em formato html.
3. Etapa 3: O código é exibido no navegador. 

<p>Logo, o código-fonte não pode ser visto no lado cliente , mas apenas o HTML gerado.</p>

<h3>Páginas dinâmicas e acesso a dados</h3>
