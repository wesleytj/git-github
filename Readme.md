# (GIT CONFIG GLOBAL) Configurando nosso hambiente

# (GIT INIT) Inicializando o Git

Para inicializar um repositório no git, utilizamos o comando `git init`.
**Exemplo:**
* Crie uma pasta com o nome do repositório que você quer que apareça no GitHub.
* Acesse essa pasta no seu terminal
* Digite o comando `git init` para inicializar o respositório

# (GIT COMMIT) Publicando o enviando o conteúdo para o GitHub 

Após inicializar o git conforme as instruções acima, podemos enviar o nosso repositório local vazio para o GitHub, ou inserir as pastas e arquivos e depois enviar tudo junto.
Vamos publicar nosso primeiro repositório com um arquivo `Readme` pelo menos. Você pode ir até seu repositório navegando pelo GUI e criar o `Readme` utilizando o editor de texto de sua preferência. Ou por linha de comando pela CLI.
Inicialmente vamos fazer da forma mais fácil, vá até seu repositório, crie um arquivo de texto (.txt) manualmente ou pode ser diretamente um markdown (.md).

Após edita-lo e salva-lo da forma que deseja. Acesse seu repositório pelo terminal e siga as intruções abaixo:

* Primeiro, vamos verificar o status que estamos, digite `git status`.
![Verificando status](img1)
Podemos verificar na imagem que temos nosso arquivo `Readme.md`, porém o mesmo não foi adicionado.
* Então, para isso, vamos adicionar através do seguinte comando: `git add *` || `git add <nome arquivo>`.
Após adicionar o arquivo, digite novamente o comando para verificar o status.
###### Utilize * para adicionar tudo ou digite o nome do arquivo em especifico que deseja adicionar.

![Adicionando arquivos para commit](img2)
Após adicionar os arquivos, podemos finalmente commitar o nosso projeto para o GitHub.

* Utilizando o comando `git commit -m "Descrição do commit"` 
![Commitando nosso projeto](img3)
**Congratulations** fizemos nosso primeiro Commit.
