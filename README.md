# ine5646-tarefa3
Mecanismo de feedback nos posts da Listicle.

Partindo da Listicle modelada com classes (tarefa 2), os alunos devem desenvolver um mecanismo de feedback para cada post.
O mecanismos se baseia em um botão do tipo "Gostei" (like), podendo ter também um botão para "Não Gostei"(dislike, opcional). 
Os botões estão inicialmente opacos e possuem a contagem de likes/dislikes. Ao clicar nesses botões, os usuários terão dois feedbacks:
* O botão perde opacidade
* O contador de likes/unlikes do post aumenta (se ativo) ou diminui (se inativo)

As imagens a seguir mostram *snapshots* da página na versão laptop e mobile:

<div style="display:flex;flex-direction:row">
<img src="/images/snapshot-laptop.png" style="margin:10px" width="400px">
<img src="/images/snapshot-mobile.png" style="margin:10px" width="400px">
</div>

## Requisitos:
* Os botões devem ser tratados com event listeners/handlers
* Botões devem poder ser ativados (clicados) e desativados (desclicados)
* Página deve ser **responsiva**

## Medidas/Fontes:
* As mesmas regras da tarefa 1 devem ser mantidas
* os ícones dos botões de like/dislike possuem altura de 30px e margem de 10px
* a opacidade de botões inativos é de 50%
* o contator de likes/dislikes deve ter fonte na cor darslategray, ocupar 30% da largura do post, possuir margem 0 e padding 0
* botões e contadores na horizontal (usando **flexbox** por exemplo), com alinhamento vertical centralizado

## Versão mobile:
* Na versão mobile, recomenda-se posts ocupando 100% da tela

## Desafios extras (opcional):
* Criar zona de comentários com ícone (tipo pop up de mensagem)
* Ao clicar no ícone, aparece uma área de comentários aparece. Ao clicar novamente, ela desaparece
* Usuários podem submeter um comentário com nome e conteúdo (máximo 150 caracteres)
* Os comentários submetidos são inseridos área de comentários

## Procedimento para entrega e data limite
* Crie um repositório com o nome ine5646-tarefa3 para sua conta Github
* Desenvolva a página nesse diretório/repositório, mantendo o Github atualizado
* Ao concluir, tirar um *snapshot* (dica: extensão *Fireshot* do Chrome gera snapshots contínuos) e enviar **no Moodle**
* A página deve ficar na conta Github do aluno, acessível pelo **Github Pages**
* **Entrega até dia 25-setembro**
* Instruções para criação de uma conta Git e habilitação do Github Pages: https://pt.wikihow.com/Criar-uma-Conta-no-GitHub
* Instruções para habilitar Github Pages: https://docs.github.com/pt/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Bom coding! :smile:
