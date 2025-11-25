
<h1 align="center"> PostMolder </h1>

---

⚠️ Para utilizar este projeto, é necessário executá-lo localmente. Não há uma versão pública online, pois ele não está integrado a nenhum sistema no momento.

---
PostModer é uma API REST que utiliza um agente de IA (via OpenAI) para transformar ideias em posts para redes sociais. Basta fornecer o contexto desejado e o conteúdo é gerado automaticamente.
 - "template": Insere um template onde o agente irá apenas completar os espaços.
 - "tonalidade": Especifica qual deve ser o tom do texto imprimido.
 - "limites": Permite que você defina um limite máximo de caracteres para cada campo do template ou do texto final.

## Exemplos de uso
 <img src="https://github.com/MrMarzeero/PostMolder/raw/main/assets/im1.png" width="1000">
  <img src="https://github.com/MrMarzeero/PostMolder/raw/main/assets/im2.png" width="1000">


## Instalação

Depois de baixar o repositório, instale as dependências:
```bash
npm install
```

Crie um arquivo `.env`com:
```bash
OPENAI_API_KEY=your_openai_api_key_here
```

## Execução
Para iniciar a aplicação, execute:
```bash
npm ts-node ./src/index.ts
```

## Documentação:

🟢 GET /api-docs (SwaggerUI)

## Licença  

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.  
