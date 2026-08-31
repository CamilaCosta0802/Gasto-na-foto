# 📸 Gasto na Foto

> Fotografe seu comprovante e deixe a Inteligência Artificial organizar seus gastos.

## 💡 Sobre o projeto

O **Gasto na Foto** é uma aplicação web desenvolvida para facilitar o registro e a visualização de gastos a partir de fotos de comprovantes.

A proposta é simples: o usuário fotografa ou seleciona um comprovante, e a aplicação utiliza **Inteligência Artificial** para analisar a imagem, identificar o estabelecimento, os itens comprados e o valor total da compra.

As informações são então organizadas automaticamente na tela, enquanto o valor da nota é somado ao **total geral dos gastos**.

Este projeto foi desenvolvido para colocar em prática conhecimentos de **HTML, CSS, JavaScript, integração com IA e Git/GitHub**.

---

## 🚀 Como funciona

O fluxo da aplicação é:

**📸 Foto do comprovante → 🤖 Inteligência Artificial → 🧾 Informações organizadas → 💰 Total dos gastos**

1. O usuário seleciona ou fotografa um comprovante.
2. A imagem é enviada para a Inteligência Artificial.
3. A IA analisa as informações presentes no comprovante.
4. O estabelecimento e os itens da compra são identificados.
5. O valor total da nota é apresentado.
6. O valor é automaticamente adicionado ao total geral dos gastos.

---

## ✨ Funcionalidades

* 📸 Seleção ou captura de foto do comprovante
* 🤖 Análise de comprovantes utilizando Inteligência Artificial
* 🏪 Identificação do estabelecimento
* 🧾 Identificação dos itens comprados
* 💰 Identificação do valor total da compra
* 📋 Exibição dos comprovantes em cards
* ➕ Soma automática dos gastos
* 🏷️ Classificação dos gastos por categoria
* 📱 Interface adaptada para dispositivos menores
* 🎨 Interface simples e intuitiva

---

## 🏷️ Categorias de gastos

A aplicação utiliza as seguintes categorias:

| Emoji | Categoria  |
| ----- | ---------- |
| 🛒    | Mercado    |
| 🚗    | Transporte |
| 🍔    | Comida     |
| 💊    | Saúde      |
| 🎉    | Lazer      |
| 🏠    | Casa       |
| 💸    | Outros     |

---

## 🛠️ Tecnologias utilizadas

| Tecnologia     | Utilização                                                  |
| -------------- | ----------------------------------------------------------- |
| **HTML5**      | Estrutura da aplicação                                      |
| **CSS3**       | Estilização, layout e responsividade                        |
| **JavaScript** | Lógica, interatividade e manipulação do DOM                 |
| **Puter AI**   | Análise dos comprovantes através de Inteligência Artificial |
| **Git**        | Controle de versão                                          |
| **GitHub**     | Versionamento e hospedagem do código                        |

---

## 🤖 Inteligência Artificial

Um dos principais diferenciais do projeto é a integração com **Inteligência Artificial**.

A aplicação utiliza a biblioteca da **Puter AI** para enviar a imagem do comprovante junto com uma instrução que orienta a IA sobre como interpretar e organizar os dados encontrados.

A resposta recebida é processada pelo JavaScript para separar as informações e apresentá-las na interface.

Entre os dados processados estão:

* Categoria da compra
* Nome do estabelecimento
* Itens comprados
* Valor de cada item
* Total da nota

---

## 💻 Interface

A interface foi desenvolvida utilizando **HTML e CSS**, com foco em simplicidade e facilidade de uso.

O layout conta com:

* 📸 Área para adicionar o comprovante
* 💰 Card com o total dos gastos
* 🧾 Cards individuais para cada comprovante
* 📋 Organização dos itens e valores
* 📱 Layout compacto para facilitar o uso em dispositivos móveis

---

## 📂 Estrutura do projeto

```text
Gasto-na-foto/
│
├── 📄 index.html
├── 🎨 styles.css
├── ⚙️ scripts.js
└── 📖 README.md
```

### `index.html`

Responsável pela estrutura da aplicação e pelos elementos exibidos na página.

### `styles.css`

Responsável pela aparência da aplicação, incluindo:

* Cores
* Tipografia
* Espaçamentos
* Bordas arredondadas
* Cards
* Área de seleção de imagens
* Layout responsivo

### `scripts.js`

Responsável pela lógica da aplicação, incluindo:

* Captura da imagem
* Comunicação com a IA
* Processamento da resposta
* Criação dos cards de comprovantes
* Cálculo do total acumulado
* Atualização dinâmica da interface

---

## 🌐 Repositório

🔗 **GitHub:**

https://github.com/CamilaCosta0802/Gasto-na-foto

---

## 🔮 Próximas melhorias

O projeto pode receber novas funcionalidades futuramente, como:

* [ ] Armazenamento dos gastos utilizando `LocalStorage`
* [ ] Exclusão de comprovantes
* [ ] Edição das informações identificadas pela IA
* [ ] Filtros por categoria
* [ ] Filtro por período
* [ ] Gráficos de gastos
* [ ] Resumo dos gastos por categoria
* [ ] Indicador de carregamento durante o processamento da IA
* [ ] Melhor tratamento para erros de leitura do comprovante
* [ ] Melhorias de acessibilidade
* [ ] Publicação da aplicação online

---

## 🎯 Objetivo

O **Gasto na Foto** foi criado como um projeto prático para desenvolver conhecimentos em **desenvolvimento web** e explorar possibilidades de utilização de **Inteligência Artificial em aplicações reais**.

Além da construção da interface, o projeto permitiu praticar a integração entre uma aplicação JavaScript e um serviço de IA para transformar informações presentes em imagens em dados estruturados.

---

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
