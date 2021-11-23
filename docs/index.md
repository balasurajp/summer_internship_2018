---
layout: default
---

<!-- 
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
 -->
 
 
# Lab Introduction

In TCS Innovation labs - Thane, people work on diverse research areas such as speech and natural language processing technologies, mobile-based social empowerment and performance engineering.

- Speech-enabled self-help application for insurance agents.
- Voice analytics like automatic speech-to-text, analytics based on acoustics.
- Non-linguistic speech processing like AgentAssistTM, AgentAssessTM etc.
- Keywords-based indexing for multilingual TV news broadcast.
- Speech biometrics.

They seek researchers who will advance work in the core research areas, create R&I assets, and enhance the visibility of organizational capabilities. They offer an intellectually stimulating research environment to develop transformative, research-based solutions in order to address present and future business as well as technology opportunities.

# Contributed Projects
  ## Speech Assessment Platform
  Speech assessment platform analyses some of primary soft skills of an individual through two speech signals i.e. read and spontaneous speech. It analyses individual speech signal to determine certain soft skill set. 
  
  - Read Speech Analysis:

    - Pronunciation is simply characterized as the way an individual speaks a word or language in a specific dialect.
    - Intonation is primarily a matter of pitch variation. It involves associated variation in other prosodic features.
    - Loudness is an attribute of sound to determine the acoustic intensity of auditory sensation produced.
    - Signal-to-noise ratio (SNR) is a measure of useful information to irrelevant information in a conversation or information exchange.

  The above stated aspects of speech helps in determining how an individual expresses emotions and attitudes. It helps in evaluating his grammatical structure, and psychological functions in organizing speech that are easy to perceive and memorize.
  
  - Spontaneous Speech Analysis:

    - Identifying fillers, a sound/word in conversation to create a pause to think without giving the impression of finished speaking. Fillers fall into the category of formulaic language, and different languages have different characteristic filler sounds.
    - Speaking rate is a measure of the number of speech units of a given type (phones, syllables or words) produced within a given amount of time. It's believed to vary within the speech according to contextual and emotional factors.
    - Speaking tone is characterized as an individual's emotional prosody of voice in speech, conveyed through changes in pitch, loudness, speech rate, and non-semantic pauses. It is decoded slightly worse than facial expressions but accuracy varies with emotions. Anger and sadness are perceived easily, followed by fear and happiness because prosody has multiple aspects such as lexical, phrasal and clausal prosody.

  ## Language Model for Human Resource Queries
  Language model for HR Queries is an end-to-end system which accepts audio speech signals (Employee queries to Human Resource department) as inputs, process them into a text format using Automatic Speech Recognition system. In next stage, text-data is processed using NLP techniques to identify appropriate query from the database and synthesize appropriate response based on context to respond back to user with audio output. Challenges observed in development of these end-to-end systems involves automatic speech recognition, which is realised by modelling the following components
  
  - Acoustic Model: It represents the relationship between an audio signal and the phonemes or other linguistic units that make up speech. The model is learned from a set of audio recordings and their corresponding transcripts using ML algorithms which create statistical representations of the sounds.
  - Language Model: It is a probability distribution over given sequences of words. Given a sequence with length m, it assigns a probability to the whole sequence. Developing a way to estimate the phrases’ relative likelihood is useful in many NLP applications, especially ones that generate text as an output.

  In speech recognition, the acoustic model maps sound with a word. The language model provides context to distinguish between words and phrases that sound similar. In American English, the phrases "recognize speech" and "wreck a nice beach" are pronounced almost the same but mean very different things. These ambiguities can be resolved by incorporating the evidence from language model into the acoustic model.

  Subsystems in Automatic Speech Recognition:
  - Weighted finite state transducer-based speech recognition: It is a promising alternative to the traditional decoding, which offers a unified framework representing various knowledge sources and producing the full search network optimized upto Hidden markov model states.
  - Smoothing / Discounting Techniques: In building language models, data sparsity is a major problem and smoothing can improve the performance. In the extreme case of too much training data where all parameters can be accurately trained without smoothing, one can almost always expand the model such as moving to higher n-gram model. With more parameters data sparsity becomes an issue again, but proper smoothing makes models more accurate than the original ones.

  <p align="center"> <img src="images/di.png" /> </p>

# Contributions

  In Speech Assessment Platform, I have contributed in development of certain components in graphical user interface, pipelining various modules in centralised backend processing server, segmentating speech sentences for calculating Goodness of pronunciation, complete intonation analysis module, and testing the desired working of complete pipeline.

  <p align="center"> <img src="images/ia.png" /> </p>
  
  <p align="center"> <img src="images/uar.png" /> </p>

  In this project, I have studied the effect of discounting techniques such as Witten-bell discounting and Kneser–Ney discounting in language modelling trained with 5500 Human Resource query dataset, which is categorised into 2 sets with 2 different lexicon.
  
  - Dashless: It contains raw sentences which are written queries without any modification.
  - Dashed: It contains modified sentences with clubbed words, to make a single entity. eg: sick leave -> sick-leave, leave without pay -> leave-without-pay etc..
  - Dashed + Questions: It contains dashed dataset appended with certain common question phrases. eg: can I apply, am I eligible, etc..
  - Dashed + Questions + Predicate: It contains 3rd dataset appended with predicates to increase their probabilities of occurring with different clauses. eg: personal-leave to be encashed.
  
  <p align="center"> <img src="images/lm1.png" /> </p>
  
  <p align="center"> <img src="images/lm2.png" /> </p>

_NOTE: There is only limited information regarding the project implementation and no project code here due to TCS confidentiality and Intellectual property rights_