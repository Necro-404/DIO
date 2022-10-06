# Comandos importantes para Pandas :panda_face:

- pandas.read_type() [documentação](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html)
- pandas.df.rename(columns={"nome_atual":"novo_nome}) [documentação](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.rename.html?highlight=pandas%20rename#)
- pandas.df.shape (mostra tamanho da base. [linhas, colunas])
- pandas.df.dtypes (exibe o typo de dados em cada uma das colunas)
- pandas.df.head() (Exibe as primeiras linhas)
- pandas.df.tail() (Exibe as ultimas linhas)
- pandas.df.describe() (Um dos métodos mais importantes, ele descreve a nossa DF com algumas informações importantes como média, mediana, menor e maior valor, etc.)
- pandas.df.loc[df["Coluna"]== "String"] (localiza colunas iguais a determinada string)
- df.groupby("Continente")["País"].nunique()