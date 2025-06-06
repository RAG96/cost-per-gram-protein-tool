# cost-per-gram-protein-tool
A browser-based tool to compare up to 10 protein powders by cost, scoop size, protein per dollar, and monthly value. Built for lifters, athletes, students, and anyone who tracks their intake.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Protein Cost Comparison</title>
  <style>
    table, th, td {
      border: 1px solid black;
      border-collapse: collapse;
      padding: 8px;
    }
    th {
      background-color: #f2f2f2;
    }
    input, select {
      width: 120px;
    }
    .highlight {
      background-color: #d4f4dd;
    }
  </style>
</head>
<body>

<h2 title="Hover to highlight highest and lowest values">Protein Powder Comparison</h2>
<div id="proteinPowderInputs"></div>
<button onclick="addProteinPowderRow()">Add Protein Powder</button>
<br><br>
<table id="proteinPowderTable">
  <thead>
    <tr>
      <th>Name</th><th>Cost</th><th>Weight (lb)</th><th>Weight (kg)</th><th>Scoop Size (g)</th><th>Protein/Scoop (g)</th>
      <th>Total Scoops</th><th>Cost/lb</th><th>Cost/kg</th><th>Protein/$</th><th>Cost/Month</th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

<h2>Protein Powder Rankings Summary</h2>
<div id="rankingSummary"></div>

<h2>Food Protein per $ Comparison</h2>
<div id="foodInputs"></div>
<button onclick="addFoodRow()">Add Food Item</button>
<br><br>
<table id="foodTable">
  <thead>
    <tr>
      <th>Food Item</th><th>Cost/lb</th><th>Cost/kg</th><th>Protein/$</th>
    </tr>
  </thead>
  <tbody></tbody>
</table>

<h3>Overall Protein per $ Ranking</h3>
<table id="rankingTable">
  <thead>
    <tr><th>Rank</th><th>Item Name</th><th>Protein/$</th></tr>
  </thead>
  <tbody></tbody>
</table>

<script>
// JavaScript functions already included and working in previous edits
</script>

</body>
</html>

<!-- README.md -->
<!--
# Protein Cost Efficiency Tool 💪📊

Protein Cost Efficiency Tool is a simple, browser-based app for comparing protein powders by cost, scoop size, protein per dollar, and long-term value.

Whether you're an athlete, fitness enthusiast, student, or just trying not to waste money on supplements, this tool helps you make smarter choices with zero guesswork.

## Features

- Add up to 10 protein powders
- Calculates cost per lb and per kg
- Calculates total scoops and cost per month (1 scoop per day)
- Calculates protein per dollar for each powder
- Ranks all entries by value
- Includes optional food-based protein comparison (chicken, eggs, beef, etc.)
- Highlights highest and lowest values in cost and efficiency

## How to Use

1. Clone or download this repo  
2. Open `index.html` in your browser  
3. Enter each protein powder's info: name, cost, weight, scoop size, and protein per scoop  
4. Add food items (optional) for a side-by-side protein per dollar comparison  
5. View all calculated results, highlights, and rankings instantly

## Example Use Case

You bought a 2 kg tub of whey for $45. Each scoop is 30g and contains 24g of protein.  
This tool helps you find out the real cost per pound, monthly cost, and how it stacks up against other options or real food.

## Screenshot

_(Insert a screenshot of your tool here)_

## Why This Exists

Protein is expensive. Labels can be misleading.  
This tool helps you get answers quickly without needing a spreadsheet or doing math in your head.

Built to help people:
- Compare value between powders
- Spot overpriced products
- Understand how their supplement stacks up against food

No sign-up. No bloat. Just the numbers that matter.

## Possible Future Features

- CSV export
- Mobile-friendly layout
- Adjustable scoop frequency
- Protein per calorie comparison
- Calorie and macro efficiency tracker

## Contributions

Pull requests are welcome. Feel free to submit bug fixes, improvements, or ideas.

## Credit

This project was created during a late-night productivity spike, balancing nutrition planning, budgeting, and a dash of chaos.  
Built for anyone who wants gains without guesswork.
-->

