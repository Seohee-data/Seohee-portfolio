# Original data visualization
[Which is The Best Performing Marvel Movie?](https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/)
!(Marvel.png)

# Redesigned 
[source:] (the-numbers.com), (rottentomatoes.com)

As a filmmaker, the title "Which is the Best Performing Marvel Movie?" captured my attention. I chose this visualization because it provided comprehensive data on various performance metrics. However, the sheer amount of detail could be streamlined, especially for viewers who want a quick comparison of films based on box office performance, it is hard to incorporate all value. Additionally, I wanted to see if there was a pattern between budget size and the percentage of budget recovered, which the original visualization hinted at but could present more clearly. Also, placing the x-axis in the middle at a 500% value (rather than starting from 0%) was confusing, as it initially looked like a negative value, so I wanted to improve it for a clearer look.


Here are my redesigned 4 different visualizations.

<div class='tableauPlaceholder' id='viz1731638408166' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;Marvelmovies1113_Assignment3&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Marvelmovies1113_Assignment3&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;Marvelmovies1113_Assignment3&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>               
<script type='text/javascript'>                   
  var divElement = document.getElementById('viz1731638408166');                  
  var vizElement = divElement.getElementsByTagName('object')[0];              
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='2027px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='2027px';} else { vizElement.style.width='100%';vizElement.style.height='1227px';}                   
  var scriptElement = document.createElement('script');                   
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);              
</script>


<br/>
<br/>
As I worked through the visualization, I made several adjustments to improve how the story was presented. Initially, I liked the original black background and clean typography—it fit the film industry theme nicely. However, to make the data stand out more, I switched to a white background. This allowed the colors representing each movie to pop more clearly. I also considered adding character icons for each franchise, but it felt cluttered, so I decided text labels were a cleaner and less overwhelming option.

<br/>
One of the first technical issues I addressed was the x-axis. In the original, it was centered at 500%, which was confusing because it made the values appear negative at first glance. I adjusted it to start at 0%, making it much more straightforward. While redesigning, I also thought about the primary audience—film production companies, distribution agencies, and marketing teams. These groups would likely need clear benchmarks to guide production decisions and marketing strategies. With this in mind, I emphasized key metrics like budget recovery and audience scores. 

<br/>
Another issue I noticed was the lack of clarity in number formatting. For example, the original visualization didn’t use dollar signs or “M” for millions, which could cause confusion. I fixed this by adjusting the number properties, adding a ‘$’ prefix and an ‘M’ suffix in the tooltips. This simple change made the monetary values instantly more understandable.

<br/>
I got feedback from two students, who were in their 20s and 30s. From feedback, it became clear that the colors needed improvement. Matching franchise colors—like red for Spider-Man or blue for Captain America—would help viewers immediately recognize categories. I also aligned text colors with chart markers to improve readability. The original design required viewers to click through sections interactively, but I found this tedious and unnecessary. Since the target audience likely already knows the Marvel franchises, I focused on making the charts more intuitive and navigable without requiring clicks.

<br/>
The visualization, while comprehensive, presented too much information at once. This made it overwhelming, especially for audiences seeking quick insights. Additionally, I got another feedback about presenting both audience scores and recovery percentages in a single chart was confusing. Therefore, I split these into two separate charts to make the data clearer. I also tried a dual-axis approach to compare metrics but found it too complex, so I ultimately created two distinct sheets for better clarity.

<br/>
I experimented with Sankey diagrams to show relationships like budget allocations, box office revenue, and category flow. These diagrams helped reveal patterns in the data, but I received feedback about inconsistent colors. Unfortunately, however, I couldn’t fully adjust the colors due to limitations in the extension version in Tableau. 
<br/>

I also considered a mixed layout with line graphs for budget trends over time and bar charts for gross profit distribution (domestic vs. international). However, feedback suggested that gross profit distribution wasn’t particularly meaningful because the domestic and international differences were minimal. Instead, I focused on the percentage of budget recovered per film by year. Also, I decided to compare the budget recovered and budgets in order to show the relationship between them. I will explain more below.
To compare budgets and budget recovery, I used a line chart, employing red for the average percentage of budget recovered and blue (with a dotted line) for the average budget. This visual approach helped highlight the trend that higher budgets often correlate with greater success. By averaging values over the years, I aimed to show a clear relationship between investment size and box office performance.
<br/>
Lastly, I decided to omit critics' scores. Production companies and marketing teams are likely more focused on audience preferences and box office outcomes than critics’ opinions. Since critics need detailed reasoning specific to artists and audiences rather than business people, I felt removing this measure would keep the focus on what matters most to decision-makers for production companies. 


