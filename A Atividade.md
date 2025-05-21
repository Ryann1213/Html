

---

## **A Semântica por Trás da Apresentação: Desvendando a Estrutura Textual em HTML**

### **1. Análise da Estrutura Textual de Páginas Web (Individual)**

**Páginas selecionadas:**

* Página de um jornal online (ex: G1)
* Página inicial de um blog de receitas
* Página de documentação do React

**Ferramenta usada:**
Utilizei a função “Inspecionar” do navegador Google Chrome para observar o HTML das páginas.

**Exemplos de elementos de formatação de texto encontrados:**

* **`<p>`:** Utilizado para parágrafos de texto nos artigos e explicações.
* **`<h1>`, `<h2>`:** Títulos principais e subtítulos, geralmente usados para destacar a hierarquia do conteúdo.
* **`<strong>`:** Destaca palavras importantes no meio do texto, com intenção de ênfase sem depender apenas da aparência.
* **`<em>`:** Indica ênfase em palavras, normalmente usada em comentários ou frases de destaque.
* **`<br>`:** Quebra de linha, comum em blocos de citação ou descrições rápidas.
* **`<hr>`:** Linha horizontal usada para dividir seções de forma visual.

**Análise semântica:**

* O uso de `<h1>` e `<h2>` organiza a estrutura da página, ajudando usuários e ferramentas de leitura (como leitores de tela) a entenderem a ordem e importância das informações.
* Usar `<strong>` tem valor semântico: indica que o conteúdo é importante. Diferente de aplicar apenas negrito com CSS, ele comunica a importância para leitores automáticos e mecanismos de busca.

---

### **2. Explorando a Organização com Listas (Individual)**

**Elementos de lista encontrados:**

* **`<ul>` (lista não ordenada):** Usada em menus de navegação, listas de ingredientes em receitas e tópicos gerais.
* **`<ol>` (lista ordenada):** Utilizada em tutoriais da documentação do React e em passo a passo de receitas.
* **`<li>` (itens de lista):** Comum a todos os tipos de listas.
* **`<dl>`, `<dt>`, `<dd>` (lista de definição):** Apareceram em páginas de glossários e definições técnicas, especialmente na documentação.

**Explicações e contextos:**

* **`<ul>`** é ideal quando a ordem dos itens não importa, como em menus ou tópicos soltos.
* **`<ol>`** é usada quando a sequência tem importância, como instruções ou classificações.
* **`<dl>`** serve para apresentar pares de termo e descrição, sendo útil para glossários ou especificações técnicas.

Exemplo prático: Em uma receita, usar `<ol>` para o preparo (1º passo, 2º passo...) é melhor do que `<ul>`, pois a ordem interfere no resultado.

---

### **3. A Expressão de Citações (Individual)**

**Elementos de citação encontrados:**

* **`<blockquote>`:** Usado em páginas de artigos e blogs para citar trechos inteiros de textos ou falas de terceiros. Exemplo: um parágrafo de uma entrevista.
* **`<q>`:** Aparece em textos jornalísticos para pequenas citações dentro de frases, geralmente entre aspas.

**Diferença semântica:**

* **`<blockquote>`** é para citações maiores e separadas do texto, geralmente com recuo visual.
* **`<q>`** é para citações curtas no meio do conteúdo.

**Análise:**
Esses elementos ajudam a deixar claro o que é citação de terceiros e o que é conteúdo próprio da página. Isso contribui para a clareza, credibilidade e organização do conteúdo.

---


