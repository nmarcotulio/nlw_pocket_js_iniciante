<h1 align="center">NLW Pocket JS — Gerenciador de Metas</h1>

<p align="center">
  Aplicação de linha de comando para cadastro e controle de metas pessoais, desenvolvida durante o evento <strong>Next Level Week #17 (Pocket)</strong> da Rocketseat.
</p>

<p align="center">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black">
  <img alt="License MIT" src="https://img.shields.io/badge/license-MIT-49AA26">
</p>

---

## Sobre o projeto

O **NLW Pocket JS** é uma aplicação CLI (linha de comando) que permite ao usuário cadastrar, visualizar, marcar e excluir metas do dia a dia — tudo de forma interativa direto no terminal.

Os dados são persistidos localmente em um arquivo `metas.json`, sem necessidade de banco de dados externo.

---

## Funcionalidades

- Cadastrar nova meta
- Listar todas as metas com opção de marcar/desmarcar como concluída
- Visualizar metas realizadas
- Visualizar metas abertas (ainda não concluídas)
- Deletar metas selecionadas

---

## Tecnologias

| Tecnologia | Versão |
|---|---|
| Node.js | 18+ |
| Inquirer.js | 10.x |

---

## Como executar

**Pré-requisito:** Node.js instalado na máquina.

```bash
# Clone o repositório
git clone https://github.com/nmarcotulio/nlw_17_pocket_js_iniciante

# Acesse a pasta
cd nlw_17_pocket_js_iniciante

# Instale as dependências
npm install

# Execute a aplicação
node index.js
```

---

## Aprendizados

- Manipulação de arquivos JSON com Node.js (`fs.promises`)
- Criação de interfaces interativas no terminal com **Inquirer.js**
- Lógica de CRUD sem banco de dados externo
- Programação assíncrona com `async/await`

---

Desenvolvido durante o evento **NLW Pocket — Iniciante** da [Rocketseat](https://rocketseat.com.br)
