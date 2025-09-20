# relatorio-experimento--Rafael-Pyetro-e-Matheus-

Relatório de aula 07/08
Foi utilizado diversas ferramentas da plataforma Git para a realização desta atividade e para a realização desta atividade foi necessário diversos procedimentos em 16 etapas as quais serão dissertadas a seguir:

Configurar o user e email com os comandos git config --global user.name e git config --global user.email, nos quais em seguidas devem estar entre aspas os respectivos nome e email do usuário.

Verificação do user e do email por meio dos comandos git config-l.

Abrir o terminal no Linux e entrar no diretório Documentos por meio do comando cd Documentos.

Criar dentro do estudante@debian/Documentos>, o seguinte diretório: AulaGit&GitHub com o comando mkdir AulaGit&GitHub.

Entre no diretório cd AulaGit&GitHub e apertar enter.

Criar dentro do diretório estudante@debian/Documentos/AulaGit&GitHub> um subdiretório chamado Aula07082024 com o comando mkdir Aula07082024.

Entrar no diretório criado com o comando cd Aula07082024.

Detro do diretório estudante@debian/Documentos/AulaGit&GitHub/Aula07082024> criar um diretório git, executando dentro da pasta que deseja retornar um repositório git o comando git init.

Entrar no vscode e criar 5 arquivos com seus respectivos conteúdos. Os arquivos são nome.txt, empresa.txt, exercício.txt, index.html e script.js.

Liste os arquivos que estão dentro do estudante@debian/Documentos/AulaGit&GitHub/Aula07082024> com o comando git status.

Adicionar os arquivos para a área de preparação com os comandos git add nomeDoArquivo(se for adicionar apenas um) ou o comando git add.(para adicionar todos os arquivos).

Enviar os arquivos para o repositório com os comandos git commit nomeDoArquivo -m "texto"(para apenas um arquivo) ou o comando git commit - "texto"(para todos os arquivos).

Listar os arquivos que estão no estudante@debian/Documentos/AulaGit&GitHub/Aula07082024> com o comando git status novamente.

Remover as configurações locais do git com os comandos git config --global --unset user.name e git config --global --unset user.email.

Remover o arquivo com o comando git rm nomeDoArquivo.extensão.

Remover o diretório com o comando git rm -r diretório.

Parte GitHub

1) Foi criada uma conta no github(https://github.com/)
    A conta foi criada com o mesmo email usado na parte de configurar o git, para que não de erro

2) Foi criado um repositório público 

3) Foi feita a tentaiva de sincronizar o repositório local do git, com o repositório na nuvem do  github
    A sincronização usando o "git push origin main" não conseguiu ser feita, o firewall do Campus bloqueava a comunicação com o github e assim não foi possível fazer o push. Para tentar contornar a situação eu tentei resolver o problema con os seguintes métodos:

Tentativas de resolver o problema: 
1 - Mudar aporta de comunicação do git com o github - Não deu certo
2 - Usar o protocolo SSH ao invés do HTTPS - Não deu certo
3 - Criar um token PAT para fazer a comunicação - Não deu certo