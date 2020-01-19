# HandWriting Recognition

## Digit Recognition
0-9 

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.92     |
| Random Forest       | 0.95     |
| Multinomial NB      | 0.84     |
| ANN                 | 0.97     |
| CNN                 | 0.98     |

**ANN Architecture**

784 -> 1024 (relu) (0.2) -> 32 (relu) (0.2) -> 10 (sigmoid)

**CNN Architecture**

(28,28,1) -> 32 Conv2D (3,3) (relu) (0.2) -> Flatten -> 128 (relu) (0.2) -> 10 (sigmoid)

## Alphabet-Digit
0123456789 ABCDEFGHIJKLMNOPQRSTUVWXYZabdefghnqrt

**CNN Architecture**

(28,28,1) -> 32 Conv2D (3,3) (relu) -> MaxPool2D(2,2) (0.2) -> Flatten -> 128 (relu) (0.2) -> 47 (softmax)

Accuracy 85.99%