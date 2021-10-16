
# Desafio CSS - Capacitação Enext
  

**Sobre o desafio**

Nesse desafio, vocês terão que estilizar uma página de produto utilizando CSS. Inicialmente o repositório contém apenas o conteúdo HTML da página e algumas linhas de CSS. Vocês devem estilizar o conteúdo existente da página para torná-la mais agradável. O design é livre, o que será avaliado será a consistência do layout (se o layout não quebra, os elementos não se empilham, responsividade (mobile/desktop) e etc.). O conteúdo HTML pode ser totalmente modificado por vocês, sintam-se a vontade para excluir ou adicionar novos conteúdos. Vocês devem clonar esse repositório e trabalhar em cima do código inicial dele, quando finalizarem, devem enviar como resposta o link para o repositório individual de vocês (no Github ou Bitbucket). 

Caso precisem de inspiração para estilizar a página, seguem alguns links de referência:

- [Amazon](https://www.amazon.com.br/Lite-128gb-6gb-RAM-Blue/dp/B08ZN8DBYC?source=ps-sl-shoppingads-lpcontext&psc=1)
- [Kabum](https://www.kabum.com.br/produto/177295/smartphone-xiaomi-mi-11-lite-4g-lte-128gb-8gb-ram-dual-sim-tela-6-55-f90hz-preto?gclid=CjwKCAjwzOqKBhAWEiwArQGwaDRTUyjnl83MZNWWe03OLhLByxDds8InBU5rPSrhpbZGH8gWMyTAChoCrsYQAvD_BwE)
- [Magazine Luiza](https://www.magazineluiza.com.br/mi-11-lite-dual-sim-128-gb-bubblegum-blue-6-gb-ram-azul/p/hhef4jh6b3/te/ceba/?&seller_id=lionshop&utm_source=google&utm_medium=pla&utm_campaign=&partner_id=54222&gclid=CjwKCAjwzOqKBhAWEiwArQGwaIGGtj-WHjLWk1sAOKvlUCXNNRx6XNPZSCLRIpS-KId2nNbxonJ89BoCBz0QAvD_BwE&gclsrc=aw.ds)
- [Americanas](https://www.americanas.com.br/produto/1854257598?pfm_carac=xiaomi&pfm_index=1&pfm_page=search&pfm_pos=grid&pfm_type=search_page&offerId=60e7261b52131c3c817889b9)
- [Casas Bahia](https://www.casasbahia.com.br/smartphone-xiaomi-mi-11-lite-dual-sim-128-gb-bubblegum-blue-6-gb-ram-1516468413/p/1516468413?utm_medium=Cpc&utm_source=GP_PLA&IdSku=1516468413&idLojista=40118&utm_campaign=3P_AllProducts_SSC&gclid=CjwKCAjwzOqKBhAWEiwArQGwaMeqVKgbbKDOFm4pps5ZmlXDLroKxcYGuGl9LdHa_qbCmGCfcT1uahoCunIQAvD_BwE)

**Considerações sobre o repositório**
Inicialmente o repositório contém 4 arquivos .css, o index.css é o arquivo que está linkado ao HTML, e ele é responsável somente por importar  os outros arquivos .css do projeto. 
```
@import  './product.css';
@import  './footer.css';
@import  './global.css';

/* Inicialmente, ele importa esses 3 arquivos, caso criem arquivos diferentes,
vocês podem importá-lo aqui também, ou adicioná-lo direto no header do site
com a tag <link rel="stylesheet" href="caminhoParaOArquivo" /> */
```
Esse tipo de abordagem nos permite criar vários arquivos pequenos e que tenham sentido semântico. Por exemplo, podemos concentrar todo o css do footer da página em um arquivo footer.css, e toda a estilização do produto em um arquivo product.css. Esse tipo de alternativa ajuda com a organização e facilidade de manutenção de código. Quando alguém precisar mexer no seu código terá muito mais facilidade de se localizar dentro do projeto. Manter essa estrutura é opcional, caso desejem vocês podem utilizar todo o css em um único arquivo.

**Referências**
O melhor amigo de um programador são as suas referências e documentações. Vou deixar alguns links que podem ser úteis para o desenvolvimento da atividade, e também para estudos posteriores. Boa sorte galera! Divirtam-se!

- [W3 Schools](https://www.w3schools.com/cssref/) e [Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS)
	A W3 Schools e o Mozilla possuem documentações extremamente vastas das propriedades que podem ser utilizadas no CSS. Os links são seções com algumas propriedades iniciais, mas ao navegar pelo site vocês podem encontrar muito mais coisa! Ambos são ótimas fontes não só para CSS mas pra diversas outras linguagens.
	
- [Media Queries (Responsividade)](https://blog.apiki.com/media-queries-breakpoints-projetos-mobile-first/)
	Vocês sabem o que é responsividade? No front-end damos o nome de responsividade a capacidade do seu site se reposicionar de acordo com a dimensão do dispositivo que está acessando a sua aplicação, de forma a evitar quebras. Esse link oferece uma boa leitura introdutória sobre o tema, que é simples e muito útil no nosso dia a dia de desenvolvimento. Pra quem quiser uma leitura mais avançanda recomendo esse link do [Mozilla](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design).
- [Flex Layout](https://www.alura.com.br/artigos/css-guia-do-flexbox)
	O flex layout é uma nova forma introduzida  no CSS para posicionar os elementos na tela. Hoje é o formato de display mais utilizado na web, pois facilita muito a responsividade e posicionamento dos elementos (centralizados, alinhados a esquerda, direita e etc.). Para quem nunca viu, inicialmente recomendo estudar apenas as propriedades display, flex-direction, justify-content e align-items e entender como os elementos filhos se relacionam com os elementos pais no flex layout. Com isso, vocês conseguirão resolver a grande maioria dos layouts que vão aparecer para vocês durante a sua trajetória como dev.
- [Arte?](https://diana-adrianne.com/purecss-francine/)
	Esse último link é mais uma curiosidade de como o CSS é poderoso e sem limite de uso. Essa arte foi feita exclusivamente utilizando tags de HTML e CSS. Existem muitas outras disponíveis, pra quem quiser se surpreender basta procurar por pure css art. Aqui tem uma [galeria](https://css-art.com/) com algumas disponíveis.

Bons estudos!
