# 🦋 Grimório Digital: Portfólio Interativo & Roda do Ano Amazônica

> *"Ler um código é como ler uma história: basta interpretá-lo e usar a imaginação."*

Bem-vindo(a) ao meu repositório principal! Este projeto é um portfólio interativo construído em formato de **Grimório Mágico**, projetado para unir o desenvolvimento de software à narrativa visual, gamificação e às Ciências Naturais. 

Além de apresentar meus projetos educacionais e de programação, o site conta com um motor lógico que calcula em tempo real as fases da lua e adapta o calendário celta da Roda do Ano para a **realidade climática do bioma Amazônico**.

---

## 🔮 Funcionalidades (Feitiços do Código)

*   **Efeito Page-Flip Realista:** Um catálogo de projetos que simula um livro físico (Grimório) com física de virada de página, suporte a toque e responsividade, utilizando a biblioteca `StPageFlip`.
*   **Widget Temporal Dinâmico:** Um painel alimentado por Vanilla JavaScript que atualiza a cada segundo, exibindo:
    *   Data e Hora locais.
    *   **Algoritmo Lunar:** Cálculo matemático autoral baseado no ciclo de 29.53 dias para prever a fase exata da lua (sem dependência de APIs externas).
    *   **Roda do Ano Amazônica:** Um motor lógico que substitui os solstícios e equinócios europeus pelo ciclo hidrológico equatorial (Cheias, Vazantes, Inverno e Verão Amazônico).
*   **Design Thematico & Dark Mode:** Estilização profunda com CSS puro, utilizando paletas de verde terroso (`#3b4d36`), fundos escuros (`#111111`) e detalhes em ouro envelhecido (`#d4af37`), garantindo conforto visual e imersão.

---

## 🛠️ Tecnologias Utilizadas (Ingredientes do Caldeirão)

O projeto foi construído focando em fundamentos sólidos e manipulação direta do DOM, sem a necessidade de frameworks pesados:

*   **HTML5:** Semântica e estruturação em múltiplas páginas (`index.html` e `rodaAno.html`).
*   **CSS3:** Flexbox, Grid, pseudo-elementos, transições e variáveis de cor.
*   **JavaScript (ES6+):** Lógica de tempo, algoritmos matemáticos para astronomia básica e manipulação de eventos.
*   **[StPageFlip](https://nodlik.github.io/StPageFlip/):** Biblioteca para o efeito 3D e responsivo do livro.
*   **Tipografia & Ícones:** Google Fonts (Sora), FontAwesome e DevIcons.

---

## 🗺️ Arquitetura do Projeto

O repositório está dividido em duas experiências principais:

1.  `index.html`: A página principal, contendo o Widget Temporal, o manifesto de ensino gamificado e o Grimório listando projetos como *Memórias Póstumas*, *A Torre Invertida* e *A Biblioteca Oculta*.
2.  `rodaAno.html`: Uma extensão narrativa que documenta os 8 marcos sazonais adaptados para o Equador (ex: Ponto Solar das Águas, Festa da Germinação e Lama, Equinócio do Equilíbrio Hídrico).

---

## 🚀 Como Conjurar (Executar Localmente)

Como o projeto utiliza tecnologias web nativas (Vanilla), não é necessário nenhum processo de build complexo.

