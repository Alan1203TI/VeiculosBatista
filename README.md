# Batista Veículos — prévia com identidade do Instagram

Desenvolvida pela Tec Del Rei para apresentação comercial. Não é o site oficial da empresa.

## Abrir

Abra `dist/index.html` no navegador. Não requer instalação nem build. Os arquivos de imagem estão incluídos. Para testar compartilhamento e área de transferência, sirva a pasta `dist` por HTTP em localhost ou HTTPS.

## GitHub Pages

1. Crie um repositório, por exemplo `batista-veiculos-demo`.
2. Envie o conteúdo deste pacote, preservando as pastas `dist` e `.github`.
3. Use a branch `main`.
4. Em Settings → Pages → Build and deployment, escolha GitHub Actions.
5. O workflow incluído publica a pasta `dist` quando houver push na branch `main`, ou por execução manual em Actions.
6. Aguarde a execução e copie o endereço exibido em Settings → Pages.

Este pacote não cria um repositório nem publica automaticamente no GitHub sem essa configuração.

## Implementado

- Identidade visual preta, vermelha e branca, com a logo recortada das referências enviadas.
- Catálogo de 11 anúncios de carros e motos reproduzidos dos prints do Instagram.
- Busca, filtros por tipo, marca e preço publicado, ordenação, favoritos salvos no próprio navegador e botão para exibir mais anúncios.
- Detalhes em modal com a imagem do anúncio, mensagem de interesse para copiar e link compartilhável por veículo.
- Galeria de imagens das publicações, com acesso ao perfil oficial da loja.
- Telefone clicável, endereço e link de localização.
- Layout responsivo e menu para celular.

## Origem e limites das informações

As imagens e os dados foram extraídos exclusivamente dos prints enviados pelo usuário do perfil `@veiculosbatista`. A resolução das fotos e da logo é limitada à dos prints. As imagens da galeria são estáticas: não existe sincronização automática com o Instagram. As capas de vídeo não reproduzem o vídeo; o botão leva ao perfil oficial.

Os preços aparecem como valores informados nas publicações, sem garantia de estoque, vigência ou disponibilidade atual. Dados que não estavam legíveis ou não constavam das referências foram deixados para consulta com a loja.

O telefone (32) 3373-4067 e o endereço Avenida Josué de Queiroz, 1995, São João del Rei, MG, CEP 36305-144 foram transcritos da bio mostrada nos prints. Não foi atribuído WhatsApp a esse número. Os links de contato abrem a ligação ou o perfil oficial; nenhuma mensagem é enviada automaticamente.

Antes de lançar como site oficial, a loja deve confirmar os dados, a disponibilidade e os valores, autorizar o uso do conteúdo e fornecer os arquivos originais para melhorar a qualidade das imagens.

## Estrutura

- `dist/index.html`: página principal.
- `dist/styles.css`: estilos e responsividade.
- `dist/app.js`: catálogo, filtros, favoritos e modais.
- `dist/assets/batista/`: recortes da logo, dos produtos e das publicações enviadas.
- `.github/workflows/pages.yml`: publicação no GitHub Pages.

Não há backend, painel administrativo, formulário persistente, integração de estoque ou simulação de crédito neste conceito.
