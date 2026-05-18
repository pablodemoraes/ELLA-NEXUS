# Ella's Nexus — Seu Segundo Cérebro Automatizado

> "As notas são suas. As conexões são o que importa."

Este é um template minimalista para **Obsidian**. O objetivo não é criar uma IA que "pensa", mas sim ter um motor (Nexus) que ajuda você a conectar suas ideias de forma automática e inteligente.

---

## 🚀 O Setup Real (Gemini CLI)

Para que a mágica aconteça, você precisa do motor de IA rodando no seu terminal. Siga estes passos:

### 1. Requisitos
- **Node.js**: [Baixe e instale aqui](https://nodejs.org/).
- **Obsidian**: [Baixe e instale aqui](https://obsidian.md/).

### 2. Instalação do Motor (Gemini CLI)
Abra o seu terminal (CMD no Windows ou Terminal no Mac/Linux) e digite:
```bash
npm install -g @google/gemini-cli
```

### 3. Configuração da sua API Key
1. Pegue sua chave gratuita no [Google AI Studio](https://aistudio.google.com/app/apikey).
2. No seu terminal, digite:
```bash
gemini configure
```
E cole a sua chave quando ele pedir.

---

## 📂 Estrutura do Vault (O Nexus)

- **📥 01 - ENTRADA**: Jogue suas notas brutas, links e ideias rápidas aqui.
- **🧠 02 - CONEXÕES**: Onde moram as notas que a IA ajudou você a conectar e expandir.
- **📂 03 - ARQUIVO**: O que já foi processado e guardado.

---

## 🧠 Como usar o Nexus para conectar suas notas

Dentro da pasta **00 - CONFIG**, você encontrará o arquivo `INSTRUCOES_IA.md`. 
Quando quiser conectar suas ideias, abra o terminal na pasta deste Vault e digite:

```bash
gemini "Analise minhas ultimas notas na pasta ENTRADA e me mostre o que elas tem em comum com o que ja salvei em CONEXOES."
```

O Nexus vai analisar seus arquivos locais e te dar o insight. Sem que seus dados saiam do seu computador de forma permanente para nuvens de terceiros.

---
**Soberania. Clareza. Conexão.**
