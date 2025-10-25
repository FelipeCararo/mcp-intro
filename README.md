# MCP de Clima do Tempo para os EUA 🌤️

Servidor MCP (Model Context Protocol) que fornece informações sobre o clima dos Estados Unidos.

## 📋 Pré-requisitos

- Node.js (versão 14 ou superior)
- npm (gerenciador de pacotes do Node.js)

## 🚀 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/FelipeCararo/mcp-intro.git
cd mcp-intro
```

2. Instale as dependências:
```bash
npm install
```

## 🔧 Como Usar

### Compilar o projeto

Para compilar o código TypeScript:
```bash
npm run build
```

### Executar o servidor

Após compilar, execute o servidor MCP:
```bash
npm start
```

Ou execute diretamente o comando weather:
```bash
./build/index.js
```

### Script de inicialização

Você também pode usar o script shell incluído:
```bash
./start-mcp.sh
```

## 📦 Estrutura do Projeto

```
mcp-intro/
├── src/           # Código fonte TypeScript
├── build/         # Código compilado (gerado após build)
├── package.json   # Configurações e dependências
├── tsconfig.json  # Configurações do TypeScript
└── README.md      # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **TypeScript** - Linguagem de programação
- **@modelcontextprotocol/sdk** - SDK do Model Context Protocol
- **Zod** - Validação de schemas e tipos

## 📝 Scripts Disponíveis

- `npm run build` - Compila o código TypeScript
- `npm start` - Executa o servidor compilado
- `npm test` - Executa os testes (ainda não implementado)

## 🤝 Contribuindo

Sinta-se à vontade para abrir issues e pull requests no repositório.

## 📄 Licença

ISC

## 🔗 Links

- [Repositório no GitHub](https://github.com/FelipeCararo/mcp-intro)
- [Documentação do MCP](https://modelcontextprotocol.io)
