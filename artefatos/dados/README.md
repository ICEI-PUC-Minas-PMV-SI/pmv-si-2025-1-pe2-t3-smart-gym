# Artefatos relativos à modelagem de dados do projeto

Este diretório mantém os artefatos relacionados à modelagem de dados do projeto.

Os principais documentos a serem produzidos são:

<img src="./Academia de Ginastica.drawio.svg" alt="Modelo Relacional e DER" width="1000">

## Diagrama de Entidades e Relacionamentos (DER)

O Diagrama Entidade-Relacionamento construído para o sistema de gestão da academia de ginástica representa de forma organizada e lógica os principais processos e entidades envolvidos. Utilizando a notação de Chen, o modelo contempla as entidades Cadastro de Cliente, Colaboradores, Agendamento de Aulas e Formulários de Feedback, definindo de maneira clara seus atributos e seus relacionamentos.

A entidade Cadastro de Cliente centraliza todas as informações pessoais e médicas dos alunos, como matrícula, nome, CPF ou CNPJ, endereço, e-mail, telefone, sexo, data de nascimento, data de matrícula e histórico médico. Essa estruturação permite um controle completo dos dados necessários para a gestão e acompanhamento dos alunos.

A entidade Colaboradores representa os funcionários da academia, especialmente os instrutores, armazenando informações como PIN (identificador único), nome, telefone, função, data de admissão e hierarquia. Esses colaboradores estão diretamente ligados às atividades de agendamento de aulas e também podem ser alvo de avaliações nos formulários de feedback.

O Agendamento de Aulas registra os dados relacionados às aulas disponibilizadas pela academia, como a identificação da aula, data e hora da realização, nome da atividade, duração e o responsável pela condução. Essa entidade se relaciona tanto com os alunos (Cadastro de Cliente) quanto com os colaboradores (instrutores), permitindo acompanhar a participação e a execução das aulas.

A entidade Formulários de Feedback é utilizada para armazenar as avaliações fornecidas pelos alunos sobre os serviços da academia e os instrutores. Ela registra informações como data, tipo de feedback, nota atribuída, observações e os dados de identificação do aluno e do colaborador avaliado.

O DER evidencia a estrutura lógica dos dados e garante a integridade das informações, servindo de base sólida para o desenvolvimento do banco de dados relacional que suportará as operações da academia.

## Modelo relacional

O modelo relacional foi derivado do Diagrama Entidade-Relacionamento com o objetivo de estruturar o banco de dados da academia de forma normalizada e eficiente. A modelagem respeita os princípios de integridade referencial e organização de dados, assegurando um sistema robusto para gestão das informações.

A tabela Cadastro de Cliente é a base para o controle dos alunos e armazena todos os dados pessoais, médicos e administrativos relevantes. Ela possui como chave primária o campo Matrícula, que garante a identificação única de cada aluno. Esta tabela concentra dados como nome, CPF ou CNPJ, data de nascimento, endereço, contatos e histórico médico.

A tabela Colaboradores, identificada pela chave primária `PIN`, registra os dados dos profissionais da academia, incluindo `nome`, `telefone`, `função`, `data de admissão` e `hierarquia`. Essa tabela se relaciona com o Agendamento de Aulas e com os Formulários de Feedback, permitindo o rastreamento das atividades realizadas pelos colaboradores.

A tabela Agendamento de Aulas utiliza o campo `IdAula` como chave primária e registra informações sobre as aulas oferecidas, incluindo a `data e hora` de realização, `nome da aula`, `duração`, `matrícula do aluno` participante e `PIN` do instrutor responsável. Essa modelagem possibilita o controle da frequência e da organização das aulas na academia.

A tabela Formulários de Feedback é identificada pelo campo `NumeroProtocolo` e armazena os feedbacks fornecidos pelos alunos, contendo informações como `tipo de feedback`, `nota`, `observações` e os vínculos com a `matrícula` do aluno e o `PIN` do colaborador avaliado.

O modelo relacional estruturado permite a gestão segura e eficiente das informações, favorecendo consultas, análises e a geração de relatórios que apoiarão a administração da academia no processo de tomada de decisões.
