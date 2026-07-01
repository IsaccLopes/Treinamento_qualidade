# Sistema de Treinamentos - Qualidade | V2 Visual

Versão visual redesenhada para ficar mais próxima do painel premium de Qualidade/Laboratório:

- Cabeçalho azul ADM com logo em imagem (`adm-logo.png`).
- Navegação mais limpa e com ícones.
- Cards com visual mais corporativo.
- KPIs e dashboards com estilo mais claro.
- Elementos visuais de laboratório/qualidade no fundo e no painel.
- Mantém o mesmo Supabase e as mesmas tabelas da versão anterior.

## Arquivos para subir no GitHub

Suba/substitua na raiz do repositório:

- `index.html`
- `style.css`
- `app.js`
- `README.md`
- `manifest.json`
- `service-worker.js`
- `icon-192.png`
- `icon-512.png`
- `adm-logo.png`

## Não subir no GitHub público

Não suba a pasta `supabase/import_csv` se ela tiver dados reais.

## Supabase

Não precisa rodar SQL novo apenas para essa mudança visual.

Se for um projeto Supabase novo, edite no `app.js`:

```js
const SUPABASE_URL = "SUA_URL";
const SUPABASE_PUBLISHABLE_KEY = "SUA_KEY";
```

Depois dê commit e force atualização no navegador com `Ctrl + F5`.
