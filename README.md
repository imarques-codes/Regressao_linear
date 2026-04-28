Sistema de Avaliação Imobiliária: Previsão de Preços no Rio de Janeiro

Este projeto consiste no desenvolvimento de um modelo de Machine Learning capaz de prever o valor de venda de imóveis no município do Rio de Janeiro. Utilizando a metodologia de Regressão Linear, o sistema analisa variáveis estruturais e de localização para estimar o valor de mercado com base em dados históricos.

Contextualização
O setor imobiliário é sensível às oscilações econômicas. Em cenários de crise, a precisão na avaliação de ativos torna-se fundamental para investidores e compradores. Este projeto busca aplicar técnicas estatísticas para entender como características específicas, como proximidade da praia ou área total, influenciam o preço final de um imóvel.

O Dataset
Os dados utilizados compreendem uma amostra aleatória de 5.000 imóveis localizados na cidade do Rio de Janeiro. As variáveis presentes no conjunto de dados são:

Valor: Preço de oferta do imóvel em Reais (R$). (Variável Alvo)

Area: Área total do imóvel em m².

Dist_Praia: Distância linear do imóvel até a praia mais próxima (km).

Dist_Farmacia: Distância linear do imóvel até a farmácia mais próxima (km).

Tecnologias Utilizadas
Linguagem: Python

Bibliotecas Principais:

Pandas e Numpy para manipulação de dados.

Matplotlib e Seaborn para análise exploratória e visualização.

Scikit-Learn para a construção e avaliação do modelo de regressão.

Metodologia
Análise Exploratória (EDA): Identificação de correlações entre as variáveis independentes e o preço.

Tratamento de Dados: Verificação de outliers e valores ausentes que possam enviesar a regressão.

Modelagem: Implementação do algoritmo de Regressão Linear Múltipla.

Avaliação: Utilização de métricas como R² (Coeficiente de Determinação) e MSE (Erro Quadrático Médio) para validar a performance do modelo.

Como Executar o Projeto

Instale as dependências:
pip install -r requirements.txt

Execute o notebook ou script principal:
python main.py

Autor: Igor Henrique Marques dos Santos

Contato: igorhmsantos@gmail.com | linkedin.com/in/igorhmarques/
