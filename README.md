# 🧩 Minicurso WSIS 2025 — Acessibilidade na Web

Repositório do minicurso **“Interfaces Acessíveis: Boas Práticas de Acessibilidade Web com HTML, CSS e JavaScript”**, ministrado durante o [**Workshop de Sistemas de Informação (WSIS 2025)**](https://wsis.crp.ufv.br/), no campus da UFV em Rio Paranaíba.

---

## 📌 Sobre o Minicurso
Este minicurso tem como objetivo apresentar, de forma teórico-prática e progressiva, **conceitos e práticas de acessibilidade na Web**, explorando:

- Fundamentos da acessibilidade digital e sua importância.  
- Princípios **POUR** (Perceptível, Operável, Compreensível e Robusto).  
- Leis, normas e recomendações (W3C/WCAG).  
- Demonstração prática de **um formulário não acessível** e sua evolução até uma versão **plenamente acessível**.  
- Técnicas com **HTML, CSS e JavaScript** para melhorar experiência de usuários com deficiência visual, auditiva, motora e/ou cognitiva.  

---

## 🧪 Conteúdo Prático
Durante a atividade, construímos e testamos um **formulário de cadastro** em duas versões:

1. **Versão não acessível**  
   - Uso incorreto de `<div>` como botão.  
   - Ausência de `<form>`, `<label>` e textos alternativos.  
   - Contraste inadequado.  
   - Erros e feedback apenas visuais.  

2. **Versão acessível (refatorada)**  
   - Uso correto de `<form>`, `<button>`, `<label>`.  
   - Estrutura semântica com `<fieldset>` e `<legend>`.  
   - Contraste ajustado para atender WCAG 2.1.  
   - Foco visível e navegação por teclado.  
   - Feedback dinâmico com `aria-live`.  
   - Resumo de erros acessível no topo do formulário.  

---

## 📂 Estrutura do Repositório
- `index.html` → versão inicial do formulário sem boas práticas.  
- `acessivel.html` → versão final corrigida com acessibilidade aplicada.  
- `assets/` → imagens utilizadas (ex.: logo).  
- `README.md` → este arquivo com informações gerais.  

---

## 📖 Material Complementar
Todo o conteúdo teórico, exemplos adicionais e referências estão disponíveis no Notion:  
👉 [Acessar o conteúdo completo no Notion](https://shard-bridge-eae.notion.site/Interfaces-Acess-veis-Boas-Pr-ticas-de-Acessibilidade-Web-com-HTML-CSS-e-JavaScript-23e224b8dcd88038be41d434c9f51385?pvs=73)

---

## 🚀 Como usar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/minicurso-acessibilidade-wsis-2025.git
   ```
2. Abra os arquivos `.html` em seu navegador.  
3. Explore as diferenças entre as versões não acessível e acessível.  

---

## 👤 Autor
[**Victor Oliveira**](https://www.linkedin.com/in/victor-alves-de-oliveira/)  
- Bacharelando de Sistemas de Informação — UFV Rio Paranaíba  
- Desenvolvedor Frontend (React & React Native)  
---

## 📜 Licença
Este repositório é de uso **educacional** e pode ser reutilizado para fins de estudo e treinamento.  
