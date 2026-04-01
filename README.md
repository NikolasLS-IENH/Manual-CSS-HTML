# WebGuides: Manual Interativo de HTML e CSS

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

> Uma documentação visual, prática e colaborativa sobre os fundamentos do desenvolvimento web, construída do zero sem o uso de frameworks.

**[https://nikolasls-ienh.github.io/Manual-CSS-HTML/](#)** *(Insira o link do GitHub Pages aqui depois)*

## Sobre o Projeto
Este projeto é um guia de consulta rápida focado puramente em **HTML5** e **CSS3**, construído de forma colaborativa por uma equipe de 4 desenvolvedores ao longo de um sprint de 2 semanas. O manual apresenta não apenas a teoria e a sintaxe das principais tags e propriedades, mas também renderiza exemplos visuais lado a lado com os blocos de código.

## Design e UI/UX
A interface do projeto foi fortemente inspirada na excelente documentação oficial do **Vue.js**. O grande desafio técnico deste projeto foi replicar uma interface moderna e responsiva **utilizando exclusivamente HTML e CSS**, sem nenhuma linha de JavaScript.

**Destaques Técnicos da Interface:**
- **Dark Mode Nativo:** Uso de Variáveis CSS (`:root`) para gerenciar a paleta de cores.
- **Layout Fluido:** Estruturação da página utilizando `CSS Grid` e `Flexbox`.
- **Navegação Sticky:** Barra lateral e cabeçalho fixos utilizando `position: sticky`.
- **Menu Mobile sem JS:** Implementação de um menu hambúrguer funcional em telas menores utilizando a técnica avançada de CSS conhecida como Checkbox Hack (`:checked`).

## Funcionalidades e Divisão de Módulos
O manual foi dividido em quatro módulos principais para facilitar a manutenção concorrente do código e o trabalho em equipe:

- **Módulo 1: Estrutura e Semântica (HTML)** - Tags de texto, títulos, listas, links e a importância da web semântica (`<header>`, `<article>`, `<footer>`).
- **Módulo 2: Interação e Formulários (HTML/CSS)** - Tipos de `<input>`, botões, `<select>`, `<textarea>` e suas validações visuais nativas.
- **Módulo 3: Estilo e Tipografia (CSS)** - Guia de cores, manipulação de fontes, espaçamentos (Margin/Padding), bordas e sombras.
- **Módulo 4: Layouts e Posicionamento (CSS)** - Exemplos práticos e interativos de como estruturar páginas utilizando `Flexbox` e `Grid`.

## Como executar localmente
O projeto não possui dependências, pacotes ou necessidade de build. Para rodar:

1. Clone este repositório executando o comando abaixo no terminal:

    git clone https://github.com/NikolasLS-IENH/Manual-CSS-HTML.git

3. Abra a pasta do projeto no VSCode.

4. Utilize a extensão Live Server para abrir o arquivo index.html ou arraste o arquivo diretamente para o seu navegador.

## Organização e Estrutura de Pastas
Para evitar conflitos de merge e facilitar o trabalho em equipe, a estrutura do projeto isola as responsabilidades de cada módulo:

    📁 webguides-manual/
    ├── 📄 index.html           (Capa/Menu principal)
    ├── 📁 paginas/             (Páginas de conteúdo)
    │   ├── 📄 semantica.html   (Módulo 1)
    │   ├── 📄 formularios.html (Módulo 2)
    │   ├── 📄 estilos.html     (Módulo 3)
    │   └── 📄 layouts.html     (Módulo 4)
    └── 📁 css/                 (Estilos isolados)
        ├── 📄 global.css       (Variáveis, reset, tipografia e layout base)
        ├── 📄 semantica.css    (Estilos do Módulo 1)
        ├── 📄 formularios.css  (Estilos do Módulo 2)
        ├── 📄 estilos.css      (Estilos do Módulo 3)
        └── 📄 layouts.css      (Estilos do Módulo 4)

## Equipe de Desenvolvimento
- **[Nikolas Lopes da Silva](https://github.com/NikolasLS-IENH)** - *Layout Base e Módulo 1*
- **[Jonathan Ruan Barros Acedero](https://github.com/jonathanacedero)** - *UI/UX (Cores/Tipografia) e Módulo 2*
- **[Guilherme Mayer Pinto](https://github.com/Guilherme-Mayer)** - *Estilização de Código e Módulo 3*
- **[Vinicius Daniel Góis Ferreira](https://github.com/vinidferreira)** - *Responsividade/Mobile e Módulo 4*
