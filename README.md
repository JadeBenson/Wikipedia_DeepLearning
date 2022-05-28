# A Survey of Deep Learning Techniques: Wikipedia Movies
## Created by Egemen Pamukçu, Jade Benson, Sabina Hartnett, Tian Chen
### For MACS 37000 Thinking with Deep Learning for Complex Social & Cultural Data Analysis

This is the repository for our final group project for the Spring 2022 Deep Learning class that uses Wikipedia data. 
[Published Final Blog Post](https://docs.google.com/document/d/e/2PACX-1vRkb8yydolwOrL3RJgd6kUFxgeLgeQLCCnsxp-kQMh71Wk_1FuBE1WoNTJeaxYeFH4zSKpQqD0QZoS2/pub)

## Introduction to Our Project 

We’re big sci-fi nerds and I bet if you’ve landed here you probably are too. It seems like sci-fi technologies are getting ever closer with the promise of self-driving cars, interactive robots, deep fakes, generated art, the list goes on. Behind these advancements is deep learning. But the influence of deep learning is not just behind flashy sci-fi technologies, it already shapes so much of our world behind the scenes - economic models, public health predictions, search engines, dating apps, admission processes, and more. If you’re interested in better understanding how these technologies are created and perhaps participating in the creation of  sci-fi today, read on!

So you’re excited by these possibilities, but still what exactly is deep learning? Deep learning is the name given to refer to multi-layered neural networks (example in figure 1). Breaking that down: multi-layered refers to many nested interconnected models within a larger one and defining neural networks depends on your chosen discipline’s philosophy. Biologists view them as neurons, mathematicians as weighted graphs, psychologists as intelligence models, engineers as connected computational models, and to computational social scientists like us we take an approach pioneered by James Evans that attempts to synthesize these perspectives. For this tutorial we’ll take more of an engineering perspective that focuses on the model selection and architecture (network layers, weights, structure), but if you want to philosophize more, feel free to reach out to our coauthor Jade. 

*What’s interesting about our case study?*

In this post we apply deep learning techniques to a case study of movie clustering and classification from two crowdsourced resources: Kaggle and Wikipedia. We think our datasets allow us interesting insight into popular culture. Movies are one of the most popularly consumed artistic mediums and Wikipedia is a publicly-created and consumed encyclopedia. This analysis allows us dual insight into how consumers view and process art (Wikipedia summaries, reviews, box office revenue) and how artists/marketers intend for their art to be consumed (posters - collected via Kaggle). Although we attempt to capture the many facets of this art and its cultural production/consumption with multiple types of data, we do need a taxonomy to guide our process and evaluation. We select movie genres since these labels try to group similar movies and their intended audiences together. Like all labels, these are not perfect. Art often bends its genre in creative and surprising ways to deliver its intended effect, genres also overlap and blend (drama is often defined by its comedic relief), and genre definitions change over time and may take on different meanings for different groups of people. However, genres are still useful since they categorize overarching similarities between movies in an understandable way that is popularly understood and also used for production.

## Data 
Below are links to the data sources we use and reference in this project.

Poster array [link](https://drive.google.com/file/d/1hE_kPhqWoZNjfV7uOnwdtMUpHyK-Muwc/view?usp=sharing)
##### The rest of the original datasets are too large to be posted directly in this Github. Links are found below. 

[CMU Wikipedia plots, characters, genres, networks](http://www.cs.cmu.edu/~ark/personas/)

[Movie poster links](https://www.kaggle.com/datasets/neha1703/movie-genre-from-its-poster) (Kaggle scraped from IMDB)
[NP Array](https://uchicago.box.com/s/z3egn1oprxgjenjmmpu5dycda4s40hpr) with RGB values of all posters (not formatted, see above link for updated version)

[Bechdel Test](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-03-09/readme.md)




