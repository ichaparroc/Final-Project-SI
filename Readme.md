# Sentiment Analysis Using Deep Learning for Spanish Shorts Texts
## Authors: Alvaro Rojas & Israel Chaparro

Paper: https://github.com/ichaparroc/Final-Project-SI/blob/master/paper.pdf

### Test corpus: InterTASS Monolingual PE 2018:
http://www.sepln.org/workshops/tass/2018/task-1/private/evaluation/evaluate.php

|Group                |Macro-P |Macro-R |Macro-F1  |Accuracy|
|---------------------|--------|--------|----------|--------|
|LARMINCC             |0.348   |0.353   |0.350     |0.403   |

http://www.sepln.org/workshops/tass/2018/task-1/private/evaluation/output/LARMINCC-task1-intertass-PE-LSTM4-2019_03_14-10_54_53.txt

# Comparative Analysis

|       | ULMFiT | SIF    | OUR    | 
|-------|--------|--------|--------|
| MODEL | CNN    | MLP    | BI-LSTM|
|              `2017`              |
| ACC   | 0.3951 | 0.2600 | 0.4762 |
| F1    | 0.1946 | 0.1395 | 0.3637 |
|              `2018`              |
| ACC   | 0.3457 | 0.2578 | 0.4540 |
| F1    | 0.2134 | 0.1446 | 0.3515 |
