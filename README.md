# Desafio de Projetos GIT/GITHUB 

## Repositorio para desafio de projetos

#### Syntaxe MARKDOWN
https://www.markdownguide.org/basic-syntax/

principais comando utilizados 

#### COMO CLONAR E INSTALAR AS DEPENDÊNCIAS DE UM PROJETO DO <a href ="https://www.youtube.com/watch?v=zje2h2nlVh8"><strong>GIT/GITHUB</strong></a>


git status (Comando para saber qual status atual)

git add . (Adiciona todos os arquivos)


<h2><strong>🪟 WINDOWS</h2></strong>

<h3>🔺 Instalação JDK Zulu</h3>

Aqui no windows, vamos fazer o download do <strong>OpenJDK Zulu</strong>.
<em>As compilações do Azul Zulu do OpenJDK são compilações de código aberto, testadas pelo TCK e certificadas do OpenJDK. O Zulu Blue está disponível para uma ampla variedade de plataformas de hardware e sistemas operacionais. A documentação do Azul Zulu inclui notas de lançamento, um guia de instalação e licenças de terceiros.</em>

🔹 <strong>1.</strong> Entre no <a href="https://www.azul.com/downloads/?package=jdk"><strong>SITE AZUL</strong></a>

🔹 <strong>2.</strong> Faça o download do arquivo .zip do JDK 11.0.11+9. No meu caso, o x86 64-bit

🔹 <strong>3.</strong> Vá no drive C://Arquivo de Programas

🔹 <strong>4.</strong> Caso não tenha um diretório com o nome Java, crie

🔹 <strong>5.</strong>  Entre neste diretório e descompacte o download do zip JDK Zulu 11.0.11+9 neste diretório

🔹 <strong>6.</strong> Vamos configurar o ambiente JAVA_HOME:

​	<strong>6.1</strong>  Menu iniciar -> Editar as varáveis de ambiente do sistema

​	<strong>6.2</strong> Irá abrir a janela Propriedades do Sistema, escolha a aba Avançado, em seguida clique em variáveis de Ambiente

​	<strong>6.3</strong> Na janela Variáveis de Ambiente,  crie um novo Variáveis do sistema

​	<strong>6.4</strong> Abrirá uma jabela: Nova Variável de Sistema.

​	<strong>6.5</strong> Nome da variável: JAVA_HOME

​	<strong>6.6</strong> Valor da variável: em seguida OK.
​	<em>O valor da variável é o caminho do diretório que você descompactou o zip JDK Zulu 11.0.11+9 no passo 5 </em>

​	<strong>6.7</strong> Na mesma janela Variáveis do Sistema, localize a variável Path, selecione e clique a opção Editar...

​	<strong>6.8</strong> Clique na opção Novo e cole o mesmo caminho do passo 5 acrescentando \bin

​	<strong>6.9</strong> Continue com o path selecionado e clique na opção Mover para Cima até chegar no topo

🔹 <strong>7.</strong> Pronto, finalizada a configuração. Próximo passo é conferir se está instalado tudo certinho

🔹 <strong>8.</strong> Abra o Prompt de Comando: Menu iniciar -> cmd

🔹 <strong>9.</strong> Vamos conferir mais uma vez se o Java está instalado na nossa máquina

```
java -version
```

<p align="right"><em>Créditos: <a href="https://www.youtube.com/watch?v=laC0fiI-IOM">DevSuperior</a></em></p>

<br>

<h3>🔺 Instalação Eclipse </h3>

🔹 <strong>1.</strong> Acessar o site oficial do <a href="https://www.eclipse.org/downloads/"><strong>ECLIPSE</strong></a>

🔹 <strong>2.</strong> Fazer o download do instalador

🔹 <strong>3.</strong> Escolha segunda a opção: Eclipse IDE for Enterprise Java and Web Developers <a href="https://www.eclipse.org/downloads/packages/"><strong>Link de download para Windows</strong></a>

🔹 <strong>4.</strong> Clique no folder da primeira opção (Java 11 + VM) e selecione o JDK que instalamos na nossa máquina

🔹 <strong>5.</strong> Mantenha as opções "create start menu entry" e "create desktop shortcut"

🔹 <strong>6.</strong> Install

🔹 <strong>7.</strong> Accept now

🔹 <strong>8.</strong> Launch

🔹 <strong>9.</strong> Pronto, intalação concluída

<br>

<h3>🔺 Instalação IntelliJ IDEA Community </h3>

🔹 <strong>1.</strong> Entre no site ofical do <a href="https://www.jetbrains.com/idea/download/#section=windows"><strong>INTELLIJ</strong></a>

🔹 <strong>2.</strong> Escolha a opção Community e faça o download 

🔹 <strong>3.</strong> Siga com next

🔹 <strong>4.</strong> Na opção Installation Options, deixe selecionado as opções:
	<strong>4.1</strong> 64-bit launcher (caso seu sistema seja 64-bit, caso não, selecione 32-bit)
	<strong>4.2</strong> Add "Open Folder as Project"
	<strong>4.3</strong> .java - .groovy - .kt - .kts
	<strong>4.4</strong> Add lauchers dir to the PATH
	<strong>4.5</strong> Next

🔹 <strong>5.</strong> Install

🔹 <strong>6.</strong> Para finalizar a instalação, escolha a opção reebot later

🔹<strong>7.</strong> Com o IntelliJ já instalado, vamos iniciar:

​	<strong>7.1</strong> Aceite os termos: I confirm that I have... >> Confirm

​	<strong>7.2</strong> Data Sharing >> Send Anonymous Statistics

🔹<strong>8.</strong> IDE pronta para uso!

<br>

<h3>🔺 Instalação Git </h3>

🔹 <strong>1.</strong> Entre no site ofical do <a href ="https://git-scm.com/downloads"><strong>GIT</strong></a>

🔹 <strong>2.</strong> Escolha a opção Windows e o instalador será baixado automáticamente

🔹 <strong>3.</strong> Mantenha as opções pré selecionadas e siga com Next

🔹 <strong>4.</strong> Install

🔹 <strong>5.</strong> Antes de finaizar a instalação, selecione a opção Lauch Git Bash 

🔹<strong>6.</strong> Ao finalizar o passo 5, irá abrir o Git Bash

🔹<strong>7.</strong> Agora vamos fazer as configurações iniciais:

🔹<strong>8.</strong> Confirme se o git realmente está instalado:

```
git --version
```

🔹<strong>9.</strong> Vamos começar as configurações iniciais:

​	<strong>9.1</strong> Configurar o nome de usuário

```
git config --global user.name "Seu nome"
```

​	<strong>9.2</strong> Configurar o endereço de e-mail:
​	<em>É de suma importância que o ENDEREÇO DE E-MAIL SEJA O MESMO DO GITHUB afim de evitar conflitos!</em>

```
git config --global user.email seuemail@email.br
```

​	<strong>9.3</strong> Vamos conferir a lista de configurações:

```
git config --list
```

🔹<strong>10.</strong> Pronto, git instalado e configurado com sucesso!
