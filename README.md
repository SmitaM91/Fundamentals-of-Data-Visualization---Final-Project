# Fundamentals of Data Visualization - Final Project

## 1)  A brief recap of your data, goals, and tasks, focusing on those that most directly influence your design

* Data Recap: The dataset used in my project is a combination of red and white wine data, with attributes such as acidity, residual sugar, alcohol content and overall quality ratings. The data provides a comprehensive look into the physicochemical properties of wines, which can be analyzed to understand their influence on wine quality. Having worked with manufacturing data in the past, I approached this project with a focus on creating an efficient, interactive dashboard that allows users to draw meaningful insights from the dataset.

* Goals: The primary goal of this project was to design an intuitive and user-friendly dashboard using Dash and Plotly, enabling users to visualize and explore the relationships between wine attributes and quality. I aimed to make the data accessible by allowing users to interactively filter attributes, wine types and compare correlations, focusing on attributes that contribute to higher-quality wine.

* Tasks:

   > Task One: Provide users with the ability to explore the distribution of individual wine attributes using violin plots or histograms. This helps in visualizing how attributes differ across red and white wines.

   > Task Two: Allow users to investigate correlations between physical attributes by providing a scatterplot matrix and detailed scatterplots for comparing two selected attributes.

   > Task Three: Analyze the relationship between physical attributes (such as alcohol content, acidity, etc.) and wine quality, offering scatterplots with regression lines to highlight trends.


## 2)  Screenshots of and/or a link to your visualization implementation (see below for additional guidance)
   
* Implementation: The dashboard, built using JupyterDash and Plotly is divided into three main tasks, each offering interactive visualizations to explore the dataset comprehensively. The interactive components such as dropdowns and tabs allow users to switch between tasks and visualize different aspects of the data.

You can refer Final Project Python code file from the same folder

* Screenshots:
  > Task One: Visualization showing the distribution of "Fixed Acidity" using violin plots, distinguishing red and white wines.

  <img width="950" alt="image" src="https://github.com/user-attachments/assets/a5dc5d53-641f-4b66-ae2a-019d669a0178">


  > Task Two: Scatterplot matrix illustrating relationships between all physical attributes in the dataset.

  <img width="809" alt="image" src="https://github.com/user-attachments/assets/36154750-8680-49d1-984d-d305c29f65c4">

  <img width="870" alt="image" src="https://github.com/user-attachments/assets/3209ea49-724f-472b-b114-05a58e69fe0f">


  > Task Three: Scatterplot demonstrating the correlation between alcohol content and wine quality, with a regression line highlighting the trend.

  <img width="867" alt="image" src="https://github.com/user-attachments/assets/13888e76-b5cb-4241-b574-b2aa8c3082a0">


## 3) A summary of the key elements of your design and accompanying justification

Interactive Design: The dashboard emphasizes user interactivity through dropdowns, allowing users to customize the visualizations. This flexibility makes it easier to explore specific relationships between attributes.

* Key Visualizations:
  
  > Violin Plots and Histograms: Used in Task One to show the distribution of each wine attribute. Violin plots highlight the density of data points across different wine types.
  
  > Scatterplot Matrix: Provides a holistic view of the relationships between multiple wine attributes, allowing users to spot patterns and correlations.
  
  > Scatterplots with Regression Lines: Task Three employs scatterplots with regression models to help users explore the effect of physical attributes on wine quality, supported by violin and histogram plots.

* Justification: The choice of visualizations aligns with the goal of helping users understand the data intuitively. For example, violin plots provide a more detailed view of attribute distributions compared to basic histograms, while scatterplots with regression lines clearly show trends between attributes and quality.


## 4) A discussion of your final evaluation approach, including the procedure, people recruited, and results. Note that, due to the difficulty of recruiting experts, you can use colleagues, friends, classmates, or family to evaluate your designs if experts or others from your target population are unavailable.
   
For evaluation, I have contacted five individuals — 3 colleagues from my previous role in manufacturing and 2 family members. They were asked to complete a series of tasks, such as comparing the acidity of red and white wines or identifying relationships between alcohol content and wine quality. My focus was on evaluating the dashboard’s usability, visual clarity and the ability to extract meaningful insights.

Results:

* Positive Feedback: If I conclude all users result, they have appreciated the interactive features and found the ability to filter and select specific attributes particularly useful. The scatterplot matrix in Task Two was praised for providing an in-depth view of attribute correlations.

* Areas for Improvement: Some users (my family members :)) found the scatterplot matrix a bit overwhelming initially due to the number of variables displayed. Suggestions included providing more instructions or allowing users to customize which variables are shown.

## 5. A synthesis of your findings, including what elements of your approach worked well and what elements you would refine in future iterations.

what elements of your approach worked well:

* Interactivity: The use of dropdowns and filters was well-received, giving users control over the data they wished to explore. It allowed them to focus on specific questions or hypotheses about the wine attributes and their effects on quality.

* Visualization Clarity: The use of contrasting colors to differentiate between red and white wines helped users quickly understand the data distributions and trends. Regression lines in Task Three offered a clear visualization of how attributes like alcohol content correlate with wine quality.
What Could Be Refined:

* Simplifying the Layout: Based on user feedback, the scatterplot matrix could benefit from a more simplified layout. Allowing users to select fewer variables at a time or customize their view could reduce complexity.
Performance Optimization: While the dashboard performed well for this dataset, future iterations could focus on optimizing the performance, particularly when handling larger datasets or more complex visualizations.

what elements you would refine in future iterations:

* I would focus on improving the layout to simplify the user experience and optimizing performance for larger datasets, ensuring the dashboard remains both intuitive and responsive.

Thank you so much for reviewing my project.
