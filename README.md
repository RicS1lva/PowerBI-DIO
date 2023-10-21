# Repositório de projetos com Power BI 

### Desafio de Projeto: Processando e Transformando dados com Power BI

Neste desafio, Segui o passo a passo mostrado pela professora, na parte de criação da instância de Banco de dados na Azure, e a inserção dos dados neste BD. O Script teve de ser adaptado (usei o script de inserção que outra aluna disponibilizou nos fóruns, pois o fornecido no arquivo estava crashando).

Depois, já com o BD criado, modelei os dados conforme descrevi nestas anotações:

    Fiz o tratamento dos dados conforme solicitado nos slides

    Mudei os nomes das consultas para melhor visualização no PowerBI

    Desfiz a coluna do endereço em tres colunas separadas(Address, City, State)

    Mudança de tipos de dados nas colunas de salário

    No nome dos colaboradores, exclui o nome do meio, e juntei a coluna do primeiro com o último nome em todas as consultas em que aparece o nome dos colaboradores

    Na consulta de dept_locations, eu fiz como ilustrado pela professora, e juntei o nome do departamento com a localização.

    Após modelar a base dos dados, antes de fazer as consultas seguintes, percebi que as relações de tabela estavam todas erradas, então precisei redefinir todas as relações, para fazer com que os relatórios tivessem função.

    As duas “consultas adicionais” foram feitas com base no solicitado, identificando os departamentos atribuídos a cada colaborador, e depois fazendo uma consulta dedicada a mostrar os managers e seus respectivos subordinados. Acabei não fazendo o agrupamento, pois achei que ficaria confuso o relatório.

    Criei também uma nova consulta para juntar as informações dos colaboradores com a consulta works_on.

Para a criação da página de relatório, tive como base de pensamento, mostrar os custos com salário da empresa, em relação à dedicação com horas de trabalho dos colaboradores, relacionando também com políticas de pareamento de salário entre Homens e Mulheres, com dois gráficos que analisam se a média salarial entre eles, corresponde com a média de horas trabalhadas.

#### E a resposta da pergunta sobre a diferença entre mesclar e atribuir, é que o Mesclar cria uma nova coluna com informações da segunda tabela selecionada, o que mantém os dados daquela tabela, e acrescenta mais ifnromações para deixar mais completa a informação da seleção. Já se acrescentassemos, juntaria o resultado das duas e formaria uma só consulta consolidada, o que nos faria perder os dados separados.

Sei que ainda preciso melhorar bastante na pare de transformação de dados, mas acho que o curso me deu um norte para começar a estudar!
