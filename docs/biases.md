---
layout: page
title: "Phrase Biases"
permalink: /biases/
---

<style>
	.center {
		text-align: center;
		}
</style>

# /aids/ Phrase Bias Collection
{: .center}

~~OOOOH SHIT, THAT'S SIX~~
{: .center}

You know the drill, not on discord log of phrase bias files.
{: .center}

***

- [/aids/ Phrase Bias Collection](#aids-phrase-bias-collection)
  - [But What ARE Phrase Biases?](#but-what-are-phrase-biases)
  - [Focus](#focus)
    - [Tender Love and Care](#tender-love-and-care)
  - [Lexicon](#lexicon)
  - [Structure](#structure)
  - [Perspective](#perspective)
  - [Franchise](#franchise)
    - [Pokedex](#pokedex)

***

## But What ARE Phrase Biases?

The NovelAI reimplementation of token biasing. Right now, a majority of what we know comes from the words of the team themselves.

> NovelAI's unique Phrase Biasing, is far more powerful than the logit biasing we implemented, tested, and open-sourced earlier but found unsatisfactory.
>
> For example, we can bias positively for `I`,` we`, `my`, `our` and make sure that Sigurd sticks to a first-person narrative.
>
> Another example would be to bias for various classes in an RPG such as a `Paladin`, `Rogue`, or `Priest`, or against fantasy races and creatures. Alpha test users have reported being able to get a very distinct experience without the use of AI Modules or Lorebooks with Phrase Biasing alone!
>
> Possible bias values are decimal numbers ranging from -2.0 (for negative bias) to 0 (for no bias) to 2.0 (for positive bias). Please note that the strength of biasing is logarithmic, not linear. For example, -2.0 is much much stronger than -1.0. We've observed that bias values in the range of -0.4 to 0.4 are often enough to have a good effect.

The phrase bias menu looks like this:

![The Phrase Bias Menu](https://i.imgur.com/WovKHjC.png)

Placed underneath the Banned Tokens section of the right-sided window.

Entering words / sentences works like banned tokens, you type however long you want it to be, and pressing enter confirms it as a "phrase" which can later be edited and removed by clicking on them. Similar to banned tokens, encasing your output in square brackets allows you to input token values, but encasing them in curly brackets allows you to enter them as is without any modification by the frontend.

Also note that what you enter is case sensitive and contains a space. `Robert` and `robert` will be treated as two unique phrases, and the tokens they point to aren't ones used to start a new paragraph. If you don't want the space, use curly brackets.

![Example versions](https://i.imgur.com/HAG65cI.png)

Increasing and decreasing the Bias value understandably increases or decreases the chance of the collection of phrases showing up in your outputs. As said by the devs, the value works logarithmically, which effectively means that the most drastic changes can be felt by only slightly nudging values.

If you're too dumb to know what means exactly, here's [a helpful graph](https://files.catbox.moe/um54xi.png) I found on the internet comparing expected curves.

Whatever value you think you need to set your phrase biases to in order to get more words to show up is probably too high. Instead, try adjusting the value by 0.1 increments and then getting more granular as you find the sweet spot. When compared to HoloAI's logit bias implementation, phrase biasing is also extremely context-aware. So far, I haven't needed to nudge things past 0.3 positive or negative, but this is all down to personal preference, and it's braindead easy to change if the AI isn't bringing up enough reptilian tails and scales.

With the plus button, you can create a new bias set (which is probably not the official term); all enabled bias sets are active at the same time as all other enabled sets. Similarly, if you have two sets that both contain the same word, the values assigned to the word stack on top of each other.

The last two options, "Ensure Completion After Start" and "Unbias When Generated" are self-explanatory, but I have a few thoughts on them based on preliminary testing.

"Ensure Completion After Start" means that whenever the AI generates the first token of a phrase, the subsequent tokens that comprise the rest of the phrase are high enough to ensure the phrase is completed. This is a very extreme option based on my experiments, as it can cause the AI to bring up the phrase at incongruous times, so why would you ever enable it?

I see two possibilities: either normal bias operation isn't good enough for you (perhaps you're attempting to use an extremely uncommon name or word), or **you actually want that because you don't want any other words to appear.**

Consider my earlier collection of phrases; increasing the bias to 0.5 reveals that they are used often, but there are also seemingly odd choices:

![blouses with blousy](https://i.imgur.com/dN1zFHi.png)

Without the option enabled, I didn't just get an increased chance for [blippo](https://i.imgur.com/ULzc15J.png), but all words that share the same starting tokens like [blouse](https://i.imgur.com/EtPKg1u.png).

The same can be said for [yingo](https://i.imgur.com/O9DgOCx.png), leading to [yum and its variations](https://i.imgur.com/QpzqWPR.png) showing up instead of my desired word.

So keep that in mind; increasing bias can increase the likelihood of a lot more words than just the ones you've entered.

"Unbias When Generated" disables the bias applied to a word if it appears only once during generation. This is certainly more useful in smaller generation sizes where what little output you get is more useful when it isn't the same couple words being repeated ad nauseum, but it can also serve to curtail more dramatic biasing efforts where you definitely want words to show up each generation but don't want them to show up more than once.

***

## Focus

### [Tender Love and Care](https://files.catbox.moe/ixzi04.bias)

[by Anon](https://arch.b4k.co/vg/thread/354566545/#354568645)

*Oh god, I used that Anon's tender love logit bias from the screenshot in the last thread and added "gently" to it. I'm doing the horizontal slow dance with my big tittied tomboy childhood friend and it's amazing.*

***

## Lexicon

***

## Structure

***

## Perspective

***

## Franchise

***

### [Pokedex](https://files.catbox.moe/qr8zkq.bias)

[by Loki](https://discord.com/channels/836774308772446268/895192255818792970/895210363744829450)

*It's the entire Pokedex (without forms). I fixed the bias, 0.1 seems to be too high for such a long list so I kept it at 0.05, which works fine for me. (also fixed a mistake where I had a whitespace token in front of all entries, so Sigurd mostly just outputted whitespaces)*

*On a side note, I used Nidoranm and Nidoranf since Sigurd apparently can use the correct symbol (screenshot below)*