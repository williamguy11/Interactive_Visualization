Link to Data Visualization: https://observablehq.com/d/78e40ad312a2983e

Suicide deaths pose a profound challenge for those left behind, often leaving friends and family searching for answers. According to the CDC, 1.6 million Americans attempted suicide in 2022. This statistic raises important questions about whether it represents an increase compared to historical rates. Research indicates that males consistently have the highest suicide death rates. To further understand this issue, we decided to explore how other demographics—specifically race, gender, ethnicity, and age—affect suicide death rates and identify which groups are most at risk.

### Rationale for Design Decisions
In designing our visualization of suicide death rates, we aimed to create an intuitive and informative experience for users. The choice to use a line plot stemmed from our need to display trends over time clearly. Line plots are particularly effective for showing changes across continuous data sets, allowing viewers to grasp increases or decreases in suicide rates across different demographic groups.

When analyzing demographic impacts, we knew we needed to visualize multiple groups simultaneously. This led us to explore various graphic options, including bar charts and area plots. Ultimately, we settled on the line plot due to its ability to facilitate comparison across groups and to highlight one aspect clearly: the base rate represented by the “All Persons” category. To distinguish this reference line, we chose to color it red, a decision aimed at intuitively signaling its importance as a baseline.

In terms of interactivity, we opted for a hover-over technique to enhance user engagement. This design choice eliminated the necessity for a detailed legend, which can be cumbersome and lead to information overload. The hover interactions allowed users to focus on specific demographic lines, providing immediate feedback about each segment without cluttering the visualization. This direct interaction helps maintain user attention while conveying essential information clearly.  

### Development Process Overview
Our development process began with exploratory data analysis (EDA), predominantly managed by Caroline and Filina. They spent approximately 5 hours on data importation, cleaning, and addressing missing data points by averaging values from the beginning and midpoint of the decade corresponding to the missing value. This stage was crucial as it laid the foundation for our final visualization, and it involved numerous variable naming corrections to ensure data integrity.

Once the dataset was cleaned, we transitioned to utilizing Observable with D3.js for our interactive visualization. William was primarily responsible for this phase, dedicating about 6 hours over two consecutive days. His tasks included importing data into Observable, plotting it on the line graph, and implementing mouse hover interactions, which provides information about each line's demographic, year and the rate of suicide death.

Collaboration was a key component of our project, especially in finalizing the visualization. All team members contributed to enhancing the chart’s labels, title, font size, and axis scaling, which took about an hour in total. This collective effort ensured that our final product was polished and user-friendly.

In total, we dedicated approximately 10 hours to developing the application. Data preprocessing dominated our timeline, accounting for more than half of the total hours, while the actual execution of visualization also required considerable focus to ensure interactivity and clarity. The organized split of responsibilities among team members fostered a conducive development environment, leading us to a successful outcome.
