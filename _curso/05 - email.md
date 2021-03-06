---
title: "Enviando livros por e-mail"
permalink: /curso/email/
excerpt: "Enviando os livros gerados por email"
last_modified_at: 2019-06-06T11:47:50-04:00
toc: true
google: false
---

{% include check-registration.html %} 
{% include find-file.html %}

Neste capítulo vamos mostrar como é possível mandar por e-mail o link para acesso ao livro digital gerado para cada aluno da turma. Como pré-requisito você deverá ter preenchido e gerado os links da planilha apresentada no capítulo [Geração para uma turma]({{site.url}}/curso/turma).

Para o envio do e-mail nós vamos usar o **Google Docs** e o complemento chamado **Zoho**.
Continue lendo abaixo. Vamos mostrar para você como isso funciona. 

## Passo a passo para envio por e-mail
Para enviar os links por e-mail você deverá realizar os passos indicados abaixo:
1. Conferir se todos os e-mails da sua planilha foram preenchidos corretamente. Você encontra a planilha no capítulo [Geração para uma turma]({{site.url}}/curso/turma){:target="_blank"}.
1. O processo de organização e envio por e-mail será feito pelo complemento gratuito chamado **Zoho: Craft, Send, and Track with Mail Merge**.
    1. Clique [neste link](https://chrome.google.com/webstore/detail/zoho-craft-send-and-track/gcmpegnpnldbkaaijmcibgofgpgidlid){:target="_blank"} e siga o passo a passo para autorizar a instalação do complemento **Zoho**.
    1. Caso já tenho o complemento instalado apenas crie um novo documento um [novo documento](http://doc.new){:target="_blank"} no **Google Docs**.
1. Preencher o documento com o texto que fará parte do corpo (ou conteúdo) do e-mail. Um exemplo de texto para o seu e-mail:
    * Você está recebendo um livro digital muito especial, O Nome da Gente, que foi pensado com carinho para unir o prazer da leitura ao processo de alfabetização e, assim, contribuir com o momento em que a criança está descobrindo o mundo das letras e das palavras.<br />
    Acesso o livro aqui:<br /> <br />
    Obrigado e curta muito.
1. Iniciar processo de geração do envio dos e-mails (*mail merge*).
    1. Acessar menu "Complementos \| Zoho: Craft, Send, and Track with Mail Merge \| Start Mail Merge".
1. Preencha os dados solicitados pelo **Zoho**.
    1. Data source -> Escolher **Google Sheet**.
    1. Select a document to merge -> **Current Document**.   
    1. Pressionar o botão **All Set, GO**.
    1. Pressione o botão **Select a Sheet**.
    1. Busque a planilha com o nome **Livros para uma turma (124578)**.
    1. Clique sobre o nome do arquivo e depois pressione o botão **Select**.
1. Selecione as colunas que serão usadas no texto do e-mail.
    1. Select Sheet -> Escolher a planilha com a turma desejada.
    1. Merge Fields -> Clique sobre as colunas e perceba a sua inclusão dentro do texto.
    1. Email To Column -> Certifique-se que a coluna selecionada seja a que contém a lista de e-mails cadastrados.
1. Pressione o botão **RUN MAIL MERGE**.
    1. Subject -> Título do e-mail que será enviado.
    1. To -> Selecionar lista de e-mails que receberão a mensagem.   
    1. Pressione o botão **ADD RECEPIENTS**.
1. Confira um exemplo por maio do botão **PREVIEW**.
1. Envie as mensagens pressionando o botão **SEND NOW**.  

**Dica:** Coloque como último e-mail da turma o seu endereço de e-mail. Desta forma você receberá uma cópia do e-mail tendo a confirmação que o processode envio foi totalmente concluído.
{: .notice--warning}

## Comentários
<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/pt_BR/sdk.js#xfbml=1&version=v4.0&appId=508861006604984&autoLogAppEvents=1"></script>
<div class="fb-comments" data-href="https://personalizar.aprender.digital/curso/email/" data-width="" data-numposts="10"></div>