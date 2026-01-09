
🧉 BarBaridade - Fábrica de Conceitos Gaudérios
O BarBaridade é uma ferramenta de gestão e criação voltada para proprietários e funcionários de bares que buscam fugir do óbvio. O sistema permite gerenciar o estoque de bebidas e, a partir dele, gerar nomes e descrições criativas com temática gauchesca para novos drinks, ajudando a entreter os clientes e personalizar o cardápio.

🚀 A Ideia do Projeto
Diferente de aplicativos de receitas para o consumidor final, o BarBaridade foi projetado como uma ferramenta B2B (Business to Business) de uso interno.

Como funciona:
Gestão de Estoque: Os funcionários gerenciam (CRUD completo) as bebidas disponíveis no estoque físico do bar através do catálogo do site.

Motor Criativo (Fábrica de Barbaridades): O dono do bar ou o bartender seleciona dois ingredientes do estoque e o sistema gera automaticamente um nome de impacto e uma descrição divertida (storytelling).

Flexibilidade Temática: Embora esta versão utilize o tema gauchesco, a arquitetura do projeto permite que o dicionário de termos seja facilmente alterado para qualquer outro tema (Pirata, Medieval, Geek, etc.), adaptando-se à identidade visual de qualquer estabelecimento.

🛠️ Funcionalidades Principais
Inventário Dinâmico: Listagem, cadastro, edição e exclusão de bebidas integradas a um banco de dados persistente.

Busca Inteligente: Filtro de bebidas por nome para agilizar a operação interna.

Algoritmo de Mixologia Criativa: Sistema que combina IDs de bebidas e gera conceitos aleatórios (Nomes, Frases de efeito e Imagens).

Cálculo Automático de Teor: O sistema calcula a média de graduação alcoólica da mistura em tempo real.

Interface Glassmorphism: Design moderno com foco em usabilidade e estética "Neon-Bar".

🧰 Tecnologias Utilizadas
Frontend: HTML5, CSS3 (Variáveis CSS, Flexbox, Glassmorphism), JavaScript (ES6+, Fetch API).

Backend: .NET Core Web API (C#).

Banco de Dados: Entity Framework Core com SQLite (Garantindo portabilidade e facilidade de teste).

Arquitetura: RESTful API.

📋 Estrutura de Arquivos Clave
Program.cs: Configuração da API, Endpoints REST e carga inicial do banco de dados.

script.js: Lógica de consumo da API, manipulação do DOM e controle de estado da interface.

GeradorDeMistura.js: O "cérebro" criativo que contém os arrays de nomes e frases gauchescas.

style.css: Identidade visual completa com foco em Dark Mode e Neon.
