<h1>🍕 Pizza Sales Analysis</h1>

<h2>Project Overview</h2>
<p>
    This project performs a comprehensive analysis of pizza sales data using SQL queries. It covers essential, intermediate, and advanced data analysis techniques to extract valuable insights, such as revenue contributions, order distribution, and popular pizza types and sizes.
</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#project-overview">Project Overview</a></li>
    <li><a href="#data-description">Data Description</a></li>
    <li><a href="#sql-queries">SQL Queries</a>
        <ul>
            <li><a href="#basic-queries">Basic Queries</a></li>
            <li><a href="#intermediate-queries">Intermediate Queries</a></li>
            <li><a href="#advanced-queries">Advanced Queries</a></li>
        </ul>
    </li>
    <li><a href="#analysis-highlights">Analysis Highlights</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#technologies-used">Technologies Used</a></li>
    <li><a href="#author">Author</a></li>
</ul>

<h2 id="data-description">Data Description</h2>
<p>
    The data used for this project includes:
</p>
<ul>
    <li><strong>Orders</strong>: Contains details about each pizza order.</li>
    <li><strong>Order Details</strong>: Provides quantity and type of pizzas ordered in each transaction.</li>
    <li><strong>Pizzas</strong>: Contains information on pizza names, categories, sizes, and prices.</li>
    <li><strong>Pizza Types</strong>: Specifies the different categories/types of pizzas.</li>
</ul>

<h2 id="sql-queries">SQL Queries</h2>
<p>This project consists of several SQL queries grouped by complexity:</p>

<h3 id="basic-queries">Basic Queries</h3>
<ol>
    <li>Retrieve the total number of orders placed.</li>
    <li>Calculate the total revenue generated from pizza sales.</li>
    <li>Identify the highest-priced pizza.</li>
    <li>Identify the most common pizza size ordered.</li>
    <li>List the top 5 most ordered pizza types along with their quantities.</li>
</ol>

<h3 id="intermediate-queries">Intermediate Queries</h3>
<ol>
    <li>Join tables to find the total quantity of each pizza category ordered.</li>
    <li>Determine the distribution of orders by hour of the day.</li>
    <li>Find the category-wise distribution of pizzas.</li>
    <li>Group orders by date and calculate the average number of pizzas ordered per day.</li>
    <li>Identify the top 3 most ordered pizza types based on revenue.</li>
</ol>

<h3 id="advanced-queries">Advanced Queries</h3>
<ol>
    <li>Calculate the percentage contribution of each pizza type to total revenue.</li>
    <li>Analyze the cumulative revenue generated over time.</li>
    <li>Determine the top 3 most ordered pizza types based on revenue for each pizza category.</li>
</ol>

<h2 id="analysis-highlights">Analysis Highlights</h2>
<ul>
    <li><strong>Top-Selling Pizzas</strong>: The most popular pizza types and categories based on order quantity and revenue.</li>
    <li><strong>Revenue Distribution</strong>: Insights into revenue contributions from each pizza type and the cumulative revenue over time.</li>
    <li><strong>Order Patterns</strong>: Analysis of order timings and size preferences for targeted marketing strategies.</li>
</ul>

<h2 id="getting-started">Getting Started</h2>
<p>
    To reproduce this analysis:
</p>
<ol>
    <li>Clone this repository: <code>git clone &lt;repository-url&gt;</code></li>
    <li>Set up a SQL environment (MySQL recommended).</li>
    <li>Import the data tables (<code>orders</code>, <code>order_details</code>, <code>pizzas</code>, <code>pizza_types</code>).</li>
    <li>Run each SQL query from the <a href="#sql-queries">SQL Queries</a> section.</li>
</ol>

<h2 id="technologies-used">Technologies Used</h2>
<ul>
    <li><strong>SQL</strong> for querying and data manipulation</li>
    <li><strong>MySQL</strong> as the database management system</li>
</ul>

<h2 id="author">Author</h2>
<p>Developed by <a href="your-github-profile-url">Your Name</a>.</p>
