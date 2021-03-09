<!-- omit in toc -->
# Awesome Artificial Humour [![Awesome](https://awesome.re/badge.svg)](https://github.com/vadim0x60/awesome-artificial-humour)

**What is Artificial Humour?** I am glad you asked! It is anything that automates the generation of jokes (in any format, but usually text). 

**What is this?** A curated list of best  examples of Artificial Humour online. 

Is something cool missing? [Pull requests welcome!](contributing.md)

<!-- omit in toc -->
## Contents

- [Generative bots](#generative-bots)
  - [In English](#in-english)
  - [In Russian](#in-russian)
- [Conversational bots](#conversational-bots)
- [Research papers](#research-papers)

## Generative bots

### In English

- [Supa Bot Fire](https://twitter.com/supabotfire) - Jokes. I tweet that.
- [Deep Drumpf](https://twitter.com/DeepDrumpf) - I Make America Rich Again for my friends.
- [Burned your tweet](https://twitter.com/burnedyourtweet) - Burnining tweetes by the aforementioned politician.
- [InspiroBot](https://inspirobot.me) - An endless source of insiprational posters.
- [SciGen](https://pdos.csail.mit.edu/archive/scigen/) - A generator of bogus scientific papers that have been accepted to a bunch of conferences.
- [HEADLINERTRON](https://twitter.com/HEADLINERTRON) - Imitating standup comedy with [Botnik](https://botnik.org) engine.

Markov chains:
- [Neuroneca](https://twitter.com/Neuroneca) - Making Stoicism Great Again.
- [King James Programming](http://kingjamesprogramming.tumblr.com) - Commutativity of addition is a single theorem because it depends on the kind of unholy rapport he felt to exist between his mind and that lurking horror in the distant black valley.
- [At the Modules of Madness](http://thedoomthatcametopuppet.tumblr.com) - Mixing software documentation with novels.
- [Taylor Swift Bot](https://twitter.com/BotTaylorSwift) - In case you think the world doesn't have quite enough Taylor wift lyrics.
- [The Great Botsby](https://twitter.com/GatsbyBot) - Because F. Scott Fitzgerald is awesome and The Great Gatsby is awesome.
- [That can be my next tweet](http://yes.thatcan.be/my/next/tweet/) - Do what they did to Trump, Bible and Taylor Swift to yourself.

And Darius Kazemi's [76 bots](https://twitter.com/tinysubversions/lists/darius-kazemi-s-bots/members), including:
- [Fellas Bot](https://twitter.com/FellasBot) - Is it gay to brag?
- [Roof Slapping Bot](https://twitter.com/RoofSlappingBot) - This bad boy can fit so many assertions in it.
- [Clicker Maker](https://twitter.com/ClickerMaker) - Generates new clicker games all the time.
- [Metaphor-a-minute](https://twitter.com/metaphorminute) - Moar philosophy.
- [HottestStartups](https://twitter.com/HottestStartups) - Free startup ideas.

### In Russian

- [Нейрокухня](https://vk.com/cooktech) - Imitating cookbooks.
- [Рамзан Нейродыров](https://twitter.com/neuromzan) - Поздно ночью завершился международный терроризм.
- [Ветхий Алгоритм](https://twitter.com/alg_testament) - King James Programming, but in Russian and funnier.
- [Neural Machine](https://twitter.com/neural_machine) - Generating gibberish phrases with Google Translate.
- [Мои нейронные юморески](https://vk.com/neuraljumoresques) - Imitates human jokes.

## Conversational bots

- [ELIZA](https://en.wikipedia.org/wiki/ELIZA) - In case you can't afford a therapist. Passed the Turing test with just a few regular expressions.
- [Mitsuku](https://www.pandorabots.com/mitsuku/) - makes you wonder if _you_ pass the Turing test.

## Research papers

[Humoroids - Conversational Agents That Induce Positive Emotions With Humour](https://eprints.lib.hokudai.ac.jp/dspace/bitstream/2115/63991/1/Humoroids%20-%20Coversational%20Agents%20That%20Induce%20Positive%20Emotions%20with%20Humor.pdf)

In this paper, we propose a definition of "Humoroids" - a new class of humor-equipped talking agents. 
We summarize existing research, discuss the concept of Humoroids and introduce our pun-telling agent, which (as shown in an evaluation experiment) induces positive emotion in human interlocutors. 

[That's What She Said: Double Entendre Identification](http://www.aclweb.org/anthology/P11-2016)

Humor identification is a hard natural language understanding problem. We identify a subproblem — the “that's what she said” problem — with two distinguishing characteristics: 
1. Use of nouns that are euphemisms for sexually explicit nouns 
2. Structure common in the erotic domain. We address this problem in a classification approach that includes features that model those two characteristics. Experiments on web data demonstrate that our approach improves precision by 12% over baseline techniques that use only word-based features.

[Dank Learning: Generating Memes Using Deep Neural Networks](https://arxiv.org/abs/1806.04510) ([GitHub](https://github.com/alpv95/MemeProject))

We introduce a novel meme generation system, which given any image can produce a humorous and relevant caption. 
Furthermore, the system can be conditioned on not only an image but also a user-defined label relating to the meme template, giving a handle to the user on meme content. 
The system uses a pretrained Inception-v3 network to return an image embedding which is passed to an attention-based deep-layer LSTM model producing the caption - inspired by the widely recognized Show and Tell Model. 
We implement a modified beam search to encourage diversity in the captions. 
We evaluate the quality of our model using perplexity and human assessment on both the quality of memes generated and whether they can be differentiated from real ones. Our model produces original memes that cannot on the whole be differentiated from real ones.

[Unsupervised joke generation from big data](https://www.aclweb.org/anthology/P13-2041.pdf)

Humor generation is a very hard problem. 
It is difficult to say exactly what makes a joke funny, and solving this problem algorithmically is assumed to require deep semantic understanding, as well as cultural and other contextual cues. 
We depart from previous work that tries to model this knowledge using ad-hoc manually created databases and labeled training examples.
Instead we present a model that uses large amounts of unannotated data to generate _I like my X like I like my Y, Z jokes_, where X, Y, and Z are variables to be filled in.
This is, to the best of our knowledge, the first fully unsupervised humor generation
system. 
Our model significantly outperforms a competitive baseline and generates funny jokes 16% of the time, compared to 33% for human-generated jokes

[Generating Original Jokes](http://www.cse.scu.edu/~mwang2/projects/NLP_generateOriginalJokes_18w.pdf)

Computational Joke generation is a complex problem in the field of artificial intelligence and natural language
processing. 
If successful, however, computational humor would play an essential role in interpersonal communication between humans and computers. 
In this paper, we use natural language processing (NLP) techniques paired with various models to generate original puns. We found that character-based recurrent neural network (RNN) is a more solid approach to generate original jokes by comparing its results with those generated by trigram and word-based RNN models. 
Using jokes from sources like [Reddit.com](reddit.com), [Twitter](twitter.com), and joke specific websites to train our models, we evaluate results and present our conclusions.

[Computer, Tell Me a Joke ... but Please Make it Funny: Computational Humor with Ontological Semantics](https://www.aaai.org/Papers/FLAIRS/2006/Flairs06-148.pdf)

Computational humor is a subdiscipline of computational linguistics with applications in human computer interfaces, edutainment, affective computing, intelligent agents, and other areas. 
Based on ontological semantics, we develop the resources and algorithms the computer needs to understand and produce humor, in principle and on a detailed example.
Our ultimate output will not be that of a toy system that fills in templates, previously the only available approach, but rather true natural language generation, based on the computer approximation of the human understanding of the joke. 
This paper shows how ontological semantics provides for and computes the full computer understanding of humor, a sine qua non of humor generation.
