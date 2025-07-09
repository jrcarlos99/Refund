# Refund

> Aplicativo web simples para registrar e gerenciar solicitações de reembolso de despesas.

---

## Índice

- [Descrição](#descrição)  
- [Funcionalidades](#funcionalidades)  
- [Tecnologias](#tecnologias)  
- [Estrutura do Projeto](#estrutura-do-projeto)  
- [Como Executar](#como-executar)  
- [Contribuindo](#contribuindo)  
- [Licença](#licença)  

---

## Descrição

O **Refund** é um protótipo de aplicação front‑end que permite ao usuário cadastrar despesas para posterior solicitação de reembolso. Cada item adicionado é listado dinamicamente, com contagem e total formatados em moeda brasileira (BRL). O projeto foi gerado a partir do template oficial da Rocketseat.

---

## Funcionalidades

- 📝 Cadastro de nova despesa com:
  - Nome
  - Categoria (Alimentação, Hospedagem, Serviços, Transporte, Outros)
  - Valor (formatado em R$)
- 📋 Listagem dinâmica de todas as despesas cadastradas
- 🗑️ Remoção individual de despesas
- 📊 Atualização automática da quantidade de despesas e do total em tempo real
- 📱 Layout responsivo para desktop e mobile

---

## Tecnologias

- **HTML5**  
- **CSS3** (Flexbox, Media Queries)  
- **JavaScript (ES6+)**  

Todos os assets (ícones SVG) estão na pasta `img/`.

---

## Estrutura do Projeto

Refund/  
├─ img/ # Ícones e logotipos (SVG)  
│ ├─ 1.svg # Alimentação  
│ ├─ 2.svg # Hospedagem  
│ ├─ … # …  
│ └─ remove.svg # Ícone de remoção  
├─ index.html # Marcações HTML  
├─ styles.css # Estilos globais e responsivos  
└─ script.js # Lógica de cadastro, listagem e totalização



---

## Como Executar

1. Faça um clone deste repositório:
   ```bash
   git clone https://github.com/jrcarlos99/Refund.git

2.Abra o arquivo `index.html` diretamente no seu navegador:

- Clique duas vezes sobre `index.html`,
    
- Ou use um servidor local (por exemplo, com a extensão Live Server do VSCode).
