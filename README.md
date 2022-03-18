### Table of Contents

1. [Project Overview](#overview)
2. [Installation](#installation)
3. [Instructions](#instructions)
4. [Dataset](#dataset)
5. [Acknowledgment](#acknowledgment)

## Project Overview <a name="overview"></a>

The objective of this project is to generate scripts for the TV series **[Seinfeld](https://pt.wikipedia.org/wiki/Seinfeld)** using Recurrent Neural Networks (RNNs). The network will receive a portion of the show's 9-season scripts and will generate new "fake" TV scripts based on the patterns it learns in training.

It's ok if the TV script doesn't make perfect sense. It should look like alternating lines of dialogue, here is one such example of a few generated lines.
```
jerry: the phone, and the wheelchair who gave me a pen.
jerry: oh, yeah!
kramer: well, i don't want you to get a little too seriously.
elaine:(to the woman) you want to talk about the rest of this thing?
kramer: yeah yeah. i don't know if i was going to have the bathroom.
elaine: oh, no. no, no, no, no. i don't know...
jerry:(to george) you want a look?
elaine: i don't know.(to george) so, uh, i don't know how you could do it.
kramer: i can't believe that i was in love.(george takes his keys and sits in his shoulder)
```

## Installation <a name="installation"></a>

For development, the following dependencies were used:

- torch
- numpy
- pickle

## Instructions <a name="instructions"></a>

1. Clone the repository and navigate to the downloaded folder.
	```	
	git clone https://github.com/gustaph/generate-tv-scripts.git
	```
2. Download the dataset included below in the [Dataset section](#dataset).
3. Open the notebook and run the cells.
	```
	jupyter notebook dlnd_tv_script_generation.ipynb
	```
## Dataset <a name="dataset"></a>

The dataset was taken from [**Seinfeld Chronicles**: Complete Seinfeld Scripts and Episode Details](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv). Additional information and license are available on the website.

## Acknowledgment <a name="acknowledgment"></a>

Must give credit to [**Udacity**](https://www.udacity.com).
