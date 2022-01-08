# Notes Prototype 0

Toxicity measure, with message "I hate you"
Testing with hand picked "positive words" no punctuation

|word count | before | behind |
|-----------|--------|--------|
| 0 | 0.951 | n.a | n.a |
| 1 (joy) | 0.868 | 0.867 |
| 2 (joy kind) | 0.867 | 0.828|
| 3 (joy kind happy) | 0.863 | 0.802 |
| 8 (joy happy kind love good awesome amazing beauty) | 0.559 | 0.356 |
| 4 repeated words (good good good good) | 0.732 | 0.453 |

## Preliminary Findings
Testing on [unitary/toxic-bert hosted API](https://huggingface.co/unitary/toxic-bert) transformer based method, indicates adding words to the end of a message increase obfuscation of intent.
