# Critique By Design

I wasn't specifically on the lookout for a music-related visualization, but when I stumbled upon one, I wasn't complaining! 
Pulled from a [study](https://www.statista.com/statistics/253915/favorite-music-genres-in-the-us/) published by Music Business Association in 2018, the visualization describes preferred music genres of 3000 U.S. consumers by age group. I was excited to work with the visualization because—as a drummer who enjoys playing several music genres—its data was immediately interesting. More importantly though, I was able to quickly identify areas of the viz. that I liked and disliked. This helped me build a strong [Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) (developed by Stephen Few), which guided my wireframing process and my eventual redesign.

## The OG Viz
This is the original visualization that I chose to work on:
![statistic_id253915_favorite-music-genres-in-the-us-2018-by-age](https://user-images.githubusercontent.com/78868693/133943355-526144bd-5a7e-4e79-9416-c50580bc6328.png)

## Critiquing Cogently
After a brief study of the visualization, I recorded my general thoughts about it: 

*"At first glance, the visualization looks interesting.*

*The colors are attractive. I especially like how the yellow and purple look towards the top of each stacked bar. The color wheel and its complementary colors substantiate why this may have been appealing. Beyond the scatter of colors that I immediately notice, I find myself being drawn to the chart because I’m a music enthusiast. I am in their target audience, and so I naturally want to learn more about how genres are perceived by different age groups. Perhaps, however, this may not be the case for everyone.* 

*Within seconds, there is a growing sense of feeling lost. While the visualization doesn’t feel jarring or irritating to look at, it still places too little consideration on the overall aesthetic appeal. The colors, percentages and legend all begin to swim around after a moment. I want to understand what numbers are being shown to me, but am unable to do it without some hard, focused searching. I feel like a visualization should make it easy for viewers to grasp interesting data, not hard. As a result, the information is interesting only for the short term—the short term being a couple of seconds. It doesn’t leave a lasting impression. I don’t feel like I learned something extraordinary. Perhaps, however, that is in part the topic’s fault, not solely the visualization’s. That is, the information doesn’t move me. I don’t find new purpose after viewing the chart. I don’t even feel compelled to simply share this information with more people.* 

*There are, however, things that I do like. I like that the visualization is credible and accurate. The study was conducted by Audiencenet and published by Music Business Association. It surveys favorite music genres of 3000 consumers in the United States as of July 2018, sorted by age group. This data is explained well in their provided Excel file, which also offers references and research methodology. This offers pretty good context, though the visualization doesn’t rely on it to be understandable – which is really great. The charts don’t show too much complex information. While this information is presented in a more complex way than needed, at least not a single element feels inscrutable. I also like that the goals of the visualization are clear, and the graph conveys exactly what it aims to. The visualization feels complete, apart from the fact that it does not include an “Other” response, raising the question: is every respondent’s answer represented or were some left out?* 

*If I could change a few things, I would begin with the colors. They bring out the notorious rainbow effect that we’ve frequently discussed in class. The percentages on the y-axis are also a little confusing; why do the numbers go beyond 300%? That takes a little more thinking, since it isn’t instantly intuitive. A final observation is that the comparisons between the age groups are unevenly distributed, so I would consider normalizing those as well."*

Then, I used Stephen Few's "Data Visualization Effectiveness Profile" and ranked the visualization in the following way:
<br>**Usefulness.  Is it useful for the intended audience?  Does it communicate valuable information?**
<br>Rank given: 7

**Completeness.  Does the visualization have everything necessary to make it understandable?**
<br>Rank given: 9

**Perceptibility.  Can the reader understand the information with minimal effort? Is the visualization type appropriate?  Does it use illogical comparisons?**
<br>Rank given: 5

**Truthfulness.  Is the visualization accurate, reliable and valid?  Is it representing what it says it is, and in the most complete and truthful manner? Does it misrepresent the data or make comparisions that aren't correct?**
<br>Rank given: 10

**Intuitiveness.  Is it easy to understand and clearly communicates the information?  If unfamiliar, does it include easy to understand instructions on how to interpret it?**
<br>Rank given: 5

**Aesthetics.  It is interesting / enjoyable to look at?  Is it a good example of what a beautiful data visualization might look like?  Is it somewhere in the middle - pleasing but otherwise not distracting to look at?**
<br>Rank given: 3

**Engagement.  Does it lead the audience to learn more about the topic?  Does it inspire the audience to talk about the data or share it with others?**
<br>Rank given: 6

### Working the Wireframes
Based on my observations and some of the high-level problems I identified through the critique, I began to brainstorm ideas for my redesign. I approached the problem-solving process using the [Six Thinking Hats](https://www.debonogroup.com/services/core-programs/six-thinking-hats/) technique devised by Dr. Edward de Bono, and developed the following strategy:
![IMG_20210919_230213__01](https://user-images.githubusercontent.com/78868693/133953538-559273be-ced2-4c8f-a9d7-8e3fa63aecf0.jpg)

Next, I considered simplifying the original dataset a little bit. I had noticed that the age groups were unevenly distributed, so I merged two age groups (16-19 and 20-24) to produce a new group. I also merged the genres "Rock" and "Classic Rock" together, since I noticed that at least 4 music genres had the word "Rock" in them. <br>
![IMG_20210919_230908__01__01](https://user-images.githubusercontent.com/78868693/133953925-245cfd53-ccfe-489d-ab39-68438142b1fb.jpg)

My first wireframe included two pie chart iterations. The first set of pie charts allows viewers to observe the age distribution within each music genre, while the second set of pie charts allows viewers to observe the most popular music genres within a certain age group. I decided to make the second set because it presents a version of the data that I would enjoy learning about more. (That is, I'd rather more easily learn which genres each age group is listening to the most as opposed to which age groups listen to a particular genre the most). <br>
![IMG_20210919_230937__01](https://user-images.githubusercontent.com/78868693/133954253-11e0a85a-1825-4e30-a4c1-760767843129.jpg)

However, I quickly realized that the pie charts were not intuitive visualizations. The colors felt crowded, and there was no way to compare the "absolute" numbers of listeners by age group. In addition, in both iterations, I faced trouble coming up with distinct colors to separate each pie slice with. 

After considering the problem for another day, I decided to simplify everything and go for a stacked bar chart. This kind of visualization would help me work with a limited number of colors, and let me show numbers _as well as_ proportions! It would also let me reorganize the data to flow from the most popular genre to the least popular genre, which would also ramp up my visualization's aesthetic score! <br>
![WhatsApp Image 2021-09-18 at 17 36 40](https://user-images.githubusercontent.com/78868693/133954638-fb58fb3b-620f-455b-9353-63465c65702f.jpeg)

...**luckily enough, I went to bed satisfied with my wireframe!**

## The Redesign
Equipped with my new wireframe, I built my redesign using [Flourish](https://flourish.studio/). I tried to pick colors that wouldn't give an overwhelming "Rainbow Effect", yet still be distinctive enough to attribute to the 6 different age groups. I ended up choosing a gradient that deepens with age (yellow to dark purple), and colored the dominant age group within each genre in red. Funnily, this happened to be the youngest group (individuals aged 16-24) in _every_ genre!
<div class="flourish-embed flourish-chart" data-src="visualisation/7297647"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Critiquing the Critique
I really enjoyed Stephen Few's evaluation method. It went beyond the Good Charts method in helping me consider pieces I wouldn’t have thought of otherwise. Completeness and usefulness to the audience are two such components. I wouldn’t have naturally articulated these in my critiques. I also liked that the scale was  from 1-10, and not from 1-5. This pushed me to think more critically about the rankings I picked under each metric. I would also rank the ease of completing this evaluation highly. The questions asked were simple, well-explained and interesting. 

Something I would add to this evaluation method is “Emotional Appeal.” This is closely related to “Engagement,” but is more spontaneous. For example, some visualizations are instantly pleasing while some can be instantly frustrating. I think these immediate, visceral reactions are useful to record because they capture first impressions… and, often, first impressions really last! 

I might even add a “How Much Time Did It Take For You To Fully Understand The Visualization?” metric. I think people tend to record higher scores under “Intuitiveness” (which captures how easy a visualization is to understand) because it gives them either a greater sense of achievement or a greater sense of leniency. That is, I feel like we are prone to remarking that a graph is easier to understand than it actually is because of an unconscious bias within us to demonstrate we’re:
(i) smart or 
(ii) forgiving of smaller flaws as long as the overall message is understood. 
Essentially, if I were asked whether a graph was intuitive or not, I would likely say yes unless there was a very strong reason to convince me otherwise. Similarly, if this binary question were expanded to a scale from 1 to 10, I would still lean towards numbers beyond 5 because going below that would be equivalent to saying, “no.” Unless there was a strong reason to convince me otherwise, I would most probably rank a graph above average (>5) on intuitiveness. 
To solve this problem, it might help to reframe the question to “how much time did it take you to fully understand this?” I think we’d get more honest responses because we’re forced to come up with a number of our own. We aren’t just settling for one of the options provided.


