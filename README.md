# Instalação e Configuração Programas Dev

## Programas que serão instalados

* VsCode
* Intellij
* Visual Studio
* MariaDB
* MongoDB
* Dbeaver
* Github Desktop
* Github
* NVM / Node 14.18.1
### ________________________________________________________________________________________________________________________
### MongoDB
<br>

#### __Para a instalação do MongoDB, utilizar o link abaixo para o download do instalador:__

#### [Link Install](https://agapys365-my.sharepoint.com/:u:/g/personal/nicolas_rocha_agapys_com/EYBdIzJ0_5hHtejwxYr_oZMBqwGJ5NAJZTk00g1R1CJ8UA?e=TYcIoe)

#### Extrair o arquivo .rar e então executar o arquivo mongodb-windows-x86_64-6.0.5-signed.msi.

#### Clicar *Next* na primeira página, aceitar os termos, selecionar a opção de instalação completa e os demais menus selecionar *Next* e *Install*.

#### Finalizada a instalação do MongoDB Compass e aberto o programa, digitar mongodb://localhost:27017 no campo de URI e então conectar.

#### ________________________________________________________________________________________________________________________
### Intellij
<br>

#### __Realizar o download e instalação do Intellij através do site da JetBrains__

#### *[Link Install](https://www.jetbrains.com/pt-br/idea/download/#section=windows)*

<br>

#### __Configuração do Orquestrador__
<br>

* Realizada a instalação e abertura do programa, selecionar a opção *Open*, para abertura de pastas

* Abrir a pasta *C:\git\orchestrator\backend* e clicar em *Trust Project*.

* Já dentro do app, realizar o download do Amazon Corretto v17 em File > Project Structure > SDK > Download SDK

* Selecionado o Amazon Corretto, abrir o menu Maven e clicar em *Reload All Maven Projects*.

* Realizada a sincronização dos projetos, abrir o arquivo RpaApplication.java no caminho *backend/src/main/java/com.agapys.rpa*.

* Assim que aberto o arquivo, executá-lo. Em caso de erro, clicar na opção *Shorten the command line and return*.

* Abrir o arquivo application.properties no caminho *backend/src/,main/java/com.agapys.rpa* e alterar a propriedade __spring.datasource.password__ para "root" (sem as aspas) e executar o arquivo RpaApplication.java novamente.
________________________________________________________________________________________________________________________

### VsCode

#### ________________________________________________________________________________________________________________________
### Visual Studio

#### Para a configuração do Visual Studio, vamos partir do principio em que ele já está instalado na máquina local, e vamos instalar apenas as cargas de trabalho necessárias.

#### Clicar em Ferramentas -> e depois em "Obter Ferramentas e Funcionalidades"
![](imagem) [Adicionar Imagem]

#### Clicar em modificar
![](imagemModificar) [Adicionar Imagem]

#### Adicionar as seguintes cargas de trabalho:

![](imagemCargasTrabalho) [Adicionar Imagem]

#### Clicar para realizar o download e instalar
![](imagemDownloadInstall) [Adicionar Imagem]
________________________________________________________________________________________________________________________
### MariaDB

#### ________________________________________________________________________________________________________________________
### Dbeaver

* Instalação
#### Para realizar a instalação do DBreaver, utilizar o link:
[Link Intall](https://dbeaver.io/download/)
#### Para realizar a instalação, basta continuar clicando Next.

* Importar Banco de Dados
#### Após a instalação, abrir o DBeaver;
#### Clicar para adicionar um novo banco de dados:
![](https://raw.githubusercontent.com/NathanBergmann/Testes/Main/ImagensMd/dbeaverNewDatabase.png)
#### Selecione o tipo do Banco de Dados -> MariaDB
![](https://raw.githubusercontent.com/NathanBergmann/Testes/Main/ImagensMd/dbeaverSelectMariaDb.png)
#### 1- Informar a senha do root:
#### 2- Clicar para testar a conexão:
![](https://raw.githubusercontent.com/NathanBergmann/Testes/Main/ImagensMd/dbeaverTestConection.png)
#### Caso aparece a mensagem de download de Driver, clicar para baixar;
![](https://github.com/NathanBergmann/Testes/blob/Main/ImagensMd/dbeaverDownloadDriverFiles.png?raw=true)
#### Após isso, ele irá informar que foi conectado com sucesso.
![](https://raw.githubusercontent.com/NathanBergmann/Testes/Main/ImagensMd/dbeaverResultConnection.png)

#### Para realizarmos a importação do Banco de Dados, vamos utilizar o dump, localizado no link:
[Link Download Dump](https://agapys365-my.sharepoint.com/:u:/g/personal/nicolas_rocha_agapys_com/ES_UWGg5s1tJq6R0S-lh2l8BpRksbIC09gPehDFyO7xgSg?e=PhYKOb)

#### Clicar no localhost com o botão esquerdo e criar um novo Database:

#### Digitar o nome do Database
![](https://raw.githubusercontent.com/NathanBergmann/Testes/Desk/ImagensMd/dbeaverNameDatabase.png)

#### Selecionar o Database criado, clicar com o botão direito e ir em Restore Database
![](https://raw.githubusercontent.com/NathanBergmann/Testes/Desk/ImagensMd/dbeaverRestoreDatabase.png)
 
#### Selecionar o arquivo dump que baixando anteriormente.
![](C:\git\Testes\ImagensMd\selecetDatabaseImport.png) - [Adicionar Imagem]

#### Após finalizar a importação, o seu DBeaver já está configurado.
________________________________________________________________________________________________________________________
### Git

#### Para instalarmos o Git, vamos utiliza o link:
#### [Link Install](https://git-scm.com/download/win)

#### Iremos realizar a instalação normalmente, clicando nos "Next", porém só deve se atendar quando ele solicitar se deseja fazer a instalação Completa ou Customizada, selecionar a opção "Completa" e continuar clicando no Next.

#### Após a instação, deverá ir na pasta C: do seu computador, e criar a pasta "git".
#### Clicar com o botão direito e abrir o "Git Bah Here", irá abrir o prompt do git.


#### __Configurar usuário Git__
#### Utilizar os códigos a baixo para entrar com seu usuário no git

#### git config --global user.name "Fulano de Tal"
#### git config --global user.email fulanodetal@exemplo.br

#### Ele irá abrir para digitar a senha do git e finalizar o login

### __Clonandos os Reposítorios__
#### __(Importante: Para essa etapa é necessário que o reposítorio esteja compartilhado com sua conta no bitbucket)__
#### [Link BitBucket](https://bitbucket.org/roboteasy/workspace/repositories)

#### Será necessário realizar o clone dos seguintes reposítorios
#### * orchestrator
#### * rpa-agent
#### * front-studio

#### Para realizar o clone, basta digitar no prompt do git o comando:
#### git clone urlDoPRojeto


#### ________________________________________________________________________________________________________________________
### Github Desktop

#### ________________________________________________________________________________________________________________________
### NVM / Node 14.18.1

#### ________________________________________________________________________________________________________________________
