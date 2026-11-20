# CLAUDE.md — Site Lustoza Store (lustozastore.com.br)

Site estático (HTML puro) da Lustoza Store, loja de eletrônicos e iPhones com entrega grátis em Salvador, Lauro de Freitas e Feira de Santana. Dono: Gabriel. Responda em português, curto e direto.

## Como é publicado
- Repositório `gabrielustozacont-cmd/lustoza-site`, branch `main`, publicado pelo GitHub Pages. Cada push na `main` atualiza o site.
- **Só fazer commit e push quando o Gabriel pedir.** Mensagem de commit curta, em português.
- Antes de enviar, abrir os arquivos alterados e conferir links e imagens.

## Estrutura
- `index.html`: página inicial (seções de produtos, motos, lançamentos e clientes, com fotos que abrem ampliadas ao clicar).
- `troca/`: formulário "Troca ou Venda de iPhone" (o cliente toca nas opções e no fim abre o WhatsApp com a mensagem pronta). Link: https://lustozastore.com.br/troca/ . É esse link que vai no atalho `/troca` do WhatsApp Business.
- `duvidas/`: artigos de dúvidas para o Google (cada artigo numa subpasta com `index.html`).
- `produtos/`, `motos/`, `lancamentos/`, `clientes/`: fotos usadas nas seções.
- `CNAME`, `robots.txt`, `sitemap.xml`, `google2a585459e100c8fa.html`, `favicon.jpg`, `logo.jpg`.

## Regras
- **Nunca alterar nem apagar** `CNAME` (mantém o domínio) e o arquivo `google...html` (verificação do Google).
- Página ou artigo novo: criar a pasta com `index.html` e acrescentar no `sitemap.xml`.
- Cores da marca: preto e dourado (logo da coroa).
- Não escrever preços nem inventar informação de produto. Se não souber o modelo ou o preço, perguntar ao Gabriel.
- Fotos novas: reduzir o tamanho antes de colocar, para a página não ficar pesada.
- Alteração pequena = edição pontual no arquivo. Não reescrever a página inteira.
