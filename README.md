# Lede Project 4: Where are the woman?

This repository include the data and notebooks used for the fourth project I've worked on as a part of the Lede program for Data Journalism from Columbia Graduate School of Journalism.

# The project

Despite being constant subjects in paintings, women still hold an almost negligible role as creators of artworks exhibited in major museums. 
In this project, I utilized artificial intelligence to explore the presence of female representations in paintings from the MASP collection, a renowned art museum in São Paulo, Brazil, and to assess how society often views women more as objects than creators.

[Read this story.](https://juditecypreste.com/portfolio-lede/project-04/)

# The files:

1. [Getting the data](https://github.com/juditecypreste/where-woman-ai/blob/main/scrapper_paintings.ipynb)

I used the information from the MASP collection on the Wikipedia page to subsequently gather details about the artworks on the museum's website.

2. [The data](https://github.com/juditecypreste/where-woman-ai/blob/main/paints_links_full.csv)

This is the result of my scraper.

4. [Analyzing the data](https://github.com/juditecypreste/zombie_songs/blob/main/tiktok_analysis.ipynb)

In this notebook, I cleaned and analyzed the data using AI.

5. [The data](https://github.com/juditecypreste/where-woman-ai/blob/main/masp_classificated.csv)

This is the result of my analysis.

6. [Urls images](https://github.com/juditecypreste/where-woman-ai/tree/main/catch_images)

The text file I used to download all the images of paintings.

7. [Final organizer and facilitator for creating graphics and illustrations](https://github.com/juditecypreste/where-woman-ai/blob/main/fancy_beeswarm_chart.ipynb)

8. [The data final](https://github.com/juditecypreste/where-woman-ai/blob/main/data_paintings.csv)

### EXTERNAL LINKS

9. [AI](https://huggingface.co/openai/clip-vit-base-patch32)

The model I use.

10. [Wikipedia](https://pt.wikipedia.org/wiki/Lista_de_pinturas_do_Museu_de_Arte_de_S%C3%A3o_Paulo)

The list of paintings in the collection.

# New tools and skills
It was the first time I used D3 and AI in a project and I realized how complex it can be. Although AI has been discussed and applied in different contexts in journalism and data analysis, the results analyzing the paintings of MASP, the most famous museum of Brasil, were not satisfactory, with a great uncertainty. 

Also, using D3 was complex, but I tried to apply the new knowledge in this project witch a way to learn and improve the skills learned during the Lede Program, using JS in and Scrollama. The complete code can be found here.

# I could not
When I first thought of this analysis, I hoped that the AI ​​model might be more accurate in identifying the depiction of humans in paintings. My objective was to identify the number of women and men represented in the Masp collection. However, the results were not satisfactory. I believe that if I created and trained a model to analyze painting, it would be more effective and accurate. (It's a plan for the future). 

Also, I tried to make a beeswarm graph using D3, but in addition to spending a lot of time, I couldn't understand the process, much less managed to draw it the way I'd like
