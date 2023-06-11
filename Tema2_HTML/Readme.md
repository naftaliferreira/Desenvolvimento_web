<h1>HTML</h1>
<h2>Linguagem de marcação de hypertexto</h2>

<p>O principal objetivo de uma linguagem de marcação de hypertexto, mais expecificamente o HTML, é o de <strong>estruturar o conteúdo</strong> de um documento. Este conteúdo pode ser composto de textos, figuras, tabelas e etc.</p>
<p>Estutura essa que pode ser definida como a organização dos elementos de conteúdo. Para realizar essa função, a HTML faz uso de um sistema hierárquico de elementos chamdados de tags.</p>

[Primeiro exemplo](exemplos/exemplo1.html)
[Segundo exemplo](exemplos/exemplo2.html)
[Terceiro exemplo](exemplos/exemplo3.html)

<h2>Estrutura de uma página web</h2>

<h3>Doctypes</h3>

<p>A sua importancia, na criação de páginas HTML, diz respeito ao conjunto de tags que podem ser usadas e que serão ou não renderizadas a partir do tipo utilizado.</p>

<h3>< !DOCTYPE html ></h3>

<p>Doctype não é uma tag HTML, mas sim uma instrução.Uma declaração que serve para informar ao navegador qual a versão do HTML usada em um arquivo HTML.</p>

Raiz (Root)

    <hml><html/>  

comentário, cabe destacar o atributo lang, deve ser inserido dentro da tag raiz:
~~~~~~
< html lang="en-US">
<html lang="en-GB">
<html lang="pt-BR">
<html lang="pt">
~~~~~~

< head > // cabeçalho

Dentro do cabeçalho do documento algumas tags importantes também fazem parte:

< title > // título do documento

< meta > // engloba informações como descrição, palavras-chave, etc. 

< script > // responsável pela inclusão e ou definição de scripts

< link > // responsável pela inclusão de folhas de estilo (externa).Também possibilita a inclusão de favicons. 

< style > // Assim como o anterior, também é responsável pelo vinculo de folhas de estilo ao documento. 

< body > // corpo da página

<h2>Estrutura básica de uma página web</h2>
   
   * Cabeçalho
   
   * Barra de navegação 
   
   * Conteúdo
   
   * Barra lateral
   
   * Rodapé

<h2>Tags HTML básicas</h2>

<h3>Como declarar tags?</h3> 

<p>Existe um conjunto já definido de tags, logo não é possível criar as próprias tags HTML. Outro ponto importante é a forma como uma tag é definida, entre os sinais de maior e menor. Além disso, deve ser fechada. </p>

<strong>Exemplo:<strong> 

<h2>Tipos e composição das tags</h2>

<p>As tags podem ser divididas em tipos, de acordo com as suas funções: </p>

<strong>Estruturais </strong>

* São responsáveis pode definir a estrutura da página. 

<strong>Textuais</strong>

* São responsáveis por organizar o conteúdo da página.

<strong>Semânticas</strong>

* são responsáveis pode organizar a estrutura de conteúdo de uma página. 

<h2>Atributos</h2>

<p>Outra coisa muito importante é que elas podem ter atributos. Os atributos servem para que algumas caracteristicas sejam adicionadas a um elemento, a uma tag. São compostos por um nome e por um valor.</p>

<strong>Exemplo:</strong>

< img src="imagem.png" alt="minha imagem" / >

<h3>Lista de tags mais utilizadas:</h3>

< head > // cabeçalho

< title> // título do documento

< meta> // engloba informações como descrição, palavras-chave, etc. 

< script> // responsável pela inclusão e ou definição de scripts

< link> // responsável pela inclusão de folhas de estilo (externa).Também possibilita a inclusão de favicons. 

< style> // Assim como o anterior, também é responsável pelo vinculo de folhas de estilo ao documento. 

< body> // corpo da página

< article> // inclui bloco de conteudo para artigo. 

< section> // define uma seção no documento, utilizado para agrupar seções, dentro de uma < section> pode conter vários < article>

< h1> < h6> // Usado para definir o tamanho da fonte, h1 titulo e vai reduzindo até h6 onde o texto é miniaturizado. 

< p> // parágrafo

< pre> // Usado para inserir um texto pré formatado. 

< div> // Não considerada semântica, pode ser usada para agrupar algum tipo de conteúdo que não tenha nenhuma semântica específica ou não se encaixe bem dentro de uma tag semântica. 

< span> // semelhante a < div>, porém não quebra o conteúdo apenas o agrupa. 

< a> // usada para inserir links 

< br/> // quebra de linha

< hr> // insere uma linha horizontal no documento. 

< strong> // aplica efeito negrito e o marca como importante

< b> // aplica efeito negrito. 

< i> // itálico

< em> // efeito itálico e dá ênfase a um texto


<h2>Tags complexas</h2>

<h3>Listas na HTML</h3>

<h4>Ordenadas</h4> 

* Usadas quando desejamos listar dados com a necessidade de representar a sua ordenação de forma numérica ou alfabética. 

< ol>
	< li>< /li>
< /ol>

<h4>Não ordenadas</h4>

* Usadas quando não há necessidade de listar ordenadamente.

< ul>
	< li>< /li>
< /ul>

<h4>De definição</h4>

* Usadas quando precisamos listar itens e atribuimos uma descrição a eles.

< dl>
	< dt>
		< dd>< /dd>
	< /dt>
< dl> 

----> vide exemplo listas.html


<h2>Tabelas dentro do HTML</h2>


<h3>Estrutura:</h3>

< table> // container principal da tabela

< tr> // representa as linhas, sendo composta pelas tags relacionadas as colunas. 

< td> // representa as colunas e precisa ser inserida dentro da tag de linha. 

< th> // também representa colunas e é usado para exibir titulo de uma coluna, possui função semântica. deve estar contida dentro da tag linha. 

< thead> // cabeçalho da tabela 

< tfoot> // rodapé da tabela 

<strong> exemplo</strong>

UMA TABELA SIMPLES
UMA TABELA QUE CONTENHA TÍTULO
UMA TABELA COM CABEÇALHO E RODAPÉ
UMA TABELA COM LINHAS E COLUNAS EXPANDIDAS
UM EXEMPLO COMPLETO

<h2>Mídias na HTML</h2>

<p>No HTML5 para incorporar vídeo e áudio em uma página Web, são usadas as tags    < video> e < audio>, veja exemplo: <p>

------> exemplo de uso das tags video e audio. 


<h2>Formulários em página Web</h2>

<h3>Composição e validação: </h3>

<p>É um dos elementos mais utilizados para prover interação entre usuários e uma página web ou até mesmo um aplicativo mobile. </p>

<h3>Estrutura básica do formulário</h3>

<p>O formulário é composto por uma tag principal, um container, e várias tags filhas. Tags como campo de texto, de uma ou mais linhas, campos de seleção, botões etc. </p>

<p>Além disso, para maior clareza, é usado tags para informar a função dos campos do formulário. São chamadas de "label".</p> 

<h4>Tags: </h4>

< form> // container principal do formulário

< input> // campo do formulário 

< textarea> // campo de texto de múltiplas linhas

< select> e < option> // campos de seleção, onde o container é definido pela tag < select> e os itens pela tag < option>. 

button // campo de botão. Permite que uma ação seja executada no formulário , enviar o formulário, limpar os dados e etc. 

label // usado para definir um título, uma legenda, que descreva para que serve cada campo do formulário. 

< fieldset> // cria seções dentro do formulário, ajudando a separar os campos no código e a visualizar a página no navegador. 

-------> Exemplo de formulário no html

<h3>Atributos do formulário</h3>

<h4>Atributo "type"</h4>

<p>Além de definir o tipo do campo, também determina como este se comporta. Além de "text" e "input", os outros tipos comuns são:</p> 

password // mascara o texto com asteriscos

Hidden // esconde o campo para não ser exibido no navegador

Checkbox // usado para seleção de valor através de click/check

Radio // Usado para seleção exclusiva de valor, quando é apresentada mais de uma opção, apenas uma poderá ser selecionada. 

Submit // Associada a tag <button>, dispara evento que envia/submete o formulário

Reset // Associa a tag <button>, dispara o evento que limpa os valores do formulário. 

Button // Uma tag <input> pode ser do tipo "button" , exercendo, assim a mesma função da tag <button>


<h2>Novos atributos e tipos</h2>

<p>O HTML5 definiu novos tipos de entrada e também novos atributos relacionados a formulários. Entre eles:</p>

placeholder // usado para dar dica ao usuário sobre o dado a ser inserido

required // Utilizado na validação dos dados de um formulário

autofocus // Utilizado quando desejamos, que ao carregar o formulário, um determinado campo seja focado. 

pattern // Validar o valor de um campo com base em uma expressão popular, RegEX. Ex.: o campo de telefone. 


<h3>Validação de formulários </h3>

<p>A importância da validade dos dados concorre com a importância da utilização das tags corretas e que permitam a melhor experiência possível aos usuários.</p> 

<h3>Como funciona a validação? </h3>

<p>A validação é um processo que pode, e deve ocorrer, tanto do lado cliente quanto no lado servidor. </p>

<h3>Tipos de validação</h3>

<p>Há dois tipos de validação possível:</p> 

* Que verifica se o dado inserido em um campo é consistente com o seu tipo e/ou padrão (pattern). 

* Que verifica se um campo obrigatório foi preenchido. 

