# Human Language Technologies project

Aspect-based sentiment analysis (ABSA) aims to detect the targets, aspects, and sentiment polarities in text. A published dataset from SemEval-2015 reveals that a sentiment
polarity depends on both the target and the aspect. However, most existing methods consider predicting sentiment polarities from either targets or aspects but not from both. Thus
they easily make wrong predictions on sentiment polarities. In particular, where the target is
implicit, i.e., it does not appear in the given text, the methods predicting sentiment polarities
from targets do not work. We propose a method for target-aspect-sentiment joint detection
to tackle these limitations in ABSA. It relies on a pre-trained language model and can capture the dependence on both targets and aspects for sentiment prediction. SemEval-2015
restaurant datasets show that the proposed method achieves high-performance detecting
target-aspect-sentiment triples even for the implicit target cases.
