# power_bi_analyst

## Desafio de Projeto Criando um Relatório com Power BI

Print da publicação no Power BI Service

![print](https://github.com/zawarudobngdev/power_bi_analyst/blob/master/Desafio%20Relat%C3%B3rio%20Criativo/relatorio_publicado.png)

---

## Desafio Processando e Transformando Dados com Power BI

Resposta da questão do desafio sobre mesclar ou atribuir:

Mesclar vs. Atribuir no Power BI

Mesclar:
A operação de mesclar no Power BI é usada para combinar duas tabelas em uma única tabela com base em uma coluna comum (chave de junção).
Quando você mescla, você está essencialmente realizando uma junção (join) das tabelas, o que permite agregar dados de ambas as tabelas em uma única exibição.
No caso específico, ao mesclar os nomes de departamentos e localização, você está combinando essas duas colunas em uma nova coluna única, criando um identificador composto que pode ser usado para análises futuras.

Atribuir:
A operação de atribuir é mais frequentemente associada à criação de novas colunas ou à atribuição de valores a colunas existentes com base em certas condições ou cálculos.
Atribuir geralmente não envolve a combinação de duas tabelas distintas, mas sim a modificação ou criação de colunas dentro de uma única tabela.

Por que usar "Mesclar"?
No caso específico, o objetivo é criar combinações únicas de departamento e localização. Isso é importante para formar um identificador único que possa ser utilizado na modelagem de dados, como na construção de um modelo estrela, onde cada dimensão deve ter identificadores únicos para evitar duplicidade e inconsistência nos dados.

Razões para usar Mesclar:

Criação de Identificadores Únicos:
Mesclar as colunas de departamento e localização permite criar uma coluna que combina esses dois campos, garantindo que cada combinação departamento-localização seja única.
Isso é essencial para criar chaves compostas que podem ser usadas como chaves primárias em modelos dimensionais.

Simplificação da Tabela:
Ao mesclar, você simplifica a estrutura da tabela, consolidando informações em uma única coluna, o que facilita a análise e a modelagem dos dados.
Reduz a complexidade da tabela, evitando a necessidade de gerenciar múltiplas colunas separadamente.

Preparação para Modelagem:
No contexto de um modelo estrela, ter colunas combinadas ajuda na definição clara das dimensões e facilita a criação de relações entre as tabelas de fatos e dimensões.
Uma coluna combinada de departamento e localização pode servir como uma dimensão em uma tabela de fatos, melhorando a integridade referencial e a eficiência das consultas.

Em resumo, a operação de mesclar é necessária para combinar as colunas de departamento e localização de maneira que se crie um identificador composto único. Isso não só simplifica a estrutura da tabela, mas também prepara os dados de forma adequada para a criação de um modelo estrela, onde cada dimensão deve ter identificadores únicos. A operação de atribuir não é adequada para esta finalidade, pois não combina duas colunas em uma única nova coluna com identificadores compostos.

