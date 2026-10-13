# Estrutura Organizada

## Frontend
wwwroot/
├── index.html          # Página principal (carrega js/app.js)
├── styles.css          # Estilos
├── js/
│   └── app.js          # Toda a lógica do frontend
└── fotos/              # Imagens (logo etc.)

## Backend
├── Program.cs          # API e acesso ao banco
├── schema.sql          # Criação das tabelas
├── appsettings.json    # Configurações
└── FabricaPneus.csproj

## Observações
- O app.js foi mantido em um único arquivo para evitar quebrar a lógica de vendas e descontos.
- Em uma próxima etapa podemos dividir em módulos (utils, forms, vendas) se desejar.
