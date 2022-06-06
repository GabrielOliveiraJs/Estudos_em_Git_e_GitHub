# Alguns Comandos Git

### git init
* Inicializa o git no projeto;
* Adiciona a projeto a pasta **.git**
* É essa pasta que o Git utiliza para gerenciar os arquivos do nosso projeto de acordo com os comandos utilizados.

### git add
* **git add nomeDoArquivo** - Adiciona um arquivo em específico;
* **" git add . "** ou **" git add * "** - Adiciona todos os arquivos existentes no respositório;
* Move o arquivo de **Untracked** para **Staged**

### git commit
* **git commit -m "mensagem"**
* Envia os arquivos salvando o estado atual do repositório;
* É criada uma versão do seu arquivo;
* Após o commit, o Git retorna todos os arquivos enviados para o estado de **Unmodified**

### git status 
* Retorna os status atual dos arquivos.

### git config --global
* Acessa a area de configurações globais do Git

* **git config --global user.email "email@exemplo.com"** - Acessa e edita as informações de email do usuário;

* **git config --global user.name "nome"** - Acessa e edita as informações de nome do usuário;
#
# Estados dos arquivos no Git
### Untracked:
* Quando o arquivo foi criado e o git ainda não foi iniciado nele.

### Unmodified:
Arquivos dentro do seu repositório que ainda não sofreram modificação.

### Modified:
* Arquivos que sofreram alguma modificação;
* O Git entende as modificações realizadas ao comparar o sha1 de ambas as versões antes e depois das alterações.

### Staged:
Estado onde os arquivos já estão prontos e ficam "aguardando" o envio final (commit).