# Minicurso de Introdução ao Git

Bem-vindos! Este repositório será usado para a nossa atividade prática, onde cada um de vocês fará sua primeira contribuição para um projeto usando o fluxo de trabalho básico do Git e do GitHub.

## Atividade Prática: Sua Primeira Contribuição

O objetivo é adicionar um arquivo Python simples com o seu nome ao projeto.

### Passo a Passo

Siga estas instruções com atenção. Os comandos que você precisa digitar no terminal estarão marcados como código.

**1. Faça um Fork do Repositório**

* Clique no botão "Fork" no canto superior direito desta página. Isso criará uma cópia deste repositório na sua conta do GitHub.

**2. Clone o Seu Fork para a Sua Máquina**

* Vá para a página do **seu fork** (ex: `github.com/SEU_USUARIO/minicurso-git`).
* Clique no botão verde "<> Code" e copie a URL HTTPS.
* No seu terminal, execute o comando abaixo, substituindo a URL pela que você copiou:
    ```bash
    git clone [URL]
    ```

**3. Entre na Pasta do Projeto**

* Após clonar, você precisa navegar para dentro do diretório que foi criado.
    ```bash
    cd minicurso-git-aracomp-eniac
    ```

**Atenção: Após isso, dê Ctrl + clique no diretório no terminal para abrir o projeto no VS Code.**

**4. Crie uma Nova Branch**

* Crie uma "ramificação" para trabalhar de forma isolada. Use seu nome ou um apelido para nomear a branch.
    ```bash
    git checkout -b seu-nome-aqui
    ```
    *Exemplo: `git checkout -b evellyn`*

**5. Crie seu Arquivo e Adicione Conteúdo**

* Crie um arquivo Python com o seu nome (ex: `evellyn.py`).
* Dentro do arquivo, adicione um código simples, como:
    ```python
    print("Olá, mundo! Meu nome é Evellyn.")
    ```

**6. Adicione e "Commite" sua Alteração**

* Agora, vamos salvar o seu trabalho no histórico do Git.
    * Primeiro, adicione o arquivo à "área de preparação" (staging area):
        ```bash
        git add .
        ```
    * Depois, crie um "commit", que é um ponto de salvamento permanente, com uma mensagem clara:
        ```bash
        git commit -m "Adiciona arquivo de Evellyn"
        ```
**Atenção: lembre-se de fazer login na sua conta do git. Você pode fazer isso no terminal com o comando `git config user.email "seuemail@email.com"` e `git config user.name "seu nome"`**

**7. Envie sua Branch para o GitHub**

* Envie as alterações da sua branch local para o seu repositório remoto (seu fork).
    ```bash
    git push origin nome-da-sua-branch-aqui
    ```
    *Exemplo: `git push origin evellyn`*

**8. Crie o Pull Request (PR)**

* Volte à página do seu fork no GitHub.
* Você verá um aviso amarelo com o nome da sua branch e um botão "Compare & pull request". Clique nele.
* Na página seguinte, adicione um título (ex: "Adiciona contribuição de Evellyn") e uma breve descrição.
* Clique em "Create pull request".

**Pronto!** Você acaba de solicitar que sua contribuição seja adicionada ao projeto principal.

### O que você aprendeu com isso?

Ao final desta atividade, você terá praticado o ciclo de colaboração mais comum usando Git:

* **Fork e Clone:** Como obter uma cópia de um projeto.
* **Branch:** Como criar um espaço seguro para fazer suas alterações.
* **Add e Commit:** Como salvar seu progresso.
* **Push:** Como enviar suas alterações para o repositório remoto.
* **Pull Request:** Como propor que suas alterações sejam incorporadas ao projeto original.