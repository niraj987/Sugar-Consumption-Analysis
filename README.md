  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Sugar Consumption Dataset - README</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f7fa;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            font-size: 2.5em;
            text-align: center;
            margin-bottom: 20px;
            background: linear-gradient(to right, #3498db, #2ecc71);
            -webkit-background-clip: text;
            color: transparent;
        }
        h2 {
            font-size: 1.8em;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            margin-top: 30px;
        }
        p {
            font-size: 1.1em;
            margin: 10px 0;
        }
        ul, ol {
            margin: 15px 0;
            padding-left: 30px;
        }
        li {
            margin-bottom: 10px;
        }
        code {
            background-color: #f1f1f1;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
        }
        pre {
            background-color: #2d2d2d;
            color: #808080;
            padding: 15px;
            border-radius: 8px;
            overflow-x: auto;
            font-size: 0.9em;
        }
        a {
            color: #3498db;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #2ecc71;
            text-decoration: underline;
        }
        .highlight {
            background-color: #e8f4f8;
            padding: 15px;
            border-left: 4px solid #3498db;
            margin: 20px 0;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: #ecf0f1;
            border-radius: 0 0 10px 10px;
        }
        footer a {
            color: #2ecc71;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Global Sugar Consumption Dataset</h1>

        <section>
            <h2>Overview</h2>
            <p>
                Welcome to the <strong>Global Sugar Consumption Dataset</strong>, a rich and insightful collection of data exploring sugar consumption trends across countries from 1960 to 2023. This dataset is designed to facilitate meaningful visualizations and analyses, uncovering patterns in sugar intake, economic factors, and health outcomes worldwide.
            </p>
        </section>

        <section>
            <h2>Dataset Description</h2>
            <p>
                The dataset is provided in an Excel file (<code>Sugar_consumption.xlsx</code>) and includes the following columns:
            </p>
            <ul>
                <li><strong>Country</strong>: Name of the country.</li>
                <li><strong>Year</strong>: Year of the data record (1960–2023).</li>
                <li><strong>Country_Code</strong>: ISO country code.</li>
                <li><strong>Continent</strong>: Continent where the country is located.</li>
                <li><strong>Region</strong>: Sub-region of the country.</li>
                <li><strong>Population</strong>: Population of the country in the given year.</li>
                <li><strong>GDP_Per_Capita</strong>: GDP per capita (in USD).</li>
                <li><strong>Per_Capita_Sugar_Consumption</strong>: Sugar consumption per person (in kg/year).</li>
                <li><strong>Total_Sugar_Consumption</strong>: Total sugar consumption for the country (in kg).</li>
                <li><strong>Sugar_From_Sugarcane</strong>: Percentage of sugar sourced from sugarcane.</li>
                <li><strong>Sugar_From_Beet</strong>: Percentage of sugar sourced from sugar beet.</li>
                <li><strong>Sugar_From_HFCS</strong>: Percentage of sugar from high-fructose corn syrup.</li>
                <li><strong>Sugar_From_Other</strong>: Percentage of sugar from other sources (e.g., maple, honey).</li>
                <li><strong>Processed_Food_Consumption</strong>: Consumption of processed foods (in kg/person/year).</li>
                <li><strong>Avg_Daily_Sugar_Intake</strong>: Average daily sugar intake (in grams).</li>
                <li><strong>Diabetes_Prevalence</strong>: Prevalence of diabetes in the population (%(s).</li>
                <li><strong>Obesity_Rate</strong>: Obesity rate in the population (%).</li>
                <li><strong>Sugar_Imports</strong>: Total sugar imports (in kg).</li>
                <li><strong>Sugar_Exports</strong>: Total sugar exports (in kg).</li>
                <li><strong>Avg_Retail_Price_Per_Kg</strong>: Average retail price of sugar per kg (in USD).</li>
                <li><strong>Urbanization_Rate</strong>: Percentage of the population living in urban areas.</li>
                <li><strong>Sugarcane_Production_Yield</strong>: Sugarcane production yield (in tonnes/hectare).</li>
            </ul>
        </section>

        <section>
            <h2>Data Source</h2>
            <p>
                This dataset is a synthetic compilation crafted for visualization and analysis. While not sourced from a specific real-world database, it reflects realistic trends in global sugar consumption, trade, and health metrics.
            </p>
        </section>

        <section>
            <h2>Usage</h2>
            <p>
                This dataset is perfect for:
            </p>
            <ul>
                <li>Visualizing temporal trends in sugar consumption by country or region.</li>
                <li>Exploring correlations between sugar intake, health outcomes (e.g., diabetes, obesity), and economic factors (e.g., GDP per capita).</li>
                <li>Analyzing the influence of urbanization and processed food consumption on sugar intake.</li>
                <li>Investigating sugar trade dynamics and production yields.</li>
            </ul>
        </section>

        <section>
            <h2>Example Visualizations</h2>
            <p>
                Create compelling visualizations such as:
            </p>
            <ul>
                <li>Time-series plots of per capita sugar consumption by country.</li>
                <li>Scatter plots comparing sugar intake with diabetes or obesity rates.</li>
                <li>Bar charts showing sugar source breakdowns (sugarcane, beet, HFCS, etc.) by region.</li>
                <li>Heatmaps of total sugar consumption across continents.</li>
                <li>Line graphs of sugar import/export trends.</li>
            </ul>
        </section>

        <section>
            <h2>Getting Started</h2>
            <p>
                To begin exploring the dataset:
            </p>
            <ol>
                <li>Clone the repository:
                    <pre><code>git clone </code></pre>
                </li>
                <li>Install dependencies (e.g., for Python):
                    <pre><code>pip install pandas matplotlib seaborn</code></pre>
                </li>
                <li>Load the dataset:
                    <pre><code>import pandas as pd
df = pd.read_excel("Sugar_consumption.xlsx")</code></pre>
                </li>
            </ol>
        </section>

        <section>
            <h2>Example Analysis</h2>
            <p>
                Below is a Python script to visualize per capita sugar consumption for France:
            </p>
            <pre><code>import pandas as pd
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_excel("Sugar_consumption.xlsx")

# Filter for France
france_data = df[df["Country"] == "France"]

# Plot
plt.figure(figsize=(10, 6))
plt.plot(france_data["Year"], france_data["Per_Capita_Sugar_Consumption"], marker="o")
plt.title("Per Capita Sugar Consumption in France (1960–2023)")
plt.xlabel("Year")
plt.ylabel("Sugar Consumption (kg/person/year)")
plt.grid(True)
plt.show()
</code></pre>
        </section>

        <section>
            <h2>Notes</h2>
            <div class="highlight">
                <p>
                    <strong>Important:</strong>
                </p>
                <ul>
                    <li>Some values (e.g., negative percentages for <code>Sugar_From_Other</code>) may require cleaning.</li>
                    <li>Not all countries have data for every year.</li>
                    <li>Validate data for statistical analysis, as synthetic data may include outliers.</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>License</h2>
            <p>
                This dataset is licensed under the <a href="https://github.com/niraj987/Sugar-Consumption-Analysis/blob/main/LICENSE">MIT License</a>. Use it freely for personal or academic projects.
            </p>
        </section>

        <section>
            <h2>Contact</h2>
            <p>
                For questions or contributions, open an <a href="https://github.com/niraj987/Sugar-Consumption-Analysis/issues">issue</a> or contact the maintainer at <a href="Kumarniraj11045@gmail.com">Kumarniraj11045@gmail.com</a>.
            </p>
        </section>
    </div>

    <footer>
        <p>
            &copy; 2025 Global Sugar Consumption Dataset | Built with  for data enthusiasts | <a href="https://github.com/niraj987/Sugar-Consumption-Analysis">View on GitHub</a>
        </p>
    </footer>
</body>
</html>
