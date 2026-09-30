# Redesign Attrium — Site institucional

Hub de parceiros da Attrium Soluções Corporativas: home + páginas dos
parceiros (Thoth Consultoria, Opte+, IEFC e Boomerang). Site estático em HTML/CSS puro.

## Estrutura de pastas

```
attrium-site/
attrium-site/
attrium-site/
attrium-site/
attrium-site/
attrium-site/
attrium-site/
attrium-site/
attrium-site/
├── index.html                 # Home (hub de parceiros)
├── parceiros/
│   ├── thoth/index.html       # Thoth Consultoria
│   ├── opte/index.html        # Opte+
│   ├── iefc/index.html        # Instituto Educacional Futuro da Ciência
│   └── boomerang/index.html   # Boomerang
├── assets/
│   └── img/                   # Imagens do site (quando houver)
└── README.md
```

## Identidade visual — paleta oficial

| Uso | Cor |
|---|---|
| Fundo claro das seções | `#F7F8FA` |
| Branco (cards e manifesto) | `#FFFFFF` |
| Azul-marinho (seções escuras, títulos, rodapé) | `#152438` |
| Dourado — único tom de acento | `#E2A645` |
| Texto corrido | `#525D6E` |
| Texto sobre fundo escuro | `#D1D5DB` |

- **Fontes:** Sora (títulos, bold) e Inter (corpo) — Google Fonts
- **Botões:** formato pill (cantos totalmente arredondados) com seta →
- **Cards:** cantos de 16px e sombra suave, sem sombras pesadas
- As variáveis ficam no bloco `:root` no topo do `<style>` de cada arquivo —
  para ajustar as cores do site inteiro, altere só esse bloco em cada página

## Como publicar na Vercel

1. Suba esta pasta para um repositório no GitHub
   (New repository → upload dos arquivos → Commit changes).
2. Acesse vercel.com e entre com a sua conta do GitHub.
3. Clique em "Add New..." → "Project" → importe o repositório.
4. Em Framework Preset, deixe "Other" (site estático) e clique em "Deploy".
5. Pronto: o site fica no ar em `https://nome-do-projeto.vercel.app`

## Como atualizar

Edite os arquivos no GitHub (ou envie versões novas) — a Vercel publica
automaticamente cada alteração na branch main.

## Domínio próprio (opcional)

Na Vercel: Settings → Domains → adicione o domínio e siga as instruções
de DNS do seu registrador.
