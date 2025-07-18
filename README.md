MAPA – Banco de Dados I: Projeto Conceitual do Sistema de Gestão de Stands

Autor: Michael Ewerton Oliveira Disciplina: Banco de Dados I Instituição: UniCesumar

Contextualização do Projeto
A proposta deste MAPA consistiu na modelagem de um sistema de gestão para uma empresa especializada na criação e montagem de stands comerciais e promocionais. O objetivo foi estruturar, a partir de regras de negócio realistas, o Projeto Conceitual (DER) do banco de dados que atenderá às necessidades da organização no que diz respeito ao gerenciamento de colaboradores, equipes, clientes e projetos.

Entidades Modeladas
Colaborador: armazena dados pessoais, função, salário e vínculo bancário. Está ligado diretamente a uma equipe.

Equipe: identificada por código e setor (Desenvolvimento ou Montagem), podendo atuar em múltiplos projetos.

Cliente: contém informações fiscais, de contato e é responsável pela contratação de projetos.

Projeto: representa a demanda contratada, contendo URLs de orçamento e arquivos, além do status que percorre as etapas: Orçamento → Desenvolvimento → Montagem → Finalização.

Equipe_Projeto: entidade associativa para conectar cada projeto a uma equipe específica e seu tipo de atuação.

Relacionamentos
Um colaborador pertence a uma única equipe, mas uma equipe pode ter vários colaboradores.

Um cliente pode contratar múltiplos projetos, mas cada projeto está vinculado a um único cliente.

Cada projeto recebe duas equipes: uma para desenvolvimento e outra para montagem/desmontagem, por isso a modelagem exige a associação via entidade Equipe_Projeto com tipo de atuação definido.

Resultado e Aplicabilidade
O modelo conceitual apresentado cumpre com clareza as exigências do cenário, respeitando as regras de negócio e utilizando corretamente os conceitos de chave primária, chave estrangeira e normalização estrutural. A atividade também reforça o domínio sobre modelagem de dados relacionais como etapa fundamental na construção de sistemas robustos.

Avaliação concluída com sucesso e elogio do professor pela organização e entendimento técnico.
