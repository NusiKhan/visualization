# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  https://open.toronto.ca/dataset/toronto-shelter-system-flow/


- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

        Figure One I used python to create a line graph of montly trend.
        FIgure Two I used google sheets to create a pie chart.

    > Who is your intended audience?
    > 
        Charities helping the homeless population of Toronto. The charts could be useful in convincing donors to donate more money to aid homelessnes. 

    > What information or message are you trying to convey with your visualization?
    > 
        Figure One: That the homeless population in Toronto has increased over the years, and in comparision there has not been an increase in the number of people moving to housing, it has stayed at a similar level in the past few years even though the total population of actively homeless people has increased. 

        Figure Two: Highlighting the proportion of people actively homeless, and newly added to the group each month, and those that have returned to homeless                 shelters. And it also shows the small proprotion of people who do manage to move into housing.
      Both figures are conveying the increase in the number of homeless people in Toronto. 

    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    > 
        Figure One:
        Substantive- I plotted the trends of actively homeless and moved to housing to help identify the dynamics between these two key indicators of homelessness in Toronto.To make the trend in number of people actively homeless and moving to housing, easy to understand, with a clear distinction between the two metrics.
        Perceptual- Line graphs with simple, easy-to-understand axes and labels. I used color coding to distinguish between different groups to make it easier to read. Also, adjusted the x-axis ticks to only show the year instead of every month to avoid overcrowding.
        Aesthetic- Ensured that the graph’s title, legend axis labels, and tick labels were readable. Used contrasting colors to make it easier to distinguish. 
        Figure Two:
        Substantive- The pie chart was designed to show the relative proportions of individuals in each of the five actively homeless, moved to housing, newly identified, returned to shelter and became inactive. Each section of the pie represents proportion of each category to the total population.
        Perceptual- The pie chart was kept simple by showing only five categories, avoiding overcrowding. Each category is labeled with both its name and its percentage to ensure the viewer can understand the data quickly.
        Aesthetic-  font size for category labels and percentages was chosen to be large enough to ensure readability. Used contrasting colors to ensure each slice is distinct and different from the other. Ensured title, legend and labels were all readable. 


    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

        I have added comments to each line of my code and provided the jupyter notebook for the first visualtization. I've also provided the link for anyone to be able to download and reproduce the same graph. 
        For the second one, anyone with access to google sheets for Excel will be able to reproduce it given how simple it is. 
    
    > How did you ensure that your data visualization is accessible?
    >  
        For both figures I  tried to use contrasting colors so the are clearly distiguishable. 
        In figure two I used a title, larger text size, labels in bold and added a clear legend.
        In figure one I tried to make the markers easier to decipher by using a different marker for both line graphs, and also used a different color to make the markers more visible to plain eyesight. I also added a label and title.


    > Who are the individuals and communities who might be impacted by your visualization?
    > 
        The overnight shelters, the people using these shelters and those who are donating to them. 

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    >  
         For simplicity and to ensure that the average person can understand my visualizations, I chose to do a pie chart and a line chart. 
        I tried to make it so that a cursory glance would get the message across. So I chose the line chart because anyone can look at it and understand that the number of homeless people has increased in the past few years. The total population of people in the shelter system was the logical thing to plot. I also chose show the number of people moving to housing in the same figure to show how few manage to move to housing and how the rate has not changed. 
        For the pie chart it made sense create it with the categories of people flowing through the shelter system. 

    
    > What ‘underwater labour’ contributed to your final data visualization product?

        First I did some exploratory data analysis to check what would work and where I might run into issues. The data is monthly, but there are different groups in the population group, which can make calculating things a bit tricky. 
        For figure one I had to filter the data to ensure only "All population" from the population group is used, otherwise the breakdown of the groups would also get counted which would mean everything would get double counted. 
        Since there were several months of data, I was running into issues with the x axis being too crowded so I changed the ticks to display every 15 months to make the graph easier to read.
        For figure two I just used Excel's built in chart function to create a pie chart. 

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
