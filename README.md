# Dog Breed Recognition Algorithm

## Table of Contents
- [Project Information](#project-information)
- [About Data](#about-data)
- [About Models](#about-models)
- [About Results](#about-results)
- [Running the Code](#running-the-code)
- [Conclusion](#conclusion)
- [Folder Structure](#folder-structure)

## Project Information

**Participants:** Andreea Lazarescu and Mihaela Moldovan

**Course:** Intelligent Modeling

**Year of the Class:** 2022-2023

**Group:** Data Science Group 245

## About Data

The dataset used in this study comprises a diverse collection of dog photos, encompassing several breeds, and it originates from the [Kaggle competition](https://www.kaggle.com/c/dog-breed-identification). The dataset was carefully curated to ensure representation of different dog breeds, variations in position, illumination, and occlusion. The dataset plays a crucial role in evaluating the effectiveness and accuracy of the dog breed recognition algorithm.

## About Models

The dog breed recognition algorithm utilizes cutting-edge methodologies, including convolutional neural networks (CNNs) and deep learning architectures. The following models were employed in the study:

- InceptionV3
- Xception
- InceptionResNetV2
- NASNetLarge

An ensemble approach was adopted to combine the predictions from multiple models, leveraging their diverse strengths and improving the overall accuracy and robustness of the classification system.

## About Results

The performance of the dog breed recognition algorithm was evaluated using various evaluation metrics, including precision, recall, and F1-score. The algorithm exhibited high accuracy in recognizing individual dog breeds regardless of their position or size in the image. However, challenges were encountered when identifying multiple breeds in the same image. The results highlighted the algorithm's versatility and effectiveness in real-world scenarios, even with the presence of other objects or people in the image.

| Evaluation Metric | Score |
|------------------|-------|
| Accuracy         | 0.93  |
| Precision        | 0.9465  |
| Recall           | 0.95  |
| F1-Score         | 0.9303  |

## Running the Code

To run the dog breed recognition code, follow the steps below:

1. Open the **Training_Testing.ipynb** notebook.
2. Execute the notebook to train and test the algorithms on the provided dataset.
3. Once the training and testing are complete, gather your test data in a zip file.
4. Open the **Results_Benchmarking_Dog_Breeds.ipynb** notebook.
5. Once you have the test data adjust the file paths in the notebook to match your test data.
6. Execute the notebook to benchmark the accuracy and performance of the algorithm using the custom test data.

Please note that the code has been separated into two notebooks, allowing each participant to test the algorithm with different files and at their own discretion.

## Conclusion

In conclusion, this research explored the domain of dog breed recognition algorithms and assessed their efficacy for real-world applications. The ensemble of multiple models, including InceptionV3, Xception, InceptionResNetV2, and NASNetLarge, demonstrated superior performance compared to using a single model. The algorithm achieved accurate breed recognition and showcased versatility in real-world scenarios.

While the algorithm excelled in recognizing individual breeds, challenges remained in identifying multiple breeds in the same image. Nevertheless, the results emphasized the algorithm's effectiveness and potential market demand in various fields, such as pet adoption, veterinary clinics, and canine research.

The research findings provide a foundation for the development of precise and efficient dog breed recognition algorithms, catering to the needs of dog lovers and pet-related enterprises. Future research can explore improvements in ensemble strategies and address privacy concerns to ensure ethical implementation.

## Folder Structure

1. **Source Code** - This folder contains the Jupyter notebooks used for training and testing the dog breed recognition algorithm and benchmarking the results.
   - *Training_Testing.ipynb* - Jupyter notebook for training and testing the algorithms.
   - *Results_Benchmarking_Dog_Breeds.ipynb* - Jupyter notebook for benchmarking the accuracy and performance of the algorithm.
2. *Doggo_project.pdf* - PDF file of the PowerPoint that was shown during our presentation.
3. *DS__Intelligent_Modelling_Project.pdf* - Research Paper for this project.
