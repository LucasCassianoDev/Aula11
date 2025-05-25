# Projeto JSON + HTML + CSS + JavaScript

Este projeto exibe uma lista de produtos com nome e preço, consumindo os dados de um arquivo JSON local via `fetch`.

## 📁 Estrutura do Projeto

```

jsondiw\_project/
├── db.json
├── package.json
├── package-lock.json
├── README.md
├── prints/
│   ├── print-navegador.png
│   └── print-vscode.png
└── public/
├── index.html
├── script.js
└── style.css

````

## 🚀 Como executar

1. Instale as dependências:
   bash
   npm install


2. Inicie o servidor JSON com:

   bash
   npx json-server --watch db.json --port 3000
   ```

3. Abra o `index.html` em seu navegador com extensão como o Live Server ou direto pelo caminho do arquivo.

## 📦 JSON de exemplo (db.json)

```json
{
  "produtos": [
    {
      "id": 1,
      "nome": "Camiseta",
      "preco": 59.9,
      "descricao": "Camiseta 100% algodão."
    },
    {
      "id": 2,
      "nome": "Tênis",
      "preco": 199.9,
      "descricao": "Tênis esportivo leve e confortável."
    },
    {
      "id": 3,
      "nome": "Tenis",
      "preco": 29.9,
      "descricao": "Tenis Preto."
    }
  ]
}
```

## 🖼 Prints do funcionamento

Os prints estão na pasta `/prints`.


