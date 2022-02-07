
0.O que são APIs. Para que servem ?
R: É um conjunto de funções que permite a comunicação entre diferentes softwares e linguagens

1.O que são Verbos HTTP ? Quais são eles e o que cada um faz ?
R:São metodos de requisição que são utilizdos para realizar uma ação.
GET = retorna dos dados da requisição.
POST = é usado para inserir dados.
PUT = usado para substituir dados de uma requisição.
PATCH = difefente do PUT, é usado para modificar uma parte específica da requisição.
DELETE = É usado para remover algum recurso.

    1.1. Instale o POSTMAN em sua máquina. OK
    1.2. Para que o POSTMAN é utilizado?
    R: É um software utilizado para o compartilhamento e testes de API's e solicitações HTTP

    2.O que acontece se voce enviar uma requisição GET pelo POSTMAN a sua githubpage ?
    R:  ele vai enviar todas as requisições feitas para webpage

    3.Quando voce acessa uma pagina web pelo navegador, qual é o verbo utilizado ?
     R: É utilizado o comando Get

4. O que são os códigos de status de resposta HTTP ?
R:  São notas que ficam no servidor para informar como as coisas estão funcionando 

4.1 Quais as classes de agrupamento dos status HTTP ?
R: 

Respostas de informação (100-199), 
Respostas de sucesso (200-299), 
Redirecionamentos (300-399),
Erros do cliente (400-499),
Erros do servidor (500-599). 

100s: Códigos informativos indicando que a solicitação iniciada pelo navegador continua.

200s: Códigos de sucesso retornados quando o pedido do navegador foi recebido, compreendido e processado pelo servidor. 
300s: Códigos de redirecionamento retornados quando um novo recurso foi substituído pelo recurso solicitado. 
400s: Códigos de erro do cliente indicando que houve um problema com o pedido 
500s: Os códigos de erro do servidor indicam que a solicitação foi aceita, mas que um erro no servidor impediu o cumprimento da solicitação.

4.2 Quando a requisição HTTP é bem sucedida, qual o código ?
R: 200s

4.3 Qual o status HTTP quando você não é autorizado a acessar um recurso ?
R: 400s

4.4 Listar e descrever a utilização os seguintes códigos de cada agrupamento: 100, 200, 201, 202, 301, 400, 401, 403, 404, 405, 500, 501, 502.

100 = Continue indica que até o momento tudo está OK e que o cliente pode continuar com a requisição ou ignorar caso já tenha terminado.

200 = “Está tudo bem.” Este é o código que é entregue quando uma página web ou um recurso age exatamente da maneira que é esperado.

201 = “Criado.” O servidor cumpriu o pedido do navegador e, como resultado, criou um novo recurso.

202 = “Aceite.” O servidor aceitou o pedido do seu navegador, mas ainda está a processá-lo. O pedido pode ou não resultar em uma resposta completa.

301 = “O recurso solicitado foi movido permanentemente.” Este código é entregue quando uma página web ou recurso foi permanentemente substituído por um recurso diferente. 

400 = “Mau pedido.” O servidor não pode retornar uma resposta devido a um erro no lado do cliente. 

401 = “Não Autorizado” ou “Autorização Necessária”. Isto é devolvido pelo servidor quando o recurso alvo não possui credenciais de autenticação válidas.

403 = “O acesso a esse recurso é proibido.” Este código é devolvido quando um usuário tenta acessar algo que não tem permissão para visualizar. 

404 = “O recurso solicitado não foi encontrado”. Esta é a mensagem de erro mais comum de todas elas. Este código significa que o recurso solicitado não existe, e o servidor não sabe se ele alguma vez existiu.

405 = “Método não permitido“. Isto é gerado quando o servidor de hospedagem (servidor de origem) suporta o método recebido, mas o recurso de destino não suporta.

500 = Indica que encontrou uma condição inesperada e que o impediu de atender à solicitação. Essa resposta de erro é uma resposta genérica "abrangente".

501 = Indica que o servidor não suporta a funcionalidade requerida para completar a requisição. Esta é a resposta apropriada para quando o servidor não reconhece o método requisitado e não tem capacidade de suportá-lo para nenhum recurso.

502 = Indica que ele, enquanto atuando como um servidor intermediário, recebeu uma resposta inválida do servidor para o qual a requisição foi encaminhada.

5. O que é Node.js ?
R: Software que permite a compilação do JavaScript fora de um navegador


5.1 Instale-o em sua máquina, versão LTS v14.17.3 | Listar os comandos que utilizou.
5.2 Para checar se você possui o node:

$ node -v || sudo apt install node
v14.17.3


 6.O que são gerenciadores de pacotes (software)?
R: é uma coleção de ferramentas de software que automatiza o processo de instalação, atualização, configuração e remoção de programas de computador para um sistema operacional de uma maneira consistente.

 6.1 Instale os principais gerenciadores de pacote para a linguagem JavaScript em sua máquina. | Listar os comandos que utilizou.
    6.2 Para checar se você possui os gerenciadores:

$ npm -v || sudo apt install npm
7.24.1

$ yarn -v || sudo apt install yarn
1.22.11

7. Java e JavaScript são a mesma linguagem ? Descreva as diferenças entre essas linguagens e pesquise do porque do nome ser parecido.
Não, Java é focado mais em orientação objeto e JavaScript para web, também é diferente o método de compilação dos dois. Ambos possuem o nome semelhante pois foram desenvolvidos pelos mesmos desenvolvedores

    Você possui o gerenciador de pacotes da linguagem Python em sua máquina?
     R: SIM

    8.1 Caso não tenha, instale o principal gerenciador de pacote para a linguagem python. | Listar os comandos que utilizou.
    8.2 Para checar se você possui o gerenciador de pacote do python (V maisusculo):

$ pip -V || sudo apt install pip
pip 21.3.1

 9.O que é linguagem interpretada ? O que é linguagem compilada ? E hibrida ?
 R: A interpretação ocorre quando o uso (comumente a execução) do código se dá junto à análise do mesmo. A compilação é o processo de análise e possivelmente transformação do código fonte em código alvo, ou seja, o uso (execução, por exemplo) se dá em processo separado posterior, ainda que não tão posterior assim.
A forma híbrida se utiliza de linguagens mais comuns para facilitar a compatibilidade entre diferentes sistemas operacionais. Assim, um único código – geralmente escrito em HTML + CSS + JavaScript – é capaz de fazer um aplicativo multiplataforma.

9.1 Escreva exemplos de linguagens compiladas, interpretadas e hibridas.
Compiladas: Java, C e C#
Interpretadas: PHP, Python e JS
Hibridas: JS, HTML e CSS

9.2 Qual o nome do compilador da linguagem C ?
R: GCC

9.3 Qual o nome do compilador da linguagem Java ?
R:  Javac

9.4 Qual o nome do interpretador do bytecode da linguagem java ?
R: Java Virtual Machine ou JVM

9.5 Qual o nome do interpretador da linguagem JavaScript ? 9.6 Qual o nome interpretador da linguagem Python? 9.7 Python é ou não compilado ? Pesquise e descreva o que encontrar.
R: NodeJS, 

10. O que é POO em programação?
R: Programação Orientada a Objetos.

10.1 Java é totalmente POO. O que é uma classe e o que é um objeto ?
R: Classe é o que utilizamos para atribuir características a um objeto do mundo real. Objeto é a entidade que recebe as características que atribuímos a ele.

10.2 O que é a JVM, JRE e a JDK ? Descreva.
R:
JVM = Java Virtual Machine é onde podemos carregar e testar nossos programas em java.

JRE = É a plataforma em que podemos testar e executar  o código java.

JDK = É um conjunto de utilitários que permitem criar sistemas de software para a plataforma Java.

10.3 Quais os principais gerenciadores de pacote da linguagem java ? 10.4 Instale o Open JDK 11 em sua máquina. | Listar os comandos que utilizou.
R: NetBeans e Eclipse, 

sudo apt install oracle-java11-installer

11. O que é uma IDE, o que é um editor de texto ?
R: IDE é um software onde o desenvolvedor possui várias ferramentas que o auxiliam no desenvolvimento de programas.
Editor de texto é um programa onde o usuário possui livre acesso para escrever qualquer coisa em texto, podendo até mesmo programar porém não irá conseguir compilar o programa.

11.1 Vs Code é uma IDE ou um editor de Texto ?
R:  É uma IDE, pois possui ferramentas que auxiliam no desenvolvimento.

11.2 Instale o Vs Code em sua máquina.
R: instalado 

11.3 IntelliJ é uma IDE ou editor de texto ?
R: IDE

11.4 Instale o IntelliJ em sua máquina
R:  ok

12. O que é docker ?
R: Docker é uma ferramenta que virtualiza programas e os exibindo em forma de contêiner 

12.1 Quais suas vantagens ?
R: Deixa o ambiente de desenvolvimento com uma forma mais ampla.

12.1 Instale o Docker em sua máquina. | Listar os comandos que utilizou.
R: 
1. sudo apt install apt-transport-https ca-certificates curl software-properties-common

2. curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

3. sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

4. sudo apt install docker.io
