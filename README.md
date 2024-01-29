# Aprendizado para Web

## [HTML](https://github.com/gabrielperessilva/AprendizadoWeb/blob/main/HTML)

### [Parte 1
](https://github.com/gabrielperessilva/AprendizadoWeb/blob/main/HTML/Parte1)

1. [Introdução as Tags](https://github.com/gabrielperessilva/AprendizadoWeb/blob/main/HTML/Parte1/IntroTags.html)

   O elemento `<body>` do HTML representa o conteúdo de um documento HTML. Sendo permitido apenas um `<body>` por documento

   O elemento **HTML `<html>` **(ou  *HTML root element* ) representa a raiz de um HTML ou XHTML documento. Todos os outros elementos devem ser descendentes desse elemento.

   O elemento HTML `<head>` providencia informações gerais (metadados) sobre o documento, incluindo seu título e links para scripts e folhas de estilos.

   O elemento HTML `<title>` ( *Elemento HTML Título* ) define o título do documento, mostrado na barra de título de um navegador ou na aba da página. Pode conter somente texto e quaisquer marcações contidas no texto não são interpretadas.

   Os elementos HTML `<h1>`–`<h6>` representam seis níveis de título de seção. `<h1>` é o nível de seção mais alto e `<h6>` é o mais baixo.

   O elemento HTML `<p>` representa um parágrafo. Em mídias visuais, parágrafos são representados como blocos indentados de texto com a primeira letra avançada e separados por linhas em branco. Já em HTML, parágrafos são usados para agrupar conteúdos relacionados de qualquer tipo, como imagens e campos de um formulário.

   A declaração <!DOCTYPE> representa o tipo de documento e ajuda os navegadores a exibir as páginas da web corretamente. Deve aparecer apenas uma vez, no topo da página (antes de qualquer tag HTML). A declaração <!DOCTYPE> não diferencia maiúsculas de minúsculas.

   O elemento `<a>` em HTML (ou elemento âncora), com o atributo [`href`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/a#href) cria-se um hiperligação nas páginas web, arquivos, endereços de emails, ligações na mesma página ou endereços na URL. O conteúdo dentro de cada `<a>` precisará indicar o destino do link.

   O elemento **HTML `<img>` **(or  *HTML Image Element* ) representa a inserção de imagem no documento, sendo implementado também pelo HTML5 para uma melhor experiência com o elemento [`<figure>`]() e [`<figcaption>`](). O Atributo "alt" define um texto alternativo, caso a imagem não carregue. Os demais atributos "width" e "height" são para ajustar respectivamente a largura e altura.
   O elemento HTML **`<hr>`** representa uma quebra temática entre elementos de nível de parágrafo (por exemplo , uma mudança da cena de uma história, ou uma mudança de tema com uma seção). Nas versões anteriores do HTML, representava uma linha horizontal. Pode continuar sendo exibida como uma linha horizontal nos navegadores, mas agora está definida em termos semânticos, em vez de termos de apresentação.

   O elemento HTML *quebra-de-linha* `<br>` produz uma quebra de linha em um texto (carriage-return).É útil para escrever poemas ou um endereço, onde a divisão de linha é significante. O elemento HTML `<style>` contém informações de estilo para um documento ou uma parte do documento. As informações de estilo específico estão contidas dentro deste elemento, geralmente no [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS).

   O [atributo global](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes) **`lang`** ajuda a definir o idioma de um elemento: a língua em que elementos não-editáveis são escritos, ou a língua em que elementos editáveis devem ser escritos pelo usuário. O atributo contém uma uma única "tag de idioma" em um formato definido em [*Tags para identificar linguagens(BCP47)*](https://www.ietf.org/rfc/bcp/bcp47.txt).
2. [Novos atributos](https://github.com/gabrielperessilva/AprendizadoWeb/blob/main/HTML/Parte1/NovosAtributos.html)

   *HTML texto preformatado* ( **`<pre>`** ) é a tag utilizada para representar texto pré-formatado. Um texto dentro desse elemento é tipicamente exibido em uma fonte não proporcional da mesma maneira em que o texto original foi disposto no arquivo. Espaços em branco são mantidos no texto da mesma forma em que este foi digitado.

   Continunado o elemento `<style>` :

   `background-color` para cor de fundo

   `color` para cores de texto

   `font-family` para fontes de texto

   `font-size` para tamanhos de texto

   `text-align` para alinhamento de texto

   Os elementos de formatação foram projetados para exibir tipos especiais de texto:

   `<b>` - Texto em negrito
   `<strong>` - Texto importante
   `<i>` - Texto em itálico
   `<em>` - Texto enfatizado
   `<mark>` - Texto marcado
   `<small>` - Texto menor
   `<del>` - Texto excluído
   `<ins>` - Texto inserido
   `<sub>` - Texto subscrito
   `<sup>` - Texto sobrescrito
3. Quotation e Citation

   O Elemento HTML `<blockquote>` (ou Elemento HTML de citação de bloco) indica que o texto incluído é uma longa citação. Normalmente, este é processado visualmente pelo recuo (ver [Notas (en-US)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote#notes "Currently only available in English (US)") sobre como mudá-lo). A URL para a fonte da citação pode ser dada usando o atributo  cite , enquanto uma representação de texto da fonte pode ser dada usando o [`<cite>`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/cite) elemento.

   O elemento HTML `<q>` indica que o texto dentro da tag é uma pequena citação. Este elemento destina-se a citações curtas que não requerem marcações de parágrafo; para citações maiores use o elemento [`<blockquote>`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/blockquote).

   O *Elemento* _HTML `<abbr>` _(ou Elemento de Abreviação HTML) representa uma abreviação e opcionalmente fornece uma descrição completa para ela. Se presente, o atributo **`title`** deve conter a descrição completa e apenas ela.

   O **elemento HTML `<address>`** fornece informações de contato para seu ancestral [`<article>`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/article) ou [`<body>`](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/body) mais próximo; no segundo caso, ele se aplica ao documento inteiro.

   O **elemento** **HTML `<cite>`** representa uma referência a um trabalho artístico. Deve incluir o título do trabalho ou uma URL de referência, que pode ser em uma forma abreviada de acordo com as convenções usadas para a adição dos metadados de citação.

   O ***elemento* HTML `<bdo>` **( *bidirectional override* ) é usado para substituir a direcionalidade atual do texto. Isso faz com que a direcionalidade dos personagens seja ignorada em favor da direcionalidade especificada.
