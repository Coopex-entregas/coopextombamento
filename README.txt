COOPEX • SITE PARA QR NO GITHUB PAGES (SEM SERVIDOR)

OBJETIVO
- Um único site (GitHub Pages).
- Cada QR abre uma página do item usando o código no final do link (hash):
  https://SEUUSUARIO.github.io/coopex-patrimonio/#COOP-000001

O site carrega "items.json" e mostra:
- Descrição
- Local guardado
- Observação
- Foto (se existir em /fotos)

PASSO A PASSO (SEM GIT, SÓ UPLOAD)
1) Crie um repositório no GitHub chamado: coopex-patrimonio
2) Suba (upload) estes arquivos para a RAIZ do repo:
   - index.html
   - items.json
   - pasta fotos/ (mesmo vazia)
3) Ative o GitHub Pages:
   - Repo -> Settings -> Pages
   - Source: Deploy from a branch
   - Branch: main / root
4) Aguarde e abra o site:
   https://SEUUSUARIO.github.io/coopex-patrimonio/

COMO GERAR O QR
- Para cada item, o QR deve conter:
  https://SEUUSUARIO.github.io/coopex-patrimonio/#COOP-000123

COMO CADASTRAR ITENS
- Edite o arquivo items.json e adicione um novo objeto em "items":
  {
    "tombamento": "COOP-000002",
    "descricao": "IMPRESSORA HP",
    "local": "SALA 02 - ARMÁRIO",
    "obs": "sem cabo",
    "foto": "fotos/COOP-000002.jpg"
  }

FOTOS
- Coloque a imagem em: fotos/COOP-000002.jpg
- Suba (upload) a foto para o GitHub junto com o items.json atualizado.

DICA (NÃO DAR 127.0.0.1)
- O QR NÃO pode ser 127.0.0.1.
- Tem que ser o link do GitHub Pages (internet), como acima.
