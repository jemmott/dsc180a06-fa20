# Week 8

## Topics

## Reading

Read a few blog posts from "Practical Recommendations":
- [The rest of the owl](https://practicalrecs.com/the-rest-of-the-owl.html)
- [Top model](https://practicalrecs.com/top-model.html)
- [From models to systems](https://practicalrecs.com/from-models-to-systems.html)

Optional, recommended: get deeper into A/B testing. https://github.com/jemmott/dsc180a06-fa20/blob/master/papers/2009controlledExperimentsOnTheWebSurvey.pdf

# Tasks

Think about a recommender system you might want to build next quarter.  It is ok if this doesn't exactly match your upcoming proposal, and also if it is different than the rest of your group.  The goal is to think through these questions for your specific problem.

## Task 1

Write down, in one or two sentiences, what the goal of your recommender system is.  This does not need to be exact or measurable, but should be the actual goal - meaning that if what you built does this, you would be happy. It should ignore the details (what platform, UI, method, etc.), and be focused on the big picture.

- Bad example: "Train a collaborative filter on music data that minimizes NDCG."
- Good example: "Make a playlist generator that generates nostalgic playlists, like 'songs from your highschool years'"

## Task 2

Remember this list from [week 5](https://github.com/jemmott/dsc180a06-fa20/blob/master/week5.md)?

1. Domain
2. Purpose
3. Context
4. Personalization Level
5. Whose opinions
6. Privacy and trustworthiness
7. Interface
8. Algorithms

I want you to go through and think about each question for the system you will be building.  Keep in mind what data you might have, how you will measure success, etc.

The goal is to be as absolutely precise as possible.  For example, "domain" is the set of items you are recommending from.  For a music recommender this isn't "songs", but might be "Songs published in the user's high school graduation year, are in the user's language, and are licensed for the user."