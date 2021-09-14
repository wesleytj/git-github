## (GIT CONFIG GLOBAL) Configurando nosso hambiente
Des o dia 13 de agosto de 2021, não é possível subir os projetos via Git para o GitHub utilizando apenas as credencias de e-mail e senha. Agora precisamos utilizar o Token. Para gerar um novo Token, precisamos realizar o login no GitHub, ir até `Settings` no menu lateral esquerdo em `Developer settings`, depois em `Personal access tokens` e `Generate new token`.
###### Obs. Vale lembrar que você deve salvar seu token em um arquivo .txt, pois depois você não conseguirá visualizar a chave novamente.

##### Configurando o nosso nome
`git config --global user.name "Seu Nome"`
##### Configurando nosso e-mail
`git config --global user.email aquivaio@seuemail.com`
###### Obs. É muito importante você colocar o mesmo e-mail de login do GitHub.

## (GIT INIT) Inicializando o Git

Para inicializar um repositório no git, utilizamos o comando `git init`.
**Exemplo:**
* Crie uma pasta com o nome do repositório que você quer que apareça no GitHub.
* Acesse essa pasta no seu terminal
* Digite o comando `git init` para inicializar o respositório

## (GIT COMMIT) Publicando o enviando o conteúdo para o GitHub 

Após inicializar o git conforme as instruções acima, podemos enviar o nosso repositório local vazio para o GitHub, ou inserir as pastas e arquivos e depois enviar tudo junto.
Vamos publicar nosso primeiro repositório com um arquivo `Readme` pelo menos. Você pode ir até seu repositório navegando pelo GUI e criar o `Readme` utilizando o editor de texto de sua preferência. Ou por linha de comando pela CLI.
Inicialmente vamos fazer da forma mais fácil, vá até seu repositório, crie um arquivo de texto (.txt) manualmente ou pode ser diretamente um markdown (.md).

Após edita-lo e salva-lo da forma que deseja. Acesse seu repositório pelo terminal e siga as intruções abaixo:

* Primeiro, vamos verificar o status que estamos, digite `git status`.
![Verificando status](https://github.com/wesleytj/git-github/blob/main/img/img1.png)<br>
Podemos verificar na imagem que temos nosso arquivo `Readme.md`, porém o mesmo não foi adicionado.
* Então, para isso, vamos adicionar através do seguinte comando: `git add *` || `git add <nome arquivo>`.
Após adicionar o arquivo, digite novamente o comando para verificar o status.
###### Utilize * para adicionar tudo ou digite o nome do arquivo em especifico que deseja adicionar.

![Adicionando arquivos para commit](https://github.com/wesleytj/git-github/blob/main/img/img2.png)<br>
Após adicionar os arquivos, podemos finalmente commitar o nosso projeto para o GitHub.

* Utilizando o comando `git commit -m "Descrição do commit"` 
![Commitando nosso projeto](https://github.com/wesleytj/git-github/blob/main/img/img3.png)<br>
**Congratulations** fizemos nosso primeiro Commit.
