# Glossário

* **Séries Temporais**: Uma sequência de observações ou medidas ao longo do tempo.
* **Decomposição (de uma Série Temporal) Aditiva e Multiplicativa**: Abordagem clássica para análise de Séries Temporais que são decompostas em componentes de Tendência, Sazonalidade e Ruído, podendo aparecer combinadas de forma aditiva ou multiplicativa.  
* **Tendência**: O padrão de crescimento ou decréscimo da série temporal.
* **Sazonalidade**: Variações regulares e previsíveis em uma série temporal que acontecem a intervalos fixos de tempo.
* **Ciclos**: Padrões de oscilação de longo prazo, geralmente com duração maior que a sazonalidade (ciclos econômicos por exemplo).
* **Ruído**: Componente aleatória da série que não pode ser explicado.
* **Estacionariedade**: Uma série temporal é estacionária quando suas propriedades estatísticas, como média e variância, são constantes ao longo do tempo.
* **Autocorrelação**: A correlação de uma série temporal com seus valores passados.
* **Modelo de Suavização (*Smoothing*)**: Técnica que estima a tendência de uma série temporal filtrando (*suavizando*) as variações aleatórias.
* **Médias Móveis (*Moving Average* - MA)**: Um modelo de suavização que estima a tendência média considerando uma janela móvel de observações.
* **Média Móvel Exponencial (*Exponential Moving Average* - EMA)**: Variação do modelo de média móvel que atribui pesos exponenciais decrescentes às observações passadas.
* **Autoregressão (AR)**: Modelo que prevê valores futuros da série com base nos valores passados da própria série.
* **ARIMA (*Autoregressive Integrated Moving Average*)**: Modelo estatístico que combina componentes de autoregressão, média móvel e diferenciação para modelar as séries.
* **Diferenciação**: Técnica para tornar a série estacionária subtraindo valores anteriores da série do valor atual. 
* **Funções de Autocorrelação (*Autocorrelation Function* - ACF, e *Partial Autocorrelation Function* - PACF)**: Medidas de correlação entre valores defasados de uma série temporal. Gráficos desses valores são empregados para estimar parâmetros de autoregressão dos modelos.
* **SARIMA (*Seasonal ARIMA*)**: Um modelo ARIMA que leva em conta a sazonalidades.
* **SARIMAX**: Extensão do modelo SARIMA que incorpora variáveis exógenas (externas) adicionais.
* **Regressão com *Lags* (Regressão com Defasagens)**: Um modelo de regressão que inclui defasagens das variáveis dependentes e independentes como preditores. Técnica aqui empregada nos modelos de Aprendizado de Máquina.
* **Aprendizado de Máquina**: Algoritmos computacionais que capturam padrões dos dados para fazer previsões. Aqui são empregados Algoritmos de Aprendizado Supervisionado em que um conjunto de dados rotulados (os valores da Série) são empregados para o aprendizado e novas predições.
* **Redes Neurais**: Modelo de Aprendizado de Máquina baseado em que vários elementos (neurônios artificiais) são combinados em uma rede. O aprendizado se dá pela minimização do erro em função dos pesos empregados para gerar as saídas de cada elemento. 
