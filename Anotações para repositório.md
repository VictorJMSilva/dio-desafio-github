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

