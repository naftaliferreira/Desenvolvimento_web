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





