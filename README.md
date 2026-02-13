🔐 Sistema de Portaria Inteligente – TechZone
📌 Descrição

Este projeto é um protótipo de sistema de portaria inteligente desenvolvido em HTML, CSS e JavaScript. Ele simula a validação de entrada de colaboradores em um edifício com base no nome cadastrado e no horário de acesso permitido.

O sistema verifica se o colaborador está na lista de autorizados e se o horário está dentro do período permitido (das 6h às 21h59).

🚀 Funcionalidades

✔ Interface moderna com design responsivo
✔ Validação de nome utilizando Array e .includes()
✔ Validação de horário com operadores de comparação
✔ Uso de estrutura condicional if / else if / else
✔ Feedback visual colorido para cada situação

🧠 Regras de Negócio

O colaborador precisa estar cadastrado na lista:

["Gbrt", "Vila", "Tukaze", "Breno", "Ludmila", "Brecci"]


O acesso só é permitido entre 06h e 21h59.

📍 Regras aplicadas:

✅ Nome cadastrado + horário entre 6 e 21 → Acesso Permitido

⛔ Nome cadastrado + horário após 22h → Acesso Negado (Fora do horário)

❌ Nome não cadastrado → Acesso Negado

⚠ Horário inválido → Mensagem de erro

🛠 Tecnologias Utilizadas

HTML5

CSS3 (Flexbox, Gradiente, Animação)

JavaScript (DOM, Arrays, Condicionais)

🎨 Layout

O sistema possui:

Fundo com gradiente moderno

Card centralizado com sombra

Inputs estilizados com efeito focus

Botão com animação hover

Mensagem dinâmica com cores indicativas

📂 Como Executar

Copie o código completo para um arquivo chamado:

index.html


Abra o arquivo no navegador (Google Chrome, Edge, Firefox etc).

Digite o nome e o horário para testar o acesso.

🎯 Objetivos de Aprendizagem

Manipulação de Arrays

Uso do método .includes()

Validação de dados com operadores lógicos

Manipulação do DOM

Aplicação de estruturas condicionais

👨‍💻 Autor

Projeto acadêmico desenvolvido para prática de lógica de programação e desenvolvimento web.# portaria
