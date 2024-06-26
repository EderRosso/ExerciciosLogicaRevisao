# Exercícios Lógica-Revisao em Java
<img align="center" alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>


Bem-vindo ao repositório do Exercícios Lógica Revisao em Java! Este README fornece um guia passo a passo para clonar o repositório, editar informações localmente e enviar suas alterações de volta para o repositório remoto.

## Índice

- [Downloads Git Bash](#downloads-git-bash)
- [Gerenciador de Credenciais](#gerenciador-de-credenciais)
- [Sua Identidade](#sua-identidade)
- [Clonando o Repositório](#clonando-o-repositório)
- [Editando Informações](#editando-informações)
- [Enviando Alterações](#enviando-alterações)

## Downloads Git Bash
Caso seja necessário baixe o
[Git Bash](https://git-scm.com/downloads).

## Gerenciador de Credenciais
 - Abra o gerenciador de credenciais, selecione Credenciais do Windows.
 <img src="./ex01/img/image.png" alt="Imagem do Gerenciador de Credenciais">

 ---

 - Em `Credenciais do Windows`, selecione `Git:https://github.com`.
 <img src="./ex01/img/image-01.png" alt="Imagem do Gerenciador de Credenciais com uma seleção em amarelo">

---

 - Remova a credencial selecionada.
 <img src="./ex01/img/image-02.png" alt="Logo da Minha Empresa">

## Sua Identidade

Configurar seu nome de usuário e endereço de e-mail. Isto é importante porque cada commit usa esta informação, e ela é carimbada de forma imutável nos commits que você começa a criar:
```bash
 git config --global user.name "Fulano de Tal"
 git config --global user.email fulanodetal@exemplo.br
 ```

## Clonando o Repositório

Para clonar o repositório para o seu computador local, siga os passos abaixo:

1. Abra o terminal, prompt de comando ou Git Bash.
2. Navegue até o diretório onde você deseja clonar o repositório.
3. Execute o comando de clonagem:

    ```bash
    git clone https://github.com/EderRosso/ExerciciosLogicaRevisao.git
    ```

4. Navegue até o diretório do projeto clonado:

    ```bash
    cd ExerciciosLogicaRevisao
    ```

## Editando Informações

1. Abra o projeto em seu editor de código preferido (ex: Net Beans.).
2. Faça as alterações desejadas nos arquivos do projeto.
3. Salve as suas alterações.

## Enviando Alterações

Para enviar suas alterações de volta para o repositório remoto, siga os passos abaixo:

1. Abra o terminal ou prompt de comando e navegue até o diretório do projeto (caso ainda não esteja lá):

    ```bash
    cd ExerciciosLogicaRevisao
    ```

2. Adicione os arquivos modificados para o próximo commit:

    ```bash
    git add .
    ```

3. Faça o commit das suas alterações com uma mensagem descritiva:

    ```bash
    git commit -m "Descrição das alterações feitas"
    ```

4. Envie as alterações para o repositório remoto:

    ```bash
    git push origin main
    ```

    *Nota: Substitua `main` pelo nome da branch apropriada, se for diferente.*



## Contato

Para dúvidas ou sugestões, entre em contato com [`Éder`] via [ederderosso@gmail.com].

---

Este README.md fornece um guia claro para novos contribuidores clonarem, editarem e enviarem suas alterações para o repositório. Certifique-se de substituir `https://github.com/EderRosso/ExerciciosLogicaRevisao.git` pelo URL real do seu repositório e ajustar quaisquer outras informações específicas do seu projeto.