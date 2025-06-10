## PySpark-Task 💾

### ⭐ Tarefa 1: Leitura e Importação de Dados para DynamoDB
#### ✅ Objetivo da Tarefa

User Story:
Como nova usuária, desejo importar meus dados legados para um sistema novo utilizando PySpark com o objetivo de migrar para um novo sistema, sem perder os dados dele.

#### ✨ Etapas:

• Ler a planilha Excel com PySpark (ou Pandas integrado ao Spark).

• Tratar os dados (converter datas, tipos, etc).

• Modelar os itens para estrutura de gravação no DynamoDB.

• Inserir os dados na tabela DynamoDB via PySpark.

• Testar a persistência dos dados.

#### ✨ Requisitos Funcionais:

• Fazer o Sistema continuar funcionando com os dados importados.

• As tarefas precisam ser vinculadas ao novo usuário.

#### ✨ Critérios de Aceite:

1- Importar planilha do Excel com o PySpark.

2- Inserir os dados no banco DynamoDB.

#### ✅ Resultado Tarefa 1 - Dados Tratados, Modelados e Inseridos no DynamoDB

![market_list](https://github.com/user-attachments/assets/8336c088-4cdd-4385-810e-32bad2636b16)

### ⭐ Tarefa 2: Identificação, Categorização e Exportação das Tarefas Abandonadas 
#### ✅ Objetivo da Tarefa

User Story:
Como usuária do sistema, quero categorizar a cada 6 meses as tarefas abandonadas por mês, para que eu possa ver o volume de tarefas abandonadas e seus tipos por mês.

#### ✨ Etapas:

• Buscar dados no DynamoDB com PySpark.

• Filtrar tarefas abandonadas:

  > Pendentes há mais de 15 dias.
  
  > Lista de compras com mais de 30 dias.
  
• Agrupar as tarefas abandonadas por mês de abandono.

• Salvar resultados no DynamoDB (como nova coleção ou item).

• Gerar uma nova planilha com os dados organizados e um relatório.

• Exportar o resultado para planilha Excel.

#### ✅ Resultado Tarefa 2 - Categorização dos Dados e Geração do Relatório

![abandoned_tasks](https://github.com/user-attachments/assets/ed6b8170-7748-4425-98fb-60b553366b5a)


