<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Tu Quoque
Make your arguments better with AI

Final project for the Building AI course

## Summary

Making valid arguments and drawing conclusions that follow from the premises can be hard, which anyone who has ever gotten involved in a discussion can attest to. 
The idea behind this project is to examine if artificial intelligence, AI, can be used to build an application that can help us identify when the arguments used, 
by ourselves or by other people, are fallacious.


## Background

Arguments are the bread and butter of human reasoning. The quality of the conclusions we reach and the decisions we make to a large degree depend on the validity
of the arguments we put forward, and using invalid arguments - whether intentionally or by oversight - can easily derail a discussion or a train of thought. And
that is, unfortunately, often what happens, especially in discussions where feelings run high and when a lot is at stake.


## How is it used?

The idea behind this solution is to examine if it's possible to use natural language processing to train an AI application to recognise different kinds of
logical fallacies and then apply those categories to real-life examples. Analysing written examples would be the logical(!) first step, and if a working solution
can in fact be constructed, the easiest way to make it available would probably be through an online service of some kind. An example would be a site where one can paste or upload one's text, have it analysed, and then be able to copy or download the assessment for further work improving one's arguments.

Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://" width="300">

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


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
* etc
