layout: post
title: "Frequently Asked Questions"
date: YYYY-MM-DD hh:mm:ss -0000
categories: aids questions

# The Frequently Asked Questions Rentry

Perhaps you may not have noticed, but a lot of us are quite bored of answering the same questions over and over again. Things have changed since March of this year, and so a new FAQ needs to exist so new or returning anons can come here instead of asking the same shit **over** and **over** ***again***.

Once again, out of respect for what was before, [here's a link to the original FAQ](https://guide.aidg.club/Resources-And-Guides/aidg%20general/aidg-FAQ.html), I'll be reworking still valid sections into here in the interests of convienience and not reinventing the wheel.

***

- [The Frequently Asked Questions Rentry](#the-frequently-asked-questions-rentry)
  - [Context](#context)
    - [So what's the current situation?](#so-whats-the-current-situation)
    - [What the fuck happened to AI Dungeon?](#what-the-fuck-happened-to-ai-dungeon)
    - [Well, I don't like sexualizing minors, so I'm fine](#well-i-dont-like-sexualizing-minors-so-im-fine)
    - [But wait, these alternatives all lack the 175B parameters that Davinci (and by extension Dragon) have](#but-wait-these-alternatives-all-lack-the-175b-parameters-that-davinci-and-by-extension-dragon-have)
  - [GPT-6B-J](#gpt-6b-j)
    - [Is it as good as Dragon?](#is-it-as-good-as-dragon)
    - [Is it as good as Davinci?](#is-it-as-good-as-davinci)
  - [Storyteller Agnostic](#storyteller-agnostic)
    - [I'd like more surprise in my stories](#id-like-more-surprise-in-my-stories)
    - [How should I style my Author's Note/Memory/World Info?](#how-should-i-style-my-authors-notememoryworld-info)
    - [But what about brackets! They—](#but-what-about-brackets-they)
  - [NovelAI](#novelai)
    - [What is NovelAI?](#what-is-novelai)
    - [How much does NovelAI cost?](#how-much-does-novelai-cost)
    - [What models does NovelAI have available?](#what-models-does-novelai-have-available)
    - [What do we know about their fine-tuning dataset?](#what-do-we-know-about-their-fine-tuning-dataset)
    - [What advantages does NovelAI have over AI Dungeon?](#what-advantages-does-novelai-have-over-ai-dungeon)
    - [The default settings are quite underwhelming, but I don’t know what to do regarding generation options. Help?](#the-default-settings-are-quite-underwhelming-but-i-dont-know-what-to-do-regarding-generation-options-help)
    - [Can Sigurd understand `[ESTABLISHED FRANCHISE]`?](#can-sigurd-understand-established-franchise)
    - [Is there any place I can go to see if others have made lorebooks of my favorite things?](#is-there-any-place-i-can-go-to-see-if-others-have-made-lorebooks-of-my-favorite-things)
    - [What are 'Story Parameters'?](#what-are-story-parameters)
      - [Okay, so where can I find tried and tested values?](#okay-so-where-can-i-find-tried-and-tested-values)
    - [Who the fuck is Turk?](#who-the-fuck-is-turk)
    - [Who the fuck is finetuneanon?](#who-the-fuck-is-finetuneanon)
    - [Who the fuck is Aini?](#who-the-fuck-is-aini)
  - [HoloAI](#holoai)
    - [What is HoloAI?](#what-is-holoai)
    - [How much does HoloAI cost?](#how-much-does-holoai-cost)
    - [What do we know about their fine-tune dataset?](#what-do-we-know-about-their-fine-tune-dataset)
    - [Is the dataset better than NovelAI’s?](#is-the-dataset-better-than-novelais)
    - [What advantages does HoloAI have over AI Dungeon?](#what-advantages-does-holoai-have-over-ai-dungeon)
    - [What advantages does HoloAI have over NovelAI?](#what-advantages-does-holoai-have-over-novelai)
  - [KoboldAI](#koboldai)
    - [What is KoboldAI?](#what-is-koboldai)
    - [How much does it cost?](#how-much-does-it-cost)
    - [How do I get it all working?](#how-do-i-get-it-all-working)
    - [Can I not just try and run it all on my own machine, then?](#can-i-not-just-try-and-run-it-all-on-my-own-machine-then)
  - [/aids/](#aids)
    - ['/aids/'?](#aids-1)
    - [But if NovelAI is the popular choice, why not rebrand to that?](#but-if-novelai-is-the-popular-choice-why-not-rebrand-to-that)
    - [What are “Theme Fridays”?](#what-are-theme-fridays)
    - [What is the state of the general?](#what-is-the-state-of-the-general)
    - [What happened to the original coomer’s guide?](#what-happened-to-the-original-coomers-guide)
    - [What happened to clubanon?](#what-happened-to-clubanon)

***

## Context

### So what's the current situation?

Everyone who is sane has progressed from AI Dungeon to three major avenues: NovelAI, HoloAI, and KoboldAI with Colab. NovelAI has the most features, HoloAI is the least expensive option, and KoboldAI with Colab is for those who are broke but technologically competent.

### What the fuck happened to AI Dungeon?

On April 27th, Mormon and co decided to implement an automatic regex filter to prevent AI generation and flag user stories if they involved sexualization of a minor. Like all forms of moral panic over user generated creative content, [the initiative went about as well as you might expect.](https://rentry.co/remember-what-they-took-from-you)

It gets worse. On August 17th, [Latitude released a blog post detailing the game plan going forward, and it's fucking hilarious.](https://latitude.io/blog/a-new-story-experience/)

Dragon is well and truly dead, and OpenAI killed it.

### Well, I don't like sexualizing minors, so I'm fine

![Taken 17th July 2021](https://files.catbox.moe/t6o7nm.png)

Ignoring the fact that we're talking about literal fucking text, no, you aren't.

Let's say you have a tale with no terms of endearment, no sexual content, no profanity, and, shit, you're a thesaurus whiz.

Even with all of that, you’ll have to work to keep the fucking AI from going down that path in the first place. Mormon’s meticulously curated CYOA finetune data also includes shady kiddie fucking and other amusing scenarios. Triggers are something you’ll always have to watch out for when doing short cooms, and they’re unavoidable for anything longer.

Also even if the focus on your cooms isn't anything "unsavory" the very fact that you're doing it will trigger OpenAI's filter which Mormon has now put in place for Dragon. So yeah, you are not fine.

### But wait, these alternatives all lack the 175B parameters that Davinci (and by extension Dragon) have

Yes, that is true. As of the time of writing, all three use [EleutherAI's 6B model](https://gpt3demo.com/apps/gpt-j-6b), and this does translate to less ingenuity. But there are two major strengths that help with the pain: 2048 tokens, freedom, and the lack of CYOA finetuning.

When Mormon inserted his insipid kid diddling second person dataset for finetuning, he effectively crippled the ability of both Griffin (which is 6B parameters, by the way) and Dragon. Even at the  initial release of GPT-6B-J when the only way to  use it was [through a website hosted by EleutherAI](https://6b.eleuther.ai/), we quickly realized how much bad finetuning can ruin a perfectly good model.

GPT-6B-J can't compete with Dragon's highest highs, and it can't hope to achieve some of the major cooms we were able to get out of summer Dragon, but it's pretty fucking good as is, and if you're willing to be creative and malleable, you'll have a much better time with it than AI Dungeon today.

And now, with Latitude's [new setup](#what-the-fuck-happened-to-ai-dungeon), you probably won't be getting a lot of outputs from 175B Dragon regardless. [The newly implemented OpenAI filter is notorious for being even stricter](https://beta.openai.com/docs/engines/content-filter) than anything Mormon could come up with, which means that a lot of your "unsafe" outputs will just be from a custom GPT-6B-J anyway.

!!! note

	*That filter often blocks even mild fantasy violence, which would obviously hurt the magic of AI Dungeon—we believe that you should be able to fight off bandits, slay dragons, and have all of the kinds of epic adventures that make AI Dungeon so fun.*

	->[*Latitude on OpenAI's filter*](https://latitude.io/blog/a-new-story-experience/)->

***

## GPT-6B-J

### Is it as good as Dragon?

For what we're doing? There's barely a difference anymore.

!!! note

	*If your story triggers OpenAI’s filters it will be handled by our own models rather than resulting in account suspension. We will still use and continue to work on our own filters to enforce our content policies, but they will be much more carefully targeted, ensuring that you aren’t unfairly penalized for incorrectly flagged content.*

	->[*Latitude on their new filter system*](https://latitude.io/blog/a-new-story-experience/)->

### Is it as good as Davinci?

Obviously not. [But OpenAI won't allow you to use Davinci for anything "ghastly"](https://beta.openai.com/docs/use-case-guidelines), so why even ask?

***

## Storyteller Agnostic

### I'd like more surprise in my stories

Consider using "Suddenly," in your inputs, or specifically noting the fast-paced unexpected nature of the story in Author's Note.

### How should I style my Author's Note/Memory/World Info?

For a majority of the time, you should do nothing else other than making it in the tense, perspective, and writing style of your main prompt. More so than ever before, memory formatting has no reason to exist; with 1024 - 2048 tokens max that these new storytellers work with, you shouldn't be in many situations where you run out of space for all your prose entries.

### But what about brackets! They—

Are primarily useful for single sentences; otherwise, the main point of "stopping the AI from regurgitating your output" becomes less obvious.

If you put an entire paragraph in brackets, the AI will be less likely to regurgitate *the entire paragraph*, not, *all specific sentences from that paragraph*. Brackets are good for influencing the AI with single sentence hints when you can't be bothered to do that through the story itself, but anything more than that rarely has a greater impact than simply writing good fucking prose.

And that doesn't even take into account the fact that the AI still recognizes it as part of the context and may pick up your shit prose anyway.

If brackets are still useful to you—that is, you constantly encounter the AI repeating your stuff verbatim or just get better stuff with it—then you're probably going to use them anyway. If they don't, or you can't tell, don't rely on brackets for any more than short sentence hinting.

***

## NovelAI

### What is NovelAI?

NovelAI is a subscription service that hosts GPT models fine-tuned to produce high-quality prose, which the user can then use to dynamically generate completions for storytelling purposes.

### How much does NovelAI cost?

NovelAI lacks a free trial of any kind, and offers three subscription tiers.

- $25 Opus Tier - Unlimited Max Priority Actions, 2048 Token Context Window, **100 Max Output Token Length**, Experimental Features, Ability to train custom modules.
- $15 Scroll Tier - 1000 Max Priority Actions, 2048 Token Context Window.
- $10 Tablet Tier - 1000 Max Priority Actions, 1024 Token Context Window.

In terms of which of these is worth it, currently Scroll tier is the best to go for. The extra 1024 tokens makes a huge difference in play compared to just half.

### What models does NovelAI have available?

Currently NovelAI has two, Calliope and Sigurd. Both of which are fine-tuned on their own custom dataset.

Calliope is GPT-Neo (2.7B parameters) while Sigurd is GPT-6B-J.

> Sigurd is the name of NovelAI fine-tuned GPT-J-6B model. This model launched during the Beta as an Experimental Feature for our opus tier subscribers and has since been rolled out to all tiers. Newer Sigurd models will continue to release as Experimental Feature for Opus subscribers first.
> Sigurd is a much bigger model and response times are a little slower in comparison to Calliope, our 2.7B model.

*NovelAI’s FAQ*

### What do we know about their fine-tuning dataset?

The specifics have yet to be revealed by any member of the team, but we do have a general understanding. Kuru and his colleagues stated in the early days of the project that they planned to work primarily with books, light novels, and high-quality novellas for their dataset.

The first version of the set was used to fine-tune Calliope, then Sigurd (5% at V1, then completed at V2), but there was an oversight regarding dialogue quality, which necessitated a dataset pruning to remove offending stories. After that, they fine-tuned again, resulting in the current iteration of Sigurd (Sigurd V3).

As of this writing, they claim that their most recent iteration contains 5.1 GB of text, which translates to approximately 2,550,000,000 words.

### What advantages does NovelAI have over AI Dungeon?

Simply put, NovelAI outperforms AI Dungeon in terms of UI and UX. Its Sigurd model outperforms Griffin in its current form, and while it isn’t as good as Dragon was in its prime, the lack of CYOAIDS more than compensates for the difference in parameter count. NovelAI is currently the best option if you are able and willing to pay for it.

### The default settings are quite underwhelming, but I don’t know what to do regarding generation options. Help?

You can take a look at [our collection of settings](https://rentry.co/settings) or Novel AI’s section on their [unofficial knowledge base](https://naidb.miraheze.org/wiki/Detailed_Concepts#Generation_Options) regarding the matter.

### Can Sigurd understand `[ESTABLISHED FRANCHISE]`?

Not so good. Partially because of GPT-6B-J’s training and partially because of the fine-tune dataset, Sigurd can recall concepts and information from most popular media, but lacks the 'understanding' necessary to correctly contextualize these things. It may know Pokemon abilities but assign them to the wrong Pokemon, for example. Most of the time, creating a lorebook is your best bet.

### Is there any place I can go to see if others have made lorebooks of my favorite things?

Right now there are two main places. The NovelAI discord or the [lorebook repository](https://rentry.co/lorebooks).

### What are 'Story Parameters'?

Based off the way Novel AI's finetuned dataset was tagged, story parameters refers to the concept of recreating said tag in your own story to steer NovelAI in a certain direction. Formatshit that [works](https://rentry.org/story-param).

#### Okay, so where can I find tried and tested values?

You could try [here](https://docs.google.com/spreadsheets/d/1Jfxf10C_s8n4dcWYQ-kW_X1lVZEkz_ORSuEs-F3-v1U/edit#gid=1099421859) or [here](https://docs.google.com/spreadsheets/d/1dgSTNbTwuAydPU4LLoMw4lL1RgDuas7XNixRce9oBZA/htmlview#gid=1099421859).

### Who the fuck is Turk?

kurumuz, or Turk when his backend is failing, is the lead developer and main guy behind NovelAI. He was an Anon like you and me, and stepped up almost immediately after Latitude confirmed their regex filter chicanery to create an alternative. Considering how good of an alternative it is and that he still posts to the general even now, he’s cool in my book.

### Who the fuck is finetuneanon?

finetuneanon is another veteran of the general who is now on the AI development team for NovelAI. He is best known for his fine-tuning work on GPT-2.7B, creating the horni fine-tuned models, one of which being a literotica dataset and the other being a light novel dataset. Granted they weren’t all that great, but he has since acknowledged that it could have been done better. Be sure to send him your love when he posts.

### Who the fuck is Aini?

Aini is the community manager for NovelAI. She was a regular in the /aidg/ threads who would occasionally drawfag, but has since moved on to the NovelAI discord.

***

## HoloAI

### What is HoloAI?

HoloAI is another online alternative, offering a fine-tuned GPT-J-6B for a more economical price point.

### How much does HoloAI cost?

HoloAI does have a free tier, with limitations on settings and a max generated output character limit.

It offers a Pro Tier with higher limits for $5 a month, and an unlimited Elite Tier for $8 a month.

### What do we know about their fine-tune dataset?

The concept is the same as NovelAI: cultivate a dataset of high-quality literature with the goal of improving the model’s prose.

### Is the dataset better than NovelAI’s?

Nobody can say which is better, but they’re both good in their current forms and accomplish what they set out to do.

### What advantages does HoloAI have over AI Dungeon?

It provides a fine-tuned GPT-6B experience with frequent significant updates and measures taken to allow you to secure your stories, while also providing unlimited generations for a lower price than AI Dungeon. So, essentially, what NovelAI provides, but at a lower cost.

### What advantages does HoloAI have over NovelAI?

So far, there haven’t been many, but for the price it offers it's pretty much neck and neck with NovelAI right now. HoloAI’s early days were rocky because they prioritised release before NovelAI could even announce a date for the public beta, and they initially offered the [Megatron transformer model](https://arxiv.org/abs/1909.08053), which sucked. They are working on various features, a revamp of their own fine-tuning dataset, and have implemented markdown support for not only the user side, but also the model side.

They also include Literotica/Goodreads tags to direct AI. The same concept as Novel AI's story paramaters, but officially implemented and more verifiable as a result.

HoloAI is a fantastic alternative to NovelAI and a great place to start for premium storyteller services if you're on a budget.

***

## KoboldAI

### What is KoboldAI?

KoboldAI is a browser-based front end for transformer AI models stylized in a similar vein to AI Dungeon. Originally created and used for GPT-Neo models and smaller, it’s found new life with colab notebooks, where you rely on Google’s spare computing power to run a GPT-6B-J model that you then directly interface with your locally run KoboldAI client.

### How much does it cost?

It doesn’t cost anything, but it does require some finicking and luck. It’s a lot easier than it used to be to set up, but this method may result in you constantly terminating certain notebook runtimes because the GPU Google saddled you with lacks sufficient VRAM to meet the model’s requirements. Furthermore, Google will close your session due to 'inactivity,' and they will track your usage over time in order to change your usage limit. You can avoid these by purchasing Google’s $10 Colab Pro subscription, but at that point you might as well use one of the other paid alternatives.

It may go without saying, but you’re going to need to use a Google account.

>Notebooks run by connecting to virtual machines that have maximum lifetimes that can be as much as 12 hours. Notebooks will also disconnect from VMs when left idle for too long. Maximum VM lifetime and idle timeout behavior may vary over time, or based on your usage. This is necessary for Colab to be able to offer computational resources for free. Users interested in longer VM lifetimes and more lenient idle timeout behaviors that don’t vary as much over time may be interested in Colab Pro.

[*Google’s FAQ*](https://research.google.com/colaboratory/faq.html)

### How do I get it all working?

A guide to set up KoboldAI exists [here](https://rentry.co/itsnotthathard), and a guide to modify it to work on external devices on the same local network exists [here](https://rentry.co/itsthateasy).

### Can I not just try and run it all on my own machine, then?

Only if you have around 16 gigs of VRAM on your machine. Otherwise, you’re stuck with colab like the rest of us.

***

## /aids/

### '/aids/'?

Originally we were going to die as /aidg/, but instead we eventually settled on a rebranding to *AI Dynamic Storytelling*. Not dead yet, it seems.

### But if NovelAI is the popular choice, why not rebrand to that?

The self-immolation of Latitude taught us that naming ourselves after a specific service was a bad idea if that service was going to turn around and shit on you later. It is preferable to cover the entire field rather than just one service, regardless of which is the most popular option.

> \>*A lot of words for “it was funny so we kept it”*

### What are “Theme Fridays”?

Theme Fridays are a biweekly event where Anons post prompts that contain a recurring idea picked on every other week. Originally the theme was decided on a vote, but recently we have changed to a random pick using the current thread’s post number as a seed for reproducibility.

### What is the state of the general?

Everyone is laughing at Latitude for biting the bullet and implementing their own GPT-6B-J model to switch to when their few users use Dragon for no no reasons.

AI Dungeon has died, and the people are overjoyed.

### What happened to the original coomer’s guide?

It’s still available due to being hosted on GitHub, but, yeah, the main guy behind it is gone. That’s kinda why I’m here.

### What happened to clubanon?

What do you mean? [He’s still around](https://arch.b4k.co/vg/thread/343497956/#343523108)