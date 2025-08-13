# fa106400.github.io

Site pessoal hospedado no GitHub Pages.

## Configuração

1. Clone o repositório:
```bash
git clone https://github.com/fa106400/fa106400.github.io.git
cd fa106400.github.io
```

2. Instale as dependências:
```bash
npm install
```

## Desenvolvimento

Para desenvolvimento local, você pode usar qualquer servidor HTTP simples. Por exemplo:

```bash
# Usando Python
python -m http.server 8000

# Usando Node.js (se tiver http-server instalado)
npx http-server
```

## Deploy

### Deploy da pasta atual (recomendado para sites simples)
```bash
npm run deploy
```

### Deploy da pasta dist (para projetos com build)
```bash
npm run build
npm run deploy:dist
```

Ou diretamente:
```bash
gh-pages -d dist
```

## Estrutura do Projeto

- `index.html` - Página principal
- `CNAME` - Configuração de domínio personalizado (se aplicável)
- `package.json` - Configurações do projeto e scripts
- `.gitignore` - Arquivos ignorados pelo Git

## GitHub Pages

O site está configurado para ser hospedado em: https://fa106400.github.io

O deploy é feito automaticamente para a branch `gh-pages` quando você executa o comando de deploy. 