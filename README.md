# Apps

Hub central dos meus apps pessoais, disponível em [apps.felipebabel.com](https://apps.felipebabel.com).

Uma página simples que lista e dá acesso a todos os projetos ativos, lendo os dados de um `apps.json` para facilitar a manutenção.

## Apps cadastrados

| App | Descrição | URL |
|-----|-----------|-----|
| Play | Jogos que estou jogando | [play.felipebabel.com](https://play.felipebabel.com) |
| Watch | Séries e filmes assistidos | [watch.felipebabel.com](https://watch.felipebabel.com) |

## Adicionar um novo app

Edite o arquivo `apps.json` na raiz:

```json
[
  {
    "name": "Nome do App",
    "description": "Descrição curta",
    "url": "https://app.felipebabel.com",
    "icon": "https://app.felipebabel.com/logo512.png"
  }
]
```

## Stack

- HTML + CSS + JS puro
- GitHub Pages com domínio customizado (`apps.felipebabel.com`)
- PWA instalável
