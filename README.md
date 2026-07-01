# Calculadora do Cruz

Calculadoras clínicas de bolso, em espanhol (padrão) e português. Roda 100% no navegador, sem servidor nem banco de dados — pode ser hospedada de graça no GitHub Pages.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (pode ser público ou privado, mas o GitHub Pages gratuito exige público em contas free).
2. Suba estes arquivos para a raiz do repositório: `index.html`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`, `favicon-32.png`.
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch `main` e a pasta `/ (root)`. Salve.
5. Em alguns minutos o GitHub mostra o link, algo como `https://seu-usuario.github.io/nome-do-repo/`.

## Como instalar no iPhone

1. Abra o link publicado no **Safari** (precisa ser o Safari — o Chrome no iOS não tem essa opção).
2. Toque no ícone de compartilhar (o quadrado com a seta para cima).
3. Escolha **"Adicionar à Tela de Início"**.
4. O app aparece com ícone próprio e abre em tela cheia, sem a barra do navegador.

## Estrutura

- `index.html` — o app inteiro (HTML, CSS e JavaScript em um único arquivo).
- `manifest.webmanifest` — metadados usados por navegadores baseados em Chromium para a instalação como app.
- `icon-*.png`, `favicon-32.png` — ícones gerados a partir de `logo.svg`.
- `logo.svg` — a arte-fonte da logo, caso queira gerar novos tamanhos ou editar.

## Calculadoras incluídas

**Geral:** IMC, MELD
**Cardiologia:** CHA₂DS₂-VASc, Wells (TEP), HEART score, GRACE score
**Nefrologia:** Clearance de creatinina (Cockcroft-Gault), TFG estimada (CKD-EPI 2021), FeNa, Anion gap, Sódio corrigido por glicemia
**Emergência:** qSOFA, Escala de coma de Glasgow

Todas as fórmulas são de literatura médica pública. Os textos, o design e o código são originais.
