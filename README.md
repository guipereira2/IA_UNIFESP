# Inteligência Artificial (UNIFESP) 

## Atividade 1: 
Essa atividade tem como objetivo introduzir conceitos básicos e iniciais de *Python* como gráficos, leitura de arquivos `csv`, modularização e documentação 

### Exercício 1: Carregar e salvar o dataset
Abra o arquivo "Iris" do *UCI Repository*. Carregue o *dataset* no seu código usando a biblioteca `Pandas` e salve-o em um *DataFrame* 

### Exercício 2: Análise inicial dos dados
Exiba as seguintes informações sobre o dataset
- O número de linhas e colunas
- O tipo de dado de cada coluna usando `.info()`
- Estatísticas descritivas usando `.describe()`

### Exercício 3: Gráficos 
Gere os seguintes gráficos usando a biblioteca `matplotlib` ou `seaborn`:
- Um **histograma** para cada uma das colunas numéricas
- Um **boxplot** para as colunas numéricas, segmentadas por espécie
- Um ***scatter plot*** (diagrama de dispersão) relacionando pares de colunas

### Exercício 4: Funções para modularização
Transforme cada uma das etapas anteriores em funções reutilizáveis, como:
- `load_dataset(file_path)` para carregar o *dataset*
- `dataset_summary(df)` para exibir informações e estatísticas básicas
- `plot_histogram(df, column)` para criar um histograma

### Exercício 5: Documentação do código
Use docstrings para documentar cada função.