## Informações Importantes Sobre Este Projeto

###### Este projeto faz parte do bootcamp da Dio "Québec Java Digital".

######  Projeto - *Introdução ao Git e ao GitHub*.

###### Desafio do Projeto: *Criando o primeiro repositório no GitHub*																																															

######                                                                                                                                                                                              [Dio._](*https://www.dio.me/*)

___



* ##### Objetivo do Projeto

> *Criar meu primeiro repositório no GitHub.*

Neste projeto, eu tive que cadastrar uma conta no GitHub, e ciar um novo repositório. Depois sinconizar a minha conta do GitHub com a minha máquina(pc) através do Git.

Então, eu criei alguns arquivos dentro de um diretório na minha máquina usando o terminal *"Git Bash"* com alguns comandos básicos, e então, enviei para o meu repositório recém criado fazendo a conexão entre o Git e o GitHub.

___

* **Informações sobre o curso**

> *Aprender o que é Git e GitHub, suas importâncias individuais, comandos, funções, e a diferença entre eles.*



###### *O que eu penso sobre o Git e ao GitHub...*

O *Git* na verdade, é uma ferramenta muito interessante para se utilizar em projetos pessoais e comerciais, através dele podemos obter uma maior organização e controle sobre nossos projetos.

Ele pode agilizar seu fluxo de trabalho em equipe, uma vez que as alterações criadas por cada membro podem ser separadas do projeto inicial, evitando que os arquivos sejam sobrescritos sem controle, e, caso você trabalhe sozinho, ele poupará tempo entre backups de versões anteriores.

Aprendi também, que o *GitHub* é uma plataforma de serviços na Web que oferece funcionalidades extras para o *Git*, além de ser utilizado para hospedar projetos.

Eu vejo que o *GitHub* é bem mais que um local para realizar a hospedagem de projetos. Ele é quase uma “rede social” para desenvolvedores e um portfólio para que as empresas possam ter uma ideia do nosso trabalho.

Resumindo... o *Git* é uma ferramenta que é usada para facilitar a vida de um programador, enquanto o *GitHub* é um serviço que é usado para hospedar projetos Git.
_______________________________________________________



###### *Alguns comandos que eu aprendi no curso para ser aplicado neste projeto*

#### Comandos Básicos

* **ls** 			> *visualizar o que tem dentro do diretório do usuário*

- **cd**            > *navegar entre as pastas listadas do diretório*
- **cd ..**         > *voltar para uma pasta anterior*

- **cd /**         > *voltar ao nível “raiz” das pastas*

- **mkdir**    > *cria uma pasta no diretório em que você está*

- **rmdir**     > *deleta o diretório inteiro e tudo que estiver dentro dele*

- **clear**      > *faz uma limpeza em todos os comandos anteriormente digitados*

> Estes comandos básicos, que aprendi usando o prompt de comando(cmd) e usados no terminal do Git.

___

#### Comandos do Git

- **git config**

> Usado para definir valores de configuração específicos do usuário como e-mail:

​	[		git config --global user.email		]
​	[		git config --global user.name		]

_______________________________________________

- **git init**

> É usado para criar um novo repositório GIT:

​	[		git init		]

________________________________________________

- **git add**

> Usado para adicionar arquivos ao índice. Por exemplo, o seguinte comando irá adicionar um arquivo chamado temp.txt presente no diretório local para o índice:

​	[ git add temp.txt	]

_________________________________________________

- **git clone**

> É usado para fins de verificação de repositório. Se o repositório estiver em um servidor remoto:

​	[		git clone name@01.234.567.89:/path/to/repository		]

___________________________________________________

- **git commit**

> Usado para confirmar as alterações na "cabeça": 

[		git commit –m “projeto-da-dio”		]

___________________________________________________

- **git status**

> Exibe a lista de arquivos alterados juntamente com os arquivos que ainda não foram adicionados ou confirmados:

[		git status		]

____________________________________________________

- **git push**

> Envia as alterações feitas para o ramo mestre do repositório remoto associado ao diretório de trabalho:

[		git push origin master		]

_____________________________________________________

- **git pull**

> Mescla todas as alterações presentes no repositório remoto para o diretório de trabalho local:

[		git pull		]

_____________________________________________________

- git remote

> Permite que um usuário se conecte a um repositório remoto. O comando lista os repositórios remotos atualmente configurados:

[		git remote -v		]

_____________________________________________________

- **git rm**

> Usado para remover arquivos do índice e do diretório de trabalho:

[		git rm filename.text		]