# relatorio-experimento--Rafael-Pyetro-e-Matheus-




# Introdução

O presente relatório tem como objetivo apresentar de forma detalhada os
procedimentos realizados durante a atividade prática de utilização das
ferramentas **Git** e **GitHub**. A atividade foi estruturada em etapas
sequenciais que abrangeram desde a configuração inicial do usuário no
terminal até a criação de repositórios locais e remotos, além da
tentativa de sincronização com a plataforma GitHub. Por meio dessa
prática, buscou-se consolidar os conceitos de versionamento de código,
organização de arquivos e aplicação dos principais comandos necessários
para o controle e gerenciamento de projetos.



Relatório IFDS:
Foi utilizado diversas ferramentas da plataforma Git para a realização desta atividade e para a realização desta atividade foi necessário diversos procedimentos em 16 etapas as quais serão dissertadas a seguir:

1. Configurar o user e email com os comandos git config --global user.name e git config --global user.email, nos quais em seguidas devem estar entre aspas os respectivos nome e email do usuário.

2. Verificação do user e do email por meio dos comandos git config-l.

3. Abrir o terminal no Linux e entrar no diretório Documentos por meio do comando cd Documentos.

4. Criar dentro do estudante@debian/Documentos>, o seguinte diretório: AulaGit&GitHub com o comando mkdir AulaGit&GitHub.

5. Entre no diretório cd AulaGit&GitHub e apertar enter.

6. Criar dentro do diretório estudante@debian/Documentos/AulaGit&GitHub> um subdiretório chamado Aula07082024 com o comando mkdir Aula07082024.

7. Entrar no diretório criado com o comando cd Aula07082024.

8. Detro do diretório estudante@debian/Documentos/AulaGit&GitHub/Aula07082024> criar um diretório git, executando dentro da pasta que deseja retornar um repositório git o comando git init.

9. Entrar no vscode e criar 5 arquivos com seus respectivos conteúdos. Os arquivos são nome.txt, empresa.txt, exercício.txt, index.html e script.js.

10. Liste os arquivos que estão dentro do estudante@debian/Documentos/AulaGit&GitHub/Aula07082024> com o comando git status.

11. Adicionar os arquivos para a área de preparação com os comandos git add nomeDoArquivo(se for adicionar apenas um) ou o comando git add.(para adicionar todos os arquivos).

12. Enviar os arquivos para o repositório com os comandos git commit nomeDoArquivo -m "texto"(para apenas um arquivo) ou o comando git commit - "texto"(para todos os arquivos).

13. Listar os arquivos que estão no estudante@debian/Documentos/AulaGit&GitHub/Aula07082024> com o comando git status novamente.

14. Remover as configurações locais do git com os comandos git config --global --unset user.name e git config --global --unset user.email.

15. Remover o arquivo com o comando git rm nomeDoArquivo.extensão.

16. Remover o diretório com o comando git rm -r diretório.

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




# Conclusão

A atividade possibilitou a aplicação prática dos principais recursos do
**Git** e a compreensão do processo de integração com o **GitHub**,
ainda que a sincronização com o repositório remoto não tenha sido
concluída devido a limitações técnicas impostas pelo firewall do campus.
Apesar dessa restrição, os passos realizados permitiram explorar desde a
configuração do ambiente até o manuseio de diretórios, arquivos e
commits, reforçando a importância do versionamento no desenvolvimento de
projetos colaborativos. Assim, a experiência contribuiu
significativamente para o aprendizado e familiarização com ferramentas
essenciais ao trabalho em equipe e à organização de código-fonte.
