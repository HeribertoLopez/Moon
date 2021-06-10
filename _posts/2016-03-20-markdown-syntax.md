---
layout: post
title:  "Pokemon Classification Project"
date:   2021-05-23
category: Data Science 
excerpt: "A Data Science Exploration Project" 
feature: http://pngimg.com/uploads/pokemon/small/pokemon_PNG148.png 
comments: true
--- 

## Introduction 

Since its release in 1996, Pokemon has become an instant success spanning seven generations with more than 802 Pokemon characters. Initially released as "pocket monsters" in Japan, Pokemon became an instant hit when it first began circulating in the United States in the '90s. The franchise largely revolved around animal-like characters in conjunction with human trainers competing in battles with each other trainers and pokemon. In the original television series, a segment of the show included attempting to guess a pokemon based on an outline of its image. The segment was called "who's that pokemon?". I remember growing up watching the series and attempting to guess the pokemon just based on the outline of a pokemon. 

For this project, I wanted to do something similar to that segment of the television series. However, instead of guessing, I decided to explore building several models that could classify Pokemon based on their individual characteristics and features.  Below are a few of the questions guiding the exploration. 

### Out of the following Statistical Methods which produces the lowest error rate when classfying the Pokemon by type? 
- LDA
- Decision Tree

### Using the following methods, how about when we build a predictive model to determine whether a Pokemon is legendary or not?
- KNN
- Ridge

### Lastly, how well does the singular value decomposition method differentiate between different types of Pokemon? 

## Datasets 

- [The Complete Pokemon Dataset from Kaggle](https://www.kaggle.com/rounakbanik/pokemon) 

- [Pokemon Image Dataset from Kaggle](https://www.kaggle.com/vishalsubbiah/pokemon-images-and-types) 



# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Body text

Lorem ipsum dolor sit amet, test link adipiscing elit. **This is strong**. Nullam dignissim convallis est. Quisque aliquam.

![Smithsonian Image](https://mmistakes.github.io/minimal-mistakes/images/3953273590_704e3899d5_m.jpg)
{: .image-right}

*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H2O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times (That’s a citation). Underline.Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and CSS are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

## Buttons

Make any link standout more when applying the `.btn` class.

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

Press <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> to move your car. **Midtown Maddness!!**

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}
