# AIYA
AI Internship July Business Leaders Ideathon

# Team Name: GROUP 8

Team Members:
- Aneesh    
- Arhan
- Devyani
- Om
- Sooraj
- Yajvin


| Title | Industry |
|-------|----------|
|Harvest of Artificial Intelligence: AI's notable importance in the agriculture sector| AI in Agriculture |

## Introduction

The industry of agriculture is focused on the extensive, intensive production of crops and domestication of animals. Artificial Intelligence is revolutionizing the [agrarian world](https://en.wikipedia.org/wiki/Agrarian_society) by replacing traditional methods by using methods that are more effective and yielding.    

## The Role of AI in the Industry

[Artificial intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) has been burgeoning in the field of agriculture with its potential applications in cultivating healthier crops, managing pests, monitoring soil and growing conditions, analysing data for farmers, enhancing other management activities of the food supply chain. Artificial intelligence further betters the conventional methods used in the filed of agriculture with its adaptability, precision, speedy performance, ability to do repetitive tasks, and cost viability.

---

# AI Application Case Study:

## The Problem

The problem we aim to provide a solution to is the suffering endured my several farmers due to plant diseases and pests in their crops which affect their harvest and produce  which, in turn, affects their livelihood and forces them into a more dire and severe situation.

## The Solution

### Describe your proposed AI-based solution

Our business idea is to create a solution that can detect and diagnose diseases, pests, malnutrition in plants, identify weeds. It aims to use various models of [machine learning](https://en.wikipedia.org/wiki/Machine_learning) to help in helping reduce the overall spread of plant diseases by detecting their issues earlier so that they can be treated effective immediately.

*Flora Sage* is an avant-garde mobile application designed to revolutionize the agricultural sector enabling gardeners, farmers, and plant enthusiasts to effortlessly identify diseases and defects in their plants. Powered by advanced Convolutional Neural Network (CNN) technology, this app provides accurate and efficient plant diagnosis, along with suitable suggestions for treatment and care.

### Target Market

Our target market will be farmers, companys assosciated with farm produce, agricultural service providers, government bodies assosciated with the agricultural sector within their respective territories, sustainable agriculture organizations, etc.

## Analysis of the Solution

The Flora Sage app presents a comprehensive and innovative solution to the common problem of identifying diseases and defects in plants. By leveraging advanced CNN technology, the app offers users a convenient and accurate means of diagnosing plant ailments and providing suitable suggestions for treatment and care.

##  Future Scope

The true beauty of Flora Sage lies in its ability to continuously improve and enhance its diagnostic capabilities. As more people utilize the app and contribute their plant images for defect analysis, leverages this collective data to further train and refine the AI algorithms. Through a process known as "indirect training," the app learns from real-world examples and evolves its understanding of plant diseases and defects, ultimately leading to more accurate diagnoses and tailored recommendations in the future.

# Conclusion

Flora Sage is not just an app; it's a game-changer in the world of agriculture. By harnessing the power of artificial intelligence, specifically Convolutional Neural Networks, Flora Sage empowers farmers, gardeners, and plant enthusiasts to detect and diagnose diseases, pests, and malnutrition in plants with unmatched accuracy. The app provides timely suggestions for treatment and care, enabling early intervention and reducing the overall spread of plant diseases.

# Sample of Defining Architecture of CNN Model

```json
import tensorflow as tf
model = tf.keras.Sequential([
    tf.keras.layers.Conv2D(32, (3, 3), activation='relu', input_shape=(image_height, image_width, channels)),
    tf.keras.layers.MaxPooling2D((2, 2)),
    tf.keras.layers.Conv2D(64, (3, 3), activation='relu'),
    tf.keras.layers.MaxPooling2D((2, 2)),
    tf.keras.layers.Conv2D(128, (3, 3), activation='relu'),
    tf.keras.layers.MaxPooling2D((2, 2)),
    tf.keras.layers.Flatten(),
    tf.keras.layers.Dense(64, activation='relu'),
    tf.keras.layers.Dense(num_classes, activation='softmax')
])
```

# References

- [Application of Artificial Intelligence in detection of diseases in plants: A Survey](https://turcomat.org/index.php/turkbilmat/article/view/1581/1335)

- [Understanding the potential applications of Artificial Intelligence in Agriculture Sector](https://www.sciencedirect.com/science/article/pii/S277323712200020X)

- [Artificial Intelligence in Agriculture](https://www.wipro.com/holmes/towards-future-farming-how-artificial-intelligence-is-transforming-the-agriculture-industry/)

- [Industrial Agriculture 101](https://www.nrdc.org/stories/industrial-agriculture-101#:~:text=Industrial%20agriculture%20is%20the%20large,the%20animals%20are%20not%20sick)
