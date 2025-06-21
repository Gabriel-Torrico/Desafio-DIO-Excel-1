***DESAFIO DE CURSO DIO - Projeto de Excel ✒***

## 📄 Descrição


O objetivo dessa ferramenta é focada em auxiliar investidores iniciantes na tomada de decisões, ajudando o usuário a entender seu perfil, apresentar cenários, sugerir opções de investimentos, e entender melhor o impacto de seus investimentos ao longo do tempo.

Este projeto foi desenvolvido com o intuito de aplicar conceitos de Excel em um simulador de **Fundos Investimentos Imobiliários** (FII's), trabalhando vários tipos de Formulas e Formatação Condicional. 

Nesta planilha também tem dois gráficos e um painél com duas formas de visualizar a ferramenta, que pode ser alterada a qualquer momento. 
Este modelo pode ser usado como base para futuras expansões e personalizações. 


## ⚙ Estrutura


Essa ferramenta contém os seguintes painéis:
- INICIALIZAÇÃO
- VISUALIZAÇÃO DA FERRAMENTA
- INVESTIMENTO MENSAL
- CENARIOS
- PERFIL DE INVESTIMENTO

Nestes painéis, os campos que estão com **FUNDO BRANCO** são os que o usuário pode editar para colocar sua entrada. Assim que os campos estiverem preenchidas corretamentes, será gerado cálculos que serão apresentados em outras células, especificamente nas que estão bloqueadas de edição e/ou com **FUNDO CINZA**.

<sub>*OBS: Na imagem em questão, todos os campos com uma **descrição em vermelho** são os que podem ser editáveis. O único campo que estará preenchido é a **Taxa de rendimento mensal em %** que por padrão é 1,079%.*</sub>

<img src="Imagens/Imagem 1 - Ferramenta Investimento.png" alt="Imagem 1" width="500"/>


## 🧱 Passo a Passo


### Etapa 1: Inicialização e Visualização

Nesta primeira etapa é onde pode ser inserido os primeiros dados para calcular uma sugestão de investimento. 
No painel **INICIALIZAÇÃO** o usuário pode inserir um *Salário Mensal* em Reais(R$) e o *Rendimento Carteira* em %. 
Após isso, será mostrado abaixo uma sugestão de investimento, sepadando 30% do salário para investimento. 

<img src="Imagens/Imagem 2 - Inicializacao.png" alt="Imagem 2" width="700"/>

> OBS: Não é um valor que precisa seguir a risca. 
Se sentir que precisa economizar mais ou investir mais do que a sugestão, na **Etapa 2** você pode inserir um novo valor que irá confirmar o quanto em R$ será separado mensalmente e investido.   

É também possível alterar o tipo de **VISUALIZAÇÃO** no painel ao lado. Ao clicar na célula, irá aparecer duas opções.   
1. "Informar avisos" adiciona textos que pode ajudar o usuário a entender os campos editáveis, útil para pessoas que não estão familiarizados e/ou esclarescer o que precisa inserir. 
2. "Simples" é a visualização limpa e padrão, útil para quem está mais familiarizado no uso de simuladores.
<img src="Imagens/Imagem 3 - Visualizacao.png" alt="Imagem 3" width="700"/>


### Etapa 2: Investimento mensal

Nesta etapa, o usuário pode fazer as confirmações do seu investimento no painel **INVESTIMENTO MENSAL**: 
1. *Aporte mensal*, o quanto vai investir mensalmente; 
2. *Investimento Anual* é por quantos anos o usuário irá investir;
3. *Taxa de rendimento mensal em %*, normalmente é ≈ 1,08%.
  Após inserir esses dados, e também o *Rendimento Carteira* em **INICIALIZAÇÃO**, será gerado o Patrimonio Acumulado e os Dividendos Mensais. Você pode alterar os dados acima para ver novos resultados. 
<img src="Imagens/Imagem 4 - Investimento Mensal.png" alt="Imagem 4" width="700"/>


### Etapa 3: Entender outros Cenários

Nesta etapa, temos a tabela não-editável **CENÁRIOS**:
- Ela serve para o usuário visualizar diferentes retornos de investimentos em diferentes anos; 
- Esses cálculos são parecidos com o painél de **INVESTIMENTO MENSAL** e depende dos dados inseridos. 
<img src="Imagens/Imagem 5 - Cenários.png" alt = "Imagem 5" width="700"/>


### Etapa 4: Identificando seu Perfíl de Investidor
Nesta etapa, o usuário pode inserir no painél **PERFIL DE INVESTIMENTO** o seu estilo de investimento em uma lista com três opções: 

1. Conservador: Investidor(a) que prioriza segurança e estabilidade. Estes tem baixa tolerância à oscilações ou que estão começando a investir.
2. Moderado: Investidor(a) que prioriza opções equilibradas e diversificadas. Estes tem tolerância moderada à oscilações e que tem mais experiência no mercado.
3. Agressivo: Investidor(a) que prioriza oportunidades de alto riscos. Estes tem alta tolerância à oscilações e que se preparam para enfretar perdas temporárias.
Depois de escolher uma das opções, será gerado cálculos na tabela abaixo. Essa tabela divide o *Aporte Mensal* em 6 categorias, cada uma com uma sugestão de investimendo ideal a depender de cada tipo de Perfil.
Por exemplo: Para um investidor Conservador, será priorizado investir o dinheiro do *Aporte Mensal* em Fundos Imobiliários (FIIs) de "Tijolo", enquanto para um investidor Agressivo terá mais prioridade para os de Papel.
<img src="Imagens/Imagem 6 - Perfil.png" alt = "Imagem 6" width="700"/>


## 📈 Gráficos

Temos dois gráficos nesta planilha:
1. Gráfico de Colunas - Linha do Tempo do Investimento - Vinculada diretamente no painél **CENÁRIOS**, representa os dados de *Retorno em Anos* e o *Patrimônio Acumulado*. 
2. Gráfico de Pizza   - Sugestão de investimento por Tipos de FII's - Vinculada diretamente a tabela de Tipos de FII, contendo o resultado do percentual de cada categoria.
<img src="Imagens/TORRICO'S INVEST - Gráficos.png" alt = "Imagem 6" width="500"/>   

## 🛠 Considerações Finais

Também tem uma planilha ****"CHAVE CONFIG"**** que são dados para alimentar o painél **PERFIL DE INVESTIMENTO**

Gostaria de agradecer ao professor da DIO, Felipe Aguiar, pelas aulas e explicações sobre o tema.
Futuramente posso fazer um ajuste ou outro no arquivo e em suas funcionalidades, caso necessário.

  Microsoft Excel.
  Fórmulas usadas: SE, E, VF, PROCV.
  Formatação Condicional e Gráfico de Pizza e Colunas.

## 📁 Planilha

<img src="Imagens/TORRICO'S INVEST - Macroview-SIMULADOR_INVESTIMENTO.png" alt = "Imagem 6" width="300"/>  <img src="Imagens/TORRICO'S INVEST - Macroview-CHAVE_CONFIG.png" alt = "Imagem 6" width="300"/> 


## 📥 Download da Planilha do Projeto

[📊 Baixar planilha Excel](ProjetoEXCEL/Desafio_Excel_DIO-Ferramenta_de_investimentos.xlsx)
