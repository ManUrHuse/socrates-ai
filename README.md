<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# The Socrates Project
Make your arguments better with AI

Final project for the Building AI course

<img src="https://github.com/ManUrHuse/socrates-ai/blob/main/MAntokolski_Death_of_Socrates.JPG" width="300">

## Summary

Making valid arguments and drawing conclusions that follow from the premises can be hard, which anyone who has ever gotten involved in a discussion can attest to. 
The idea behind this project is to examine if artificial intelligence, AI, can be used to build an application that can help us identify when the arguments used, 
by ourselves or by other people, are fallacious.

The name of this project obviously comes from the Greek philosopher Socrates (c. 470–399 BC), known to both his contemporaries and to posterity as a relentless
critic of poor reasoning.


## Background

Arguments are the bread and butter of human reasoning. The quality of the conclusions we reach and the decisions we make to a large degree depend on the validity
of the arguments we put forward, and using invalid arguments &ndash; whether intentionally or by oversight &ndash; can easily derail a discussion or a train of
thought. And that is, unfortunately, often what happens, especially in discussions where feelings run high and when a lot is at stake.


## How is it used?

The idea behind this solution is to examine if it's possible to use natural language processing (NLP) to train an AI application to recognise different kinds of
logical fallacies and then apply those categories to real-life examples. Analysing written examples would be the logical(!) first step, and if a working solution
can in fact be constructed, the easiest way to make it available would probably be through an online service of some kind. An example would be a website where 
we can paste or upload our text, have it analysed, and then be able to copy or download the assessment for further work on improving our arguments.

<!--

Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Socrates](https://github.com/ManUrHuse/socrates-ai/blob/main/MAntokolski_Death_of_Socrates.JPG)

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```

-->

## Data sources and AI methods
<!-- Where does your data come from? Do you collect it yourself or do you use data collected by someone else? -->
At this point, no attempt has been made to find sources of texts with already classified examples of fallacious arguments. I know there are webpages that list
different kinds of logical fallacies and give examples, but I don't know if these can be easily "harvested", if there's enough of them to serve as training data,
or, indeed, if this project would be allowed to use them (although I can't see why not).

If no such sources can be found, or if they don't have enough examples, I believe the Internet can provide all the training data needed. It would, however, take a
substantial effort to find, analyse and classify the data. The best way to do it would probably be to concentrate on when type of fallacy at a time, and then
develop the solution incrementally.

<!--

If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

-->

## Challenges
<!--
What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
-->
To be fair, I have no idea what it would take to pull this off. Can AI and NLP even be used to do what I am proposing, and, if so, what would it take to do it?
At this stage I must admit that I don't know.

## What next?
<!--
How could your project grow and become something even more? What kind of skills, what kind of assistance would you need to move on?
-->
If it actually is possible to create a solution capable of analysing arguments in a text, an obvious next stage would of course be to try to analyse spoken
material. It would be really interesting to see a political debate where the speakers' arguments are analysed in real time by a dispassionate and impartial
"referee". 

## Acknowledgments

* Statue of Socrates: Mark Antokolski, _Death of Socrates_ (1875), [photo from the Hermitage by Alex Bakharev](https://sv.m.wikipedia.org/wiki/Fil:MAntokolski_Death_of_Socrates.JPG), edited by Szczebrzeszynski / public domain
