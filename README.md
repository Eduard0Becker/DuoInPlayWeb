diff --git a/README.md b/README.md
index 6065c85da3dfb71e575bf112b9c258a5312acd60..fdd73101f156d7a159d61741e1516a120a093c50 100644
--- a/README.md
+++ b/README.md
@@ -1,3 +1,55 @@
-<h1 align="center"> Meu Primeiro Projeto </h1>
+<h1 align="center">Duo In Play Web</h1>
+
+<p align="center">Site institucional estático do canal Duo In Play, com páginas de apresentação, sobre e lista de jogos recomendados.</p>
+
+## Páginas
+
+- `index.html`: home com apresentação do canal e links para redes sociais.
+- `about.html`: informações sobre o canal e equipe.
+- `best.html`: seleção dos 10 melhores jogos.
+
+## Tecnologias
+
+- HTML5
+- CSS3
+
+## Melhorias aplicadas
+
+- Ajustes de acessibilidade (descrições de imagens e navegação).
+- Correções de semântica HTML (hierarquia de títulos e elementos).
+- Melhorias de responsividade e manutenção no CSS.
+
+## Como ver as alterações localmente
+
+1. Abra o terminal na pasta do projeto.
+2. Rode um servidor local (Python):
+
+```bash
+python -m http.server 8000
+```
+
+3. Acesse no navegador:
+   - `http://localhost:8000/index.html`
+   - `http://localhost:8000/about.html`
+   - `http://localhost:8000/best.html`
+
+## Como publicar na web (GitHub Pages)
+
+1. Suba os commits para o GitHub.
+2. No repositório, acesse **Settings → Pages**.
+3. Em **Build and deployment**, selecione:
+   - **Source:** `Deploy from a branch`
+   - **Branch:** `main` (ou a branch padrão) e pasta `/ (root)`
+4. Salve e aguarde a publicação.
+5. A URL pública aparecerá na mesma tela do Pages.
+
+## Deploy na Vercel (Node.js 24)
+
+Se a Vercel mostrar erro de versão inválida do Node (`18.x`), este projeto já define Node 24 via `package.json` (`engines.node`) e `.nvmrc`.
+
+No painel da Vercel, confirme também:
+
+1. **Project Settings → General → Node.js Version**
+2. Selecione **24.x**
+3. Faça um novo deploy
 
-![Imagem banner](https://github.com/Eduard0Becker/DuoInPlayWeb/assets/125703447/2a1d59b9-2702-4ed4-b842-11455affdaf9)
