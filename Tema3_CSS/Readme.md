<h1>Linguagem de marcação e estilos - CSS</h1>

<p>CSS, ou folhas de Estilos em Cascata (Cascading Style Sheets), é uma linguagem de estilo que fornece total controle sobre a apresentação de um documento escrito em HTML.</p> 

<p>No ambiente web, o HTML é a linguagem responsável pela estrutura do conteúdo de uma página. Embora seja capaz de organizar o conteúdo visualmente, é função da CSS cuidar desse aspecto e de tudo relacionado ao estilo e layout da página.</p> 

<p>Com a CSS, por exemplo, é possível alterar a forma e o posicionamento dos elementos, as cores, tipos de fontes e muito mais.</p> 

<h2>Fundamentos do CSS</h2>

<h3>Como a CSS funciona? </h3>

<p>A CSS permite a aplicação seletiva de estilos a elementos em uma página HTML. Isso significa dizer que um ou mais estilos podem ser aplicados em um documento inteiro ou mesmo em apenas parte dele. Além disso, um mesmo tipo de elemento pode ter, ao longo do documento, diferentes estilos.</p> 

<h3>Sintaxe da CSS</h3>

Para aplicar um estilo CSS a um elemento específico, é necessário identificá-lo e apontar qual de suas propriedades queremos alterar e qual valor queremos atribuir-lhe. Essas três informações definem a sintaxe da CSS, conforme exemplo a seguir: 
´´´
p{
   background-color:blue;
   color: white;
}
´´´

* p = seletor

* blue = valor 

* background-color = propriedade


<h3>Seletores</h3>

<p>Nos referimos a tag < p> como sendo um seletor ao qual o estilo foi aplicado. Existem muitos outros seletores disponíveis além daqueles correspondentes as tags HTML.</p>

<h3>Seletores class e id</h3>

<p>O seletor de classe é definido a partir da declaração do atributo class em um elemento HTML. Já o seletor de identificação é definido com o atributo id.</p>

<i>Embora um elemento possa ter mais de uma classe, terá apenas um identificador. </i>


<h3>Restrições e boas práticas na utilização do identificador</h3>

<p>Embora não exista um padrão ou preferência quanto a utilizar o seletor id ou class, é importante frisar novamente que um id deve ser aplicado a
apenas um elemento, enquanto a class pode ser aplicada a um ou vários elementos.
Embora o navegador não verifique se um mesmo id foi utilizado em diferentes elementos, tal método pode trazer alguns problemas de estilização e
comportamento, uma vez que esse seletor também é bastante usado pelo Javascript. Frente a isso, adote a boa prática de definir identificadores
únicos.</p>

<h3>Seletores de atributos </h3>

<p>Esses seletores utilizam nomes de atributos dentro de colchetes, sendo possível combiná-los com valores. Abaixo são mostrados alguns dos seletores de atributo disponíveis:</p>

* [checked] - seleciona todos os elementos que possuem o atributo checked.
* [type=’text’] - seleciona todos os elementos do tipo text.
Os seletores de atributo são flexíveis, permitindo inúmeras combinações. Por exemplo, é possível usá-los para selecionar todas as imagens com
uma determinada extensão, selecionar todos os elementos com o atributo title contendo determinado valor etc

<h3>Seletores baseados em relacionamento</h3>

<p>É possível declarar estilos utilizando a relação entre os elementos. A tabela a seguir mostra os principais seletores baseados em relacionamento.</p>

H1P // Qualquer elemento P que seja descendente de um elemento H1
H1>P // Qualquer elemento P que seja o filho de um elemento H1
H1+P // Qualquer elemento P que seja o próximo irmão de um elemento H1. 

<h2>Propriedades CSS</h2>

<p>Existem inúmeras propriedades CSS, desde as definidas pela sua especificação, ditas propriedades padrão, até as proprietárias, que funcionam
apenas em alguns navegadores. A fim de garantir uma maior compatibilidade, assim como otimizar o desenvolvimento, deve-se sempre dar
preferência às primeiras. A seguir, são apresentadas algumas das propriedades mais comuns da CSS.</p>


* Background
    *	Estabiliza o fundo de elementos. Para tal há uma série de propriedades, além do atalho “Background”, como “background-color”, “background-image” etc.
* Border
    *	Controla as bordas de um elemento, sendo possível definir suas cores, espessuras, entre outras propriedades.
 * Top, Bottom, Righ e Left 
	 * Controlam o posicionamento, relativo ou absoluto, dos elementos em relação a outros elementos.
* Color 
	* Estila a cor do conteúdo textual de um elemento.
* Font-family, Font-size,Font-weight etc.
	* Série de propriedades usada para estilizar o conteúdo textual de um elemento no que diz respeito à fonte, como a família de fontes, seu tamanho, peso (mais clara ou mais escura - negrito) etc
* Height 
	* Define a altura de um elemento.
*	List-style, List-styleimage etc.
	*	Propriedades usadas para estilizar as listas HTML.
*	Margin 
	*	Controla a distância em função da margem de um elemento para outro.
*	Padding 
	*	Controla a distância entre as bordas e o conteúdo de um elemento.
*	Position 
	*	Define como um elemento deve ser posicionado na página.
* Text-...
	*	Muitas propriedades controlam o comportamento do conteúdo textual de um elemento, como alinhamento (justificado, centralizado etc.), aparência (sublinhado etc.) etc.
*	Width 
	*	Define a largura de um elemento.
*	Z-index
	*	 Define a profundidade de um elemento – usado, por exemplo, para sobreposição de elementos.

<h2>Integrando a CSS a HTML</h2>

<p>Há três formas usuais de aplicar estilos em um documento HTML fazendo uso de CSS: Inline, Interna e Externa. Além dessas, a HTML5 permite ainda a aplicação em escopo. Vamos conhecer um pouco mais de cada uma delas?</p>

Css inline

CSS interna

CSS externa

CSS em escopo
