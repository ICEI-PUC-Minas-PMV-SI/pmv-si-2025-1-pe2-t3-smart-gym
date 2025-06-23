# Lista dos processos de negócio do sistema

## Gestão de Cadastro de Clientes

<img src="./Processo de Cadastro de Cliente.png" alt="Processo de Cadastro de Clientes" width="500">

Para solucionar os problemas de centralização e atualização de informações cadastrais, a academia implementou um Sistema de Gestão Integrado que permitirá a automatização do cadastro de clientes. Esse sistema contará com um banco de dados relacional bem estruturado, garantindo consultas rápidas e precisas.

Nesse modelo aprimorado o cliente da academia consegue realizar seu cadastro digitalmente, ao existir um banco de dados no qual armazena os dados, evitando erros comuns de digitação e possibilitando correções no cadastro. Após inserir os dados no sistema e verificado sua validade junto ao banco de dados, o sistema consegue validar a liberação do acesso deste usuário. Entretanto, caso algum dado seja digitado de maneira incorreta, o banco de dados relacional atua solicitando de algum colaborador da recepção a correção dos dados inseridos.  

Melhorias propostas:

* Cadastro Online: Os novos alunos poderão preencher suas informações diretamente em um portal, eliminando a necessidade de formulários físicos.

* Relatórios Gerenciais: O sistema permitirá a geração de relatórios sobre número de alunos ativos, planos contratados, auxiliando na tomada de decisões estratégicas.

## Organização e Agendamento de Aulas

<img src="./Processo de Agendamento de Aulas.png" alt="Processo de Agendamento de Aulas" width="500">

O fluxo TO BE do processo de agendamento das aulas foi criado focando na resolução dos problemas anteriormente identificados. Com ele, destacamos a importância da modernização do processo e dos sistemas que serão implementados para que as consequências causadas, como perda de clientes e informações inconsistentes, sejam minimizadas.

O aluno dependia de um atendimento 100% presencial, o que tornava o processo lento e passível de divergências nos dados, por isso, a nova versão implementa um sistema de Autoatendimento digital, permitindo que o cliente tenha acesso remoto a lista de aulas disponíveis e indisponíveis para prosseguir no fluxo. Com isso, vemos uma redução significativa nas filas de espera, economia de tempo promovendo agilidade e aumento da autonomia dos alunos.

O mesmo ocorre com a etapa de envio dos documentos, agora feita inteiramente pela plataforma online sem precisar fazer com que o aluno retorne ao início do processo caso não anexe todos os documentos, bem como na etapa de preenchimento do, agora, formulário de inscrição onde ele será inteiramente preenchido na plataforma, sem ocupar espaço físico e diminuindo o risco de perdas de dados. Ambas as etapas modificadas trazem mais segurança aos dados, deixando-os mais consistentes para serem usados no suporte à tomada de decisões, visto que o acesso a eles será feito diretamente em um banco de dados.

Seguindo a análise, foi feita a melhoria do processo de marcação de presença e validação da matrícula, pois parte dessa fase dependia da ação do professor responsável pela aula, o que trazia riscos como atrasos, esquecimentos, ou até mesmo, fraudes. Como alternativa, foi adicionado ao fluxo a validação da presença do aluno via check-in com QR code e localização geolocalização disponíveis, pois assim diminuímos a dependência no professor e a margem de erro.

Por fim, a possibilidade de cancelamento de matrícula era totalmente manual, dependendo de algum dos colaboradores da academia para fazer a baixa da ficha física e posteriormente o descarte da mesma. Resolvendo esses impasses implementando um sistema digital onde o aluno pode solicitar o cancelamento e deixar um feedback, promove a transparência, elimina a papelada física e traz facilidade na hora de usar os dados para realizar análises de retenção de alunos, por exemplo.

Com isso, o sistema antes arcaico e manual foi transformado em um processo dinâmico, totalmente digital e autônomo, superando os resultados esperados.

## Gestão e Análise de Feedback dos Clientes

<img src="./Processo de feedback.png" alt="Processo de Feedback" width="500">

Para entender melhor a experiência dos alunos e identificar pontos de melhoria, será implementado um Sistema de Pesquisa de Satisfação, garantindo a coleta estruturada de feedbacks.

Melhorias propostas:

* Centralização dos Feedbacks: Todos os retornos dos alunos que dependem de atuação da gerência ficarão registrados em uma plataforma para fácil análise.

* Métricas de Satisfação: O sistema calcula indicadores como Net Promoter Score (NPS), avaliações de instrutores e infraestrutura, permitindo a análise de tendências.

* Ações Baseadas em Dados: Com base nos feedbacks, a academia poderá implementar melhorias contínuas, como ajustes na programação, treinamentos para instrutores e melhorias estruturais.

A implementação dessas melhorias garantirá mais eficiência, agilidade e qualidade na gestão da academia, melhorando a experiência dos clientes e aumentando a retenção de alunos. Com processos de dados precisos, a academia poderá tomar decisões mais estratégicas, reduzindo desperdícios e otimizando seus serviços.
