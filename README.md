# 🎨 Estilos WPLMS - Liquid Glass

Este repositório contém a folha de estilo (`style.css`) com **personalizações completas de design no WPLMS**, utilizando o conceito de **Liquid Glass (vidro líquido)** para proporcionar uma experiência moderna, translúcida e elegante.

---

## 🧩 Conceito de Liquid Glass

O **Liquid Glass** é caracterizado por:
- Fundos translúcidos com `rgba` e `backdrop-filter: blur(...)`.
- Bordas suaves (`border-radius` generoso).
- Bordas discretas (`border: 1px solid rgba(...)`).
- Sombreamento difuso para dar profundidade (`box-shadow`).
- Efeitos de **hover** sutis com movimentação (`transform: translateY`) e maior luminosidade.

Esses efeitos foram aplicados de forma consistente em **todas as seções do WPLMS**, criando uma identidade visual unificada.

---

## 📂 Estrutura da Estilização

Abaixo estão os principais blocos estilizados com **Liquid Glass**:

- **Instruções do Curso**
  - `.course_instructions_wrapper`
  - Fundo translúcido com blur.
  - Botão de fechar com ícone estilizado.
  - Textos internos com realce em contraste.

- **Componentes do Curso**
  - `.course_components`
  - Campos de grupo (`.coursegroups`).
  - Botões principais com hover suave.

- **Criação de Curso**
  - `#create_course .create_course_wrapper`
  - Painéis internos (left, right, grid, actions).
  - Blocos de mídia (thumbnail, vídeo).

- **Certificados e Conquistas**
  - `.my_achievements_wrapper`
  - `.my_certificates_wrapper`
  - Certificados estilizados com ícones SVG e efeitos de destaque.

- **Blocos de Curso (Instructor / Vibebp)**
  - `.course_instructor_block`
  - `.vibebp_course .course_card .courseitem`
  - Estrutura clean com imagens, categorias e botões.

- **Visão Geral do Curso**
  - `.course_overview_wrapper`
  - Estilização translúcida para overview e navegação.

- **Configurações de Perfil**
  - `.profile_settings`
  - Portais, abas e formulários com Liquid Glass aplicado.

---

## 🌐 Compatibilidade

- Requer navegadores modernos que suportem:
  - `backdrop-filter`
  - `-webkit-backdrop-filter`

---

## 🚀 Como Usar

1. Copie o arquivo `style.css` para a pasta de estilos do seu tema filho no WordPress.
2. Certifique-se de que ele seja carregado **após** os estilos padrão do WPLMS.
3. Limpe o cache do navegador e do WordPress para aplicar as alterações.

---

## ✨ Resultado

O resultado final é uma interface com aparência de **vidro líquido**, proporcionando:
- Leveza visual
- Consistência estética
- Maior imersão para os usuários da plataforma de cursos

---
