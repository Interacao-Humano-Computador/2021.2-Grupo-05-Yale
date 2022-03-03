# <center>Análise de Tarefas

## Histórico de Versão

| Data       | Versão | Descrição              | Autor(es)           | Revisor(es) |
| ---------- | ------ | ---------------------- | ------------------- | ----------- |
| 24/02/2022 | 0.1    | Criação do documento   | Pedro, Maicon       | ----        |
| 26/02/2022 | 0.2    | Melhorias no documento | Pedro, Maicon       | ----        |
| 02/03/2022 | 0.3    | Correções pontuais     | Pedro Helias Carlos | ----        |

<div align="justify">

# 1. Introdução.

Análise de Tarefas consiste em procedimentos para entender qual é o trabalho dos usuários, como esse trabalho é realizado e a motivação por trás, o por quê desse trabalho. Quando se define trabalho, realiza-se menção direta aos objetivos do usuário quanto ao sistemas - quais objetivos o usuário almenja atingir. O que se busca com essa análise, e até se define como característica crucial, é entender e definir o que seria o "Desempenho satisfatório" do sistema. É entender como o sistema de trabalho afeta o domínio da aplicação, e vice-versa.

Especificamente, a análise de tarefas é utilizada em 3 atividades: Quando se procura realizar análise de situação atual; quando se procura determinar o redesign do sistema; e, por fim, quando se busca realizar a avaliação d resultado de uma intervençaõ que inclua a introdução de um novo sistema computacional.

Dentre os métodos para avaliar a Análise de Tarefas, temos a Análise Hierárquica de Tarefas.

# 2. Análise Hierárquica de Tarefas(AHT).

Esse método foi desenvolvido para entender as competências e habilidades exibidas em tarefas complexas e não repetitivas - por exemplo serviços de compra, login, adição de atividade em calendário, entre outros. Além disso, essa técnica detecta o comportamento e direcionamento de um site/sistema, e assim auxiliar na identificação de problemas de desempenho. Existem pontos importantes sobre essa técnica que é importante ser ressaltado:

- Tarefa: Qualquer parte do trabalho que precisa ser realizada. As tarefas podem ser definidas em termos dos seus objetivos. Tarefas mais complexas possuem sub-objetivos.
- Objetivo: Um estado final das coisas, aquilo que se busca, almeja atingir. Os objetivos compõe boa parte das tarefas. Utilizando a Técnica de AHT, identifica-se primeiramente os objetivos de alto nível, decompondo-se em sub-objetivos.
- Plano: O Plano representa os sub-objetivos oriundos de um objetivo de alto nível. Ele define não só os sub-objetivos necessários para alcançar um outro objetivo maior, mas como a ordem que esses sub-objetivos devem ser alcançados para realizar um processo maior.
- Operação: Operação é representada pelo nível mais baixo da hierarquia de objetivos. Os sub-objetivos são alcançados por uma operação, que é a unidade fundamental no processo de Análise Hierárquica. Uma operação é composta por entradas de sistema, os Inputs; as atividades ou ações; e o retorno das condições se baseia no Feedback.

  - Ação: Pode ser entendidade como uma instrução para executar algo.
  - Input: Pode ser entendido como os estados atribuidos ao sistema.
  - feedback: Pode ser entendido como o retorno dos testes, o estado final.

A seguinte representação demonstra um diagrama básico a respeito da estrutura da AHT.

<div align="center">

<b>Figura 1: </b> Estrutura básica de diagramação para Análise de Tarefas.

<img width="450" src="https://github.com/Interacao-Humano-Computador/2021.2-Grupo-05-Yale/blob/inicio/docs/documentos/imagens/estrutura_hta.png?raw=true"  />

</div>

<div align="center">

<b>fonte:</b> BARBOSA, 2010

</div>

Para o nosso projeto, propôs-se a leitura de duas funcionalidades. A primeira se trata de uma funcionalidade de visualização de calendário, com alterações de tipo de visualização, sistema de busca, de filtragem, e de inscrição em eventos. Além dessa, temos a funcionalidade de Login, onde o usuário possui duas formas de se logar ao sistema e formas de recuperar a senha.

# 3. Diagrama do projeto.

(Imagem diagrama)

<div align="center">

<b>Figura 2: </b> Estrutura criada para diagramar a funcionalidade do calendário.

<img width="450" src="https://github.com/Interacao-Humano-Computador/2021.2-Grupo-05-Yale/blob/inicio/docs/documentos/imagens/hta1.png?raw=true" />

<b>Fonte: </b> Autoria própria.

<b>Figura 3: </b> Estrutura criada para diagramar a funcionalidade do Login.

<img width="450" src="https://github.com/Interacao-Humano-Computador/2021.2-Grupo-05-Yale/blob/inicio/docs/documentos/imagens/hta2.png?raw=true"  />

<b>Fonte: </b> Autoria própria.

</div>

# 4. Passos para se executar uma análise hierárquica de tarefas.

Segundo Diaper (2003), uma Análise Hierárquica de Tarefas consiste nos seguintes passos:

1. Decidir os objetivos da análise. Em geral, envolvem projetar um sistema
   novo, modiﬁcar um sistema existente e desenvolver treinamento para os
   operadores.
2. Obter consenso entre as partes interessadas na deﬁnição dos objetivos da tarefa e medidas de sucesso. Devem ser deﬁnidos os resultados de desempenho desejados, tal como frequência de erros, e as formas como esses resultados serão aferidos. Para cada objetivo, as questões-chave são: “qual evidência objetiva indicará que esse objetivo foi atingido?” e “quais as consequências da falha em atingir esse objetivo?”.
3. Identiﬁcar as fontes de informações das tarefas e selecionar as formas de aquisição de dados. Embora a observação direta seja amplamente utilizada como forma de aquisição de dados, geralmente contribui pouco sobre eventos incomuns que possam ser essenciais. Entrevistas com especialistas, registros do desempenho real e relatos de incidentes costumam trazer informações preciosas para a HTA.
4. Coletar dados e esboçar uma tabela ou diagrama de decomposição. Numa decomposição, os subobjetivos devem ser mutuamente exclusivos e exaustivos,
   ou seja, devem deﬁnir completamente o objetivo a que estão subordinados,
   sem que haja sobreposições entre os subobjetivos. A decomposição é esboçada em um diagrama hierárquico e em uma tabela, que contém mais detalhes sobre as circunstâncias (inputs) que disparam o objetivo,
   ações e feedbacks de cada objetivo.
5. Veriﬁcar a validade da decomposição junto às partes interessadas, visando
   assegurar a conﬁabilidade da análise.
6. Identiﬁcar operações signiﬁcativas, tendo em vista o objetivo da análise.
7. Gerar e, se possível, testar hipóteses relacionadas aos fatores que afetam oaprendizado e o desempenho. Nessa etapa, pode ser útil utilizar as classiﬁcações de erro humano propostas por Reason (1990): desempenho baseado
   em habilidades, em regras, ou em conhecimento.

# 5. Referencial Bibliográfico utilizado.

- BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação humano-computador. Elsevier, 2010.
