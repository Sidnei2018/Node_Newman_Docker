# Node_Newman_Docker 🌍

API node contendo uma lista criada no banco de dados mysql para<br>
consultas GET, POST, PUT e DELETE.

## Iniciando o processo de configuração do ambiente 🚀<br>

1 - Após a instalação do Docker, acessamos o mesmo pelo terminal do Visual Studio Code para baixarmos as imagens que iremos utilizar!<br>

Documentação Docker:<br>
Para a instalação do Docker no windows = https://docs.docker.com/desktop/install/windows-install/ <br>
Para instalação do Docker no Mac = https://docs.docker.com/desktop/install/mac-install/ <br>
Para a instalação do Docker no Linux = https://docs.docker.com/desktop/install/linux-install/ <br><br>

2 - Dentro de nossa aplicação, baixamos as dependêcias necessárias 🚩<br>

![instalando dependencias](https://user-images.githubusercontent.com/28484134/209213005-e0ea4345-f4ec-4732-a844-e92a38a4f4a4.jpg)<br>

3 - Após instaladas as dependências, utilizaremos uma imagem do mysql baixada via docker 🚩<br>

![utilizando imagem mysql via docker](https://user-images.githubusercontent.com/28484134/209213221-f3d27ec1-2e47-48ee-b65b-702ae4797b43.jpg)<br>

4 - No passo seguinte criamos a conexão com o banco de dados 🚩<br>

![conexao success](https://user-images.githubusercontent.com/28484134/209213508-93d0e329-3f66-4b34-861a-f6bd9854224f.jpg)<br>

5 - Agora acessamos o banco de dados e realizamos a inserção de uma tabela com alguns dados 🚩

![criando tabelas](https://user-images.githubusercontent.com/28484134/209213872-879b6a22-89a7-4ee0-80af-b712c703cf61.jpg)<br>

6 - Com o servidor rodando, acessamos a API via Postman para realizar alguns testes, inserir, alterar, atualizar e apagar dados 🚩<br>

![testando a API get](https://user-images.githubusercontent.com/28484134/209214200-cf137e67-6205-4128-8bb6-3cdcb8e42577.jpg)<br>

7 - Realizamos um teste de coleções 🚩<br>

![testando as colecoes](https://user-images.githubusercontent.com/28484134/209214341-7af17a79-ca2a-41e9-a814-d9bf8ee9251c.jpg)<br>

8 - Com os ambientes de testes finalizados e exportados, realizamos os testes via Newman 🚩<br>

![testes efetuados com newman](https://user-images.githubusercontent.com/28484134/209214607-feacd220-240f-4c94-aa16-5b223312d148.jpg)<br>

9 - Após os testes com Newman, geramos o arquivo HtmlReport via linha de comando 🚩<br>

![gerando o arquivo htmlReport](https://user-images.githubusercontent.com/28484134/209214847-75926075-f77b-4c1b-a36f-d88bdb751cbb.jpg)<br>

10 - Acessando o arquivo HtmlReport via Browser 🌍<br>

![1](https://user-images.githubusercontent.com/28484134/209216044-f4ab509b-7dd8-4c51-8bae-d00f2497d228.jpg)
![2](https://user-images.githubusercontent.com/28484134/209215085-f8f82467-4f33-4671-876d-ffaf598c3ba9.jpg)<br>

