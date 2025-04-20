
# 🔌 browser-extension-manager

Um gerenciador de extensões de navegador criado com React, com foco em filtros de status, controle de ativação e remoção de extensões.

## 🧩 Sobre o projeto

Este projeto exibe uma lista de extensões fictícias carregadas a partir de um arquivo `data.json`. Cada extensão pode estar ativa ou inativa, e o usuário pode:

- Remover extensões individualmente
- Ativar ou desativar extensões
- Filtrar por status: `Todos`, `Ativo` ou `Inativo`

Foi desenvolvido como um desafio prático após o primeiro módulo de um curso de React, com o objetivo de aplicar os conhecimentos aprendidos até então sem copiar código.

O design do projeto foi baseado em um desafio da plataforma [Frontend Mentor](https://www.frontendmentor.io/).

## ⚙️ Tecnologias utilizadas

- React
- CSS puro
- Dados locais via JSON (`data.json`)

## 🖥️ Como rodar o projeto localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/KevinADemetro/browser-extension-manager.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd browser-extension-manager
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Inicie o servidor de desenvolvimento:
   ```bash
   npm start
   ```

## 🌐 Deploy

O projeto será publicado em breve via GitHub Pages.

## 📚 Aprendizados

- Prática real de estruturação de componentes em React
- Uso de `props` e `state` para gerenciar dados e interações
- Primeira vez lidando com o conceito de "prop drilling" (quando o `state` precisa ser passado por várias camadas)
- Primeira experiência com frontend moderno e foco em estilização visual e responsividade

## 💡 Desafios enfrentados

- Lógica de filtros com manipulação de dados local sem perder o controle do `state`
- Decidir a divisão da árvore de componentes de forma eficiente e reaproveitável
- Fazer a estrutura dos cards com grid responsivo e altura fixa, além de manter consistência visual

## 🧠 Melhorias futuras

Atualmente, não há planos para expandir o projeto. Ele serviu como um importante exercício de fixação de conteúdo.

## 📸 Preview

![ksnip_20250420-192007](https://github.com/user-attachments/assets/be29ebd5-2211-4f91-b0d9-acaba6a0c0f8)

---

Feito com 💙 por [Kevin Albino Demetro](https://github.com/KevinADemetro)
```
