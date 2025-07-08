# vue-pdf-app-with-sign

> **Fork do [vue-pdf-app](https://github.com/sandanat/vue-pdf-app)** adaptado para uso próprio com suporte a visualização e interação com documentos PDF em aplicações Vue 2. Compatível com Node.js `v16.16.0`.

[![](https://data.jsdelivr.com/v1/package/npm/vue-pdf-app-with-sign/badge)](https://www.jsdelivr.com/package/npm/vue-pdf-app-with-sign)
[![npm version](https://badge.fury.io/js/vue-pdf-app-with-sign.svg)](https://badge.fury.io/js/vue-pdf-app-with-sign)

---

## 📦 Sobre

Componente Vue.js 2 baseado na biblioteca PDF.js da Mozilla, com suporte completo à renderização e interação com arquivos PDF.

### 🔧 Funcionalidades

- Zoom
- Abertura de arquivos locais ou via URL
- Impressão
- Download
- Rotação de páginas
- Seleção de texto
- Painel de busca
- Senha de documentos
- Miniaturas, sumário, anexos, anotações
- Customização de cores, ícones e temas (claro/escuro)
- Interface totalmente personalizável
- Suporte nativo a TypeScript
- Suporte UMD / Unpkg
- Compatível com navegadores modernos (incluindo IE11)

---

## 🧱 Requisitos

- **Vue.js**: v2.x
- **Node.js**: `v16.16.0`

---

## 🚀 Instalação

```bash
npm install vue-pdf-app-with-sign
````

---

## 💻 Exemplo de uso básico

```vue
<template>
  <vue-pdf-app
    style="height: 100vh"
    pdf="https://file-examples-com.github.io/uploads/2017/10/file-example_PDF_1MB.pdf"
  ></vue-pdf-app>
</template>

<script>
import VuePdfApp from "vue-pdf-app-with-sign";
import "vue-pdf-app-with-sign/dist/icons/main.css";

export default {
  components: {
    VuePdfApp
  }
};
</script>
```

---

## 📚 Documentação

A documentação completa das **props**, **eventos**, **slots**, **temas**, **personalização de toolbar**, **exemplos com TypeScript**, lazy loading e interação direta com a API do PDF.js está disponível abaixo.

👉 Continue lendo abaixo ou acesse os exemplos diretamente em:

* [Live demo no CodeSandbox](https://codesandbox.io/s/vue-2-vue-pdf-app-wz5kv)
* [Live demo no Codepen](https://codepen.io/sandanat/pen/xxVdgYM)
* [Fonte dos exemplos](https://github.com/sandanat/vue-pdf-app/tree/master/examples)

---

## 📦 Tamanhos dos arquivos

| Arquivo                | Tamanho                             | Gzipped    |
| ---------------------- | ----------------------------------- | ---------- |
| vue-pdf-app.umd.min.js | 1742.89 KiB                         | 478.86 KiB |
| vue-pdf-app.umd.js     | 3115.59 KiB                         | 677.87 KiB |
| vue-pdf-app.common.js  | 3115.12 KiB                         | 677.71 KiB |
| icons/main.css         | 15–40 KiB (dependendo do navegador) |            |

---

## 📄 Licença

MIT

---

> *Este projeto é um fork do [`vue-pdf-app`](https://github.com/sandanat/vue-pdf-app), com personalizações para atender casos específicos como assinatura digital, customizações visuais e controle de interação.*

```

---
