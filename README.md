# Portfólio — Pedro Ivo Gomes

Portfólio profissional de análise de dados hospedado no GitHub Pages.

## 🗂 Estrutura do projeto

```
portfolio-pedro/
│
├── index.html                 ← Página principal do portfólio
│
└── projects/                  ← Subpáginas de cada projeto
    ├── projeto-vendas.html    ← Template de projeto (já preenchido como exemplo)
    ├── projeto-financeiro.html  ← Adicione este próximo
    └── projeto-sql.html         ← Adicione este próximo
```

## 🚀 Como publicar no GitHub Pages

1. Crie um repositório no GitHub com o nome: `seu-usuario.github.io`
2. Coloque todos os arquivos na raiz do repositório (ou em uma branch `main`)
3. Acesse **Settings → Pages** no repositório
4. Em "Source", selecione a branch `main` e pasta `/root`
5. Clique em **Save** — seu site estará em: `https://seu-usuario.github.io`

Ou, se preferir um repositório com nome diferente (ex: `portfolio`):
- O site ficará em: `https://seu-usuario.github.io/portfolio`
- Nesse caso, ajuste os links internos adicionando o prefixo do repositório.

## ✏️ Como personalizar

### Dados pessoais (`index.html`)
Substitua os placeholders em `index.html`:
- `seuemail@email.com` → seu e-mail real
- `linkedin.com/in/seu-linkedin` → seu LinkedIn
- `github.com/seu-github` → seu GitHub

### Adicionar um novo projeto
1. Copie o arquivo `projects/projeto-vendas.html`
2. Renomeie para `projects/projeto-novo.html`
3. Edite o conteúdo: título, descrição, ferramentas, código de exemplo
4. Em `index.html`, adicione um novo card na `.projects-grid`:

```html
<a href="projects/projeto-novo.html" class="project-card">
  <div class="project-thumb blue">
    <span class="thumb-label">Power BI</span>
    <!-- seu visual aqui -->
  </div>
  <div class="project-body">
    <div class="project-name">Nome do Projeto</div>
    <div class="project-desc">Descrição breve do projeto.</div>
    <div class="project-tools">
      <span class="tool-chip">Ferramenta</span>
    </div>
    <div class="project-link">Ver projeto →</div>
  </div>
</a>
```

### Cores disponíveis para cards de projeto
- `.project-thumb.blue` → tema azul (Power BI, SQL)
- `.project-thumb.green` → tema verde (Python, dados)
- `.project-thumb.amber` → tema âmbar (SQL, queries)
- `.project-thumb.purple` → tema roxo (Machine Learning, IA)

## 🛠 Tecnologias
- HTML5 puro — sem frameworks, sem dependências
- Google Fonts (DM Serif Display + DM Sans + DM Mono)
- Compatível com todos os navegadores modernos
