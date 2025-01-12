# AugARC - Augmented Abstraction and Reasoning Corpus

This repository contains the source code for producing the augmented ARC datasets, training LLMs and testing them on the AugARC Benchmark.

The AugARC provides is easy and unified benchmark to evaluate LLMs on 3-shot accuracy on reasoning tasks. In AugARC, each ARC task starts with a textual description explaining the format of the problem. Each ARC grid is represented as a 2D matrix of numbers.

In AugARC, the first prediction is based on a normal ARC task, whereas the second and the third ones are 90° and 270° clockwise rotated versions of the same task. The AugARC benchmark is tailored towards LLMs’ architecture, as those models process inputs in an auto-regressive, sequential manner. By rotating the ARC tasks, LLMs are presented with a different sequence of numbers (2D matrices) which contain the same abstract logic.

Transformations on an ARC task to obtain its Augmented ARC variants are visualised below.

- base ARC task
  ![770cc55f_base](https://github.com/user-attachments/assets/f7410738-9237-4481-9bb3-74ac43614311)
- 90° rotated task
  ![770cc55f_90](https://github.com/user-attachments/assets/c14af79d-dcc8-42d9-9c1d-b3b0c796628b)
- 270° rotated task
  ![770cc55f_270](https://github.com/user-attachments/assets/f076714b-5c8a-4a59-909b-aa57e9ce9bb5)






