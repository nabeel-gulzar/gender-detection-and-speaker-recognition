# multinomial-logistic-regression

A project that aims to solve following two problems:

## Gender Detection
using the multinomial logistic regression, we tried to detect the gender of the speaker. MCFF features of the voice were used as the input. All the weight vectors are managed using numpy. The last layer uses the softmax activation and then after computing the gradient, we update the weight matrix repeatedly until minimal error is acheived.
## Speaker Recognition
using the multinomial logistic regression, we tried to recognize the speaker. There are total of 170 speakers. This problem also uses MCFF features of the voice as the input.
