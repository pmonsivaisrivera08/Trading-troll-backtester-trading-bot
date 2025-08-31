Analysis of the Backtester Bot 💻📈
The bot is a trading strategy backtesting tool written in Python. It's designed to evaluate the performance of various technical indicators using historical price data. The script utilizes popular libraries like yfinance to download financial data, pandas for data manipulation, and matplotlib for visualization.

Key Code Highlights:
Modularity: The code is organized into specific functions (fetch_data, run_backtest, calculate_metrics, save_to_csv, main), making it easy to read, maintain, and reuse.

Interactivity: The main() function guides the user through an interactive menu available in both Spanish and English. It allows you to select a ticker, a time period, and one of eight available trading strategies.

Implemented Strategies:

Moving Average Crossover (SMA): A classic strategy that generates buy or sell signals when a short-term moving average crosses a long-term one.

Bollinger Bands (BB): Generates signals when the price touches the upper or lower bands.

Relative Strength Index (RSI): Identifies overbought and oversold conditions.

Moving Average Convergence Divergence (MACD): Based on the crossover of the MACD line and the signal line.

On-Balance Volume (OBV): Uses the relationship between volume and price to predict market movements.

Awesome Oscillator (AO): Measures market momentum.

Stochastic Oscillator: Compares the closing price to its price range over a given period to identify overbought/oversold conditions.

Parabolic SAR: Uses a system of dots to indicate trend direction.

Error and Input Handling: The code includes basic error handling, such as validating data downloads and suggesting library installations. For example, it warns the user if pandas_ta is not installed when the Parabolic SAR strategy is selected.

Metrics Report: The calculate_metrics function provides a detailed summary of the strategy's performance, including initial and final capital, net profit/loss, win rate, and average profit/loss per trade.

GitHub Description
Trading Troll Bot - Trading Strategy Backtester 🤖📊
!

Trading Troll Bot is a Python backtesting tool that allows you to quickly and easily evaluate the viability of various trading strategies on historical data. With this script, you can simulate trades on stocks, cryptocurrencies, or indices to understand the potential performance of a strategy before you apply it in a live market.

Main Features 🚀
User-Friendly: An intuitive command-line interface guides you step-by-step.

Multiple Strategies: Evaluate 8 popular technical indicators, including:

Moving Average Crossover (SMA)

Bollinger Bands (BB)

Relative Strength Index (RSI)

MACD

On-Balance Volume (OBV)

Awesome Oscillator (AO)

Stochastic Oscillator

Parabolic SAR

Real-Time Data: Download historical data directly from Yahoo Finance for any ticker.

Detailed Analysis: Generates a summary of key metrics such as:

Initial and final capital

Net profit/loss

Total return

Win rate

Clear Visualizations: Creates charts that show the asset's price, buy/sell signals, and the evolution of your portfolio's value.

Data Export: Option to save the complete backtest report to a CSV file.

Requirements 🛠️
Make sure you have the following Python libraries installed. You can easily install them using pip:

Bash

pip install pandas matplotlib yfinance numpy pandas_ta
How to Use It? 🤔
Clone this repository or download the trading_troll_bot_backtester.ipynb file.

Open the file in an environment like Jupyter Notebook or Google Colab.

Run the cells and follow the instructions in the console to:

Select your language (English or Spanish).

Enter the asset's ticker (e.g., AAPL, BTC-USD).

Choose the time period (e.g., 1y, 5y).

Select one of the available trading strategies.

Decide whether to use default parameters or customize your own.

Start testing your trading strategies in an informed and visual way!
_____________________________________________________________________________________________________
Análisis del Backtester Bot 💻📈
El bot es una herramienta de backtesting de estrategias de trading escrita en Python, diseñada para evaluar el rendimiento de diferentes indicadores técnicos en datos históricos de precios. Utiliza bibliotecas populares como yfinance para descargar datos financieros, pandas para manipularlos, y matplotlib para visualizarlos.

Puntos clave del código:
Modularidad: El código está organizado en funciones específicas (fetch_data, run_backtest, calculate_metrics, save_to_csv, main), lo que facilita su lectura, mantenimiento y reutilización.

Interactividad: La función principal, main(), guía al usuario a través de un menú interactivo en español e inglés. Permite seleccionar un ticker, un período de tiempo, y una de las ocho estrategias de trading disponibles.

Estrategias Implementadas:

Cruce de Medias Móviles (SMA): Una estrategia clásica que genera señales de compra o venta cuando una media móvil a corto plazo cruza una a largo plazo.

Bandas de Bollinger (BB): Genera señales cuando el precio toca las bandas superior o inferior.

Índice de Fuerza Relativa (RSI): Identifica condiciones de sobrecompra y sobreventa.

Convergencia/Divergencia de Media Móvil (MACD): Basado en el cruce de la línea MACD y la línea de señal.

On-Balance Volume (OBV): Utiliza la relación entre el volumen y el precio para predecir movimientos.

Awesome Oscillator (AO): Mide el impulso del mercado.

Oscilador Estocástico: Compara el precio de cierre con su rango de precios durante un período determinado para identificar condiciones de sobrecompra/sobreventa.

SAR Parabólico: Utiliza un sistema de puntos para indicar la dirección de la tendencia.

Manejo de Errores y Entradas: El código incluye manejo de errores básico, como la validación de la descarga de datos y la sugerencia de instalación de librerías. Por ejemplo, avisa al usuario si pandas_ta no está instalado cuando se selecciona la estrategia SAR Parabólico.

Reporte de Métricas: La función calculate_metrics proporciona un resumen detallado del rendimiento de la estrategia, incluyendo el capital inicial y final, la ganancia/pérdida neta, la tasa de éxito (win rate) y las ganancias/pérdidas promedio por operación.

Descripción para GitHub
Trading Troll Bot - Backtester de Estrategias de Trading 🤖📊
!
Trading Troll Bot es una herramienta de backtesting en Python que te permite evaluar de forma rápida y sencilla la viabilidad de diversas estrategias de trading en datos históricos. Con este script, puedes simular operaciones en acciones, criptomonedas o índices para entender el rendimiento potencial de una estrategia antes de aplicarla en el mercado real.

Características Principales 🚀
Fácil de Usar: Interfaz de línea de comandos intuitiva que te guía paso a paso.

Múltiples Estrategias: Evalúa 8 indicadores técnicos populares, incluyendo:

Cruce de Medias Móviles (SMA)

Bandas de Bollinger (BB)

Índice de Fuerza Relativa (RSI)

MACD

On-Balance Volume (OBV)

Awesome Oscillator (AO)

Oscilador Estocástico

SAR Parabólico

Datos en Tiempo Real: Descarga datos históricos directamente desde Yahoo Finance para cualquier ticker.

Análisis Detallado: Genera un resumen de métricas clave como:

Capital inicial y final

Ganancia/Pérdida Neta

Rendimiento total

Tasa de operaciones exitosas (Win Rate)

Visualizaciones Claras: Crea gráficos que muestran el precio del activo, las señales de compra/venta y la evolución del valor de tu portafolio.

Exportación de Datos: Opción para guardar el informe de backtesting completo en un archivo CSV.

Requisitos 🛠️
Asegúrate de tener instaladas las siguientes bibliotecas de Python. Puedes instalarlas fácilmente con pip:

Bash

pip install pandas matplotlib yfinance numpy pandas_ta
¿Cómo Usarlo? 🤔
Clona este repositorio o descarga el archivo trading_troll_bot_backtester.ipynb.

Abre el archivo en un entorno como Jupyter Notebook o Google Colab.

Ejecuta las celdas y sigue las instrucciones en la consola para:

Seleccionar el idioma (español o inglés).

Ingresar el ticker del activo (ej. AAPL, BTC-USD).

Elegir el período de tiempo (ej. 1y, 5y).

Seleccionar una de las estrategias de trading disponibles.

Decidir si quieres usar los parámetros predeterminados o personalizar los tuyos.

¡Empieza a probar tus estrategias de trading de manera informada y visual!
