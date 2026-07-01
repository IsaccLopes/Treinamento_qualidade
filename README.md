# Sistema de Treinamentos da Qualidade ADM

Versão separada do app de treinamentos, preparada para um novo projeto Supabase / novo banco de dados.

## O que vem no pacote

- `index.html`
- `style.css`
- `app.js`
- `manifest.json`
- `service-worker.js`
- `icon-192.png`
- `icon-512.png`
- `supabase/01_schema_qualidade.sql`
- `supabase/import_csv/colaboradores.csv`
- `supabase/import_csv/treinamentos.csv`
- `supabase/import_csv/matriz_treinamentos.csv`
- `supabase/import_csv/usuarios_app.csv`

## Passo a passo

1. Criar um novo projeto no Supabase, por exemplo `BD_qualidade`.
2. Rodar o SQL `supabase/01_schema_qualidade.sql`.
3. Importar os CSVs da pasta `supabase/import_csv` nas tabelas correspondentes.
4. Criar o usuário da gerência em Authentication > Users.
5. Copiar o User UID e vincular na tabela `usuarios_app`.
6. No arquivo `app.js`, trocar:
   - `COLE_AQUI_A_URL_DO_SUPABASE_QUALIDADE`
   - `COLE_AQUI_A_PUBLISHABLE_KEY_DO_SUPABASE_QUALIDADE`
7. Subir somente os arquivos do app para o GitHub Pages.

## Importante LGPD

Não suba a pasta `supabase/import_csv` no GitHub público. Ela contém dados de colaboradores.
O GitHub deve receber somente o código do app.
