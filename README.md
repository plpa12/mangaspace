# MangaSpace

Site responsivo minimalista para uma comunidade de mangás.

## Como abrir
1. Extraia o ZIP.
2. Abra `index.html` no navegador. Não precisa instalar nada.

## Funcionalidades
- Layout responsivo para desktop e celular.
- Catálogo de mangás e reviews de exemplo editáveis pelo código.
- Busca por título, autor, gênero e texto de review.
- Formulário para publicar reviews com nota, gênero, texto e upload de capa.
- Modal de leitura completa e opção de excluir reviews criadas localmente.
- As reviews ficam salvas no `localStorage` do navegador usado.

## Como colocar suas imagens e reviews
Você pode publicar novas reviews usando o botão **Adicionar review**. Para trocar o conteúdo inicial, edite a lista `starterManga` no fim do `index.html` e adicione o campo `image` com o caminho de uma imagem local, por exemplo `assets/vinland.jpg` (coloque os arquivos na pasta `assets` e ajuste os caminhos).

## Importante: publicação online
Esta versão funciona no navegador e guarda as reviews localmente naquele dispositivo/navegador. Para que uploads e reviews apareçam para todos os visitantes, é necessário hospedar o site e conectar um backend/banco de dados e armazenamento de imagens (por exemplo Supabase). O formulário atual é um protótipo funcional local, não um sistema multiusuário.
