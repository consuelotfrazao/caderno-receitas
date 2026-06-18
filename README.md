# 📒 Caderno de Receitas

App PWA para extrair receitas de vídeos do Instagram, Facebook e YouTube usando IA.

## Funcionalidades

- Extrai receita completa a partir de um link de vídeo
- Gera ilustração do prato com IA
- Tabela nutricional com calorias
- Funciona offline após instalado
- Aparece no botão **Compartilhar** do celular (Android)
- Dark mode automático

---

## Como publicar no GitHub Pages

### 1. Crie um repositório no GitHub
- Acesse [github.com](https://github.com) e faça login
- Clique em **New repository**
- Nome sugerido: `caderno-receitas`
- Deixe como **Public**
- Clique em **Create repository**

### 2. Suba os arquivos
Faça upload de todos os arquivos desta pasta:
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.svg`
- `icon-512.svg`

Para fazer upload: na página do repositório, clique em **Add file → Upload files**.

### 3. Ative o GitHub Pages
- Vá em **Settings** (no repositório)
- No menu lateral, clique em **Pages**
- Em **Source**, selecione **Deploy from a branch**
- Em **Branch**, selecione **main** e pasta **/ (root)**
- Clique em **Save**

Aguarde 1-2 minutos. Seu app estará em:
```
https://SEU_USUARIO.github.io/caderno-receitas
```

---

## Como instalar no celular (Android)

1. Abra o link do app no **Chrome**
2. Toque no banner **"Instalar"** que aparece no app
   — ou —
   Toque nos 3 pontinhos do Chrome → **Adicionar à tela inicial**
3. Pronto! O ícone aparece na tela inicial

### Para usar com o botão Compartilhar:
1. Abra um vídeo de receita no Instagram, Facebook ou YouTube
2. Toque em **Compartilhar**
3. Escolha **Caderno de Receitas** na lista
4. A receita é extraída automaticamente!

## Como instalar no celular (iPhone/iOS)

1. Abra o link no **Safari**
2. Toque no botão de compartilhar (quadrado com seta)
3. Toque em **Adicionar à Tela de Início**
4. Toque em **Adicionar**

> ⚠️ No iOS o Share Target ainda não é suportado. Você precisará copiar o link e colar manualmente no app.

---

## Arquivos do projeto

| Arquivo | Função |
|---------|--------|
| `index.html` | App completo (HTML + CSS + JS) |
| `manifest.json` | Configuração do PWA e Share Target |
| `sw.js` | Service Worker para funcionamento offline |
| `icon-192.svg` | Ícone do app (pequeno) |
| `icon-512.svg` | Ícone do app (grande) |
