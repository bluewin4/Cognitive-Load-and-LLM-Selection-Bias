# Compensatory Biases Under Cognitive Load: Reducing Selection Bias in Large Language Models
by Jonathan Eicher and Rafael Irgolič

http://arxiv.org/abs/2402.01740

## Graphical Abstract
![graphical_abstract](https://github.com/bluewin4/Cognitive-Load-and-LLM-Selection-Bias/assets/47462814/6d57577c-073a-4523-b03a-5b0a642b66f9)
The two data collection methods used in this paper: a two-step method which separates the sample step and guard rail, and a direct guard rail method which combines them into a single step. Each method is annotated with its relative cognitive load and bias as a result of the method.


## Abstract: 
Large Language Models (LLMs) like gpt-3.5-turbo and claude-instant-1.2 have become instrumental in interpreting and executing semantic-based tasks. Unfortunately, these models' inherent biases, akin to human cognitive biases, adversely affect their performance. Particularly affected is object selection from lists; a fundamental operation in digital navigation and decision-making. This research critically examines these biases and quantifies the effects on a representative list selection task. To explore these biases, we conducted a series of controlled experiments, manipulating temperature, list length, object identity, object type, prompt complexity, and model. This enabled us to isolate and measure the influence of the biases on selection behavior. Our findings show that bias structure is strongly dependent on the model, with object type modulating the magnitude of the effect. With a strong primacy effect, causing the first objects in a list to be disproprotionately represented in outputs. Furthermore the usage of guard rails, a prompt engineering method of ensuring a response structure, can increase bias and decrease instruction adherence when combined with a selection task. The bias is ablated when the guard rail step is separated from the list sampling step, lowering the complexity of each individual task. The implications of this research are two-fold, practically providing a guide for designing unbiased LLM applications and theoretically suggesting that LLMs experience a form of cognitive load compensated for by increasing bias. 
