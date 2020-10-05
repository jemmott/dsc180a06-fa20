# Schedule

Reading assignments are due before class, so we can talk things over.

Main schedule here: https://dsc-capstone.github.io/student/schedule/

## Background

If you need to brush up on recommender systems, you might find these links helpful:

- UCSD's [CSE158: "Web Mining and Recommender Systems"](https://cseweb.ucsd.edu/~jmcauley/) with McAuley. If you haven't taken this class, you should take it this quarter.  Notes and such from previous versions are online.
- Google's "[Recommendation Systems"](https://developers.google.com/machine-learning/recommendation/) course is free, and takes about four hours to complete. 
- The book "[Practical Recommender Systems"]() by Falk is more approachable, and does a good job discussing the pitfalls that happen in real-world applications. I don't love the informal tone, and the code samples aren't my favorite, but the advice is solid.
- ["Recommender Systems: The Textbook" by Aggarwal](https://www.springer.com/gp/book/9783319296579) is a nice, fairly complete and technical reference. I often pick it up when I am stuck.

## Week 1

The paper that we will be mainly working with this quarter is "[Are We Really Making Much Progress?  A worrying Analysis of Recent Neural Recommendation Approaches](https://github.com/jemmott/dsc180a06-fa20/blob/master/papers/are%20we%20making%20progress.pdf)" by Dacrema, Cremonesi, and Jannach.

Before the first meeting on October 7th, you should try to read the paper.  The goal is to give it a quick read.  Later you will make sure you understand all the details, but the goal in the first pass is to make sure you understand the argument the authors are making and the way that they are reasoning to support it.

I like to read academic papers in the following order:

1. Quick read of Abstract, Conclusion, Introduction (in that order).
2. Careful read of the abstract, making sure you really understand it.  You may need to look up terms. This read takes a long time. This is when I decide if a paper is "worth it".
3. Quick read of the paper, keeping a list of terms & concepts to look up.
4. Look up the stuff you didn't know.
5. Do a careful read of the paper, spending the time to really understand.

For the first class I am asking you to do steps 1-3.

Class Discussion topics

- What recommender systems do we interact with online?  Offline?  What could be a recommender that isn't?
- Reflecting on times when those recommendations are good: what does that look like?
- And what does it look like when they are bad?

## Week 2

Complete steps 4 & 5 from the previous list.

The code for the paper is [here](https://github.com/MaurizioFD/RecSys2019_DeepLearning_Evaluation), along with some detailed documentation and links to additional info about baselines, parameter tuning, etc.

The replication assignment for the quarter is to adapt that baseline code (with citations!) in a way that will be helpful to you. I would like it if you try to replicate a paper that the authors didn't do.

## Week 3

Replication Checkpoint #1 due.

Read [this brief article about the New York Times recommender](https://open.blogs.nytimes.com/2015/08/11/building-the-next-new-york-times-recommendation-engine/).

## Week 4

Do you know about the Netflix Prize?  It is a huge deal in the history of recommender systems.  In 2006 Netflix offered a million dollars to anyone who could beat their algorithm by 20%. It took years, but a team did win the prize!  But then the code from the winning team was never used, and the follow up prize for further improvements was canceled. 


Read Netflix description, and how their thinking about the problem of recommending movies to people evolved:
- [Netflix Recommendations: Beyond the 5 stars (Part 1)](https://netflixtechblog.com/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429)
- [Netflix Recommendations: Beyond the 5 stars (Part 2)](https://netflixtechblog.com/netflix-recommendations-beyond-the-5-stars-part-2-d9b96aa399f5)

More resources (not assigned):
- Wikipedia gives a slightly different account than Netflix: https://en.wikipedia.org/wiki/Netflix_Prize 
- The original rules: https://www.netflixprize.com/rules.html
- Play with the data set! https://www.kaggle.com/netflix-inc/netflix-prize-data
- Learn why the $1M algorithm was never used: https://www.wired.com/2012/04/netflix-prize-costs/
- Learn why the follow up was canceled: https://www.wired.com/2010/03/netflix-cancels-contest/

## Week 5

Replication Checkpoint #2 due.

## Week 6

Give a quick read: ["Evaluating Recommendation Systems"](https://github.com/jemmott/dsc180a06-fa20/blob/master/papers/Evaluating_Recommendation_Systems.pdf) by Shani and Gunawardana. No need to memorize all the material here, but it is important to know what your options are.

## Week 7

Reach chapter 3 of Cathy O'Neil's "Weapons of Math Destruction" [here](https://github.com/jemmott/dsc180a06-fa20/blob/master/papers/Weapons-of-Math-Destruction-Cathy-ONeil-pages-deleted.pdf).  I recommend reading the whole book - I don't agree with everything in it, but it is on my [list of books I like](https://github.com/jemmott/books).

## Week 8

Listen to [Rabbit Hole](https://www.nytimes.com/2020/04/16/podcasts/rabbit-hole-internet-youtube-virus.html) episodes 1-4.  You can also listen wherever you get podcasts. Episodes 5-8 are also interesting, but don't focus as directly on recommender systems, and so aren't assigned.

Read about [Goodhart's Law](https://en.wikipedia.org/wiki/Goodhart%27s_law)

Optional: [Recommender systems and their ethical challenges](https://github.com/jemmott/dsc180a06-fa20/blob/master/papers/RecommenderSystemsAndTheirEthics.pdf)

## Week 9

Project Proposal due.

Some reading from "Practical Recommendations" blog:
- [The rest of the owl](https://practicalrecs.com/the-rest-of-the-owl.html)
- [Top model](https://practicalrecs.com/top-model.html)
- [From models to systems](https://practicalrecs.com/from-models-to-systems.html)

## Week 10

Final Replication due.