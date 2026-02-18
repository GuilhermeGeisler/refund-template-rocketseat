# 💰 Refund - Sistema de Solicitação de Reembolso

## 🌟 Sobre o Projeto  
Sistema de solicitação de reembolso desenvolvido como exercício do curso de Full Stack da Rocketseat. O projeto permite o cadastro de despesas com nome, categoria e valor, exibindo uma lista atualizada em tempo real com total e contador de itens.

- 🎨 Design clean e responsivo com foco na usabilidade
- 📱 Layout adaptável para desktop e dispositivos móveis
- 🔢 Formatação automática de valores monetários
- ➕ Adição e remoção dinâmica de despesas
- 💰 Cálculo automático do total e quantidade de itens

---

## 🚀 Funcionalidades  

| **Funcionalidade**          | **Descrição**                                      |  
|-----------------------------|---------------------------------------------------|  
| ✅ Cadastro de despesa      | Nome, categoria e valor da despesa                |  
| ✅ Formatação de moeda      | Campo valor formatado automaticamente (R$ 0,00)   |  
| ✅ Lista de despesas        | Exibição de todas as despesas adicionadas         |  
| ✅ Remoção de item          | Remova uma despesa clicando no ícone de lixeira   |  
| ✅ Atualização em tempo real| Total e quantidade são recalculados automaticamente |  
| ✅ Validações básicas       | Impede valores inválidos e exibe alertas          |  

---

## 🛠️ Tecnologias Utilizadas  
<div align="center">  
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">  
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">  
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">  
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white" alt="Google Fonts">  
</div>  

---

## 📂 Estrutura de Arquivos
```
refund/
├── index.html # Estrutura principal da página
├── styles.css # Estilos da aplicação
├── scripts.js # Lógica de cadastro e atualização
└── img/ # Recursos visuais
├── logo.svg # Logo do projeto
├── food.svg # Ícone de alimentação
├── accommodation.svg # Ícone de hospedagem
├── services.svg # Ícone de serviços
├── transport.svg # Ícone de transporte
├── others.svg # Ícone de outros
├── chevron-down.svg # Ícone do select
└── remove.svg # Ícone de remoção
```

---

## 🎨 Design e Estilo  
**Paleta de Cores:**

- `#e4ece9` - Fundo da página
- `#f9fbfa` - Fundo do formulário e da lista
- `#1f8459` - Cor principal (botão, bordas de foco)
- `#2cb178` - Hover do botão
- `#1f2523` - Texto principal
- `#4d5c57` - Texto secundário
- `#cdd5d2` - Bordas e separadores

**Tipografia:**

- Fonte Principal: Open Sans (Google Fonts)
- Tamanhos variados: 0.62rem (legenda), 0.87rem (texto comum), 1rem (títulos)

---

## 🔥 Destaques Técnicos

- **Formatação em Tempo Real:** O campo de valor é formatado automaticamente enquanto o usuário digita, utilizando expressões regulares e `toLocaleString`.
- **Manipulação Dinâmica do DOM:** Criação de elementos `li` com ícones e informações a partir dos dados do formulário.
- **Cálculo de Totais:** Função que percorre a lista, extrai os valores e atualiza o total e a quantidade de itens.
- **Remoção de Itens:** Evento de clique delegado na lista para remover o item correspondente e atualizar os totais.
- **Validação e Tratamento de Erros:** Uso de `try/catch` para capturar possíveis falhas na criação de itens ou no cálculo.
- **Responsividade:** Media queries para adaptar o layout em diferentes tamanhos de tela (empilhamento das colunas em telas menores).
- **Scrollbar Customizada:** Estilização da barra de rolagem da lista de despesas.

---

## 🧑‍💻 Desenvolvedor  
<table> <tr> <td align="center"> <a href="https://www.linkedin.com/in/guilhermegeisler/"> <img src="https://avatars.githubusercontent.com/u/53203780?s=400&u=9a85ac6d2d3c55a872ab0bafd1d38d8bd0da5cc4&v=4" width="100px;" alt="Foto do Guilherme Geisler"/><br> <sub> <b>Guilherme Geisler</b> </sub> </a> </td> </tr> </table>

---

## 📧 Contato

Se tiver alguma dúvida, sugestão ou quiser entrar em contato, fique à vontade:  

- **LinkedIn**: [Guilherme Geisler](https://www.linkedin.com/in/guilhermegeisler/)  
- **Email**: [guilherme.sgeisler@gmail.com](mailto:guilherme.sgeisler@gmail.com)  

---

Feito com ❤️ por [Guilherme Geisler](https://www.linkedin.com/in/guilhermegeisler/) no curso da Rocketseat 🚀
