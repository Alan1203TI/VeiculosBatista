# Batista Veículos — site para GitHub Pages

Pacote com a página e os arquivos diretamente na raiz, preparado pela Tec Del Rei.

## Corrigir a publicação existente

1. Extraia este ZIP no seu computador.
2. Abra o repositório VeiculosBatista no GitHub e clique em Add file → Upload files.
3. Envie o conteúdo extraído: index.html, styles.css, app.js, a pasta assets e este README.md. Envie os arquivos na raiz do repositório, sem criar uma pasta externa. Inclua .nojekyll se ele estiver visível no seu computador; o layout deste site não depende dele.
4. Clique em Commit changes na branch main. Se sua branch de publicação tiver outro nome, use essa branch.
5. Em Settings → Pages, selecione Source: Deploy from a branch; Branch: main; pasta: /(root); clique em Save.
6. Aguarde a conclusão da publicação em Actions e abra o endereço exibido pelo próprio GitHub Pages. Atualize com Ctrl+F5 se ainda aparecer a versão antiga.

A raiz deve conter index.html, styles.css, app.js e assets/. A pasta dist da versão anterior pode permanecer no repositório, mas não é usada por esta configuração. Não envie apenas o ZIP fechado.

Este pacote não exige instalar dependências, compilar arquivos ou adicionar um workflow próprio de GitHub Actions.

## O que foi corrigido

Na versão anterior, a página principal estava em dist/index.html e dependia de um workflow que publicasse a pasta dist. Quando o Pages publica a raiz do repositório, o README pode ser usado como página inicial na ausência de index.html. Esta versão coloca a página, o CSS, o JavaScript e as imagens na raiz e usa caminhos relativos, inclusive para repositórios publicados em subpastas como /VeiculosBatista/.

## Conteúdo da prévia

Logo e imagens recortadas dos prints fornecidos do Instagram da Batista. Catálogo de 11 anúncios, filtros, ordenação, favoritos locais, modais, galeria de publicações, telefone e endereço reproduzidos da bio enviada. Preços e disponibilidade devem ser confirmados com a loja. A galeria é estática e não sincroniza com o Instagram. A resolução das imagens é a dos prints. Não há backend nem painel administrativo.

Prévia conceitual da Tec Del Rei, sem vínculo oficial com a Batista Veículos.
