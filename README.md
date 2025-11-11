# Eloh Service — Protótipo Navegável (React)

Protótipo front-end para gerenciamento de Ordens de Serviço (OS) com foco em fluxo para técnicos e administrador. Este repositório contém um protótipo React que:
- Permite login por usuário (simulado).
- Cria e lista ordens de serviço.
- Executa ordens com fotos, anotações e assinatura do cliente (canvas).
- Simula modo offline e sincronização (localStorage).
- Fornece um painel admin com filtros e exportação CSV.

Observação importante
O README original continha o próprio código React e estava truncado. Para facilitar manutenção e execução, coloque o código React em `src/App.jsx` (ou `src/App.js`) e mantenha este arquivo apenas para documentação.

Como rodar (exemplo)
1. Instale dependências:
   - npm:
     npm install
   - ou yarn:
     yarn

2. Inicie o servidor de desenvolvimento:
   npm start
   ou
   yarn start

Estrutura recomendada
- src/
  - App.jsx      (componente principal — o protótipo)
  - index.jsx
  - assets/      (logo, ícones, etc.)
- public/
  - index.html

Notas de implementação
- O protótipo usa localStorage para persistência local e simula sincronização.
- A assinatura é salva como dataURL PNG a partir de um canvas.
- Limite de fotos por execução: 5 (ajustável).
- O código disponível em `src/App.jsx` foi também corrigido para remover trechos truncados e erros de sintaxe.

Contribuição
Sinta-se à vontade para:
- Mover o código para componentes separados.
- Adicionar testes.
- Integrar com API real para sincronização.

Licença
Este projeto é um protótipo e pode ser adaptado conforme necessário.