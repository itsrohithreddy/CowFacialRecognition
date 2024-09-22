# Cow Facial Recognition

## Overview

The **Cow Facial Recognition** project aims to streamline cattle management by leveraging facial recognition technology. The project focuses on differentiating cows based on their unique facial features, particularly muzzle patterns, using deep learning techniques. By analyzing muzzle images of cows, this project develops a unique identification system similar to AADHAAR, providing an efficient and scalable solution for managing cattle.

## Key Features

- **Siamese Neural Network**: A deep learning model using Convolutional Neural Networks (CNN) was implemented to differentiate cows based on their muzzle patterns.
- **Unique ID System**: Inspired by the AADHAAR system, a Unique ID is assigned to each cow based on its facial features, making cattle management more efficient.
- **Accurate Facial Recognition**: Achieved an impressive **95% validation accuracy** in recognizing cows from their facial patterns.

## Motivation

Traditional cattle management practices rely on manual identification methods such as ear tags or branding or microchipping, which can be invasive(harmful) and prone to errors. This project offers an innovative approach by using facial recognition to identify cattle non-invasively, enhancing the accuracy and ease of managing large herds.

## Use Cases / Real-Time Applications

The Cow Facial Recognition system can be used in various real-world scenarios to improve cattle management and provide crucial benefits to farmers and livestock owners. Some of the potential applications include:

- **Insurance for Livestock**: In the event of natural disasters or unforeseen circumstances leading to the death of cows, the system can be used to identify and verify the ownership of deceased cows for insurance claims. This ensures that farmers receive timely compensation based on accurate identification.
  
- **Cattle Management in Dairy Farms**: The system can maintain a separate database for each cow, starting from birth. This database can track the cow's health, breeding history, and production data. If a cow falls sick, the data can be used to analyze patterns and provide early diagnosis and treatment, improving overall herd health.

- **Tracking and Monitoring**: The unique identification system allows for precise tracking and monitoring of cows within large farms, ensuring that each animal's activities, diet, and health are tracked over its lifetime.

- **Efficient Breeding Programs**: By identifying cows with desirable traits, farms can implement more effective breeding programs, selecting for genetic traits that improve milk production, disease resistance, or other valuable characteristics.

## Dataset

- The project utilized muzzle images of **268 unique cows**.
- Each cow was represented by multiple images, which were processed and fed into the model for training.

## Results

- Achieved a **95% validation accuracy rate** in cow identification.
- The Unique ID system significantly improved cattle management efficiency by providing a reliable and non-invasive identification method.

## Setup


Follow the steps below to set up and run the application on your local machine:


1.Clone the repository: git clone https://github.com/itsrohithreddy/CowFacialRecognition.git


2.Install dependencies: pip install -r requirements.txt


3.This project uses **MongoDB** as the database to store information about the cows, such as their Unique ID, health records, and other metadata.


4.Ensure MongoDB is installed locally on your machine. You can download it from [MongoDB's official website](https://www.mongodb.com/try/download/community).


5.Start the MongoDB service on your local machine by running the following command: mongod


6.Navigate to frontend_backend directory from the present working directory.


7.Run the application: python app.py


8.Access the application in your web browser at http://localhost:5000.

