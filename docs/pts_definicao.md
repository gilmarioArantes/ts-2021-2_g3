<!--![Estado de Goiás](./images/sedi.png)-->
<div align=center>
  <img src="./imagens/teste-software.png">
</div>

# <p style="text-align: center;">Processo de Teste de Software</p>

<b>
<p style="text-align: center;">Universidade Federal de Goiás</p>
<p style="text-align: center;">Instituto de Informática</p>
<p style="text-align: center;">Bacharelado em Enenharia de Software</p>
<p style="text-align: center;">INF303 Teste de Software - 2021/2</p>
<p style="text-align: center;">Professor: Gilmar Ferreira Arantes</p>
<p style="text-align: center;">Aluno 1: (201804673) Kesley Rozas dos Santos</p>
<p style="text-align: center;">Aluno 2: (201804642) Carlos Henrique Silva Bispo Rodrigues</p>
<p style="text-align: center;">Aluno 3: (201905543) Mateus da Silveira Batista</p>
<p style="text-align: center;">Aluno 4: (201802760) Dener Pereira Barbosa</p>
<p style="text-align: center;">Aluno 5: (202000300) Alexandre Wagner Cardoso Rodrigues</p>
</b>

## Histórico

| Versão | Data       | Alteração                             | Autor          |
| ------ | ---------- | ------------------------------------- | -------------- |
| 0.1    | 24/04/2019 | Elaboração do Documento               | gilmar.arantes |
| 0.2    | 26/04/2019 | Revisão da versão 0.1                 | gilmar.arantes |
| 0.3    | 08/08/2019 | Correções e Atualizações              | gilmar.arantes |
| 0.4    | 24/06/2020 | Adaptação às novas tecnologias da STI | gilmar.arantes |

# Introdução

<span style="color:blue">
Fazer uma introdução ao processo de teste elaborado pelo grupo. Nesta introdução deverá informar se o processo de teste do grupo é para um projeto de desenvolvimento ou para um projeto de manutenção de software.
</span>

<!--![Figura 1 - Etapas do Processo de Teste](./images/ptts.png)-->
<div align="center">
  <img src="./imagens/ptts.png">
  <figcaption><br/>Figura 1 - Etapas do Processo de Teste</figcaption>
  </div>
<br>

<span style="color:blue">Descrever em alto nível as etapas constituintes do processo, conforme Figura 1.</span>

## Papéis

<span style="color:blue">Descrever quais os papéis (roles) envolvidos no processo de teste.</span>

## Ambiente de teste

<span style="color:blue">Descrever o ambiente de testes, que envolve tanto software, quanto infraestrutura.</span>

# Planejar

<span style="color:blue"></span>

## Atividade - Definir conjunto de funcionalidades
```diff
- Existem duas dessa atividade, Esta e um 'Identificar Conjunto de Funcionalidades', e de acordo com a norma ela pertence a Projeto.
```

<span style="color:blue">
  Analisar o plano de testes e definir a partir dos requisitos todas funcionalidades do software que serão testadas, admitindo todos as funções de uso do software em questão, fazer fluxo de controle do software
</span>

### Responsável(eis):

<span style="color:blue">
  Analista de software
</span>

### Quando:

<span style="color:blue">
  Software aprovado para testes, plano de teste definido
</span>

### Como:

<span style="color:blue">
  como é a execução da atividade?
</span>

### Prazo:

<span style="color:blue">
  qual o prazo para execução?
</span>

### Entradas:

<span style="color:blue">
  quais são as entradas que subsidiam a execução?
</span>

### Saídas:

<span style="color:blue">
  quais são as saídas geradas pela execução?
</span>

### Fluxo:

<span style="color:blue">
  qual a próxima atividade a ser executada na sequencia?
</span>

## Atividade - Projetar Estratégia de Testes

<span style="color:blue">
  A estratégia de teste é um passo crítico na criação de um plano de teste. Um documento de estratégia de teste, é um documento de alto nível, geralmente desenvolvido pelo Test Manager. Este documento define:

Os objetivos de teste do projeto e os meios para alcançá-los Determina o esforço e os custos do teste
</span>

### Responsável(eis):

<span style="color:blue">
  Test Manager.
</span>

### Como:

#### Definir o escopo do teste

```diff
! Esta parte está um pouco estranho.
! Tente reescrever isso como se você estivesse instruindo alguem em como fazer, ao inves de explicando como fazer.
```

<span style="color:blue">

Antes do início de qualquer atividade de teste, o escopo do teste deve ser conhecido. Você deve pensar muito sobre isso.

Os componentes do sistema a serem testados (hardware, software, middleware, etc.) são definidos como "no escopo".

Os componentes do sistema que não serão testados também precisam ser claramente definidos como "fora do escopo". Definir o escopo do seu projeto de teste é muito importante para todas as partes interessadas. Um escopo preciso ajuda você

Dê a todos uma confiança e informações precisas dos testes que você está fazendo

Todos os membros do projeto terão uma compreensão clara sobre o que é testado e o que não é

Como você determina o escopo do seu projeto?

Para determinar o escopo, você precisa:

Exigência precisa do cliente

Orçamento do projeto

Especificação do produto

Habilidades e talento da sua equipe de teste</span>

#### Identifique o tipo de teste

<span style="color:blue">

Um tipo de teste é um procedimento de teste padrão que fornece um resultado de teste esperado.

Cada tipo de teste é formulado para identificar um tipo específico de problemas em um produto. Porém, todos os tipos de testes visam atingir um objetivo comum: "Detecção antecipada de todos os defeitos antes de liberar o produto para o cliente"</span>

#### Criar Logística de Teste

<span style="color:blue">

Em Test Logistics, o Test Manager deve responder às seguintes perguntas:

Quem vai testar?

Quando o teste ocorrerá?

Quem vai testar?
Você pode não saber o nome exatos do testador, mas o tipo de testador pode ser definido. Para selecionar o membro certo para a tarefa especificada, você deve considerar se a habilidade dele está qualificada para a tarefa ou não, também estimar o orçamento do projeto. Selecionar um membro errado para a tarefa pode causar falha ou atraso no projeto. A pessoa com as seguintes habilidades é a mais ideal para realizar testes de software:

Capacidade de entender o ponto de vista dos clientes

Forte desejo de qualidade

Atenção aos detalhes

Boa cooperação Em seu projeto, o membro que assumirá a execução do teste será o testador. Com base no orçamento do projeto, você pode escolher membro de origem ou terceirizar como testador.</span>

#### Definir critérios de teste

<span style="color:blue">
Critérios de teste é um padrão ou regra na qual um procedimento de teste ou julgamento de teste pode ser baseado. Existem 2 tipos de critérios de teste da seguinte forma

Critérios de Suspensão

Especifique os critérios críticos de suspensão para um teste. Se os critérios de suspensão forem atendidos durante o teste, o ciclo de teste ativo será suspenso até que os critérios sejam resolvidos.

Exemplo: se os membros da sua equipe relatarem que 40% dos casos de teste falharam, você deverá suspender o teste até que a equipe de desenvolvimento corrija todos os casos com falha.

Critério de saída

Especifica os critérios que indicam uma conclusão bem-sucedida de uma fase de teste. Os critérios de saída são os resultados desejados do teste e são necessários antes de prosseguir para a próxima fase de desenvolvimento. Exemplo: 95% de todos os casos de teste críticos devem passar.</span>

### Fluxo:

<span style="color:blue">a proxima atividade e: Determinar Equipe e Agendamento</span>


## Atividade - Determinar Equipe e Agendamento

<span style="color:blue">Agora neste atividade deve ser incluir a estimativa do tempo de cada tarefa a ser realizada, bem como a identificação das funções e habilidade da equipe para realizar os testes descritos no planejamento identificado. Essa atividade pode exigir a identificação das necessidadas de recrutamento ou treinamento de pessoal.</span>

### Responsável(eis)

<span style="color:blue">Test Manager - Com base na estimativa, o Test Manager sabe quanto tempo leva para concluir o projeto. Então ele pode fazer o cronograma do projeto apropriado.</span>

### Como

<span style="color:blue">Cada atividade de teste necessária na Estratégia de Teste deve ser agendada com base nas estimativas, dependências
e disponibilidade de pessoal, fazendo um cronogram para o gerenciamento, para poder utilizar no momitoramento do progresso do projeto.</span>
<span style="color:blue">A aprovação de pessoal e programação deve ser obtida das partes interessadas relevantes.</span>

### Entradas

<span style="color:blue">Para criar o cronograma do projeto, o Test Manager precisa de vários tipos de entrada, conforme abaixo:</span>
<span style="color:blue">Prazo para funcionários e projetos: os dias úteis, o prazo final do projeto, a disponibilidade de recursos são os fatores que afetaram o cronograma</span>
<span style="color:blue">Estimativa de projeto: Com base na estimativa, o Test Manager sabe quanto tempo leva para concluir o projeto. Então ele pode fazer o cronograma do projeto apropriado.</span>

### Fluxo:

<span style="color:blue">a proxima atividade e: Registrar Plano de Teste</span>

## Atividade - Registrar Plano de Teste

<span style="color:blue">Nesta atividade deve se registrar o plano de teste com base nas estimativas e estrátegias definidas.</span>

### Responsável(eis):

<span style="color:blue">Test Manager</span>

### Como:

<span style="color:blue">As estimativas finais para o teste devem ser calculadas com base na estratégia de teste projetada no Teste de Projeto Atividade de estratégia e a equipe e agendamento acordados na Determinação de Pessoal e Programação atividade.</span>
<span style="color:blue">A Estratégia de Teste identificada na atividade Criar Estratégia de Teste, o perfil de pessoal e cronograma acordado na atividade Determinar Pessoal e Agendamento, e as estimativas finais calculadas no tarefa anterior deve ser incorporada no plano de teste.</span>

### Entradas:

<span style="color:blue">Para registrar o teste, o Test Manager precisa da entrada, conforme abaixo:</span>
<span style="color:blue">Documentações anteriores para analise, para registrar o plano.</span>

### Fluxo:

<span style="color:blue">a proxima atividade e: Obter consenso sobre o plano de teste</span>

## Atividade - Obter consenso sobre o plano de teste

<span style="color:blue">Nesta etapa devemos conectar as partes interessadas para alhinhar opniões sobre o plano de teste para avalisar o desenvolviemento do plano.</span>

### Responsável(eis):

<span style="color:blue">Test Manager e Partes Interessadas</span>

### Como:

<span style="color:blue">
As opiniões das partes interessadas sobre o plano de teste devem ser coletadas.</br>
Os conflitos entre o plano de teste e as opiniões das partes interessadas devem ser resolvidos.</br>
O plano de teste deve ser atualizado para levar em consideração o feedback das partes interessadas.</br>
A aprovação do plano de teste deve ser obtida das partes interessadas.
</span>

### Entradas:

<span style="color:blue">
  Para criar o cronograma do projeto, o Test Manager precisa de vários tipos de entrada, conforme abaixo: </br>
  Isso pode ser alcançado por meio de workshops, entrevistas ou outros meios adequados.
  </span>

### Fluxo:

<span style="color:blue">a proxima atividade e: Projetar os Casos de Teste</span>

# Projetar os Casos de Teste

<span style="color:blue">Descrever a fase de Projetas os Casos de Teste, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.</span>

## Atividade 1

### Responsável(eis):

### Quando:

### como

### Prazo:

### Entradas:

### Saídas:

### Fluxo:

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

<span style="color:blue">Analise do plano de testes e projeto de testes pelo analista, definindo os requisitos a serem testados e processo de teste a ser usado pelos testadores</span>

## Atividade - Identificar Conjunto de Funcionalidades

### Responsável(eis):
<span style="color:blue">Analista de software</span>

### Quando:
<span style="color:blue">Plano de testes definido e aprovado</span>
### Como:
<span style="color:blue">Analista de software consulta plano de testes e seleciona requisitos funcionais que sejam passiveis de teste, documentando no plano a lista de requisitos que serão testados</span>
### Prazo:
<span style="color:blue">Algumas horas</span>
### Entradas:
<span style="color:blue">Plano de testes, documentação de requisitos</span>
### Saídas:

### Fluxo:

<span style="color:blue">Derivar condições de teste</span>

## Atividade - Derivar condições de teste

### Responsável(eis):
<span style="color:blue">Analista de software</span>
### Quando:
<span style="color:blue">Requisitos a serem testados definidos</span>
### como
<span style="color:blue">Definir Condições de teste para cada requisito a ser testado, atraves de particionamento por equivalencia e analises de valor limite</span>
### Prazo:
<span style="color:blue">algumas horas</span>
### Entradas:
<span style="color:blue">Plano de testes, documentação de requisitos</span>
### Saídas:
<span style="color:blue">Condições a serem testadas, estados a serem testados, preparação para casos de teste definidas em gráfico de causa e efeito</span>
### Fluxo:
<span style="color:blue">Derivar itens de cobertura de teste</span>

## Atividade - Derivar itens de cobertura de teste

### Responsável(eis):
<span style="color:blue">Analista de software</span>
### Quando:
<span style="color:blue">grafico de causa e efeito construido, plano de testes definido e condições a serem testadas definidas</span>
### como
<span style="color:blue">Analista observa quais funções do sistema realizam as ações a serem testadas e isola funcionalidades para teste, definindo funções do software para teste das causas definidas no grafico</span>
### Prazo:
<span style="color:blue">Algumas horas</span>

### Entradas:
<span style="color:blue">Gráfico de causa e efeito, plano de testes, documento de requisitos</span>

### Saídas:
<span style="color:blue">Lista de arquivos onde será realizado os testes e funções do programa a serem testadas</span>
### Fluxo:
<span style="color:blue">Derivar Casos de Teste</span>

## Atividade - Derivar Casos de Teste

### Responsável(eis):
<span style="color:blue">Analista de software</span>
### Quando:
<span style="color:blue">Funções do programa definidas pra teste e isoladas, preparadas para teste. Grafico de causa e efeitos esperados definidos</span>
### como
<span style="color:blue">Construção de planilhas de caso de teste para cada documento e requisito funcional a ser testado do programa, preparando as planilhas para  teste de todas as partições de equivalencia e registrando seus possiveis resultados esperados do grafico de causa e efeito</span>
### Prazo:
<span style="color:blue">1 dia</span>
### Entradas:
<span style="color:blue">Documento de requisitos, graficos de causa e efeito, plano de testes com especificação de testes</span>
### Saídas:
<span style="color:blue">Casos de testes especificados e prontos para execução</span>
### Fluxo:

# Executar

<span style="color:blue">Descrever a Executar, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.</span>

![image](imagens/Executar.png)

## Atividade - Preparar Ambiente de Teste

<span style="color:blue">
  Um ambiente de teste é preparado, simulando o ambiente de implanatação do software, o que garante uma maior precisão na execução dos testes. </br>
  O ambiente de teste está sujeito à alterações baseadas nas necessidades ou resultados de testes. 
</span>

### Responsável(eis):

<span style="color:blue">
  Gerente de Configuração </br>
  Tester
</span>

### Quando:

<span style="color:blue">
  Antes de realizar os testes.
</span>

### Como:

<span style="color:blue">
  De acordo com o especificado nas Configurações de Ambiente de Teste presente no Plano de Teste.
</span>

### Prazo:

### Entradas:

<span style="color:blue">
  Plano de Teste
</span>

### Saídas:

<span style="color:blue">
  Aprovação para Execução de Testes.
</span>

### Fluxo:

<span style="color:blue">
  Próxima Atividades: Executar Testes, Registrar Execução de Teste.
</span>

## Atividade - Executar Testes

<span style="color:blue">
  Os testes são executados de acordo com o planejado e seus resultados são registrados.
</span>

### Responsável(eis):

<span style="color:blue">
  Tester
</span>

### Quando:

<span style="color:blue">
  Após preparação do Ambiente de Teste. </br>
  Após o projeto de testes do componente a ser testado for concluido.
</span>

### Como:

<span style="color:blue">
  De acordo com o especificado no Projeto de Teste.
</span>

### Prazo:

### Entradas:

<span style="color:blue">
Aprovação para Execução de Teste. </br>
Conjunto de Testes. 
</span>

### Saídas:

<span style="color:blue">
Resultados Atuais de Testes. 
</span>

### Fluxo:

<span style="color:blue">
  Próxima Atividade: Comparar Resultados de Testes
</span>

## Atividade - Comparar Resultados de Testes

Os resultados dos testes são comparados com as saidas esperadas, para verificar se o software está funcionando corretamente

### Responsável(eis):

### Quando:

<span style="color:blue">
Imediatamente após as execução dos testes. 
</span>

### Como:

### Prazo:

### Entradas:

<span style="color:blue">
Resultados Atuais de Teste </br>
Resultados Esperados de Teste
</span>

### Saídas:

<span style="color:blue">
Resultados de Teste
</span>

### Fluxo:

<span style="color:blue">
  Próxima Atividade: 
</span>

## Atividade - Registrar Execução de Teste

<span style="color:blue">
  A execução de testes é registrada.
</span>

### Responsável(eis):

<span style="color:blue">
  Registro de Testes
</span>

### Quando:

<span style="color:blue">
  Durante o processo de execução de testes e comparação de resultados de teste.
</span>

### Como:

<span style="color:blue">
  Atraves de um log de execução dos testes, e registros manuais, caso necessário.
</span>

### Prazo:

### Entradas:

### Saídas:

<span style="color:blue">
  Registro de Testes
</span>

### Fluxo:

<span style="color:blue">
  Próxima Atividade:
</span>

# Entregar

<span style="color:blue">
  Descrever a Entregas, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.
</span>

## Atividade 1

### Responsável(eis):

### Quando:

### Como:

### Prazo:

### Entradas:

### Saídas:

### Fluxo:

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Considerações Finais
<span style="color:blue">Descrever as considerações finais a respeito deste processo de teste de software.</span>

