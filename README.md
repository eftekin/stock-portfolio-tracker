<html>
<h1>Stock Portfolio Tracker</h1>

<img src="https://img.shields.io/badge/python-3.x-blue.svg" alt="Python Version">

<p>This project is a simple Python application designed to help users track their stock portfolios and calculate the total value of their investments.</p>

<h2>Features</h2>

<ul>
    <li>Add multiple stocks to your portfolio along with the quantity of shares.</li>
    <li>Fetch real-time stock prices using the Yahoo Finance API.</li>
    <li>Calculate the total value of your portfolio based on current stock prices.</li>
    <li>Easily extendable for adding more functionality.</li>
</ul>

<h2>Getting Started</h2>

<ol>
    <li>Clone the repository:</li>
</ol>

<pre><code>git clone https://github.com/eftekin/Stock-Portfolio-Tracker.git</code></pre>

<ol start="2">
    <li>Install the required Python packages:</li>
</ol>

<pre><code>pip install yfinance</code></pre>

<ol start="3">
    <li>Open the <code>main.py</code> file and customize the <code>stocks</code> list with your own stock symbols and quantities.</li>
    <li>Run the application:</li>
</ol>

<pre><code>python main.py</code></pre>

<h2>Example Output</h2>

<pre><code>
Portfolio Status:
Holding 3 shares of AAPL, Total value: 563.61
Holding 5 shares of GOOG, Total value: 686.75
Holding 2 shares of TSLA, Total value: 516.16
Total portfolio value: 1766.52
</code></pre>

<h2>Contributing</h2>

<p>Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit a pull request.</p>

<h2>License</h2>

<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

</body>

</html>
