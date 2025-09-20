# Relatório de Experimento
**Autores:** Rafael, Pyetro e Matheus

---

## Introdução

O presente relatório tem como objetivo apresentar de forma detalhada os procedimentos realizados durante a atividade prática de utilização das ferramentas **Git** e **GitHub**. A atividade foi estruturada em etapas sequenciais que abrangeram desde a configuração inicial do usuário no terminal até a criação de repositórios locais e remotos, além da tentativa de sincronização com a plataforma GitHub. Por meio dessa prática, buscou-se consolidar os conceitos de versionamento de código, organização de arquivos e aplicação dos principais comandos necessários para o controle e gerenciamento de projetos.

---

## Relatório IFDS

Foram utilizadas diversas ferramentas da plataforma **Git** para a realização desta atividade. Para isso, foram necessários diversos procedimentos em **16 etapas**, que serão dissertadas a seguir:

### Etapas com Git

1.  **Configurar o user e email** com os comandos `git config --global user.name "nome"` e `git config --global user.email "email"`.

2.  **Verificar a configuração** do usuário e do email por meio do comando `git config-l`.

3.  **Abrir o terminal no Linux** e entrar no diretório `Documentos` com o comando `cd Documentos`.

4.  **Criar o diretório** `AulaGit&GitHub` com o comando `mkdir AulaGit&GitHub` dentro de `estudante@debian/Documentos>`.

5.  **Entrar no diretório** `AulaGit&GitHub` com o comando `cd AulaGit&GitHub`.

6.  **Criar o subdiretório** `Aula07082024` com o comando `mkdir Aula07082024` dentro de `estudante@debian/Documentos/AulaGit&GitHub>`.

7.  **Entrar no diretório criado** com o comando `cd Aula07082024`.

8.  **Iniciar um repositório Git** executando o comando `git init` dentro da pasta `estudante@debian/Documentos/AulaGit&GitHub/Aula07082024>`.

9.  **Criar 5 arquivos com conteúdo** dentro do VS Code. Os arquivos são: `nome.txt`, `empresa.txt`, `exercício.txt`, `index.html` e `script.js`.

10. **Listar os arquivos** dentro do diretório `estudante@debian/Documentos/AulaGit&GitHub/Aula07082024>` com o comando `git status`.

11. **Adicionar os arquivos para a área de preparação** (staging area) com os comandos `git add nomeDoArquivo` (para adicionar um único arquivo) ou `git add .` (para adicionar todos os arquivos).

12. **Fazer o commit dos arquivos** para o repositório com os comandos `git commit -m "texto"` (para todos os arquivos) ou `git commit nomeDoArquivo -m "texto"` (para um único arquivo).

13. **Listar os arquivos novamente** com o comando `git status`.

14. **Remover as configurações locais** do Git com os comandos `git config --global --unset user.name` e `git config --global --unset user.email`.

15. **Remover um arquivo** com o comando `git rm nomeDoArquivo.extensão`.

16. **Remover um diretório** com o comando `git rm -r diretório`.

---

## Parte GitHub

1.  **Criação de conta**: Foi criada uma conta no GitHub (https://github.com/) utilizando o mesmo e-mail configurado no Git para evitar problemas.

2.  **Criação de repositório**: Um repositório público foi criado.

3.  **Tentativa de sincronização**: Foi feita uma tentativa de sincronizar o repositório local do Git com o repositório remoto no GitHub. No entanto, o comando `git push origin main` não pôde ser executado, pois o firewall do campus bloqueou a comunicação com o GitHub.

    **Tentativas para resolver o problema:**
    * Mudar a porta de comunicação do Git com o GitHub. (Não funcionou)
    * Usar o protocolo SSH em vez do HTTPS. (Não funcionou)
    * Criar um token PAT (Personal Access Token) para a comunicação. (Não funcionou)

---

## Conclusão

A atividade possibilitou a aplicação prática dos principais recursos do **Git** e a compreensão do processo de integração com o **GitHub**, ainda que a sincronização com o repositório remoto não tenha sido concluída devido a limitações técnicas impostas pelo firewall do campus. Apesar dessa restrição, os passos realizados permitiram explorar desde a configuração do ambiente até o manuseio de diretórios, arquivos e commits, reforçando a importância do versionamento no desenvolvimento de projetos colaborativos. Assim, a experiência contribuiu significativamente para o aprendizado e familiarização com ferramentas essenciais ao trabalho em equipe e à organização de código-fonte.