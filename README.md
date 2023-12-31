# Challenge_14
Interactive_Visualisations

# Deployment
Here is a link to the dashboard: https://vanhg33.github.io/Challenge_14_Interactive_Visualisations/

# Background

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogues the microbes that colonise human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


# Instructions

Complete the following steps:
  1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
  2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
       - Use [sample_values] as the values for the bar chart.
       - Use [otu_ids] as the labels for the bar chart.
       - Use [otu_labels] as the hovertext for the chart.

      ![image](https://github.com/VanHg33/Challenge_14_Interactive_Visualisations/assets/135322223/54dbdbd0-9add-4b51-aa71-18e7d4596731)

  3. Create a bubble chart that displays each sample.
       - Use [otu_ids] for the x values.
       - Use [sample_values] for the y values.
       - Use [sample_values] for the marker size.
       - Use [otu_ids] for the marker colors.
       - Use [otu_labels] for the text values.

      ![image](https://github.com/VanHg33/Challenge_14_Interactive_Visualisations/assets/135322223/bd38b2b2-86ad-4a81-808f-43cb0271bc16)

  4. Display the sample metadata, i.e., an individual's demographic information.
  5. Display each key-value pair from the metadata JSON object somewhere on the page.

      ![image](https://github.com/VanHg33/Challenge_14_Interactive_Visualisations/assets/135322223/d5dec44a-b7ad-49a3-8475-718a4fd653f2)

  6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
     
      ![image](https://github.com/VanHg33/Challenge_14_Interactive_Visualisations/assets/135322223/9767dd7e-b011-4619-a608-188d1747ac0c)

  7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file


# Advanced Challenge Assignment (Optional with no extra points earning)

The following task is advanced and therefore optional:
  - Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.
  - You will need to modify the example gauge code to account for values ranging from 0 through 9.
  - Update the chart whenever a new sample is selected.

      ![image](https://github.com/VanHg33/Challenge_14_Interactive_Visualisations/assets/135322223/63b49168-7216-42b3-90b7-5d818ef86487)

**Hints**
  - Use [console.log] inside of your JavaScript code to see what your data looks like at each step.
  - Refer to the Plotly.js documentation (https://plotly.com/javascript/) when building the plots.
