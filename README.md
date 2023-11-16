# Androlendas - Trabalho Final de Machine Learning
Grupo: Natália Alcantara, Kayllany Oliveira, Daniel Carrasco e Gabriel González

<b>Descrição do Projeto</b><br>
Este repositório trata-se do trabalho final que se concentra na criação de um modelo de aprendizado de máquina para prever se uma pessoa teve ou não um infarto. O modelo utiliza dados clínicos, incluindo a quantidade de duas proteínas específicas, para fazer previsões. 

![Cópia de Apresentação de Negócios Plano de Projeto 3D Azul Branco](https://github.com/KayllanyLara/androlenda/assets/135054073/3c68c95b-fc00-47bb-99a3-0355b24c42cf)


<b>Informações sobre o Dataset</b><br>
O Dataset em questão possui os seguintes atritubos:

_Idade:_<br>
A idade é um fator crucial na previsão de doenças cardiovasculares, como o infarto, pois o risco aumenta com o envelhecimento. Pessoas mais velhas têm uma probabilidade maior de desenvolver problemas cardíacos. Unidade de medida: Anos.

_Gênero:_<br>
O gênero também é um fator importante, pois existem diferenças biológicas entre homens e mulheres que podem afetar o risco de doenças cardíacas. Normalmente, os homens têm um risco maior. Unidade de medida: Variável categórica (masculino = 1/feminino = 0).


_Batimentos por Minuto (BPM):_<br>
A frequência cardíaca indica como o coração está funcionando. Taxas elevadas ou baixas de batimentos por minuto podem indicar problemas no sistema cardiovascular. Unidade de medida: Batimentos por minuto (bpm).


_Pressão Máxima (Sistólica):_<br>
A pressão arterial sistólica é uma medida da pressão nas artérias quando o coração está batendo. Valores elevados podem indicar hipertensão, um fator de risco para doenças cardíacas. Unidade de medida: Milímetros de mercúrio (mmHg).


_Pressão Mínima (Diastólica):_<br>
A pressão arterial diastólica é a pressão nas artérias quando o coração está relaxado entre batimentos. Valores elevados podem indicar estresse nas artérias. Unidade de medida: Milímetros de mercúrio (mmHg).


_Glicose:_<br>
Níveis elevados de glicose no sangue podem indicar resistência à insulina ou diabetes, fatores que aumentam o risco de doenças cardíacas. Unidade de medida: Miligramas por decilitro (mg/dL).


_Ck-Mb:_<br>
A enzima CK-Mb é liberada quando há dano nas células musculares, incluindo as do coração. Níveis elevados podem indicar um possível ataque cardíaco. Unidade de medida: Unidades por litro (ng/mL).


_Troponina:_<br>
A troponina é outra proteína liberada quando ocorre dano ao músculo cardíaco. Seus níveis elevados também podem indicar problemas cardíacos. Unidade de medida: Nanogramas por mililitro (ng/mL).

<b> Funcionamento Código </b><br>
O codigo usa como modelo uma "Floresta de Classificação". Sendo as Bibliotecas e funções usadas e necessárias para importação:

- Pandas: Biblioteca fundamental para manipulação e análise de dados em Python. Utiliza estruturas de dados, como o DataFrame, facilitando operações como carregamento, limpeza e transformação de dados de forma eficiente.

- Scikit-learn (sklearn): Biblioteca abrangente de aprendizado de máquina em Python, oferecendo ferramentas eficazes para análise preditiva, incluindo algoritmos de classificação, regressão e clustering.

- Seaborn (sns): Extensão do Matplotlib, Seaborn é uma biblioteca para visualização estatística de dados em Python. Possui uma interface de alto nível que simplifica a criação de gráficos informativos e atraentes.

- NumPy: Biblioteca fundamental para computação numérica em Python. Fornece suporte para arrays multidimensionais e operações matemáticas eficientes.

- RandomizedSearchCV: Classe em scikit-learn utilizada para otimização de hiperparâmetros por meio de busca aleatória. Ideal para encontrar os melhores parâmetros para modelos de machine learning.

- Confusion Matrix: Função em scikit-learn para calcular a matriz de confusão, uma ferramenta essencial na avaliação do desempenho de modelos de classificação.

- Train-Test Split: Função em scikit-learn para dividir conjuntos de dados em conjuntos de treino e teste, essencial para avaliar a capacidade de generalização de um modelo.

- RandomForestClassifier: Algoritmo de aprendizado de máquina baseado em árvores de decisão, implementado em scikit-learn. Amplamente utilizado para tarefas de classificação.


