# <center>Análise de Tarefas

## Histórico de Versão

| Data       | Versão | Descrição                            | Autor(es)                | Revisor(es)  |
| ---------- | ------ | ------------------------------------ | ------------------------ | ------------ |
| 24/02/2022 | 0.1    | Criação do documento                 | Pedro, Maicon            | ----         |
| 26/02/2022 | 0.2    | Melhorias no documento               | Pedro, Maicon            | ----         |
| 02/03/2022 | 0.3    | Correções pontuais                   | Pedro Helias Carlos      | Luiz Gustavo |
| 08/03/2022 | 0.4    | Correções na diagramação das imagens | Pedro Helias Carlos      |              |
| 08/03/2022 | 0.5    | Atualização do documento             | Pedro Helias Carlos      |              |
| 08/03/2022 | 0.6    | Adição do Método GOMS.               | Maicon Rodrigues Queiroz |              |

<div align="justify">
 
# 1. Introdução.

Análise de Tarefas consiste em procedimentos para entender qual é o trabalho dos usuários, como esse trabalho é realizado e a motivação por trás, o porquê desse trabalho. Quando se define trabalho, realiza-se menção direta aos objetivos do usuário quanto ao sistemas - quais objetivos o usuário almeja atingir. O que se busca com essa análise, e até se define como característica crucial, é entender e definir o que seria o "Desempenho satisfatório" do sistema. É entender como o sistema de trabalho afeta o domínio da aplicação, e vice-versa.
Especificamente, a análise de tarefas é utilizada em 3 atividades: Quando se procura realizar análise de situação atual; quando se procura determinar o redesign do sistema; e, por fim, quando se busca realizar a avaliação d resultado de uma intervenção que inclua a introdução de um novo sistema computacional.
Dentre os métodos para avaliar a Análise de Tarefas, temos a Análise Hierárquica de Tarefas.

# 2. Análise Hierárquica de Tarefas(AHT).

Esse método foi desenvolvido para entender as competências e habilidades exibidas em tarefas complexas e não repetitivas - por exemplo serviços de compra, login, adição de atividades em calendário, entre outros. Além disso, essa técnica detecta o comportamento e direcionamento de um site/sistema, e assim auxiliar na identificação de problemas de desempenho. Existem pontos importantes sobre essa técnica que é importante ser ressaltado:

- Tarefa: Qualquer parte do trabalho que precisa ser realizada. As tarefas podem ser definidas em termos dos seus objetivos. Tarefas mais complexas possuem sub-objetivos.
- Objetivo: Um estado final das coisas, aquilo que se busca, almeja atingir. Os objetivos compõem boa parte das tarefas. Utilizando a Técnica de AHT, identifica-se primeiramente os objetivos de alto nível, decompondo-se em sub-objetivos.
- Plano: O Plano representa os sub-objetivos oriundos de um objetivo de alto nível. Ele define não só os sub-objetivos necessários para alcançar um outro objetivo maior, mas como a ordem que esses sub-objetivos devem ser alcançados para realizar um processo maior.
- Operação: Operação é representada pelo nível mais baixo da hierarquia de objetivos. Os sub-objetivos são alcançados por uma operação, que é a unidade fundamental no processo de Análise Hierárquica. Uma operação é composta por entradas de sistema, os Inputs; as atividades ou ações; e o retorno das condições se baseia no Feedback.
- Ação: Pode ser entendida como uma instrução para executar algo.
- Input: Pode ser entendido como os estados atribuídos ao sistema.
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

<div align="center">

<b>Figura 2: </b> Estrutura criada para diagramar a funcionalidade do calendário.

   <img width="450" src="https://github.com/Interacao-Humano-Computador/2021.2-Grupo-05-Yale/blob/inicio/docs/documentos/imagens/hta1.png?raw=true" />
   
   <div>
      <div align="center">
      <b>Fonte: </b> Autoria própria.
      </div>
   </div>

<b>Figura 3: </b> Estrutura criada para diagramar a funcionalidade do Login.

   <img width="450" src="https://github.com/Interacao-Humano-Computador/2021.2-Grupo-05-Yale/blob/inicio/docs/documentos/imagens/hta2.png?raw=true"  />
   
   <div>
      <div align="center">
      <b>Fonte: </b> Autoria própria.
      </div>
   </div>

</div>

# 4. Passos para se executar uma análise hierárquica de tarefas.

Segundo Diaper (2003), uma Análise Hierárquica de Tarefas consiste nos seguintes passos:

1. Decidir os objetivos da análise. Em geral, envolvem projetar um sistema
   novo, modiﬁcar um sistema existente e desenvolver treinamento para os
   operadores.
2. Obter consenso entre as partes interessadas na deﬁnição dos objetivos da tarefa e medidas de sucesso. Devem ser deﬁnidos os resultados de desempenho desejados, tal como frequência de erros, e as formas como esses resultados serão aferidos. Para cada objetivo, as questões-chave são: “Qual evidência objetiva indica que esse objetivo foi atingido?” e "Quais as consequências da falha em atingir esse objetivo?”.
3. Identiﬁcar as fontes de informações das tarefas e selecionar as formas de aquisição de dados. Embora a observação direta seja amplamente utilizada como forma de aquisição de dados, geralmente contribui pouco sobre eventos incomuns que possam ser essenciais. Entrevistas com especialistas, registros do desempenho real e relatos de incidentes costumam trazer informações preciosas para a HTA.
4. Coletar dados e esboçar uma tabela ou diagrama de decomposição. Numa decomposição, os subobjetivos devem ser mutuamente exclusivos e exaustivos,
   ou seja, devem deﬁnir completamente o objetivo a que estão subordinados,
   sem que haja sobreposições entre os sub-objetivos. A decomposição é esboçada em um diagrama hierárquico e em uma tabela, que contém mais detalhes sobre as circunstâncias (inputs) que disparam o objetivo,
   ações e feedbacks de cada objetivo.
5. Veriﬁcar a validade da decomposição junto às partes interessadas, visando
   assegurar a conﬁabilidade da análise.
6. Identiﬁcar operações signiﬁcativas, tendo em vista o objetivo da análise.
7. Gerar e, se possível, testar hipóteses relacionadas aos fatores que afetam o aprendizado e o desempenho. Nessa etapa, pode ser útil utilizar as classiﬁcações de erro humano propostas por Reason (1990): desempenho baseado em habilidades, em regras, ou em conhecimento.

# 5. O Modelo GOMS

O modelo GOMS pode ser usado para medir a eficácia e eficiência da usabilidade com o intuito de aperfeiçoar o comportamento humano no que tange a IHC. Este tipo de modelo representa os conhecimentos procedurais exigidos para operar um sistema em termos de 4 componentes: Metas do usuário, Operadores ou ações básicas, Métodos, e Regras de Seleção. Motivado para fornecer um modelo de engenharia para a performance humana, capaz de produzir predições quantitativas a priori ou em um estágio anterior ao desenvolvimento de protótipos e teste com usuários. Ele prevê tempo de execução, tempo de aprendizado, erros, etc. identificando partes da interface associadas a essas previsões, de forma a orientar o re-design.

GOMS baseia-se na premissa de que nosso entendimento sobre o desenvolvimento de sistemas pode ser melhorado se levarmos em conta as atividades cognitivas e de processamento da informação do usuário. Ele se baseia no modelo é conseqüência direta dos princípios números 8 e 9 do MPIH: o princípio da racionalidade e o princípio do espaço do problema.

## O acrônimo GOMS representa os componentes de um modelo GOMS:

## Metas (G):

Metas constituem uma estrutura simbólica que define o estado de coisas a serem alcançadas e determina o conjunto de métodos possíveis. A função dinâmica da meta é prover um “ponto de memória” para o qual o sistema pode retornar no caso de falha ou erro. Além disso, as metas carregam informação sobre o que é desejado, métodos disponíveis, o que já foi tentado, etc. Metas expressam o que o usuário deseja realizar com o software. Normalmente as metas formam uma hierarquia de submetas;

## Operadores (O):

Operadores são atos elementares – percentuais, cognitivos e motores - cuja execução é necessária para mudar aspectos do estado mental do usuário ou afetar o ambiente da tarefa. Operadores são as ações que o software possibilita ao usuário realizar. Embora possam ser definidos em diferentes níveis de abstração, os modelos GOMS os definem em termos concretos como o pressionar de um botão, o selecionar de um item de menu, etc;

## Métodos (M):

Métodos são procedimentos necessários para conseguir realizar a meta. Relacionam se à maneira como o usuário armazena conhecimento sobre a tarefa, e à seqüência condicional de submetas e operadores que usa na realização da tarefa; envolvem testes no conteúdo da memória de curta duração do usuário e no estado corrente do ambiente envolvido. Métodos são seqüências bem aprendidas de submetas e operadores que permitem realizar a tarefa. Regras de seleção são requeridas quando há mais de um método disponível para a realização da mesma meta. Seleção refere-se à estrutura de controle usada no processo, em geral regras se-então. São as regras pessoais que o usuário escolhe para decidir que método usar.

## Regras de seleção (S):

Regras de seleção são requeridas quando há mais de um método disponível para a realização da mesma meta. Seleção refere-se à estrutura de controle usada no processo, em geral regras se-então. São as regras pessoais que o usuário escolhe para decidir que método usar.

## Exemplos de Componentes:

Com base na premissa de que “os usuários agem racionalmente para conseguirem alcançar as metas”, quatro componentes básicos compõem, portanto, o modelo:

1. um conjunto de metas;
2. um conjunto de operadores;
3. um conjunto de métodos para alcançar as metas;
4. um conjunto de regras para seleção dos métodos.

Operadores podem mudar um estado mental interno do usuário ou um estado do ambiente externo. Tempo de execução é um parâmetro importante dos operadores. Assim, a interação com o mundo físico aparece definida por um efeito específico e por uma duração específica. São operadores: mover o mouse, clicar o botão do mouse, shift-clicar no botão do mouse e pressionar a tecla delete. Operadores definem a granularidade da análise. Englobam uma mistura de mecanismos psicológicos básicos e comportamento organizado aprendido. Quanto mais fina a granularidade da análise, mais os operadores refletem os mecanismos psicológicos básicos.
Métodos são procedimentos já aprendidos; não são planos criados durante a realização da tarefa. Constituem a expressão da familiaridade e habilidade do usuário. Refletem a estrutura detalhada da tarefa no ambiente e o conhecimento da seqüência exata de passos requeridos pela ferramenta para a realização da tarefa. No exemplo citado, um método para a meta deletar-frase seria: mover mouse para o inicio da frase, pressionar botão do mouse, mover mouse para o final da frase, soltar botão do mouse, pressionar tecla Del (método marca e deleta).A estrutura de controle no GOMS é a seleção. A essência do comportamento habilidoso pressupõe que as seleções acontecem suavemente, sem a problemática da busca que caracteriza comportamento de resolução de problemas. No exemplo o usuário poderia ter selecionado como método o posicionar o mouse no início da frase e pressionar o delete tantas vezes quantas for o número de caracteres da frase a deletar (método deleta caracteres). Seleção de métodos pelo usuário pode se dar pela experiência na tarefa ou por treinamento. O usuário poderia ter uma regra para o deletar-frase como a seguinte: se a frase tem mais de oito caracteres, usar método marca e deleta; caso contrário, usar método deleta caracteres. Associando-se tempo a cada operador, tal modelo fornecerá previsão de tempo total para realização da tarefa. O modelo não é apropriado se erros ocorrem, uma vez que a detecção e correção de erros são rotineiras em comportamento habilidoso.

Pode ser usado no exemplo da ferramenta MOVER, O texto é movido através do uso do cut e paste. Para tal, o texto é primeiramente selecionado e então o cut é acionado. A seleção do texto pode ser feita de duas maneiras dependendo do tamanho do texto a ser selecionado. A meta paste requer posicionar o cursor no ponto de inserção e então acionar o paste.

# 6. Conclusão

A partir do conteúdo desenvolvido nesse tópico, verifica-se que há maiores aplicações para os métodos AHT e GOMS, onde AHT é um método que busca entender os princípios por trás de tarefas não muito complexas e pouco repetitivas, atingindo diretamente o proposto pelo site em estudo, primeiro pelo fato que as atividades não são rotineiras, o que as caracteriza como não repetitivas. Serviços semelhantes a associar eventos ao calendário pessoal não é muito comum e constantemente repetida pelo usuário e o Modelo GOMS que pode ser bastante dividido onde usuários novatos utilizarão o sistema, busca os procedimentos necessários para que seja possível de se concluir uma determinada tarefa, busca artefatos dos sistemas perceptivo, cognitivo e motor, sendo fundamentais para que se atinja a meta, faz com que os usuários mais experientes que utilizarão o sistema irão dar treinamento para os novatos, e busca também as estruturas de monitoramento e controle utilizadas no processo como um todo, fazendo com que seja um método prático.

# 6. Referencial bibliográfico utilizado.

- BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação humano-computador. Elsevier, 2010.
