# 📊🚀 Simulator Télos - Nível 4 Trilha de Dados

### Contextualização / Contextualización 

PT:
Olá e bem-vindo ao emocionante mundo da análise de dados! Neste projeto, mergulhamos na coleta e visualização de dados através de duas atividades desafiadoras: raspagem de dados do IMDB e criação de KPIs com base na NBA. A capacidade de analisar dados e extrair insights significativos é fundamental para a tomada de decisões estratégicas. 

ES:
¡Hola y bienvenido al emocionante mundo del análisis de datos! En este proyecto, nos adentramos en la recopilación y visualización de datos a través de dos desafiantes actividades: la raspagem de datos de IMDB y la creación de KPIs basados en la NBA. La capacidad de analizar datos y extraer insights significativos es fundamental para la toma de decisiones estratégicas.

###  🎯 Desafíos / Desafios

#### PT: 1. Raspagem de Dados IMDB
   
Objetivo: Aprender a extrair e analisar informações de sites usando técnicas de web scraping. Raspagem da URL https://www.imdb.com/chart/top/ para extrair os 25 primeiros filmes.

Ação: Crie um DataFrame no pandas com as seguintes colunas: Título, Ano, Duração, Nota, Classificação Indicativa.

##### KPIs Sugeridos:

Filmes por Ano: Visualize quantos filmes foram lançados a cada ano.

Relação entre Nota e Duração: Explore como a duração do filme se relaciona com sua avaliação.

Relação entre Nota e Classificação Indicativa: Analise como a classificação indica a qualidade percebida dos filmes.



#### ES: 1. Raspado de Datos IMDB

Objetivo: Aprender a extraer y analizar información desde sitios web utilizando técnicas de web scraping. Raspado de la URL https://www.imdb.com/chart/top/ para extraer los 25 primeros filmes.

Acción: Crea un DataFrame en pandas con las siguientes columnas: Título, Año, Duración, Calificación, Clasificación Indicativa.

##### KPIs Sugeridos:

Películas por Año: Visualiza cuántas películas se lanzaron cada año.

Relación entre Calificación y Duración: Explora cómo la duración de la película se relaciona con su calificación.

Relación entre Calificación y Clasificación Indicativa: Analiza cómo la clasificación indica la calidad percibida de las películas.



#### PT: 2. KPIs com a Base da NBA

Objetivo: Assumir o papel de Analista de Dados do time ‘Sacramento Kings’.

Ação: Com a base de dados dos jogadores da NBA, elabore KPIs que possam melhorar o desempenho do time.

##### KPIs Sugeridos:

##### Salários:

Boxplot de Salários: Visualiza a distribuição de salários, identificando outliers e tendências.

Média de Gastos com Salário: Compara os gastos do seu time com os dos concorrentes.

Salário Máximo, Mínimo e Mediano: Informações críticas sobre a tendência central e extremos dos salários.

##### Relação Salário x Outros Atributos:

Gráfico de Dispersão Salário x Idade: Descubra padrões entre salário e idade.

Gráfico de Dispersão Salário x Altura/Peso: Examine a correlação entre salário e características físicas.

Gráfico de Barras Salário Médio por Time: Compare o salário médio dos jogadores de cada time.

##### Performance dos Jogadores:

Gráfico de Barras Média de Rating por Posição: Compare a performance média de cada posição.

Gráfico de Dispersão Rating x Salário: Explore a relação entre desempenho e salário.

##### Comparação entre Times:

Gráfico de Pizza Distribuição de Posições por Time: Analise a composição de cada time em termos de posições.

Gráfico de Radar Atributos Médios por Time: Compare os times em diferentes atributos (rating, altura, peso, etc.).

Gráfico de Barras Total de Salários por Time: Analise o gasto de cada time em salários.

Gráfico de Colunas Rating por Time: Crie um ranking baseado no rating médio dos jogadores.



#### ES: 2. KPIs con la Base de la NBA

Objetivo: Asumir el papel de Analista de Datos del equipo ‘Sacramento Kings’.

Acción: Con la base de datos de jugadores de la NBA, elabora KPIs que puedan mejorar el rendimiento del equipo.

##### KPIs Sugeridos:

##### Salarios:

Boxplot de Salarios: Visualiza la distribución de salarios, identificando outliers y tendencias.

Media de Gastos con Salario: Compara los gastos de tu equipo con los de los competidores.

Salario Máximo, Mínimo y Mediano: Información crítica sobre la tendencia central y extremos de los salarios.

##### Relación Salario x Otros Atributos:

Gráfico de Dispersión Salario x Edad: Descubre patrones entre salario y edad.

Gráfico de Dispersión Salario x Altura/Peso: Examina la correlación entre salario y características físicas.

Gráfico de Barras Salario Medio por Equipo: Compara el salario medio de los jugadores de cada equipo.

##### Performance de los Jugadores:

Gráfico de Barras Media de Rating por Posición: Compara la performance media de cada posición.

Gráfico de Dispersión Rating x Salario: Explora la relación entre rendimiento y salario.

##### Comparación entre Equipos:

Gráfico de Pizza Distribución de Posiciones por Equipo: Analiza la composición de cada equipo en términos de posiciones.

Gráfico de Radar Atributos Medios por Equipo: Compara los equipos en diferentes atributos (rating, altura, peso, etc.).

Gráfico de Barras Total de Salarios por Equipo: Analiza el gasto de cada equipo en salarios.

Gráfico de Columnas Rating por Equipo: Crea un ranking basado en el rating medio de todos los jugadores.

### 📋   Preparação de Dados / Preparación de Datos

PT:
Antes de realizar qualquer visualização ou análise, é fundamental limpar e organizar os dados. Isso inclui:

**Eliminação de dados faltantes:** Remova ou impute valores faltantes para evitar distorções na análise.

**Normalização e transformação:** ajuste os formatos de dados para garantir consistência.

**Criando Novas Colunas:** Gere colunas adicionais que podem facilitar análises, como cálculo da idade dos jogadores.

**Remover duplicatas** certifique-se de que não haja registros repetidos que possam distorcer a análise.

<br>
ES:
Antes de realizar cualquier visualización o análisis, es crucial limpiar y organizar los datos. Esto incluye:

**Eliminación de Datos Faltantes:** Remover o imputar valores faltantes para evitar distorsiones en el análisis.

**Normalización y Transformación:** Ajustar los formatos de datos para asegurar la coherencia.

**Creación de Nuevas Columnas:** Generar columnas adicionales que puedan facilitar el análisis, como el cálculo de la edad de los jugadores.

**Remover Duplicados:** Asegurar que no existan registros repetidos que puedan sesgar el análisis.

<br>

### 🛠️ Ferramentas Utilizadas /  Herramientas Utilizadas 

PT:

Python: linguagem de programação primária para manipulação e análise de dados.

Pandas: Biblioteca para manipulação de dados na forma de DataFrames.

BeautifulSoup & Requests: Ferramentas para realizar web scraping e extração de informações de sites.

Matplotlib e Seaborn: Bibliotecas para criação de visualizações gráficas.

<br>

ES: 

Python: Lenguaje de programación principal para la manipulación y análisis de datos.

Pandas: Biblioteca para la manipulación de datos en forma de DataFrames.

BeautifulSoup & Requests: Herramientas para realizar web scraping y extracción de información de sitios web.

Matplotlib & Seaborn: Bibliotecas para la creación de visualizaciones gráficas.
