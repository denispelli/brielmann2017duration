## Data Github Repository

This is a public data repository for the manuscript:

Brielmann, A., Vale, L., & Pellli, D. G. (2017) Beauty at a glance. The feeling of beauty and the amplitude of pleasure are independent of stimulus duration. Submitted to Journal of Vision.


denis.pelli@nyu.edu


## How to use

### Collaborate, discuss, and evolve

## Description of data file

allData.m contains the following variables:
- allFinalRating: vector containing 1 final beauty rating (0-3) per trial
- allObjectType: vector encoding the stimulus kind shown on each trial with 1=self-selected; 2=high-valence IAPS; 3=mid-valence IAPS; 4=candy; 5=IKEA furntiture
- allRatings: matrix containing the continuous pleasure ratings for each trial
- allStimDur: vector encoding the stimulus duration for each trial in seconds
- allTimes: exact time stamp for the continuous pleasure ratings allRatings
- rSteady_beautyCat: rSteady values calculated based on parameter estimates derived from average time courses sorted by final beauty judgment
- rSteady_stimType: rSteady values calculated based on parameter estimates derived from average time courses sorted by final stimulus kind
- subjectID: participant identifier number
