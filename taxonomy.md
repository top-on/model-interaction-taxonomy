# A taxonomy of user interfaces with predictive models

### Author
Thorben Jensen

## Introduction to model interfaces
Predictive models are becoming increasingly useful and important.
This is because they have recently become increasingly capable.
Also, their surging acceptance and use make them more important.

A crucial property of predictive models is the way humans can interact with them.
Good interaction is key to making them useful for us humans.
A negative example would be interaction that creates unnecessary overhead,
which overall might render interacting with a model worse than not using it.
In contrast, we want to interact with models in *just the right* way.

It turns out that in different contexts, different *model interfaces* are better.
Assume the usage of weather prediction models.
You might either prefer a dashboard with detailed weather parameters for today.
Or you might only want your door knob to remind you of bringing an umbrella.
Given this range of design options, it is important to know which ones are available.
Hence this work.

<!-- Quote by Dix et al (1992): "Human computer interaction can be defined as the discipline concerned with the design, evaluation, and implementation of interactive computing sstems for humand use ..." -->

## Purpose: taxonomy of model interfaces
We would like to assist at choosing the right interfaces to predictive models.
Also, this review shall assist designing new model interfaces.

This work works towards this in two steps:
Initially, design properties of model interfaces are presented.
Given these properties, interfaces to predictive models are then reviewed.
Finally, this review is summarized in a *taxonomy of model interfaces*.

## Criteria of interface comparison
Comparing existing interfaces is guided by the following binary design properties:

1. Is data for improvement generated?
2. Is user addressed actively and timely?
3. Required skillful user?
4. Detailed insights?
5. Does deployment require webserver?
6. Is human-human cooperation facilitated?
7. Do working examples exist?

## Review of interfaces with predictive models

In the following, types of model interfaces are presented.
For each type, the questions above are addressed.

**Brain-computer interface**
(e.g. Elon Musk's company Neuralink)

**Chatbots.**
(e.g. chatbots for customer support)

**Command Line Interface (CLI).**
(e.g. terminal output from a Python script)

**Content filtered by predicted preferences.**
(e.g. online shop recommendations, Facebook stream)

**Control interfaces.**     --- other description?
(e.g. Google Nest)

**Conversation with human analyst.**
(e.g. presentation by analyst who directly used model)

**Dashboards.**
(e.g. 'Shiny App' with R)

**Input-heavy expert systems.**
(e.g. crime predictions for individual inmates)

**Haptic interaction.***
(any example?)

**Standardized reports.**
(e.g. generated PDF, graphics, API responses - both on demand or scheduled)

**Smart daily objects.**
(e.g. a tooth brush, but smart and responsive)

**Spreadsheets.**
(e.g. Excel)

**Text notifications.**
(e.g. emails/messages on events, e.g. predicted rain)

**Virtual/augmented reality.**
(e.g. virtually flying through your data warehouse, including recognition of gestures)

**Voice interfaces.**
(e.g. Cortana)

<!-- TODO. read up on technology for soldiers -->

## Model interaction taxonomy
...

Ideas:

* show t-sne plot on binary vectors that represent criterions
* grouping by hierarchical clustering

Potential sources:

* [Fiebrink 2011][fiebrink2011real]
* http://grouplab.cpsc.ucalgary.ca/saul/hci_topics/taxonomy.html
* https://eprints.soton.ac.uk/261149/1/GestureTaxonomyJuly21.pdf
* [A Brief History of Human Computer Interaction Technology](https://s3.amazonaws.com/academia.edu.documents/30932899/myers-history-hci-tech.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1509979386&Signature=Sbr2EzbKfcylDdxNU9EW7WFJ1hs%3D&response-content-disposition=inline%3B%20filename%3DA_brief_history_of_human-computer_intera.pdf)

## Conclusion
...

### Acknowledgements
Thanks for feedback to Chris Davis.

<!-- References -->
[fiebrink2011real]: http://edithlaw.ca/cs889/2015/reading/IML/2013AIMagIML.pdf
