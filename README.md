# rockeset_Tabela_Nutricional_2.0

Neste desafio, você deverá refatorar o aplicativo Tabela Nutricional, desenvolvido no módulo 06, com foco em organização arquitetural, autenticação local, persistência de dados e melhorias na experiência do usuário.

Instruções
Estrutura, regras e requisitos do projeto

1. Estrutura inicial
Objetivo: Usar como base o projeto Tabela nutricional para aplicar conceitos diversos, como arquitetura, autenticação e persistência de dados

2. Modularização + Clean Architecture
Objetivo: Refatorar o app para utilizar uma estrutura modular com camadas bem definidas (data, domain, presentation).

Criar pelo menos 3 módulos: ⁠app, ⁠presentation, ⁠domain, ⁠data.
Separar entidades, use cases e interfaces de repositórios no módulo ⁠domain. 
Implementar a camada de dados com uma estrutura que permita alternar fontes (ex: local vs remoto).
Adaptar a UI atual para consumir os dados da nova estrutura.
3. Login Local com Persistência
Objetivo: Implementar uma tela de login que permita acessar as funcionalidades do app apenas após authentication, utilizando armazenamento local de dados.

Tela de Login:

Campos: e-mail (ou nome de usuário) e senha.
Botão “Entrar” com validação local dos campos.
Feedback de erro se as credenciais forem inválidas.
Checkbox “Lembrar-me” (para manter o usuário logado entre sessões).
Cadastro (opcional):

Tela ou bottom sheet para cadastrar um novo usuário localmente.
Armazenar os dados em uma base local segura (usar Room ou DataStore).
Persistência:

Se o usuário marcar "Lembrar-me", salvar o login localmente (preferencialmente com DataStore).
Ao abrir o app, verificar se o usuário está autenticado e redirecionar direto para a tela de receitas.
Logout:

Botão de logout acessível no app que limpa o estado de autenticação.
4. Persistência com Room + Cache Local
Objetivo: Permitir salvar às receitas utilizando Room.

Implementar Room para salvar receitas.
5. Busca e Filtro de Receitas
Objetivo: Permitir que o usuário busque e filtre receitas de forma rápida e prática, atualizando a lista em tempo real conforme os critérios selecionados.

Implementar campo de texto com ícone de lupa.
Atualizar a lista de receitas conforme o usuário digita (filtro em tempo real). 
Permitir a busca por nome parcial ou completo da receita.
Filtro de receitas por tipo de refeição (Café da manhã, almoço, jantar, lanche), permitir múltipla seleção. 
Filtro por macronutriente (sugestão: componente sliders).
6. Interface (baseada no layout do Figma)
O layout deve ser feito com base no Figma do projeto. Após ele ser finalizado, se sinta livre para publica-lo e realizar alterações, mas para o desenvolvimento do desafio, se atenha ao que temos especificado no Figma.

7. Desenvolvendo o projeto
Para desenvolver esse projeto, recomendamos utilizar as principais ferramentas que utilizamos durante a formação até aqui.

Caso você tenha alguma dificuldade você pode ir no nosso 
fórum
 e deixar sua dúvida por lá!

Após terminar o desafio, caso você queira, você pode tentar dar o próximo passo e deixar a aplicação com a sua cara. Tente mudar o layout, cores, ou até adicionar novas funcionalidades para ir além 🚀

8. Entrega
Lembre-se que o intuito de um desafio é te impulsionar, por isso, dependendo do desafio, pode ser que você precise ir além do que foi discutido em sala de aula. Mas isso não é algo ruim: ter autonomia para buscar informações extras é uma habilidade muito valiosa e vai ser ótimo pra você treinar ela aqui com a gente!

E lembre-se: tenha calma! Enfrentar desafios faz parte do seu processo de aprendizado!

Após concluir o desafio, você deve enviar a URL do seu código no Github.

Além disso, que tal fazer um post no LinkedIn compartilhando o seu aprendizado e contando como foi a experiência?

É uma excelente forma de demonstrar seus conhecimentos e atrair novas oportunidades!

Obs: Se você se sentir à vontade, pode postar um print do resultado final e nos marcar! Vai ser incrível acompanhar a sua evolução! 💜

Feito com 💜 por Rocketseat 👋
