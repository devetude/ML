---
description: What is the machine learning?
---

# Machine learning

### 1. Limitations of explicit programming

Some problems have so **many rules** so it is hard to create a program by using explicit programming methods. For example, spam filtering program, automatic driving system, or etc.

In 1959, Arthur Samuel said that '**field of study that gives computers the ability to learn without being explicitly programmed**'.

Therefore, the machine learning means that **we give computers only rules and find them the most perfect solving method themselves**.

### 2. Types of the machine learning

**Supervised learning**: Learning with **labeled examples\(=training set\)**. For example, we give cats and dogs image and labeled data to computers and they classify a image is a cat or a dog. The supervised learning is the most common problem type.

**Unsupervised learning**: Learning with **unlabeled examples**. There is data that it is hard to label. For example, Google news grouping or word clustering.

### 3. Types of the supervised learning

Let's think about a super easy example of student's exam score. We prepared study hours and exam score data. It may like below table.

| x\(=study hours\) | y\(=exam score\) |
| :---: | :---: |
| 10 | 90 |
| 9 | 80 |
| 3 | 50 |
| 2 | 30 |

By using above data, our computer can hypothesize a linear function. And then, we can predict an exam score if a student studied 7 hours. We call these types of problems to **regression**.

We can modify y data to binary cases\(=pass or fail\) like below.

| x\(=study hours\) | y\(=pass or fail\) |
| :---: | :---: |
| 10 | Pass |
| 9 | Pass |
| 3 | Fail |
| 2 | Fail |

By using above data, our computer can hypothesize a point that determines pass or fail. So, we can predict a binary result if a student studied 7 hours. We call these types of problems to **binary classification**.

We can also modify y data to some cases\(=A, B, C, D, or F\) like below.

| x\(=study hours\) | y\(=grade\) |
| :---: | :---: |
| 10 | A |
| 9 | B |
| 3 | D |
| 2 | F |

By using above data, our computer can hypothesize points that determines each grades. So, we can predict a grade if a student studied 7 hours. We call these types of problems to **multi-label classification**.

