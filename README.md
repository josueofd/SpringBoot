# SpringBoot
Spring Boot 
Usando : https://start.spring.io/
Escolho o projeto, a linguagem;
Coloco o nome e a descrição;
O Pacote e o Java;
Após em Generate;
NA IDE, importo o projeto.
----------------------------------------------------------------------------------------------------------------------------------------

No Guithub
criar novo repositório no guithub
copiar url
dar o gt clone
com o git
git clone htt://...
----------------------------------------------------------------------------------------------------------------------------------------
Comitar (Fonte de pesquisa: http://guides.railsgirls.com/guides-ptbr/github)

Na linha de comando –tenha certeza de que você entrou na sua pasta railsgirls utilizando cd–e insira:

git init
Isso inicializa um repositório git no seu projeto

Nota: Se você já concluiu o guia Heroku, então você já inicializou um repositório git e pode prosseguir para os próximos passos.

Depois, verifique se um arquivo chamado README.rdoc existe na sua pasta railsgirls:

dir README.rdoc
Escolha seu sistema operacional: Windows | Outro
Se o arquivo não existe, você pode criá-lo digitando:

touch README.rdoc
Ou se você está utilizando Windows, digite o seguinte comando:

type nul > README.rdoc
Instrutor(a): Fale um pouco sobre README.rdoc

Então digite:

git status
Isso irá listar todos os arquivos no seu diretório de trabalho.

Instrutor(a): Fale um pouco sobre os seus comandos git favoritos

Então digite:

git add .
Isso adiciona todos os seus arquivos e alterações numa área temporária.

Então digite:

git commit -m "primeiro commit"
Isso commita todos os seus arquivos, adicionando a mensagem “primeiro commit”

Então digite:

git remote add origin https://github.com/usuario/rails-girls.git
A página do seu repositório GitHub mostrará a URL do seu repositório, então sinta-se a vontade para copiar e colar de lá, melhor do que inserir manualmente. Você pode copiar e colar o link da página do seu repositório GitHub clicando em “Clone or download”.

Isso cria um remoto, ou conexão chamado “origin” apontando para o seu repositório GitHub que você acabou de criar.

Então digite:

git push -u origin master
Isso envia seus commits para sua branch “master” no GitHub

Parabéns pelo seu primeiro app no GitHub! Você pode conferir utilizando a mesma url que você utilizou antes: https://github.com/usuario/rails-girls (sem a pasta .git)

Se quiser continuar fazendo alterações e as enviando para o GitHub, você precisará utilizar os três seguintes comandos:

git add .
git commit -m "digite sua mensagem de commit aqui"
git push origin master


