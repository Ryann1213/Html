---

## **A Semântica por Trás da Apresentação: Desvendando a Estrutura Textual em HTML**

### **1. Analisando a Estrutura de Texto nas Páginas (Individual)**

**Sites que eu usei:**

* Um portal de notícias (tipo o G1)
* Um blog de receitas
* A documentação oficial do React

**Como eu fiz:**

Abri cada site e usei o “Inspecionar Elemento” do navegador (aquele botão direito → inspecionar) pra dar uma olhada no HTML por trás das páginas.

**O que eu encontrei:**

* **`<p>`:** Aparece direto, separando os parágrafos de texto normal.
* **`<h1>` e `<h2>`:** São os títulos principais e subtítulos. Bem importantes pra organizar o conteúdo.
* **`<strong>`:** Dá destaque pras palavras importantes, não só em negrito, mas com sentido de "isso aqui é relevante".
* **`<em>`:** Dá uma ênfase mais leve, tipo quando a gente quer destacar uma palavra com itálico.
* **`<br>`:** Quebra de linha, usado principalmente em listas ou frases soltas.
* **`<hr>`:** Uma linha que separa conteúdos, tipo pra mudar de assunto na página.

**Sobre a função de cada um:**

Esses elementos ajudam muito a deixar o site mais organizado. Por exemplo, usar `<h1>` ou `<h2>` em vez de só aumentar a letra com CSS ajuda a manter a hierarquia da informação — bom pra acessibilidade e pra quem usa leitores de tela também. E usar `<strong>` tem mais sentido semântico do que só deixar o texto em negrito por aparência.

---

### **2. Explorando as Listas (Individual)**

**Listas que eu vi nos sites:**

* **`<ul>` (lista sem ordem):** Usada em menus e listas de ingredientes.
* **`<ol>` (lista com ordem):** Apareceu nos passos das receitas e nos tutoriais da documentação.
* **`<li>`:** Tá em todas, é o item da lista mesmo.
* **`<dl>`, `<dt>`, `<dd>` (lista de definições):** Vi na documentação do React, explicando termos técnicos.

**Pra que serve cada uma?**

* A **`<ul>`** é boa quando a ordem não importa, tipo lista de tópicos ou opções do menu.
* A **`<ol>`** é perfeita quando a sequência faz diferença, como passo a passo ou rankings.
* A **`<dl>`** serve pra fazer tipo um dicionário ou glossário, com o termo e a explicação.

**Exemplo:** Na receita, não dá pra inverter a ordem dos passos, né? Então ali, só `<ol>` mesmo. Já os ingredientes, tanto faz a ordem, então vai de `<ul>`.

---

### **3. Citando com Estilo (Individual)**

**O que eu achei de citação nos sites:**

* **`<blockquote>`:** Apareceu em artigos e blogs quando o texto citava uma fala inteira de alguém.
* **`<q>`:** Usado quando só uma frase curta era citada no meio de um parágrafo, tipo uma fala rápida.

**Qual a diferença entre eles?**

* O **`<blockquote>`** é usado quando a citação é maior, geralmente ganha um destaque visual, com recuo e tudo.
* O **`<q>`** é pra citações mais curtinhas, aquelas entre aspas no meio do texto.

**Por que usar isso importa?**

Usar esses elementos direitinho ajuda a mostrar pro leitor (e até pro Google) o que é conteúdo original da página e o que veio de outra fonte. Isso deixa tudo mais claro, confiável e organizado.

---


