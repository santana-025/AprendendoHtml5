            # AprendendoHtml5
Curso  e Aprendizagem de Html5 (Programação Web)

	Iniciar o Codigo na Mão

<!DOCTYPE html> : Tipo do documento 
<html> 		: abertura do Formato
<head></head>   : Cabeçario 
<body></body> 	: Corpo do site
</html>		: Fechamento do Formato


		Metatags


<html lang="en"> = Linguagem do site ( "pt-br" portugues do brasil )
		<html lang="en">

<meta charset="UTF-8"> = Compatibilidade com acentos 

<meta name="viewport" content="width=device-width, initial-scale=1.0"> = Tela se Adapta ao tamanho da tela do usuario

<meta name="description" content = " Esse é meu Primeiro Site !"> = Descrição do site 

<meta name="keywords= " programação, html, "> =  Palavras Chaves para a interpretação do google

<meta name="author" content="Jorge Santtana"> = nome do autor do site


		Tags


<b> (Texto) </b> = Negrito
<i> (Texto) </i> = Italico
<u> (Texto) </u> = Subilinhado
<p> (Texto) </p> = Paragrafos 
	p>Lorem = Conteudo aleatorio 
	P*3>Lorem = 3 Paragrafos

<hr> = Divide em linha _______
<br> = Pula a linha para baixo 
&nbsp; = Dar espaços

<h1> (Texto) </h1> = Importancia 1 
	<h1> * Somente 1 Por pagina *
<h2> (Texto) </h2> = Importancia 2 
<h3> (Texto) </h3> = Importancia 3
<h4> (Texto) </h4> = Importancia 4 
<h5> (Texto) </h5> = Importancia 5 
<h6> (Texto) </h6> = Importancia 6 
 
<small> (Texto) </small> = Deixa pequeno
<strong> (Texto) </strong> = Enfase
<del> (Texto) </del> = Risco no meio 
<sub> (Texto) </sub> = Texto embaixo
<sup> (Texto) </sup> = Texto elevado
<mark> (Texto) </mark> 


	Elementos de citação

<abbr title="S/ Abreviação">(Abreviado)</abbr> = Mostra o nome de uma abreviação

<address> (Endereço) </address> = Algum enderreso ou link

<cite> (Texto) </cite> = Texto em italico citação curta.

<q> (Texto) </q> = Coloca entre aspas, ou seja citação de fala

<blockquote> (Texto) </blockquote> = Da uma previa do texto deixando ele destacado com uma identação diferente


<bdo dir="rtl"> (Texto) </bdo> = Direita para esquerda 

<bdo dir="ltr"> (Texto) </bdo> = Esquerda para Direita

	Comentario 

<!-- Abertura 
	(Tudo aqui dentro é comentario)
--> Fechamento 

ctrl + k + c = Atalho no vscode
ctrl + ; = Atalho no vscode

		Links 

usa a tag <a> </a>
com parametro : href ="Link"

abri nova aba : target = "_blank"
abri propria pag : target = "_self"
abri no iframe : target = "nome;id-do-iframe"


    		Link Absoluto

Leva direto para um link externo
<a href="http://Google.com"> Ir Para o Google </a>

   
 		Link Não Absoluto(ancora)


Leva Para os documentos dentro da mesma pasta do arquivo
	<a href="nomedoarquivo.html"> ( Texto ) </a>


Leva Para os documentos dentro de outra pasta
	<a href="nome_da_pasta/nome_do_arquivo.html"> ( Texto ) </a>


Voltar de Dentro da pasta para a pasta principal 
	<a href="../index4.html"> Voltar </a>

../ = Para quantidade de pastas for preciso voltar


		Imagens no HTML

Ao ultilizar, tente comprimir no maximo a img para que ela nao demore no carregamento do site, e deixe seu codigo mais fluido.
Pode ser ultilizadas dentro de outras tags. Ex: H1 
<h1> <img src="caminho_da_img" width="500" > Titulo da Pág </h1>


<img > = Não Precisa de Fechamentos
<img src="caminho_da_img" > = mostra onde pegar a img
<img src="caminho_da_img" alt="lago azul" > = Descrição da img
<img src="caminho_da_img" width="500" > = Largura da img (Altura se ajusta)
<img src="caminho_da_img" height="500" > = Altura da img

		Tipos de Img

png = Imagens sem fundo 
jpeg = Imagens comun
gif = Imagens Animadas 


		Img com Caminho absolutos

<img src="https://Caminho_da_img_na_web" width="500" alt="Por do sol alaranjado">

1 - A img pode ser quebrada 
2 - Pode conter direitos autorais (Sites de banco de img Gratis)
3 - Você não tem controle sobre a img

		Img com Caminho absolutos

<img src="pasta/nome_do_arquivo" width="500" alt="Por do sol alaranjado">

		Linnk ao click na img

<a href="../index4.html">  = Abre a tag de link, com o link que vai ir 
 <img src="pexels-pixabay-39855.jpg" width="500"> = Dentro da tag adciona a img
</a>

		Map img
		
	Passo - a - Passo
Redimesiona a img do tamanho preferido
Abre o map img no google
Faz a marcação do item da img
Adiciona a foto e o link
Gera um codigo com o map da img so colar no codigo 


1 <img src="pexels-pixabay-39855.jpg" usemap="#image-map">
2    <map name="image-map">
3        <area target="" alt="Google" title="Google"   
4 ref="https://www.youtube.com/" coords="362,608,1808,1567" shape="rect"> 
5    </map>

Ou seja:
Linha 1 : define a imagens e o map ultilizado
Linha 2 : Faz a abertura do map com o id name que foi adicionado na linha acima
Linha 3&4 : Area com as informação da img incuindo o map que foi feito no site
Linha 5 : Fechamento da tag map

		Tabelas

<table> </table> = Usa a tag table
<table width="80%"> </table> = Largura da tabela
<table border="1"> </table> = Adiciona uma borda a tabela

<tr> </tr> = Linha da Tabela
<th> </th> = Linha dos Titulos da Tabelas
<td> </td> = Coluna da Tabelas

1 <tr>  = Abertura da linha dos titulos
2  <th> Nome </th>
3  <th> Idade </th>     = Linha de Titulos 
4  <th> Peso </th>
5 </tr> = Fechamentos 
	
		Adicionado os valores
	
<tr>  = Abertura da linha dos valores
2  <td> Jorge </td>
3  <td> 25 </td>     = Linha de Valores da Tabela 
4  <td> 80kg </td>
5</tr> = Fechamento 

		Listas 

Listas Não Ordenada:
<ul></ul> = Lista Não Ordenada 

Dentro dela usamos ->
<ul>
<li> itens </li>
<li> itens </li>
</ul>

A lista sem uma ordem especifica (pontinho)


Listas Ordenada:
<ol></ol> = Lista Ordenada

Dentro dela usamos ->
<ol>
<li> itens1 </li>
<li> itens </li>
</ol>

A lista com 1 ordem especifica (1,2,3)

		Iframe

Ao Pegar um video do youtube no botão de compartilhar tem a opção de incorporar, dando o codigo do iframe para aquele video, copy & Paste. Podendo alterar o tamanho !

<iframe> </iframe> = Abertura e Fechamento

<iframe href="pasta/arquivo"> </iframe> = iframe de um arquivo do codigo

<iframe href="linkAbsoluto"> </iframe> = 
Abre um site no iframe


<iframe frameborder="0"> </iframe> = Retira a Borda do iframe

<iframe style="border: none;"> </iframe> = Retira a Borda do iframe 


<iframe width="560" height="315"> </iframe> = Largura e Altura do iframe

		Formulario 

<form> </form> = Abertura do Formulario 

value=" " = o que vai ser enviado para o banco de dados 

<label>"nome"</label> = menssagem amostra pois o imput não tem textos

<label for:id do input> = uso do for para indentificar a qual input esse label pertence, usando o seu id
		
		Input
	
<input> Não contém Fechamentos

	parametros

id="indentificador "			
type="tipo_do_input"
placeholder="msg_dentro_do_input"
value="oq_vai_ser_enviado_para_backend"

requared = preenchimento se torna automatico
  

<button> msg </button> = Cria um botão
	
	Tipos de input

<input type="text"> = para textos curtos 
<input type="number"> = para numeros
<input type="email"> = para emails
<input type="password"> = para senhas
<input type="range"> = para volumes
<input type="color"> = para cores
<input type="time"> = para hora
<input type="date"> = para data
<input type="datetime-local"> = para data/hr
<input type="month"> = para mês
<input type="week"> = para semana
<input type="file"> = para enviar arquivos
<input type="image"> = para enviar msg
<input type="url"> = para enviar url
<input type="search"> = para pesquisa no site
<input type="reset"> = para resetar o formulario
<input type="submit"> = para enviar backend 
	
	Input Radio	

<input type="radio"> = São os circulos de opões com apenas 1 escolha. deve conter o mesmo name="" para funcionar corretamente

ex:
<input type="radio" id="bird" nome="animal"
value="Passarinho" >

	Input Checkbox

<input type="checkbox"> = Check tipo lista de compras marcando o que ja comprou. podendo selecionar varias opções, value="" o que vai ser resgatado pelo backend

ex: 

<imput type="checkbox" id="bird" nome="animal" value="Passarinho" >

	Select
	
<select></select> = Abertura da tag select 
precisa ter a tag <option></option> dentro de si para funcionar : faz uma lista de opções para selecionar apenas uma

<select name="cores"> = indentificador

<option>vermelho</option> = abertura da primeira opção, fazer para quantas for nescessario

selected = já comerça selecionado
disabled = a pessoa não pode escolher

Para colocar um opção orientando a pessoa, que ela não possa mais selecionar:

usase o selected e o disabled e uma mensagem

ex:
<option selected disabled value=""> escolha uma cor </option>

value="" = vazio pois não precisamos desta informação

	TextArea

<textarea></textarea> = Abertura e Fechamento da tag, abre um bloco para poder escrever textos mais longos.

name="textarea" = indentificador
placeholder=messagem = marca d´agua "digite algo"
rows="15" = Quantidade de linhas
cols="55" = Quantidade de Colunas

Para ter algo já escrito basta escrevere entre as tags

		Audio

muito ultilizado para sites que ultiliza o audio como leitura do conteudo

Podendo ser caminho absoluto ou ancora

<audio></audio> = Tag de abertura com fechamento
<audio controls> = controles do audio (Mostra o play de musica)
<audio autoplay> = Toca ao iniciar a pagina  
<audio loop> = musica em loop
<audio muted> = Inicia a pagina mutado
<audio preload> = Ajuda com o processamento da pagina

<audio controlsList="nodownload"> = Retira a opção do download da musica

<source> = dentro da tag de audio
<source src="caminho.mp3" = indica o caminho da musica relativo ou ancora
type="audio/mpeg"  
     "audio/ogg"   3 tipos de musicas
     "audio/wav" >

NOVO METODO :::

<audio  controls  src="musica.mp3"></audio> = Passa tudo direto na tag de audio sem o uso da tag source.


		VIdeos

<video></video> = Abertura e fechamento da tag
<video controls> = controles do video 
<video autoplay> = toca ao abri a pagina
<video width="60%" = Largura (altura se ajusta)
<video poster="caminhodaimg.jgp" = tumb
<video controlsList="nodownload" =sem download
<video controlsList="nofullscreen"> = sem tela cheia
   
<source> = dentro da tag <video>
<source src="pasta+arquivo" = caminho do video 
<source type="video/mp4" = tipo do video
    
NOVO METODO :::

<video src="caminhodovideo.mp4" controls ></video>
indica tudo na tag de video sem a ultilização da tag de <source>

		HTML Semantico

<div></div> = tag generica cria os blocos para ajudar o css a estruturar o site

<header></header> = topo
<nav></nav> = navegação
<section></section> = seção do site
<footer></footer> = rodapé do site
<main></main> - Especificamos o conteúdo principal e, consequentemente, de maior relevância dentro da página;

<article></article> = artigo
<aside></aside> - Utilizado quando precisamos criar um conteúdo de apoio/adicional ao conteúdo principal;

<figure></figure> - é uma marcação de uso específico para a inserção de uma figura;
