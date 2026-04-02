# Carrinho de Compras - Modelos de Aviões de Guerra

Projeto desenvolvido em 2021, durante aulas de Linguagem e Desenvolvimento Web, do curso Técnico de Informática integrado ao Ensino Médio, no Instituto Federal de Caraguatatuba.

## Descrição do Projeto

Este projeto simula uma interface web de um carrinho de compras especializada em modelos de aviões de guerra da Segunda Guerra Mundial. O site permite aos usuários visualizar uma coleção de modelos de aviões históricos, selecionar tamanhos (escalas), quantidades e adicionar itens ao carrinho, com cálculo automático de subtotal, desconto e total.

## Funcionalidades

- **Visualização de Produtos**: Exibição de modelos de aviões em uma grade responsiva.
- **Detalhes do Produto**: Modal interativo com imagem ampliada, descrição, opções de escala (1/72, 1/48, 1/32) e controle de quantidade.
- **Carrinho de Compras**: Barra lateral com itens adicionados, quantidades ajustáveis e cálculo de preços.
- **Descontos**: Aplicação automática de desconto de 10% no subtotal.
- **Interface Responsiva**: Design adaptável para diferentes dispositivos.

## Produtos Disponíveis

1. **F4F Wildcat** - Caça utilizado nos primeiros anos de combate no Pacífico pela Marinha dos EUA.
2. **Focke Wulf Fw190 A5** - Caça de motor em estrela da Luftwaffe, temido em médias e baixas altitudes.
3. **Ki 61 - Hien** - Caça fabricado pela Kawasaki para o Exército Japonês, com motor em linha.
4. **Me 109 G6** - Famoso caça da Messerschmitt, voando pelos maiores ases da Luftwaffe; a versão G foi a mais produzida.
5. **P47 D - Thunderbolt** - Caça-bombardeiro de fabricação americana utilizado pela FAB.
6. **P51 D - Mustang** - O mais conhecido caça americano, importante escolta para os bombardeiros diurnos.
7. **Spitfire Mk-IX** - O mais famoso caça britânico, utilizado em toda a guerra.
8. **A6M Zero** - O mais famoso caça da Marinha Japonesa, terror do Pacífico nos anos iniciais da guerra.

Cada modelo possui três escalas com preços diferenciados:
- 1/72 (tamanho pequeno): R$ 100,00
- 1/48 (tamanho médio): R$ 150,00
- 1/32 (tamanho grande): R$ 200,00

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página e elementos semânticos.
- **CSS3**: Estilização responsiva com Flexbox e Grid, fontes do Google Fonts (Hepta Slab e Lato), ícones do Material Icons.
- **JavaScript (ES6)**: Lógica de interação, manipulação do DOM, eventos e cálculos dinâmicos.

## Estrutura do Projeto

```
carrinho/
├── index.html          # Página principal com estrutura HTML
├── README.md           # Este arquivo
├── css/
│   └── style.css       # Estilos CSS para layout e design
├── js/
│   ├── models.js       # Dados dos produtos (JSON-like)
│   └── script.js       # Lógica JavaScript para interatividade
├── img/                # Imagens dos modelos de aviões
│   ├── F4FWildcat.png
│   ├── Fw190A5.png
│   ├── Ki61Hien.png
│   ├── Me109G6.png
│   ├── P47D.png
│   ├── P51D.png
│   ├── SpitMk9.png
│   └── Zero.png
└── Códigos/
    ├── Carrinho_HTML.jpg
    ├── Carrinho_Models_JS.jpg
    └── Carrinho_Script_JS.jpg
```

## Objetivos Educacionais

Este projeto foi desenvolvido como parte do currículo de Linguagem e Desenvolvimento Web, visando:
- Praticar conceitos fundamentais de HTML, CSS e JavaScript.
- Implementar interatividade com manipulação do DOM.
- Trabalhar com dados estruturados em JavaScript.
- Desenvolver habilidades em design responsivo e UX básica.

## Possíveis melhorias

- Completar a implementação do script.js para funcionalidades completas do carrinho (adicionar/remover itens, atualizar total).
- Adicionar persistência de dados (localStorage) para salvar o carrinho entre sessões.
- Implementar validações e feedback ao usuário.
- Integrar com backend para processamento de pedidos.

## Autor

Desenvolvido por estudante do curso Técnico de Desenvolvimento de Sistemas do SENAI (2026).