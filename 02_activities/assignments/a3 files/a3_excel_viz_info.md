# Data Visualization

## Assignment 3: Final Project - Excel visual

The following are my answers for the Excel generalted visualization.
I chose a dataset on Toronto Neighborhood Crime Data, which can be found at this link https://open.toronto.ca/dataset/neighbourhood-crime-rates/

Description of visualization: The visualization is a stacked bar chart showing rates of various crimes in 2024 per 100,000 population across the top 10 neighborhoods in Toronto with the highest overall crime rates. Each bar represents a neighborhood and is divided into color-coded segments for different crime types.

    > What software did you use to create your data visualization?
    Excel

    > Who is your intended audience? 
    Community safety advocates
    Municipal decision makers
    Residents of Toronto and local neighborhood associations
    
    > What information or message are you trying to convey with your visualization?
    The Toronto neighborhoods with the highest overall crime rates in 2024.
    The composition of various crime types contributing to the total crime rate in each area. It aims to emphasize that some neighborhoods are disproportionately affected by specific crimes, which may help inform targeted solutions for these areas.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    I added a clear title, and cleaned up the legend labels to make them more readable
    Each crime type is assigned a distinct color (and order of appearance) in the legend for quick identification
    The stacked format helps visualize both the total crime rate as well as the distribution of crime type within each neighborhood 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The visualization is partially reproducible. Anyone with the dataset can recreate it in Excel by summing the crime rates for each neighborhood, filtering the top 10 neighborhoods, cleaning up the data so that only the crime rates for the 10 neighborhoods remain, and inserting a stacked bar chart.
    Excel does not have built-in scripting, so it might be difficult to reproduce the exact same chart
    Lack of reproducibility makes it harder for others to verify or extend my work unless I share the cleaned data set and a step-by-step guide of how to recreate the chart.
    
    > How did you ensure that your data visualization is accessible? 
    I chose the color palette that had the best contrast so it is easy to distinguish the different crime types, however, there must be a color-blind friendly palette on Excel - I just haven't found one, and don't have the time at the moment to create one!
    I added alt-text to the visual, but I'm not sure how it gets displayed. The alt-text is "Stacked bar chart showing rates of various crimes in 2024 per 100,000 population across the top 10 neighborhoods in Toronto with the highest overall crime rates. Each bar represents a neighborhood and is divided into color-coded segments for different crime types, including assault, auto theft, bike theft, break & enter, homicide, robbery, shooting, theft from motor vehicle (MV), and theft over. Yonge-Bay Corridor has the highest total crime rate, driven largely by assault. Other neighborhoods like Kensington-Chinatown and Downtown Yonge East also show high levels of multiple crime types. The chart helps compare both total crime and crime type composition between neighborhoods." 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Residents of the 10 neighborhoods
    Local police
    Policy planners
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I included data from 2024 only and excluded data from earlier years to avoid visual overload. I chose to include only the top 10 neighborhoods by total crime rate and excluded other neighborhoods to avoid overwhelming the audience with information. I chose to include the crime rates as opposed to the raw crime counts, as rates are more comparable.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    I had to sum up all the crime rates and sort them to identify the top 10 neighborhoods 
    I had to clean the data
    I had to fine-tune the layout of the chart for clarity
