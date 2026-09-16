# Fundamentos do HTML 
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

## ​Aula 2 - Tags Semânticas 📐​
**As tags semânticas servem para dar significado e contexto ao conteúdo de uma página web, indicando claramente qual é a função de cada elemento para o navegador, para os mecanismos de busca e para ferramentas de acessibilidade.**

## 🔎​ Descrição das Tags:

* ### ​Header (cabeçalho)
    A tag HTML *header* representa um conteúdo introdutório ou um grupo de links de navegação para uma página ou uma seção específica dela.
    > sintaxe 
    ```bash
    <header></header>
    ```
    **O que contém na tag header**
    * Logotipos ou ícones
    * Títulos(elementos de < h1 > a < h6 > que são tags de textos e será abordado em outro tópico)
    * Menus de nevegação ( como tag < nav >)
    * Formulários de pesquisa 
    * Informações de utoria ou datas

    **Regras importantes de uso**
    * **Não é o < head >:** A tag < header > fica visível dentro do corpo (< body >) da página. Ela é diferente da tag < head >, que fica oculta e guarda configurações técnicas e metadados do site.
    * **Múltiplos usos:** Pode utilizar mais de um < header > por página. Um para o topo geral do site e outros dentro de seções (< section >) ou artigos (< article >).

* ### Main (Principal)
    Esta tag define o conteúdo principal do corpo (< body >) de um documento ou aplicação
    > sintaxe
    ```bash
    <main></main>
    ```
    **Uso:**
    * **Significado:** Indica a parte mais importante da página, que está diretamente ligada ao assunto central ou à função principal do aplicativo
    * **Acessibilidade e SEO:** Ajuda leitores de tela e os mecanismos de busca (como o Google) a entenderem rapidamente qual é o miolo útil do site, ignorando distrações.

* ### Article
    Esta tag representa uma seção de conteúdo independente, autocontida e reutilizável em uma página ou site.
    > sintaxe
     ```bash
    <article></article>
    ```
    **Uso:** 
    * **Conteúdo independente:** Significa que o bloco de código faz sentido por si só, mesmo se for retirado do contexto da página ou exibido em outro site (como em um feed de notícias, posts de blogs, comentário de usuários).
    * **Vantagens:** Melhora a semântica do código, ajuda leitores de tela na acessibilidade e facilita a leitura por mecanismos de busca (SEO).
    * **Conteúdo Aninhado:** é possível colocar um < article > dentro do outro. Por exemplo, a postagem principal de um blog usam um < article >, e os comentários dessa postagem também usam tags < article > dentro do principal.

* ### Section
    Esta tag é usada para agrupar conteúdos relacionados que compartilham um mesmo tema. Diferente da  tag < div >, que se trata de uma tag totalmente genérica e não possui valor semântico, sendo recomendada apenas para fins de estilização ou sripts.
    > sintaxe
     ```bash
    <section></section>
    ```
    **Uso:**
    * **Função Semântica:**  Indica o significado do bloco de código, ajudando leitores de tela e mecanismos de busca (como o Google) a entenderem a estrutura da página.
    * **Coteúdo Temático:** Geralmente inclui um título (h1 a h6) para definir o assunto daquele grupo de informações.
    * **Uso Correto:** Deve ser utilizada quando não existe uma tag semântica mais específica para a função(como nav,header,footer ou article).

* ### Aside
    Esta tag representa uma seção de uma página cujo conteúdo está apenas indiretamente ou tangencialmente relacionado ao conteúdo principal do documento.
    > sintaxe:
     ```bash
    <aside></aside>
    ```
    **Uso:**
    * **Significado Semântico:** Informa aos navegadores, leitores de tela e mecanismos de busca que aquele bloco é um conteúdo complementar (como uma barra lateral).
    * **Onde aplicar:**  Barras laterais (sidebars), biografias de autores, caixas de destaque, listas de links relacionados, anúncios ou menus de navegação secundária.
    * **Aparência Visual:** Ela não possui nenhum estilo padrão ou posicionamento lateral automático; é apenas um elemento em bloco (display: block) e precisa do CSS para ser posicionada visualmente ao lado do conteúdo principal.

* ### Footer
    Esta tag representa o rodapé de sua página ou de uma seção específica dentro dela.
    > sintaxe:
     ```bash
    <footer></footer>
    ```
    **Conteúdo que vai dentro da tag footer:**
    * Avisos de direitos autorias *(copyright)*
    * Informações de contat ou endereço.
    * Links para políticas de privacidade e termos de uso
    * Links para redes sociais ou mapa do site.

    * **Vantagens** 
    * **Acessibilidade:**  Facilita a leitura por leitores de tela usados por pessoas com deficiência visual.
    * **Organização semântica:** Informa aos navegadores e mecanismos de busca onde fica o conteúdo conclusivo.



















<section></section> 
    usada para definir uma seção genérica e temática de conteúdo em um documento, geralmente acompanhada de um título

<aside></aside>
    server para definiir uma seção de página cujo conteúdo está apenas indiretamente ou tangencialmente relacionado ao conteúdo principal ao seu redor 
    Usada para conteúdo complementar, ou seja, informações que agregam contexto, como biografias de autores, definições de glossário, caixas de destaque ou listas
    de link relacionados.
    É muito utilizada estruturalemnte para cirar as tradicionais sidebars em blos e portais

<footer></footer>
    cria um rodapé, sendo a última tag declarada
      
        
      
        
            
            


