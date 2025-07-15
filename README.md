# 🕒 Registro de Atividades com Cronômetro – Web App

Este é um aplicativo web simples desenvolvido com **HTML**, **JavaScript puro** e **TailwindCSS**, que permite **cronometar o tempo de uma atividade**, **registrar a data e descrição**, manter um **histórico local** e **exportar para Excel**.

---

## ✅ Funcionalidades

- ⏱️ **Cronômetro** com botão de iniciar, parar e zerar
- 📝 **Formulário de registro** com data, descrição e tempo cronometrado
- 💾 **Histórico persistente com LocalStorage**
- 📤 **Exportação do histórico para Excel (.xlsx)**
- 🗂 **Filtros inteligentes**:
  - Por **data inicial e final**
  - Por **palavra-chave na descrição**
  - Por **tempo mínimo** da atividade
- 🧽 **Botão de limpar filtros**
- 🗑 **Botão de excluir atividade individual**
- 📅 Data padrão preenchida automaticamente

---

## 💡 Tecnologias Utilizadas

- HTML5
- JavaScript puro (sem frameworks)
- [TailwindCSS](https://tailwindcss.com) via CDN
- [SheetJS (xlsx)](https://sheetjs.com/) para exportar dados para Excel
- Armazenamento local com `localStorage`

---

## 🚀 Como usar

### 📁 1. **Abra o arquivo HTML**

Basta abrir o arquivo `index.html` no seu navegador.

### ☁️ 2. **Ou publique na Vercel/GitHub Pages**

- Suba o HTML em um repositório GitHub
- Conecte ao [Vercel](https://vercel.com) ou ative o GitHub Pages

### 💾 3. **Registre atividades**

1. Inicie o cronômetro
2. Preencha a data e descrição
3. Clique em "Salvar atividade"
4. A atividade será salva no `localStorage`

### 🔍 4. **Filtre atividades**

Use os campos de filtro para:

- Mostrar atividades por data
- Procurar por palavras específicas
- Ocultar atividades com duração curta

Clique em **"Limpar"** para ver tudo novamente.

### 📤 5. **Exporte para Excel**

Clique em "Exportar para Excel" para baixar seu histórico no formato `.xlsx`.

---

## 📎 Arquivo principal

- [`index_registro_atividades_filtrado.html`](sandbox:/mnt/data/index_registro_atividades_filtrado.html)

---

## 🔐 Privacidade

> Todas as informações são salvas apenas no seu navegador (via `localStorage`) e **não são enviadas para nenhum servidor**.
