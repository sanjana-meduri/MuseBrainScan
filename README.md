# MuseBrainScan

## Inspiration
There is a huge issue in society where people who are speech impaired (7 million in the US alone) aren't able to communicate effectively.

## What it does
BrainScan gives speech impaired people a voice by converting their brain waves into audible speech.

## How we built it
1. Hardware and Data Processing -- Used the Muse BrainSensing Headset to read brainwaves.
2. Neural Networks -- Used the python keras library to convert brainwaves into readable text.
3. Amazon Web Services -- Used AWS to create an Alexa skill that read out the readable text.

## Challenges we ran into
We only had 1000 data points, which was not enough to effectively train our neural network model on.

## Accomplishments that we're proud of
We got our validation accuracy of the number classification 5% over the baseline.

## What we learned
We learned a lot about Amazon Web Services, specifically about Lambda Functions.

## What's next for BrainScan
We hope to implement the three step process with synchronous communication and have an instantaneous feedback loop.
