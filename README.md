# business-analytics-Mastering-Data-in-Excel-week2

Bombers and Seagulls confusion matrix - 

This file was an introduction to binary classification and the confusion matrix. When we have binary outcomes and a binary classification, 
we can be right in two different ways and we can be wrong in two different ways. If the true condition is the thing that we are trying to identify, 
in the case of the radar image, the true bombers. And we correctly classify an event as positive, this is known as a True Positive. On the other hand, 
if we correctly identify a condition as nothing to be worried about, this the seagull or some other blotch on our radar that does not have any particular meaning, 
we are classifying something as negative and it is a True Negative. The idea that we're trying to communicate is that our binary classification system involves 
something that generates ratings. Ratings that can be turned into rankings, to which we can apply a threshold. Then everything above the threshold is going to be 
declared positive, and everything below the threshold is going to be declared negative.


Binary performance metric lab -

In this lab, we turned to another example of binary classification and this one is a typical kind of distribution for a cancer diagnostic. It is a protein blood test
that identifies a rare type of cancer and has an incidence in the population we are studying of 1%. This means before people walk into the doctor's office and take the test there is a 1% chance they have the cancer and a 99% chance they don't.

TOTAL # OF POSITIVE TESTS = .2075
TOTAL # OF NEGATIVE TESTS = .7925
TRUE POSITIVES = .0095
TRUE NEGATIVES = .198
FALSE NEGATIVES = .0005
FALSE POSITIVES = .792
TRUE POSITIVE RATE = 95%
TRUE NEGATIVE RATE = 80%

The true positive rate is the conditional probability of having a positive test, if one has the condition, cancer. 
The true negative rate is the probability of having a negative test if one does not have the condition, however that is not actually what we would want to know. What we would want to know is something a little bit different. We would want to know what is the conditional probability? What is the conditional probability that we have the condition
if we have a positive test? Or, what is the probability that we don't have the condition if we have a negative test. These two conditional probabilities have special names because they come up all the time. One is called positive predictive value of the test. One is called the negative predictive value.

POSITIVE PREDICTIVE VALUE = TRUE POSITIVES / TOTAL # OF POSITIVE TESTS = 4.58%    So if I receive a positive test, what that is telling me is that I have a 4.58% chance of having cancer. 

NEGATIVE PREDICTIVE VALUE = TRUE NEGATIVES / TOTAL # OF NEGATIVE TESTS = 99.937%     =    100% - 99.937% = .063% chance of having cancer. 

