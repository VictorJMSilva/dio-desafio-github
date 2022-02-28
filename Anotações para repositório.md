# Lógica de programação essencial



- Programar é resolver problemas.
- Busca melhor alternativas de soluções.

- **Metacognição**: Pensar como nos pensamos.

- **Algoritmo**: Sequência de passos que soluciona um problema.

- **Pseudocódigo**: Forma genérica de escrever um algoritmo de forma simples.

  ##### Exemplo:

  1.  Acordar

  2. Levantar

  3. Escovar os dentes

  4. Tomar banho

  5. Se vestir

  6. Tomar café

  7. Escovar os dentes

  8. etc

     

- **Fluxograma**: É uma ferramenta utilizada para representar graficamente o algoritmo.

- **Diagrama de blocos**: Utilizado para representar o método de fluxograma.

- **Variáveis**: Na programação, uma variável é um objeto capaz de reter e representar um valor ou uma expressão.

- **Constantes**: As constantes, são valores imutáveis e não são alterados durante a vida útil do programa.

   **Exemplo**:

   Declarar pi = 3,14... (sempre o mesmo valor portanto uma constante)

   Declarar raio = número (variável)

  Exercício no Flowgorithm

### Tomadas de decisões e expressões

- **Expressões aritméticas**: São expressões que utilizam operadores aritméticos e funções aritméticas envolvendo constantes e variáveis.
- **Operadores aritméticos**

![Operadores aritméticos](https://user-images.githubusercontent.com/91347461/153034780-89a795e3-5296-4fe2-9019-b20ba01c0b21.png)

- **Expressões literais**: São expressões com constantes e ou variáveis que tem como resultado, valores literais.

  **Exemplo**:

​		*variável ou constante*="valor"

​		*nome*="José da Silva"

​		*media*=(nota1+nota2+nota3+nota4)/4

​	

![Exemplo de expressões aritméticas e  literais](https://user-images.githubusercontent.com/91347461/153034296-5b4445d1-0d02-44b8-a545-1758b6a6bb31.png)



- **Operadores relacionados**: São expressões compostas por outras expressões ou variáveis numéricas com operadores relacionados. As expressões relacionadas retornam valores lógicos (Verdadeiro/falso).

![Operadores relacionados](https://user-images.githubusercontent.com/91347461/153033752-457c3d4a-bd7e-4a7f-9925-33612c360af2.png)



- **Tomadas de decisão**: Quando escrevemos programas, geralmente ocorre a necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução.

  **Exemplo**: Site de vendas que só aceita pagamentos por cartão. Quando o cliente não tiver o cartão, não será possível realizar a compra. Quando for variável, utilizar "", apenas quando for texto.

  ![Tomadas de decisão](https://user-images.githubusercontent.com/91347461/153032878-70be9ebf-28fd-4e17-94c1-a3cf7d0fb28e.png)

  

  **Concatenação**: Designa a operação de unir o conteúdo de 2 strings (sequência de caracteres).

- **Exemplo**:

  ![Exemplo de concatenação](https://user-images.githubusercontent.com/91347461/153035269-8ebbf322-3ce2-4777-b9e2-426ef4868d45.png)

# Primeiros passos para desenvolvimento web



- **TCP/IP**

  - Protocolos de comunicação entre computadores em rede

  - Transmission Control Protocol (TCP)

  - Internet Protocol (IP)

  - Modelos de camadas

    **Exemplo**:

    1. Física (ex.: Placa de rede)

    2. Rede (ex.: IP)

    3. Transporte (ex.:TCP, UDP)

    4. Aplicações (ex.:FTP, SMTP, HTTP)

       

       

       ​                  **TCP X UDP**

  

- **UDP**

  - Rápido
  - Não confiável
  - Carro do ovo (dispara a info mas não sabe quem está recebendo)
  - Livestream

- **TCP**

  - Voltado à conexão
  - Handshake (dispara a info e sabe quem está recebendo)
  - Integridade, ordem dos dados.
  - Aplicativo de mensagens de texto

**Portas**(ports)

- As "Ports" por onde dados sairão e chegarão:

  

  - 20: FTP (Apenas para enviar arquivos)
  - 22: SSH (Conexão segura entre computadores)
  - 25: SMTP (Envio de e-mails)
  - 53: DNS (Tradutor para números IP's os endereços dos sites dos navegadores)
  - 80: HTTP (Protocolo de Transferência de Hipertexto. Realiza uma comunicação de sistemas de dados entre servidores e computadores)
  - 443: HTTPS (É a implementação do protocolo HTTP sobre uma camada adicional de segurança que utiliza o protocolo SSL/TLS. Essa camada adicional permite que os dados sejam transmitidos por meio de uma conexão criptografada e que se verifique a autenticidade do servidor e do cliente por meio de certificados digitais.)



**WI-FI**



- IEE 802.11: 2.4 GHz = 2Mbps
- IEE 802.11a: 5 GHz = 54Mbps
- IEE 802.11b: 2.4 GHz = 11Mbps (menos interferência)
- IEE 802.11g: 2.4 GHz = 54Mbps
- IEE 802.11n: 2.4 GHz/5GHz = 150-600Mbps



**Segurança**



- WEP: chaves de 64 bits e de 128 bits
- WPA: chave trocada periodicamente
- WPA2 (AES) (802.11i)
  - +Segurança
  - +processamento



**Web-server**

- Existem 2 tipos: Estático e dinâmico

  - Estático: Servidor físico onde são armazenados arquivos.
  - Dinâmico: Refere-se aos softwares que estão presentes no servidor físico. (RACKS)

  

**Stacks**

- Pilhas de tecnologia.
- Conjunto de softwares necessários e suficientes para executar um app/programa.
- Linguagens de programação.
- Ambientes e ferramentas de interação com o app/sw.
- Capacidade e limitação de performance.
- Pontos fortes e fracos do app/sw.



**Front-end**

- "Parte visual do site,software, app entre outros"
- Interface, UX/UI
- Lógica de programação, HTML(Linguagem de marcação), CSS, jQuery/JS/AJAX, PHP, Bootstrap/ outros frameworks.



**Back-end**

- "Parte de trás"
- Servidores, bancos de dados
- Faz a ponte entre a interface e bancos de dados, regras de negócios, validações.
- MySQL, Oracle, protocolos de comunicação, PHP, Java node.js.



**Fullstack**

- Profissional que sabe trabalhar em ambas as áreas.

![exemplo FBF](https://user-images.githubusercontent.com/91347461/153417697-fa79f8db-8dfd-4c29-b610-32409bb9862c.png)



**Principais Linguagens**(LP)

- HTML (Linguagem de marcação)
- CSS (Linguagem de marcação)
- JavaScript (jQuery, AJAX, diversas libs)
- PHP
- .NET
- ASP
- Java
- Ruby (on Rails)
- Python
- Perl
- C/C++/C#



**XAMPP**

- Configurar o local que o arquivo ficará
- No XAMPP, na linha Apache, clicar em config.
- Abrirá um arquivo de texto e procurar por "DocumentRoot"
- Alterar a linha que estiver "C:...." e Directory.
- Após alterar e salvar, iniciar o apache.
- Se o nome apache estiver verde, está funcionando.



# Introdução ao HTML5 e ao CSS3



## HTML5



- Tim Berners-Lee  criou o HTML

  - HTML 1 - 1991
  - HTML 2 - 1995 
  - HTML 3 - 1997
  - HTML 4 - 1997
  - HTML 5 - 2014

- Com o HTML definimos o significado e a estrutura do conteúdo da web e, além de texto, nossas páginas precisam de imagens, vídeos e vários outros formatos e para isso temos os elementos HTML. Um elemento HTML é formado pela tag de abertura e seus atributos, o conteúdo e uma tag de fechamento. E mais a frente veremos que existem elementos que não tem tag de fechamento.

  

- **Elemento HTML**

![Estrutura html](https://user-images.githubusercontent.com/91347461/153878731-4f530be4-2cbc-47d1-8f2d-ba42237fbfbe.png)



- **Estrutura básica**



​		![Estrutura html 2](https://user-images.githubusercontent.com/91347461/153881647-151ab30b-b17b-4b49-9e2b-6158c15efd66.png)





- **DOCTYPE:** A primeira linha do documento deve ser o <!DOCTYPE html>, apesar de parecer um elemento HTML ela apenas diz ao navegador que ele está lidando com um arquivo do tipo HTML5. Os elementos HTML vem logo abaixo.

- **html:** A tag html é a raiz do seu documento, todos os elementos HTML devem estar dentro dela. E nela nós informamos ao navegador qual é o idioma desse nosso documento, através do atributo lang, para o português brasileiro usamos pt-BR.

- **head:** A tag head contém elementos que serão lidos pelo navegador, como os metadados - um exemplo é o charset, que é a codificação de caracteres e a mais comum é a UTF-8, o JavaScript com a tag script, o CSS através das tags style e link - veremos a diferença quando falarmos sobre CSS - e o título da página com a tag title.

- **body:** E dentro da tag body colocamos todo o conteúdo visível ao usuário: textos, imagens, vídeos.

  

### Semântica

- Durante muitos anos o elemento padrão no HTML era a div, construíamos nosso conteúdo todo baseado nela, e assim nascia a sopa de divs. Mas em 2014 saiu a quinta versão do HTML, e com ela vieram vários mudanças importantes, como performance e acessibilidade, mas nesse curso introdutório vamos focar na semântica. A semântica nos permite descrever mais precisamente o nosso conteúdo, agora um bloco de texto não é apenas uma div, agora é um article e tem mais significado assim. E temos vários elementos para ressignificar as divs.
  - **section:** Representa uma seção genérica de conteúdo quando não houver um elemento mais específico para isso.
  - **header:** É o cabeçalho da página ou de uma seção da página e normalmente contém logotipos, menus, campos de busca.
  - **article:** Representa um conteúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia em uma barra lateral ou um bloco de comentários. Um article pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens.
  - **aside:** É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor e publicidade. Normalmente são representadas como barras laterais.
  - **footer:** Esse elemento representa o rodapé do conteúdo ou de parte dele, pois ele é aceito dentro de vários elementos, como article e section e até do body. Exemplos de conteúdo de um <footer> são informações de autor e *links* relacionados.
  - **h1 - h6:** Eles não foram criados na versão 5 do HTML e nem são específicos para semântica, mas servem para esse propósito. São utilizados para marcar a importância dos títulos, sendo <h1> o mais importante e <h6> o menos. Uma dica: use apenas um <h1> por página, pois ele representa o objetivo da sua página.
  
- **Exemplo**

  - Vamos abrir nosso arquivo index.html e começar pelo cabeçalho: criamos um <header> logo abaixo do <body> e colocamos o título da nossa página dentro de um <h1>.

    Depois criaremos a lista de postagens: abrimos um elemento section e dentro dele adicionamos outro <header> contendo um <h2>. Notem que eu posso ter mais de um <header> na página.

    Para criar nossa postagem adicionamos um <article> com um <header> e um <h3>.

    O último passo desta etapa é criar um rodapé para nossas informações de contato: crie um elemento footer antes de fechar o </body>.

​	

### Textos e links



![Elemento p](https://user-images.githubusercontent.com/91347461/154085639-5ddf1bae-63f5-4ffd-b488-e2a66ab452c8.png)





-  criação do HTML foi motivada pela necessidade de compartilhar textos e documentos, e mesmo depois de quase 30 anos, com toda a evolução da web, isso ainda representa uma boa parte do conteúdo da web.
- O elemento <p> é utilizado em textos maiores. Tag para texto.
- O <p> representa um parágrafo, ele suporta texto, podemos adicionar imagens, código, vídeos e vários outros tipos de conteúdo dentro dele.
- O elemento <a> (anchor), tag para link, ele significa um hyperlink, ele interliga vários conteúdos da internet. O elemento a tem vários atributos, mas vamos focar em dois, o href e o target.
  - O href representa o *hyperlink* para onde sua âncora aponta, pode ser uma página do seu ou de outro site, um e-mail e até mesmo um telefone, os dois últimos precisam dos prefixos mailto: e tel:, respectivamente.
  - O target neste momento vai servir para nos ajudar a abrir nossos links em outra aba do navegador usando o valor _blank.

![tag a](https://user-images.githubusercontent.com/91347461/154086081-42d07fec-615f-4887-b3b6-a032414d9a0f.png)



### Imagens

![imagens](https://user-images.githubusercontent.com/91347461/154095799-9a3f59fc-b0a2-4465-8d4f-bd88bbf26af4.png)



- O elemento img é bem simples, contendo apenas 2 atributos próprios, o src e o alt.
  - O src é obrigatório e guarda o caminho para a imagem que você quer mostrar na página.
  - O alt não é obrigatório mas é altamente recomendado por melhorar a acessibilidade, ele mostra a descrição da imagem caso ela não carregue e leitores de tela usam esse atributo para descrever a imagem para o usuário saber o que ela significa.



### Listas



- lista <ul> a ordem não é importante

  Item 1

  Item 2

- lista <ol> a ordem é importante

  1. Item 1
  2. Item 2

- Lista <li> item da lista

  

Listas servem para agrupar uma coleção de itens, como uma lista de ingredientes ou, como será no nosso caso, uma lista com contatos.

O elemento ul cria uma lista não ordenada, onde a ordem dos elementos não é importante, e é representada com pontos, círculos ou quadrados.

O <ol> serve para criar lista ordenadas, nessas a ordem importa, portanto elas são representadas com números, algarismos romanos ou letras.

E o elemento li é um item dentro de uma dessas listas. Um <li> pode conter vários tipos de conteúdos, como parágrafos, imagens e até outras listas.





## CSS3



- **Definição e seletores**

Após a criação do HTML a necessidade de formatar as páginas ficou evidente, assim, em 1996, foi criada a linguagem de estilo que conhecemos por CSS.

A sintaxe é bem simples e pode ser explicada com a frase "você cria regras de estilo para elementos ou grupos de elementos".

Vamos usar um elemento HTML que vimos anteriormente, a âncora <a>, para exemplificar.

Uma regra CSS é representada por um seletor ou um grupo de seletores, no nosso caso é o <a>, então dentro de um par de chaves adicionamos as declarações, no exemplo acima estamos alterando cor e tamanho da fonte dessa âncora, as declarações são formadas por uma propriedade e um valor.

Percebam que podemos colocar vários seletores em uma regra separando-os por vírgula.

E há um último detalhe nesse exemplo: a pseudo-classe. Elementos HTML sofrem alterações causadas pela interação do usuário, como mover o mouse por cima ou clicar nesse elemento.

O *a:hover* do exemplo significa que a âncora também terá essa aparência quando o usuário passar o mouse por cima de um *hyperlink*.

![Seletores](https://user-images.githubusercontent.com/91347461/154127582-0f3cdf68-663e-4d17-b1bf-88b88bb33e39.png)







- **IDxClasse**

Para ficar mais tangível vamos relembrar um pouco o site que começamos a fazer no módulo passado, ele tinha vários elementos header, mas não vamos querer que o header principal tenha a mesma formatação que o header de uma postagem, é aí que entram os IDs e Classes.

O seletor que vimos no primeiro exemplo é um seletor de tipo, pois ele representa um elemento HTML, e com IDs e Classes podemos representar qualquer tipo de elemento mas há algumas diferenças entre eles:

ID: é representado pelo símbolo # (hash) seguido de um nome para esse ID.

Classe: a classe é representada de forma parecida do ID, mas é precedida por um ponto em vez do hash.

E a diferença mais importante entre eles é a forma como devem ser usados: o ID só pode ser usado uma vez em uma página HTML enquanto a classe não tem restrições.

![idclass](https://user-images.githubusercontent.com/91347461/154127738-8667d674-c74e-4965-acd2-4a03b793333f.png)





- **Box-model**

  

Quando estamos criando o layout de um site o navegador representa cada elemento HTML como uma caixa retangular, isso é o box-model. E com CSS nós alteramos a aparência dessa caixa (largura, altura, cor de fundo, etc.). Essa caixa é composta por 4 áreas: o conteúdo, o padding, a borda e a margem.

- As margens (margin) são espaçamentos entre elementos;
- As bordas (border) ;
- O padding é um espaçamento entre as bordas e o conteúdo, a diferença para as margens é que declarações de imagem de fundo funcionam nele;
- O conteúdo (content) é o que o seu bloco representa, um texto, uma imagem, um vídeo;



![box model](https://user-images.githubusercontent.com/91347461/154128167-09c0641f-2d3f-4179-86bd-c021fb6bf11c.png)



- **Padding e Margin**

​	

Se quisermos atribuir tamanhos diferentes para cada lado do *box* nós podemos. A primeira é colocando um valor para as partes superior e inferior e depois para os lados esquerdo e direito.

O valor de 10 *pixels* se refere ao eixo Y, ou partes superior e inferior, e os 5 *pixels* se referem aos lados esquerdo e direito.

 ![Padding](https://user-images.githubusercontent.com/91347461/154128371-2c1cb2bc-8d8e-4479-b614-3465d5b1b65d.png)

A segunda forma é dando valores para cada lado do *box*.

Então começamos pelo topo com 15 pixels, passamos o lado direito com 10 pixels, depois para a parte inferior com 5 pixels e por último o lado esquerdo com 0, e sempre nessa ordem.

Uma boa dica também é que quando o valor for 0 não precisamos não precisamos colocar a unidade.

 ![padding 2](https://user-images.githubusercontent.com/91347461/154128427-018ff2a4-b37f-4b9d-a697-be868ec786a2.png)

Para o margin se ajustar a telas de diversos tamanhos, usar "auto"

Usar max-width para o conteúdo se ajustar caso o valor da janela seja menor que o estipulado.

A terceira forma é com as propriedades específicas para cada lado, até agora tínhamos visto atalhos para essas propriedades.

Essa opção é mais usada quando temos o mesmo valor para 3 lados, e o quarto precisa ter um valor diferente, então usamos o padding com apenas um valor e uma dessas opções para representar o lado diferente.

![padding 3](https://user-images.githubusercontent.com/91347461/154128519-994e87af-b0a3-4ba6-8356-1f03740d3dd6.png)



​		

- **Background**



E aqui temos 3 formas de colocar uma cor de fundo, e ainda existem outras.

A primeira é pelo nome da cor em inglês, a segunda é pelo código hexadecimal e a terceira é usando apenas o atalho *background*.



![background](https://user-images.githubusercontent.com/91347461/154129068-e4de3fbb-9809-49b4-b8be-91d53ac5ce28.png)



- **Border**



 *border* pode ter 3 valores: a largura, a cor e o estilo, mas existem algumas particularidades nisso.

A largura pode ser usada com várias unidades, como px, em e mm. A cor pode ser atribuída pelo nome ou por um código hexadecimal, assim como fizemos com o *background*, e o estilo é representada por palavras-chave, vamos ver algumas delas:

 

**solid**: mostra uma borda simples e reta;

**dotted**: são bolinhas com um pequeno espaçamento entre elas;

**dashed**: forma uma linha tracejada.

E aproveitando que mostrei esse código temos que falar sobre como separar a estilização dos lados de uma borda.

![border](https://user-images.githubusercontent.com/91347461/154129930-9ea1240d-ddf8-409c-924e-276ed373017b.png)

E se você não quiser usar a propriedade *border* existem as propriedade específicas para cada aspecto de uma borda, são elas *border-width* para a largura, *border-color* para a cor e *border-style* para o estilo.

![border 2](https://user-images.githubusercontent.com/91347461/154130564-9cb12dc4-be94-49ed-80ac-ec069afc9fba.png)



![border 3](https://user-images.githubusercontent.com/91347461/154130631-e3cfcf58-9585-49ba-a5b7-7d4ffa253223.png)



Border-radius

E a última propriedade é o *border-radius*, ele permite arredondar os cantos de um elemento. Podemos usar várias unidades, mas as mais comuns são os pixels e a porcentagem.

Colocando apenas um valor mudamos todos os cantos do elemento, mas seguindo aquela mesma ordem que vimos no *padding* e *margin* - topo, direita, inferior e esquerda - conseguimos alterar cada canto separadamente.



- **Font-Family**

  

![fontfamily](https://user-images.githubusercontent.com/91347461/154134269-fe1d76d8-5386-40cd-861f-4ce2f55baaf6.png)



Com o font-family podemos alterar a fonte dos nossos textos, como uma fonte da internet ou uma que esteja instalada no nosso computador, mas vamos nos ater às fontes seguras, chamadas de web safe fonts.

Essas fontes são chamadas assim pois são encontradas em quase todos os sistemas e podem ser usadas sem preocupação.



- **Font-size**



![font size](https://user-images.githubusercontent.com/91347461/154134483-9a300222-16eb-42ed-95ee-be7aebbdbe19.png)

O font-size nos ajuda a mudar o tamanho do texto, existem algumas unidades de medida para ele mas por enquanto os pixels são suficientes para nós.

- **Font-style**

![font style](https://user-images.githubusercontent.com/91347461/154134553-523a77c5-9fed-4c7c-87c7-bbc6a47df1bb.png)

Usamos o font-style para tornar um texto itálico, na maioria das vezes você usará apenas o valor *italic* para ele, mas se precisar tirar o itálico de um texto você pode usar o valor *normal*.

- **Font-weight**

![font weight](https://user-images.githubusercontent.com/91347461/154134856-49c91e6e-3fd1-4dcb-9bdf-9a626474eed5.png)

Peso da fonte, e caso queira colocar em negrito, digitar "bold".

- **Text-transform**

  ![Texttransform](https://user-images.githubusercontent.com/91347461/154135349-8e1af4e5-bdea-44d5-90d4-c6e557b1d0b2.png)

text-transform coloca todo texto em caixa alta (uppercase)

text-transform coloca todo texto em caixa baixa (lowercase)

text-transform coloca todo as primeiras letras de cada palavra em maiúsculo (capitalize)



- **Text-decoration**

  

![textdecoretion](https://user-images.githubusercontent.com/91347461/154135865-22c1f901-2ced-4db1-987f-490ad0e1a9e9.png)

underline: sublinha a palavra

overline: acima da palavra

line-through: linha cortando a palavra



- **List-style-type** (Lista ordenada e não ordenada)

  

![liststyletype](https://user-images.githubusercontent.com/91347461/154136982-742d7d67-d1a3-49a2-a70d-b3e9653c473b.png)



![liststyleimage](https://user-images.githubusercontent.com/91347461/154137259-f8cc4250-737b-47ba-bd2b-35819f26228b.png)

Para inserir uma imagem





# Bootstrap



- Framework para desenvolvimento de sites responsivos.
- Possui vasta biblioteca de componentes que facilita desenvolvimento de páginas web.
- Um dos frameworks mais conhecidos e usados para front-end.
- Baixar boostrap compilado JS e CSS.
- Arquivos com terminação apenas css são mais pesados. Demora mais para carregar a página.
- Arquivos com terminação min.css são mais leves. Ideal para um carregamento mais rápido da página.
- Div Container não pega a página inteira, para pegar tem que usar container-fluid.





# Recriando a interface do Netflix

- Quando for referenciar um TAG do HTML, não precisa colocar ponto antes. Ex: "header"

- Quando for referenciar uma class, precisa colocar o ponto antes. Ex: ".container"

- Usar *{} para se referir a todo o conteúdo que está dentro do site não fique com espaços.

  Ex: *{

  margin: 0;

  padding: 0;

  box-sizing: border-box; // para delimitar o conteúdo dentro da box

  }
  
- text-decorantion:none (ele remove a linha do texto)

- Para dar efeito de mouse em cima, usar no css :hover

# Introdução ao JavaScript

- Interpretada
- Baseada em protótipos 
- Multiparadigma
- Aplicações 
  - WEB
  - Mobile
  - Smartwatches
  - Games
  - Internet das coisas
  - APIs
- Constantes em JavaScript são escritas em maiúsculo, já variáveis em minúsculo.
- Função
  - function soma (a, b) {
  - return a + b;
  - }
  - O parênteses serve pra declarar parâmetros, tipo function soma (a, b, c ....)
- Array = lista

- var = Escopo global e local, pode ter seu valor alterado, se não tiver um valor inicial será tratada como null;
- let = Escopo local de bloco, pode ter seu valor alterado se não tiver um valor inicial será tratada como null;
- const = Escopo local de bloco, somente leitura, o valor inicial obrigatório e não pode ser alterado.
- Escopo global = Quando a variável é declarada fora de qualquer bloco, sua visibilidade fica disponível em todo código.
- Escopo local = Quando a variável é declarada dentro de um bloco, sua visibilidade pode ficar disponível ou não.

- = é atribuição
- == é para comparação de valores
- === é para comparação de valores e tipos

- && - "e" considera que todos os valores sejam true;
-  || - "ou"  considera que qualquer valor seja true;
- ! - "não" inverte o valor de true para false ou vice-versa;

- forEach() - Itera um array;
- push() - adiciona item no final do array;
- pop() - remover item no final do array;
- shift() - remove item no início do array;
- unshift() - adiciona item no início do array;
- indexOf() - retorna o ínidce de um valor;
- splice() - remove ou substitui um item pelo índice;
- slice() - retorna uma parte de um array existente;

### Orientação a objetos

Paradigmas

- Imperativos: Foca em como você irá solucionar o problema.
- Declarativo: É o que você irá fazer.



- Pilares
  - Herança
  - Polimorfismo
  - Encapsulamento
  - Abstração



- Abstração: Processo que consiste em isolar um aspecto determinado de um estado de coisas relativamente complexo, a fim de simplificar a sua avaliação, classificação ou par a permitir a comunicação do mesmo.

- Herança: Objeto que herda a propriedades e métodos dos objetos anteriores.
- Encapsulamento: Cada classe tem propriedades e métodos independentes do restante do código.
- Polimorfismo: Objetos podem herdar mesma classe pai, mas se comportarem de forma diferente quando invocamos seus métodos.

### Protótipos e classes 

- São esqueletos de todos os objetos. Os objetos JavaScript herdam propriedades e métodos de um prototype. Objeto Object.prototype está no topo desta cadeia.
- Classes: "Syntatic sugar" uma sintaxe feita para facilitar a escrita.

- Constructor: Ele constrói a classe, se você atribuir parâmetros, ele atribui os parâmetros a certos valores dentro da classe.

  - Ex: constructor(type = 'animal'){

    this.type = type

    }

- Getter: Ele retorna o tipo 
- Setter: Determina que outro valor
- Super(): Manda pra função pai os parâmetros que estão nela.
- método: makeSound

## Operadores

Tipos:

- Aritmética

  ![Aritmetica](https://user-images.githubusercontent.com/91347461/155821486-9d57ce4a-ed0d-4020-a409-bc269e2dd912.png)

- Atribuição

  ![atribuiçao](https://user-images.githubusercontent.com/91347461/155821462-af0c6929-fa3b-4609-8504-015256393cd8.png)

- Comparação

  ![comparacao](https://user-images.githubusercontent.com/91347461/155821574-389311a8-7d89-4f2c-9db3-910bc4926b56.png)

- Lógica

  ![logica](https://user-images.githubusercontent.com/91347461/155821632-a6a19ac5-951e-45a6-bd90-3806514ec14e.png)

- Condicional 

​	

![condicional](https://user-images.githubusercontent.com/91347461/155821683-d75fe232-8cf2-4be0-b55f-8c4cdf36cc11.png)

## Funções

- Estrutura:

  - Variáveis criadas dentro de uma função apenas podem ser utilizadas dentro dela.

  - Exemplo:

    function nome(parametros){

    //instruções

    }

  - return: Quando usado, ele para a função e retorna o valor para ser usada em outras funções.

  - Ex:

    const soma = function (a, b) {

    ​	return a + b;

    }

​	

​				soma(1, 2) //3

​				soma(5, 4) //9

### Função autoinvocável

- é uma função anônima entre parênteses, seguidapor outro par de parênteses, seguida por outro par de parênteses, que representa sua chamada.





### Função Callbacks

- Tem maior controle sobre as ordens de chamadas.

  ![callbacks](https://user-images.githubusercontent.com/91347461/155850670-b9576e00-e155-4ae1-9247-1bcbfe0a777b.png)



### Arrays

- Spread: uma forma de lidar separadamente com elementos. O que era parte de um array se torna um elemento independente.



![spread](https://user-images.githubusercontent.com/91347461/155850866-2fa3ce49-04ae-40d3-87a2-32886e61abd0.png)



- Rest: Combina os argumentos em uma array. O que era um elemento independente se torna parte de um array.

  ![rest](https://user-images.githubusercontent.com/91347461/155850951-9dc85914-b274-4c00-a7d5-514eb4798839.png)



### Loops

- if/else: 
  - If: Caso a condição seja verdadeira.
  - else: Caso a condição seja falsa.

![ifelse](https://user-images.githubusercontent.com/91347461/155851684-002e0e8b-2fe9-4a84-a273-569e0fe29683.png)



### Switch

- Usado quando tem muitas verificações a fazer.
  - Equivale a uma comparação de tipo e valor (===).
  - Sempre precisa de um valor "default".
  - Ideal para quando se precisa comparar muitos valores.

![switch](https://user-images.githubusercontent.com/91347461/155852068-bc112aa9-2703-4921-9926-961da84312d7.png)



### For

- for: é um loop dentro de elementos iteráveis (arrays, strings).
- for...in: Loop de propriedades enumeráveis.

![forin](https://user-images.githubusercontent.com/91347461/155852351-97236119-7bf8-433a-a31d-b62659bebadc.png)



- for...of: loop entre estruturas iteráveis (arrays, strings).

![forof](https://user-images.githubusercontent.com/91347461/155852366-c295ae52-bcbd-49b6-852e-de91c98e58cc.png)



### While

- Executa instruções até que a condição se torna falsa.

  ![while](https://user-images.githubusercontent.com/91347461/155852530-1837c094-daca-402b-9b0e-928269e5eeea.png)

- Do...While: Executa instruções até que a condição se torne falsa.

  ![dowhile](https://user-images.githubusercontent.com/91347461/155852543-8482aa31-96a0-4462-8d8c-acdd5f6c1c60.png)



### This

- É uma palavra referência para o contexto que você está.

- No exemplo, this refere-se ao objeto pessoa.

  ![this](https://user-images.githubusercontent.com/91347461/155852654-24cab47c-e498-46f9-9099-e64afa5c5b33.png)

## Coleções

- Map: é uma coleção de arrays no formato [chave, valor]; e pode ser iterado por um loop for...of

- Métodos:

  ![metmap](https://user-images.githubusercontent.com/91347461/155856503-9c68bad5-6d16-4979-9c4b-b6f7ff60692f.png)

- Set: São estruturas que contém valores únicos, que não se repetem nunca.

- Métodos:

![metset](https://user-images.githubusercontent.com/91347461/155856513-1cbdf5b6-778a-4969-9e8a-752bfcd1ba42.png)

- Set vs Array: Possui valores únicos;
- Em vez da propriedade length, consulta-se o número de registros pela propriedade size;
- Não possui os métodos map, filter, reduce etc.



## JavaScript Assíncrono

- Que não ocorre ou não se efetiva ao mesmo tempo.



### Promises

- Inicialmente, seu valor é desconhecido. Ela pode, então, ser resolvida ou rejeitada.
- Tem 3 estados: Pendente, completada ou rejeitada.

### Async/await

- Await para o código para esperar a promisse resolver, aí somente depois o código continua rodando.

### API

- É uma forma de intermediar os resultados do back-end com o que é apresentado no front-end.

  

## D.O.M



- DOM HTML é um padrão de como acessar e modificar os elementos HTML de uma página.

### DOM VS BOM

- BOM: Browser Object Model, é tudo que está dentro do objeto window.

## Debugging e Error Handling

- Error do ECMAScript : Erro que acontece em tempo de execução. Ele avisa que algo não foi declarado, ou faltou alguma pontuação. Composto por: Mensagem, nome do erro, linha do erro e callstack.
- DOMException: Erro relacionado ao DOM.
- Throw: Ela verifica se a string enviada é um palindromo. 
- O return retorna uma string qualquer e o throw retorna o objeto de erro.
- Try...Catch: Verifica se um determinado pedaço de código tem um erro.
- Finally: É uma instrução que vai ser chamada independente se tem um erro ou não.
