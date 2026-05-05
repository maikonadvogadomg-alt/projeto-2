# PLANO DO PROJETO: HTML/CSS/JS

> Gerado automaticamente pelo SK Code Editor em 05/05/2026, 15:37:42
> **226 arquivo(s)** | **~46.445 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React, TypeScript

**Para rodar o projeto:**
```bash
# Abra index.html no Preview (botao Play)
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS/
├── apk-builder/
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── public/
│   │   ├── favicon.svg
│   │   ├── icon-192.svg
│   │   ├── icon-512.svg
│   │   ├── manifest.json
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   │   └── ui/
│   │   │       ├── accordion.tsx
│   │   │       ├── alert-dialog.tsx
│   │   │       ├── alert.tsx
│   │   │       ├── aspect-ratio.tsx
│   │   │       ├── avatar.tsx
│   │   │       ├── badge.tsx
│   │   │       ├── breadcrumb.tsx
│   │   │       ├── button-group.tsx
│   │   │       ├── button.tsx
│   │   │       ├── calendar.tsx
│   │   │       ├── card.tsx
│   │   │       ├── carousel.tsx
│   │   │       ├── chart.tsx
│   │   │       ├── checkbox.tsx
│   │   │       ├── collapsible.tsx
│   │   │       ├── command.tsx
│   │   │       ├── context-menu.tsx
│   │   │       ├── dialog.tsx
│   │   │       ├── drawer.tsx
│   │   │       ├── dropdown-menu.tsx
│   │   │       ├── empty.tsx
│   │   │       ├── field.tsx
│   │   │       ├── form.tsx
│   │   │       ├── hover-card.tsx
│   │   │       ├── input-group.tsx
│   │   │       ├── input-otp.tsx
│   │   │       ├── input.tsx
│   │   │       ├── item.tsx
│   │   │       ├── kbd.tsx
│   │   │       ├── label.tsx
│   │   │       ├── menubar.tsx
│   │   │       ├── navigation-menu.tsx
│   │   │       ├── pagination.tsx
│   │   │       ├── popover.tsx
│   │   │       ├── progress.tsx
│   │   │       ├── radio-group.tsx
│   │   │       ├── resizable.tsx
│   │   │       ├── scroll-area.tsx
│   │   │       ├── select.tsx
│   │   │       ├── separator.tsx
│   │   │       ├── sheet.tsx
│   │   │       ├── sidebar.tsx
│   │   │       ├── skeleton.tsx
│   │   │       ├── slider.tsx
│   │   │       ├── sonner.tsx
│   │   │       ├── spinner.tsx
│   │   │       ├── switch.tsx
│   │   │       ├── table.tsx
│   │   │       ├── tabs.tsx
│   │   │       ├── textarea.tsx
│   │   │       ├── toast.tsx
│   │   │       ├── toaster.tsx
│   │   │       ├── toggle-group.tsx
│   │   │       ├── toggle.tsx
│   │   │       └── tooltip.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   ├── android.ts
│   │   │   ├── archive.ts
│   │   │   ├── github.ts
│   │   │   ├── storage.ts
│   │   │   └── utils.ts
│   │   ├── pages/
│   │   │   └── not-found.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   ├── components.json
│   ├── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── vite.config.ts
├── code-editor/
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── public/
│   │   ├── favicon.svg
│   │   ├── manifest.json
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button-group.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── empty.tsx
│   │   │   │   ├── field.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-group.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── item.tsx
│   │   │   │   ├── kbd.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── sonner.tsx
│   │   │   │   ├── spinner.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── AIChat.tsx
│   │   │   ├── AssistenteJuridico.tsx
│   │   │   ├── CampoLivre.tsx
│   │   │   ├── CodeEditor.tsx
│   │   │   ├── DriveBackupPanel.tsx
│   │   │   ├── EditorLayout.tsx
│   │   │   ├── FileTree.tsx
│   │   │   ├── GitHubPanel.tsx
│   │   │   ├── manual.tsx
│   │   │   ├── PackageSearch.tsx
│   │   │   ├── Preview.tsx
│   │   │   ├── QuickPrompt.tsx
│   │   │   ├── RealTerminal.tsx
│   │   │   ├── StreamTerminal.tsx
│   │   │   ├── TemplateSelector.tsx
│   │   │   ├── Terminal.tsx
│   │   │   ├── VoiceCard.tsx
│   │   │   └── VoiceMode.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   ├── ai-service.ts
│   │   │   ├── github-service.ts
│   │   │   ├── projects.ts
│   │   │   ├── store.ts
│   │   │   ├── templates.ts
│   │   │   ├── tts-service.ts
│   │   │   ├── utils.ts
│   │   │   ├── virtual-fs.ts
│   │   │   └── zip-service.ts
│   │   ├── pages/
│   │   │   └── not-found.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   ├── capacitor.config.ts
│   ├── components.json
│   ├── index.html
│   ├── MANUAL-APK.md
│   ├── package.json
│   ├── tsconfig.json
│   ├── vite.config.apk.ts
│   └── vite.config.ts
└── habit-tracker/
    ├── .replit-artifact/
    │   ├── artifact.edit.toml
    │   └── artifact.toml
    ├── app/
    │   ├── (tabs)/
    │   │   ├── _layout.tsx
    │   │   ├── ai.tsx
    │   │   ├── editor.tsx
    │   │   ├── export.tsx
    │   │   ├── github.tsx
    │   │   ├── guide.tsx
    │   │   ├── index.tsx
    │   │   ├── juridico.tsx
    │   │   ├── keys.tsx
    │   │   ├── playground.tsx
    │   │   ├── progress.tsx
    │   │   ├── settings.tsx
    │   │   └── sk-editor.tsx
    │   ├── habit/
    │   │   └── [id].tsx
    │   ├── _layout.tsx
    │   └── +not-found.tsx
    ├── components/
    │   ├── ErrorBoundary.tsx
    │   ├── ErrorFallback.tsx
    │   ├── HabitCard.tsx
    │   ├── HabitFormModal.tsx
    │   ├── IaraModal.tsx
    │   ├── KeyboardAwareScrollViewCompat.tsx
    │   ├── ThirtyDayGrid.tsx
    │   └── WeeklyProgressBar.tsx
    ├── constants/
    │   └── colors.ts
    ├── context/
    │   ├── HabitContext.tsx
    │   └── ProjectContext.tsx
    ├── hooks/
    │   └── useColors.ts
    ├── lib/
    │   ├── android.ts
    │   ├── archive.ts
    │   ├── eas.ts
    │   ├── github.ts
    │   ├── keyDetector.ts
    │   └── neon.ts
    ├── scripts/
    │   ├── build.js
    │   └── bundle-webapps.mjs
    ├── server/
    │   ├── templates/
    │   │   └── landing-page.html
    │   └── serve.js
    ├── .gitignore
    ├── app.json
    ├── babel.config.js
    ├── credentials.json
    ├── eas.json
    ├── expo-env.d.ts
    ├── metro.config.js
    ├── package.json
    └── tsconfig.json
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React, TypeScript

---

## ROTAS DA API (endpoints detectados automaticamente)

```
GET    /api/items  (em code-editor/src/lib/templates.ts)
GET    /api/items/:id  (em code-editor/src/lib/templates.ts)
POST   /api/items  (em code-editor/src/lib/templates.ts)
GET    /api/health  (em code-editor/src/lib/templates.ts)
USE    /api/auth  (em code-editor/src/lib/templates.ts)
USE    /api/usuarios  (em code-editor/src/lib/templates.ts)
POST   /register  (em code-editor/src/lib/templates.ts)
POST   /login  (em code-editor/src/lib/templates.ts)
GET    /perfil  (em code-editor/src/lib/templates.ts)
```

---

## VARIAVEIS DE AMBIENTE NECESSARIAS

Crie um arquivo `.env` na raiz com estas variaveis:

```env
PORT=seu_valor_aqui
BASE_PATH=seu_valor_aqui
REPL_ID=seu_valor_aqui
ALLOWED_ORIGINS=seu_valor_aqui
JWT_SECRET=seu_valor_aqui
JWT_EXPIRES_IN=seu_valor_aqui
DATABASE_URL=seu_valor_aqui
EXPO_PUBLIC_DOMAIN=seu_valor_aqui
REPLIT_INTERNAL_APP_DOMAIN=seu_valor_aqui
REPLIT_DEV_DOMAIN=seu_valor_aqui
EXPO_PUBLIC_REPL_ID=seu_valor_aqui
```

---

## ARQUIVOS PRINCIPAIS

- `apk-builder/index.html` — Arquivo principal
- `apk-builder/src/App.tsx` — Componente raiz do frontend
- `apk-builder/src/main.tsx` — Arquivo principal
- `code-editor/index.html` — Arquivo principal
- `code-editor/src/App.tsx` — Componente raiz do frontend
- `code-editor/src/main.tsx` — Arquivo principal
- `habit-tracker/app/(tabs)/index.tsx` — Arquivo principal

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 `apk-builder/`
> Pasta 'apk-builder' — agrupamento de arquivos relacionados.

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(40 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(87 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(23 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.ts`** _(76 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `code-editor/`
> Pasta 'code-editor' — agrupamento de arquivos relacionados.

**`MANUAL-APK.md`** _(258 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`capacitor.config.ts`** _(24 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(36 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(129 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(16 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.apk.ts`** _(21 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`vite.config.ts`** _(91 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `habit-tracker/`
> Pasta 'habit-tracker' — agrupamento de arquivos relacionados.

**`.gitignore`** _(42 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`app.json`** _(53 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`babel.config.js`** _(7 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`credentials.json`** _(11 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`eas.json`** _(23 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`expo-env.d.ts`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`metro.config.js`** _(4 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`package.json`** _(63 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(25 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

---

### 📁 `apk-builder/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `apk-builder/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.svg`** _(12 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-512.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`manifest.json`** _(45 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(71 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `apk-builder/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(1994 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(62 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(6 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `code-editor/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `code-editor/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`manifest.json`** _(49 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(41 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `code-editor/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(210 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(269 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(6 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `habit-tracker/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.edit.toml`** _(22 linhas)_
Arquivo TOML — parte do projeto.

**`artifact.toml`** _(28 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `habit-tracker/app/`
> Pasta 'app' — agrupamento de arquivos relacionados.

**`+not-found.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`_layout.tsx`** _(62 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

---

### 📁 `habit-tracker/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`ErrorBoundary.tsx`** _(55 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`ErrorFallback.tsx`** _(279 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`HabitCard.tsx`** _(229 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`HabitFormModal.tsx`** _(367 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`IaraModal.tsx`** _(824 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`KeyboardAwareScrollViewCompat.tsx`** _(30 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`ThirtyDayGrid.tsx`** _(209 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`WeeklyProgressBar.tsx`** _(98 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `habit-tracker/constants/`
> Pasta 'constants' — agrupamento de arquivos relacionados.

**`colors.ts`** _(62 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `habit-tracker/context/`
> Gerenciamento de estado global — dados compartilhados entre telas.

**`HabitContext.tsx`** _(269 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`ProjectContext.tsx`** _(203 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

---

### 📁 `habit-tracker/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`useColors.ts`** _(25 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de 'colors'.

---

### 📁 `habit-tracker/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`android.ts`** _(413 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`archive.ts`** _(244 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eas.ts`** _(147 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`github.ts`** _(256 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`keyDetector.ts`** _(162 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`neon.ts`** _(85 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `habit-tracker/scripts/`
> Pasta 'scripts' — agrupamento de arquivos relacionados.

**`build.js`** _(574 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`bundle-webapps.mjs`** _(53 linhas)_
Arquivo MJS — parte do projeto.

---

### 📁 `habit-tracker/server/`
> Pasta 'server' — agrupamento de arquivos relacionados.

**`serve.js`** _(136 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `apk-builder/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `apk-builder/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`android.ts`** _(858 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`archive.ts`** _(166 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`github.ts`** _(342 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`storage.ts`** _(117 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `apk-builder/src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`not-found.tsx`** _(22 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `code-editor/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`AIChat.tsx`** _(2226 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`AssistenteJuridico.tsx`** _(1190 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CampoLivre.tsx`** _(499 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CodeEditor.tsx`** _(154 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`DriveBackupPanel.tsx`** _(200 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`EditorLayout.tsx`** _(2550 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`FileTree.tsx`** _(400 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`GitHubPanel.tsx`** _(632 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`PackageSearch.tsx`** _(415 linhas)_
Componente de BUSCA — campo e logica para filtrar/encontrar conteudo.

**`Preview.tsx`** _(496 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`QuickPrompt.tsx`** _(274 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`RealTerminal.tsx`** _(634 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`StreamTerminal.tsx`** _(495 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`TemplateSelector.tsx`** _(501 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Terminal.tsx`** _(1516 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VoiceCard.tsx`** _(427 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`VoiceMode.tsx`** _(277 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`manual.tsx`** _(1726 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `code-editor/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `code-editor/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`ai-service.ts`** _(392 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`github-service.ts`** _(197 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`projects.ts`** _(206 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`store.ts`** _(38 linhas)_
STORE de estado — gerencia o estado global do app (dados compartilhados entre telas).

**`templates.ts`** _(1629 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tts-service.ts`** _(294 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

**`virtual-fs.ts`** _(200 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zip-service.ts`** _(163 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `code-editor/src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`not-found.tsx`** _(22 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `habit-tracker/app/(tabs)/`
> Pasta '(tabs)' — agrupamento de arquivos relacionados.

**`_layout.tsx`** _(100 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`ai.tsx`** _(10 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`editor.tsx`** _(481 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`export.tsx`** _(565 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`github.tsx`** _(969 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`guide.tsx`** _(167 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`index.tsx`** _(838 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

**`juridico.tsx`** _(273 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`keys.tsx`** _(1182 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`playground.tsx`** _(725 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(2 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`settings.tsx`** _(2 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

**`sk-editor.tsx`** _(261 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

---

### 📁 `habit-tracker/app/habit/`
> Pasta 'habit' — agrupamento de arquivos relacionados.

**`[id].tsx`** _(254 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `habit-tracker/server/templates/`
> Pasta 'templates' — agrupamento de arquivos relacionados.

**`landing-page.html`** _(461 linhas)_
Arquivo HTML — parte do projeto.

---

### 📁 `apk-builder/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(44 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(66 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `code-editor/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(44 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(66 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS
Tipo: Aplicacao Web Frontend (React)
Stack: React, TypeScript
Arquivos: 226 | Linhas: ~46.445
Rotas API: 9 endpoint(s) detectado(s)
Variaveis de ambiente necessarias: PORT, BASE_PATH, REPL_ID, ALLOWED_ORIGINS, JWT_SECRET, JWT_EXPIRES_IN, DATABASE_URL, EXPO_PUBLIC_DOMAIN, REPLIT_INTERNAL_APP_DOMAIN, REPLIT_DEV_DOMAIN, EXPO_PUBLIC_REPL_ID

Estrutura principal:
  apk-builder/.replit-artifact/artifact.toml
  apk-builder/components.json
  apk-builder/index.html
  apk-builder/package.json
  apk-builder/public/favicon.svg
  apk-builder/public/icon-192.svg
  apk-builder/public/icon-512.svg
  apk-builder/public/manifest.json
  apk-builder/public/sw.js
  apk-builder/src/App.tsx
  apk-builder/src/components/ui/accordion.tsx
  apk-builder/src/components/ui/alert-dialog.tsx
  apk-builder/src/components/ui/alert.tsx
  apk-builder/src/components/ui/aspect-ratio.tsx
  apk-builder/src/components/ui/avatar.tsx
  apk-builder/src/components/ui/badge.tsx
  apk-builder/src/components/ui/breadcrumb.tsx
  apk-builder/src/components/ui/button-group.tsx
  apk-builder/src/components/ui/button.tsx
  apk-builder/src/components/ui/calendar.tsx
  apk-builder/src/components/ui/card.tsx
  apk-builder/src/components/ui/carousel.tsx
  apk-builder/src/components/ui/chart.tsx
  apk-builder/src/components/ui/checkbox.tsx
  apk-builder/src/components/ui/collapsible.tsx
  apk-builder/src/components/ui/command.tsx
  apk-builder/src/components/ui/context-menu.tsx
  apk-builder/src/components/ui/dialog.tsx
  apk-builder/src/components/ui/drawer.tsx
  apk-builder/src/components/ui/dropdown-menu.tsx
  apk-builder/src/components/ui/empty.tsx
  apk-builder/src/components/ui/field.tsx
  apk-builder/src/components/ui/form.tsx
  apk-builder/src/components/ui/hover-card.tsx
  apk-builder/src/components/ui/input-group.tsx
  apk-builder/src/components/ui/input-otp.tsx
  apk-builder/src/components/ui/input.tsx
  apk-builder/src/components/ui/item.tsx
  apk-builder/src/components/ui/kbd.tsx
  apk-builder/src/components/ui/label.tsx
  apk-builder/src/components/ui/menubar.tsx
  apk-builder/src/components/ui/navigation-menu.tsx
  apk-builder/src/components/ui/pagination.tsx
  apk-builder/src/components/ui/popover.tsx
  apk-builder/src/components/ui/progress.tsx
  apk-builder/src/components/ui/radio-group.tsx
  apk-builder/src/components/ui/resizable.tsx
  apk-builder/src/components/ui/scroll-area.tsx
  apk-builder/src/components/ui/select.tsx
  apk-builder/src/components/ui/separator.tsx
  apk-builder/src/components/ui/sheet.tsx
  apk-builder/src/components/ui/sidebar.tsx
  apk-builder/src/components/ui/skeleton.tsx
  apk-builder/src/components/ui/slider.tsx
  apk-builder/src/components/ui/sonner.tsx
  apk-builder/src/components/ui/spinner.tsx
  apk-builder/src/components/ui/switch.tsx
  apk-builder/src/components/ui/table.tsx
  apk-builder/src/components/ui/tabs.tsx
  apk-builder/src/components/ui/textarea.tsx
  apk-builder/src/components/ui/toast.tsx
  apk-builder/src/components/ui/toaster.tsx
  apk-builder/src/components/ui/toggle-group.tsx
  apk-builder/src/components/ui/toggle.tsx
  apk-builder/src/components/ui/tooltip.tsx
  apk-builder/src/hooks/use-mobile.tsx
  apk-builder/src/hooks/use-toast.ts
  apk-builder/src/index.css
  apk-builder/src/lib/android.ts
  apk-builder/src/lib/archive.ts
  apk-builder/src/lib/github.ts
  apk-builder/src/lib/storage.ts
  apk-builder/src/lib/utils.ts
  apk-builder/src/main.tsx
  apk-builder/src/pages/not-found.tsx
  apk-builder/tsconfig.json
  apk-builder/vite.config.ts
  code-editor/.replit-artifact/artifact.toml
  code-editor/MANUAL-APK.md
  code-editor/capacitor.config.ts
  code-editor/components.json
  code-editor/index.html
  code-editor/package.json
  code-editor/public/favicon.svg
  code-editor/public/manifest.json
  code-editor/public/sw.js
  code-editor/src/App.tsx
  code-editor/src/components/AIChat.tsx
  code-editor/src/components/AssistenteJuridico.tsx
  code-editor/src/components/CampoLivre.tsx
  code-editor/src/components/CodeEditor.tsx
  code-editor/src/components/DriveBackupPanel.tsx
  code-editor/src/components/EditorLayout.tsx
  code-editor/src/components/FileTree.tsx
  code-editor/src/components/GitHubPanel.tsx
  code-editor/src/components/PackageSearch.tsx
  code-editor/src/components/Preview.tsx
  code-editor/src/components/QuickPrompt.tsx
  code-editor/src/components/RealTerminal.tsx
  code-editor/src/components/StreamTerminal.tsx
  code-editor/src/components/TemplateSelector.tsx
  code-editor/src/components/Terminal.tsx
  code-editor/src/components/VoiceCard.tsx
  code-editor/src/components/VoiceMode.tsx
  code-editor/src/components/manual.tsx
  code-editor/src/components/ui/accordion.tsx
  code-editor/src/components/ui/alert-dialog.tsx
  code-editor/src/components/ui/alert.tsx
  code-editor/src/components/ui/aspect-ratio.tsx
  code-editor/src/components/ui/avatar.tsx
  code-editor/src/components/ui/badge.tsx
  code-editor/src/components/ui/breadcrumb.tsx
  code-editor/src/components/ui/button-group.tsx
  code-editor/src/components/ui/button.tsx
  code-editor/src/components/ui/calendar.tsx
  code-editor/src/components/ui/card.tsx
  code-editor/src/components/ui/carousel.tsx
  code-editor/src/components/ui/chart.tsx
  code-editor/src/components/ui/checkbox.tsx
  code-editor/src/components/ui/collapsible.tsx
  code-editor/src/components/ui/command.tsx
  code-editor/src/components/ui/context-menu.tsx
  code-editor/src/components/ui/dialog.tsx
  code-editor/src/components/ui/drawer.tsx
  code-editor/src/components/ui/dropdown-menu.tsx
  code-editor/src/components/ui/empty.tsx
  code-editor/src/components/ui/field.tsx
  code-editor/src/components/ui/form.tsx
  code-editor/src/components/ui/hover-card.tsx
  code-editor/src/components/ui/input-group.tsx
  code-editor/src/components/ui/input-otp.tsx
  code-editor/src/components/ui/input.tsx
  code-editor/src/components/ui/item.tsx
  code-editor/src/components/ui/kbd.tsx
  code-editor/src/components/ui/label.tsx
  code-editor/src/components/ui/menubar.tsx
  code-editor/src/components/ui/navigation-menu.tsx
  code-editor/src/components/ui/pagination.tsx
  code-editor/src/components/ui/popover.tsx
  code-editor/src/components/ui/progress.tsx
  code-editor/src/components/ui/radio-group.tsx
  code-editor/src/components/ui/resizable.tsx
  code-editor/src/components/ui/scroll-area.tsx
  code-editor/src/components/ui/select.tsx
  code-editor/src/components/ui/separator.tsx
  code-editor/src/components/ui/sheet.tsx
  code-editor/src/components/ui/sidebar.tsx
  code-editor/src/components/ui/skeleton.tsx
  code-editor/src/components/ui/slider.tsx
  code-editor/src/components/ui/sonner.tsx
  code-editor/src/components/ui/spinner.tsx
  code-editor/src/components/ui/switch.tsx
  code-editor/src/components/ui/table.tsx
  code-editor/src/components/ui/tabs.tsx
  code-editor/src/components/ui/textarea.tsx
  code-editor/src/components/ui/toast.tsx
  code-editor/src/components/ui/toaster.tsx
  code-editor/src/components/ui/toggle-group.tsx
  code-editor/src/components/ui/toggle.tsx
  code-editor/src/components/ui/tooltip.tsx
  code-editor/src/hooks/use-mobile.tsx
  code-editor/src/hooks/use-toast.ts
  code-editor/src/index.css
  code-editor/src/lib/ai-service.ts
  code-editor/src/lib/github-service.ts
  code-editor/src/lib/projects.ts
  code-editor/src/lib/store.ts
  code-editor/src/lib/templates.ts
  code-editor/src/lib/tts-service.ts
  code-editor/src/lib/utils.ts
  code-editor/src/lib/virtual-fs.ts
  code-editor/src/lib/zip-service.ts
  code-editor/src/main.tsx
  code-editor/src/pages/not-found.tsx
  code-editor/tsconfig.json
  code-editor/vite.config.apk.ts
  code-editor/vite.config.ts
  habit-tracker/.gitignore
  habit-tracker/.replit-artifact/artifact.edit.toml
  habit-tracker/.replit-artifact/artifact.toml
  habit-tracker/app.json
  habit-tracker/app/(tabs)/_layout.tsx
  habit-tracker/app/(tabs)/ai.tsx
  habit-tracker/app/(tabs)/editor.tsx
  habit-tracker/app/(tabs)/export.tsx
  habit-tracker/app/(tabs)/github.tsx
  habit-tracker/app/(tabs)/guide.tsx
  habit-tracker/app/(tabs)/index.tsx
  habit-tracker/app/(tabs)/juridico.tsx
  habit-tracker/app/(tabs)/keys.tsx
  habit-tracker/app/(tabs)/playground.tsx
  habit-tracker/app/(tabs)/progress.tsx
  habit-tracker/app/(tabs)/settings.tsx
  habit-tracker/app/(tabs)/sk-editor.tsx
  habit-tracker/app/+not-found.tsx
  habit-tracker/app/_layout.tsx
  habit-tracker/app/habit/[id].tsx
  habit-tracker/babel.config.js
  habit-tracker/components/ErrorBoundary.tsx
  habit-tracker/components/ErrorFallback.tsx
  habit-tracker/components/HabitCard.tsx
  habit-tracker/components/HabitFormModal.tsx
  habit-tracker/components/IaraModal.tsx
  habit-tracker/components/KeyboardAwareScrollViewCompat.tsx
  habit-tracker/components/ThirtyDayGrid.tsx
  habit-tracker/components/WeeklyProgressBar.tsx
  habit-tracker/constants/colors.ts
  habit-tracker/context/HabitContext.tsx
  habit-tracker/context/ProjectContext.tsx
  habit-tracker/credentials.json
  habit-tracker/eas.json
  habit-tracker/expo-env.d.ts
  habit-tracker/hooks/useColors.ts
  habit-tracker/lib/android.ts
  habit-tracker/lib/archive.ts
  habit-tracker/lib/eas.ts
  habit-tracker/lib/github.ts
  habit-tracker/lib/keyDetector.ts
  habit-tracker/lib/neon.ts
  habit-tracker/metro.config.js
  habit-tracker/package.json
  habit-tracker/scripts/build.js
  habit-tracker/scripts/bundle-webapps.mjs
  habit-tracker/server/serve.js
  habit-tracker/server/templates/landing-page.html
  habit-tracker/tsconfig.json
```

---

*Plano gerado pelo SK Code Editor — 05/05/2026, 15:37:42*