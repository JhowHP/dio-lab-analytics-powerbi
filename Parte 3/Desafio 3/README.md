# Desafio 3

### Nesse desafio vamos está verificando fazendo desde a criação do banco sendo instanciado na Azure, como também suas devidas transformações direto no Power BI.

## Iremos utilizar as seguintes ferramentes:
- Power BI;
- Power Query;
- MYQSL;
- Microsoft Azure.

## Fluxo de dados
- Coleta;
- Transformação;
- Criação do relatório;
- Publicação do relatório;
- Inserção em um Dashboard.

### Transformação de dados
- Verifique os cabeçalhos e tipo de dados; ✓
- Modifique os valores monetários para o tipo double preciso; ✓
- Verique a existência dos nulos e analise a remoção; ✓
- Os employees com nulos em Super_ssn podem ser os gerentes; ✓
- Verifique se há algum colaborador sem Gerente; ✓
- Verificar se há algum departamento sem Gerente; ✓
- Se houver depart sem Gerente, preencher como se tivessem os dados; ✓
- Verificar horas dos dos projetos; ✓
- Separar colunas complexas (Ex: Endereços); ✓
- Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores (Mescla terá como base EMPLOYEE e elimine as colunas desnecessárias); ✓
- Explicar o por que que nesse caso foi usado o mesclar e não o combinar colunas, o motivo da operação; ✓
- Realizar a junção dos colaboradores e rescpectivos nomes dos gerentes. (Necessitando realizar)
- Caso seja feito com consulta SQL especificar qual a query utilizada no processo ou caso seja feito com mescla de tabelas tmabém; 
- Mesclar as colunas de nome e sobrenome; ✓
- Mescle os nomes de departamentos e localização. Depart-local único; ✓
- Explique porque, neste caso supracitado, podemos mesclar e não atribuir; ✓
- Agrupe os dados a fim de saber quantos colaboradores existem por gerente; (Necessitando realizar)
- Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela. ✓

✓

#### Explicando os casos de mesclar e acrescentar
- Caso 1: Nesse caso é utilizado o mesclar para que seja associado corretamente as informações de acordo com suas linhas, no caso, cada DNO de departament seja atribuido corretamente em employee;
- Caso 2 (Departament & Local): Nesse caso utilizamos mescar para podermos associar as devidas localizações aos devidos departamentos, isso é feito a partir do Dnumber que é igual para ambas as tabelas e locais;