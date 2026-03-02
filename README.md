# 🎨 Design Tokens

![Preview Styleguide](./assets/style%20guide.png)

[![NPM Version](https://badge.fury.io/js/@priscilamoura29%2Fdesign-tokens.svg)](https://www.npmjs.com/package/@priscilamoura29/design-tokens)
[![GitHub Actions Status](https://github.com/priscilamoura-creator/design-tokens/actions/workflows/publish.yml/badge.svg)](https://github.com/priscilamoura-creator/design-tokens/actions/workflows/publish.yml)

## Instalação

```bash
npm install @priscilamoura29/design-tokens

This repository stores and manages the core Design Tokens for all products and interfaces of the priscilamoura-codestudio-creator ecosystem.

Design Tokens serve as the Single Source of Truth, ensuring:

Visual consistency

Smooth alignment between Design & Dev

Scalability

Automated delivery (via GitHub Actions)

📁 Project Structure
design-tokens/
├─ index.html        
├─ tokens.json      
├─ config.json        
├─ build/            
│  ├─ css/
│  │  └─ tokens.css   
│  └─ js/
│     └─ tokens.js    
└─ .github/
   └─ workflows/
      └─ publish.yml  

✨ Generated Artifacts
Path	Format	Description	Usage
build/css/tokens.css	CSS Custom Properties	--token-name: value;	Web / CSS
build/js/tokens.js	ES Modules	Exported object	JS / Node / Front-end
🛠️ How to Contribute
Designers / Token Masters

All changes must be made only in:

tokens.json


Workflow:

git add .
git commit -m "feat: add new primary color"
git push origin main


GitHub Actions will automatically generate updated artifacts.

🧩 Using Tokens in Code
JavaScript (ESM):
import { color, space } from './path/to/design-tokens/build/js/tokens.js';

const primary = color.primary.base;
const spacing = space.medium;

element.style.background = primary;
element.style.padding = spacing;


# 🇧🇷 Português – Brasil

Este repositório armazena e gerencia os **Design Tokens centrais** para todos os produtos e interfaces do ecossistema **priscilamoura-codestudio-creator**.

Os Design Tokens funcionam como a **Single Source of Truth**, garantindo:

- Consistência visual  
- Sincronização entre Design & Dev  
- Escalabilidade  
- Automatização na entrega (via GitHub Actions)

---

## 📁 Estrutura do Projeto

design-tokens/
├─ build/
│ ├─ css/
│ │ └─ tokens.css
│ └─ js/
│ └─ tokens.js
├─ .github/
│ └─ workflows/
│ └─ publish.yml
├─ tokens.json
├─ config.json
└─ package.json

yaml
Copiar código

---

## ✨ Artefatos Gerados

| Caminho | Formato | Descrição | Uso |
|--------|---------|-----------|-----|
| `build/css/tokens.css` | CSS Custom Properties | `--token-name: value;` | Aplicações Web |
| `build/js/tokens.js` | ES Modules | Objeto exportado | JS / Node / Front-end |

---

## 🛠️ Como Contribuir

### Designers / Token Masters  
Toda alteração deve ser feita **exclusivamente** no arquivo:

tokens.json

sql
Copiar código

Fluxo:

```bash
git add .
git commit -m "feat: adiciona nova cor primária"
git push origin main
O GitHub Actions se encarrega de gerar os tokens atualizados.

🧩 Como Consumir os Tokens
JavaScript (ESM):
javascript
Copiar código
import { color, space } from './path/to/design-tokens/build/js/tokens.js';

const primary = color.primary.base;
const spacing = space.medium;

element.style.background = primary;
element.style.padding = spacing;

O Gemini disse
Aqui está uma sugestão de "About" (Sobre) completa e estilizada para o seu repositório, Priscila! Ela foi escrita para destacar tanto as funcionalidades do TechNews quanto a sua evolução técnica com as ferramentas da Rocketseat.

🚀 TechNews - Portal de Notícias Tecnológicas
O TechNews é um projeto de portal de notícias focado no ecossistema de inovação, desenvolvido como parte da trilha Full Stack da Rocketseat. O desafio principal consistiu em transformar um layout complexo em uma interface funcional, utilizando as técnicas mais modernas de estilização e estruturação web.

<div align="center">
<img src="styles/screenshots/Captura%20de%20tela%202026-03-01%20170517.png" width="100%" alt="Banner TechNews">
</div>

📝 Sobre o Projeto
Este portal simula a experiência de um usuário consumindo notícias de tecnologia em tempo real. O foco do desenvolvimento não foi apenas a estética, mas a semântica do HTML5 para garantir acessibilidade e a organização eficiente do código CSS.

A estrutura conta com diversas seções dinâmicas:

Destaques Principais: Com foco em Robótica e tendências.

Mais Lidas: Organizadas em uma grade horizontal precisa.

Destaques de IA: Uma seção lateral dedicada a artigos profundos.

Sidebar "Viu isso aqui?": Para navegação secundária e engajamento.

🧠 O que eu aprendi de mais valioso?
Durante o desenvolvimento, foquei em dois pilares que transformaram minha forma de codar:

1. O Poder do CSS Grid 📐
Aprendi a criar layouts bidimensionais complexos sem a necessidade de "gambiarras". Utilizei grid-template-areas para mapear visualmente cada seção do site no CSS, facilitando a leitura e futuras manutenções.

2. Variáveis CSS e Design System 🎨
Implementei variáveis no :root para gerenciar cores, fontes e espaçamentos. Isso permitiu manter a consistência visual em todo o projeto, desde os títulos em Archivo até os tons de azul da marca.

💻 Tecnologias Utilizadas
HTML5: Estruturação semântica avançada.

CSS3: Uso intensivo de Grid Layout, Flexbox e Nesting.

Design Thinking: Interpretação de layouts e extração de medidas.

Google Fonts: Tipografia otimizada para leitura web.



Desenvolvido por Priscila Moura 🦊


