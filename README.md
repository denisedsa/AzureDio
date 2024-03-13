# AzureDio IA
## Trabalhando com Machine Learning na Prática no Azure ML

### Configurando Modelos e Conjunto de Dados


Acessar a opcao do menu a esquerda:

- Criacao
- ML Automatizado
  

Sera exibido ao lado direito os devidos preenchimentos para a criacao do ML:

- Método de Treinamento / Configuracoes Basicas;
- Nome do trabalho - DIOSANT (criacao exemplo);
- Nome Experimento;
- Novo nome do experimento;

  
  ![image](https://github.com/denisedsa/AzureDio/assets/90991366/09438251-b33e-4620-9288-21b8b239cdde)


- Descricao – opcional insere-se informacoes quando achar pertinente para apresentacao do ML;
- Marcas – Nome e Valor sao preenchimentos opcionais;


![image](https://github.com/denisedsa/AzureDio/assets/90991366/636ddad2-e148-448a-a5be-cdfdf6dce264)


No menu “Tipo de tarefa e dados” e necessario selecionar a opcao “Regressao – Para rever valores numericos contínuos” conforme lista/demonstracao abaixo:

1.	Classificacao;
2.	Regressao;
3.	Previsao de série temporal;
4.	Processamento de linguagem natural;
5.	Pesquisa visual computacional.

![image](https://github.com/denisedsa/AzureDio/assets/90991366/cc60598e-63eb-4b00-8749-94f901e4d2a0)


O proximo passo e clicar no item selecionar a opcao CRIAR;


![image](https://github.com/denisedsa/AzureDio/assets/90991366/9c93dfde-8dc3-4752-9fff-1b7b51cb6b50)


Em “Tipo de dados” inserir as informacoes conforme o exemplo:

- Nome: 
- Descricao: 
- Tipo: TABULAR 

![image](https://github.com/denisedsa/AzureDio/assets/90991366/0d27f2fa-08e6-4ab1-9a9b-8c883e351a39)


Apos a insercao dos dados clicar em AVANCAR.

- Em Fonte de Dados – acessar a opcao "DE ARQUIVOS DA WEB";
  

![image](https://github.com/denisedsa/AzureDio/assets/90991366/98734750-6106-443e-a59f-568452e1cec6)


- Neste preenchimento so precisa inserir o link da organizacao / controle e avancar novamente;

![image](https://github.com/denisedsa/AzureDio/assets/90991366/31f778b7-cb69-4732-9461-8bf0c8b5bcfa)


- Em Configuracoes insere-se as seguintes informacoes:

  :heavy_check_mark: Formato de arquivo: Delimitado

  :heavy_check_mark: Delimitador: Virgula

  :heavy_check_mark: Codificacao: UTF-8 (versao para o usuario)

  :heavy_check_mark: Cabeçalho de coluna: Somente o primeiro arquivo tem cabecalho

  :heavy_check_mark: Ignorar as linhas: Nenhum

  :heavy_check_mark: Dataset contem dados multi-linha: nao selecione


![image](https://github.com/denisedsa/AzureDio/assets/90991366/b3fafc1c-c79c-4350-87c3-41a5dc7fdb12)


![image](https://github.com/denisedsa/AzureDio/assets/90991366/0ce3187e-92ee-4d2a-91e6-3490cb8cd81d)


-	Na opcao EXAMINAR clicar em avançar para que sejam validados todos os processos de criacao;

- Tipo de Tarefas e Dados – Seleciona o ML criado para a inserção dos demais dados;


![image](https://github.com/denisedsa/AzureDio/assets/90991366/7f673b12-525e-4aaa-8023-ae8e197beaec)


![image](https://github.com/denisedsa/AzureDio/assets/90991366/6fd171c8-10cc-4e0b-8886-71313c51e4f7)


- Em configuracao acional seleciona apenas estas opcoes;

![image](https://github.com/denisedsa/AzureDio/assets/90991366/eb5b098b-95a8-4f6f-be0f-70cbbdfaa99c)


- Na opcao Limites deve-se inserir as seguintes informacoes;

![image](https://github.com/denisedsa/AzureDio/assets/90991366/2244c9b8-ca16-4c1a-9673-156da1d54d2e)


- Em Validar e Testar preencher apenas estas informacoes:

  Tipo de validacao: Divisao de validacao de treinamento;
  Validacao de percentual de dados: 10


![image](https://github.com/denisedsa/AzureDio/assets/90991366/e0879371-ccf0-491b-8f2e-c7c84d2fa9bd)

-	Para a opcao “Computacao” os dados ja existentes nos filtros devem ser mantidos - caso necessitem de algum ajustes estas sao as opcoes corretas:

  :ballot_box_with_check: Selecione o tipo de computacao: Serverless
  
  :ballot_box_with_check: Tipo de maquina virtual: CPU
  
  :ballot_box_with_check: Nível da maquina virtual: Dedicado
  
  :ballot_box_with_check: Tamanho da maquina virtual: Standard_DS3_V2
  
  :ballot_box_with_check: Numero de instancias: 1


![image](https://github.com/denisedsa/AzureDio/assets/90991366/693a27c5-c14d-41c9-bbf1-c4e027b0278e)


- Por último só precisa selecionar a opção “Enviar trabalho de treinamento” para que todos as informações sejam executadas e validadas.

![image](https://github.com/denisedsa/AzureDio/assets/90991366/ab9fda17-09eb-48a8-88f1-35e4487dccc0)


:pushpin: É sempre bom acompanhar o Deployment para saber se todos os dados inseridos foram processados corretamente.




:pushpin: REFERENCIAS DE PROCESSOS & DADOS DE ORIGEM


[Acesso ML Azure:](https://ml.azure.com/?azure-portal=true)


[DIO – Cursos Tecnologia](https://web.dio.me/track/microsoft-azure-ai-fundamentals)




[Documentação ML Azure:](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#create-an-azure-machine-learning-workspace)


[Explore o Azure AI Services](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html)
 
