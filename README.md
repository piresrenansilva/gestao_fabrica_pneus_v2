# Fábrica de Pneus — Estrutura Organizada

## Frontend (wwwroot/)
- `index.html` — Página principal
- `styles.css` — Estilos
- `js/app.js` — Lógica da aplicação (navegação, formulários, vendas, máscaras)

## Backend
- `Program.cs` — Endpoints da API e lógica do banco
- `schema.sql` — Script de criação do banco
- `appsettings.json` — Configurações

## Como rodar
1. Configure a connection string no `appsettings.json`
2. Execute o `schema.sql` no SQL Server
3. Rode o projeto (F5 no Visual Studio ou `dotnet run`)
