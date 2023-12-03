---
title: Creanalytics
draft: false
tags:
  - presentation
date_created: 25 Sep 2023
date_modified: 28 Sep 2023
margin: 0
width: 1920
height: 1200
transition: slide
theme: moon
---

# Creanalytics
### _Between Data Analysis and Media Synthesis_

Dr Daniel Chávez Heras

![[assets/images/db3a81949ab652d55054d76b287e03fa_MD5.jpg|250]]

[@chavezheras@sigmoid.social](https://sigmoid.social/@chavezheras)

[movingpixel.net](https://movingpixel.net/)

note: Thank you for the invitation, delighted to be here.

---

![[assets/images/183e9e0918ae84bbdba0e566dd06a5e7_MD5.jpg]]

note:
A project in 2018 to "machine-see" the BBC television archive, and "machine-edit" new sequences "television by the meter" ―we jokingly referred to it.

Aired on BBC 4 on September 2018, seen by half a million people in the UK.
It included four sections that corresponded to different computational techniques to traverse the archive: including text analysis over subtitled material, object detection, motion estimation (visual energy), and a mixed between the three (what we would call today a multimodal method).

---

<iframe src="https://player.vimeo.com/video/429123167?h=a9f1da53da" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<p><a href="https://vimeo.com/429123167">2. MbM: Object Detection</a> from <a href="https://vimeo.com/chavezheras">Daniel Ch&aacute;vez Heras</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
note:
This was a project in experimental television, in hindsight it was very much of its time, and frankly, as time goes by I am more and more surprised that no one stopped us from doing it. 

In light of everything that happened after with AI, this project stands a somewhat of a quaint expression of many of the issues discussed yesterday, from access and copyright, to the role of generative technologies and their impact on screen culture today.

---


## An epistemic gap between archives and datasets
## A functional proximity between data analysis and media synthesis

note:

In this talk I want to highlight two key insights I gained from this project:

By this I mean the gap between how it is that AI systems contribute to the production of knowledge, what kinds of knowledge, and how this knowledge might be valuable for the understanding of moving images. And how this is radically different from how moving image archives contribute to knowledge and produce value to the societies that keep them.

By this I mean the rather unexpected way in which scientific and creative computing are entangled in generative AI systems.

I will spend a couple of slides on the first point, because I think most of this ground has been covered in one way or another yesterday, and spend some more time on the second premise, including examples.

---


## Archives and Datasets

![[assets/images/eye_film_installation.jpg|1000]]

note: 
Archives are made for humans, datasets are by humans for machines.

Oversimplification: we know machines are made by and for humans too, but still, the purpose of their 

Archives are created under a historical impulse; they are organised according to the record-keeping needs of the cultures that build them. This historical impulse requires system that facilitates cataloguing and retrieval, and that aspires to a certain degree of historical accuracy, integrity, and permanence.

Datasets also respond to the sense-making needs of the cultures that build them, but they come together to lay claim on the future more than the past, usually in response to specific problems and questions that need solving, which is to say they are much more instrumental.

In data science and machine learning engineering, datasets tend to be granular, flattened to matrix-like structures whose individual items are not meant to be publicly accessible or even individually meaningful to human observers.
 
Arguably, contemporary AI has succeeded precisely for not caring at all about whether specific media artefacts are deemed significant enough to go ‘on the record’, and be keept for posterity, with all the cost implications that this kind of collective memory keeping entails, but because of the opposite approach, by voraciously ingesting heaps of data that in themselves were not canonical or significant. 

I would got a step further still, and say that archives and datasets produce value in almost opposite ways: while archives endow their constituent artefacts and records with additional symbolic layers, making them stable and tractable, datasets that feed contemporary AI systems atomise these artefacts, stripping them from context in order to make patterns visible through computational processing. In the first case value is produced by stability and addressability, in the second by aggregation and mutability.

--

## Data palimpsests

| Artefact     | Processing level       | Example                                                     |
|--------------|------------------------|-------------------------------------------------------------|
| Cinema       | Social – aggregate     | Popular Hollywood cinema                                    |
| Film         | Human                  | Jurassic Park (1993)                                        |
| Clip         | Human/computer         | Raptors in the Kitchen Scene (https://youtu.be/dnRxQ3dcaQk) |
| Shot         | Human-computer         | 130 frames (5.421 s)                                        |
| Frame        | Computer/human         | Individual frame (512 × 340 pixels)                         |
| Pixels       | Numeric – disaggregate | Vector ([176800x1]); Tensor ([16, 3, 340, 512])             |

note:

Yet, there is a relation between archives and datasets.
Each of the films contained in a film archive can be thought of a dataset of frames, and every frame as dataset of pixels.  Through computing, individual frames and their pixels can relate much more freely, not only to other frames in the same film, but to a multitude of other frames in a multitude of other films, in high-dimensional spaces where every pixel might be put in contact with any other.

This table exemplifies the palimpsest of artefacts and levels of analysis at play between audiovisual archives, comprised of artefacts, and datasets atomised for machine learning operations. The epistemic gap between the two ends of the table are yet to be fully understood in the configuration of a computational archive.

---

## Data Analysis and Media Synthesis


![[assets/images/CSN_newsreels_1.png|1000]]

note:

Analytic and generative approaches in computing tend to be split between scientific and creative domains, with their respective tools and communities of practice.

Deployed as analytical engines, computers can be used to find patterns across vast collections of imagery, and these patterns are often expressed as relations of proximity in space. We have seen examples of this yesterday in multiple way of projecting archives onto 2d or 3d spaces.

The image in this slide shows a t-SNE mapping of a collection of soviet news reels. The dataset and the tool were developed by colleagues in CUDAN from the cultural data analytics lab in Tallinn, Estonia.

But to amount to knowledge, these spatial correlations require interpretation and explanation, which require relations of necessity, not just proximity, and tend to unfold sequentially, as researchers, critics and users seek to organise these patterns to infer causal relations and plausible reasons for data objects and events to be organised in space the way they are.

By coupling an analytical engine with a generative one, computing can be used to configure narratives about these proximity patterns and enable explanatory propositions through compositional techniques familiar to media scholarship.


--

## Supercuts


>Just as capitalism treated workers as machines as a prelude to workers being replaced by machines, so also supercutters simulate database thinking in apparent anticipation of a moment, perhaps in the near future, when **neural networks will be able to search the entirety of digitized film history and create supercuts themselves, automatically**.

\- Max Tohline, 2021


>In the near future there will be a simple software or app, feeding its algorithm with keywords and other elements of interest, which will **automatically generate a perfect supercut of media content of any kind within a blink of an eye**.

\- Miklós Kiss, 2013

note:

a supercut is an editing technique in which short video clips with common motifs or salient stylistic characteristics are extracted from their original context and are sequenced together in a montage. The commonalities are highlighted through repetition and interpreted by viewers as a form of _aboutness_, which then becomes the thematic content of the supercut.

The supercut entails not simply a mode of editing, but a mode of thinking expressed by a mode of editing.

--

## Computational supercuts


<iframe title="vimeo-player" src="https://player.vimeo.com/video/830237949?h=5fb9301c4d" width="640" height="360" frameborder="0"    allowfullscreen></iframe>

note:
This was made using a tool called VGREP, developed by artist and creative coder Sam Lavigne as part of a small project funded through a small grant I got last year to explore computational media formats.

The tool takes a video file as an input, transcribes its dialogue, and then analyses the text to find common ngrams. These can then selected and edited as a supercut.

The lecture was called "Modeling Doubt, Coding Humility" and through this technique I found there were many more mentions of doubt than of coding or humility (the lecture however was ver good).

I wanted to take this idea a step forward and see if a similar effect could be achieved by operating directly on the images, automating a supercut of visual characteristics.

--

## Movie Clips YouTube channel
 ![[assets/images/e3ee5592f9728d7d204e90a475a2a42f_MD5.jpg]]

note: 
An archive-like collection that is publicly available online: the _Movieclips_ YouTube channel ([2006](https://journals.sagepub.com/doi/full/10.1177/13548565231174592#bibr29-13548565231174592)), which serves as a corpus that is both large and consistent enough to be analysed and intervened using computational methods. 

This channel is operated by the American media company _Fandango_, which owns the popular review aggregator website _Rotten Tomatoes_, and the recommender platform _Flixter_, and which is itself jointly owned by the Warner and Universal media conglomerates. 

In their YouTube channel _Movieclips_ is described as ‘the largest collection of licensed movie clips on the web’. At the time of writing, it had over 58 million subscribers and almost 60 billion aggregated views. 

In terms of access, these numbers dwarf most film archives, but it is important to note that in terms of breadth and diversity, these movie clips are only one deep but thin slice of global film production, namely, recent Hollywood popular cinema licenced by these large media companies.

--

## Movie Clips Corpus

- 2691 clips 
- 350 films
- From 1931 to 2019
- 287 unique directors

--

## Pre-trained FER detection 

![[assets/images/ladybird_FER_1.jpeg|1000]]

--

## Shot scale detector

![[assets/images/schot_scale_detector.jpg|1000]]

--

## Feature Engineering

|Feature|Value|
|:----|:----|
|People|1|
|Scale|23.2|
|Inferred motion|0.24|
|Scale category|‘CU’|
|Inferred motion category|‘Stable’|
|Top emotion|‘Angry’|
|Top emotion confidence|0.79|


--

## Shot duration distribution

![[assets/images/shot_histogram.jpeg|1200]]

note:
conventional statistics give overview of this dataset of shots

--

## Shot scale breakdown

![[assets/images/shot_scale_chart.jpeg|1200]]

note:
more sophisticated tools to do this now, like Cineshot deep learning method to find shot scale in films

--

## Shot emotion breakdown

![[assets/images/shot_emotion_chart.jpeg|1200]]

note:
the obvious caveats of this is the simplification of emotions to few categories, an approach that has been criticised and widely updated in psychology.

--
## shot scale supercut
<iframe src="https://player.vimeo.com/video/602000956?h=71ac4fdc22" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<p><a href="https://vimeo.com/602000956">Big Angry Faces v.01</a> from <a href="https://vimeo.com/chavezheras">Daniel Ch&aacute;vez Heras</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

note:
On the one  hand the computational supercut involves applying computer vision methods to annotate large collections of moving images to find patterns, much in the guise of cultural analytics. 

But on the other, as well as plotting these images in space to view them at a distance, to make sense of them we need to reinscribe these patterns in time, giving data objects a duration again, and enabling interpretation through the familiar operations of montage and the syntactic and synoptic apparatus of (dis)continuity as a modality for meaning making and explanation. 

The kind of reverse editing proposed in the computational supercut links in this way analytical and creative epistemic strategies: knowledge and value created through the making and unmaking of moving imagery; visual culture that feeds AI that feeds back into visual culture.>)

--

![[assets/images/computational_supercuts.png|1200]]


note:

I have experimented further with this type of parametric sampling/editing, and some of these experiments can be found online. If there is enough interest I might develop the technique further and might distribute it as a tool that can be used in other collections.

--

## Continuity Matrix (Noël Burch)

| **Time**/**Space** | **Continuous** | **Ellipsis (definite)** | **Ellipsis (indefinite)** | **Time reversal (definite)** | **Time reversal (indefinite)** |
| ------------------- | -------------- | ----------------------- | ------------------------- | ---------------------------- | ------------------------------ |
| Continuous          | CC             | CE                      | CEi                       | CR                           | CRi                            |
| Contiguous          | CtC            | CtE                     | CtEi                      | CtR                          | CtRi                           |
| Discontinuous       | DC             | DE                      | DEi                       | DR                           | DRi                            |


note: 
But we know we make sense of images not only by what is shown on screen, but by what is omitted. Arguably, films convey as much meaning through time elision than they do through time recording.

Therefore, in order to model a “computational Burch” we need both the edit points that separate one shot from the next _and_ an annotation of what viewers infer to be in-between the shots. This second signal is much more elusive because it needs to be encoded form a subjective unconscious process that appears to leave no traces.

--

![[assets/images/godfather_continuity.png]]

--

![[assets/images/burch_continuity_1.png]]

--

![[assets/images/burch_continuity_2.png]]


note:
Note that while the patterns above reflect the parallel editing technique in this sequence, they are not representations of the shots themselves, but of the relations between them as inferred by a viewer; the subjective invisible that makes the objective visible meaningful.

---

# Moving image archive of the future

- Create and recreate the archive
- Play the archive


note:
- Structurally similar to a system of systems
- Accessed through narrative forms of interaction
- Shaped and reshaped on demand
	- access different versions of the archive, and simulate what might have been under different circumstances
	- play (reproduce) the archive, as if it were a larger form of media




---

![[assets/images/book_and_article_2.png]]

note:

