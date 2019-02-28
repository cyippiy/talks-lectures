# Machine Learning for Modern Javascript Developer  2/27/19
## Lecturer: Suyash Joshi from Oracle

## Interesting Links
* teachablemachine.withgoogle.com

## Big Picture
* AI is composed of three elements
    * Big Data
        * Autonous Database
        * Data Warehouse,
        * Analytics
        * Data Lake
    * Cloud Computing
        * OCI
        * Perf:
        * Cloud Native
    * Neutral Networks
        * OpenSource

## Deep Learning Era
* untrained (neural Network Model)
* training (learning a new capability from exisiting data) - Data Scientists
    * deep learning framework
    * training dataset
* inference (applying this capability to new data) - App Developer
    * trained model (new capability)
    * new data -> trained model
    * app or service (featuring capability)

## Deep Learning Frameworks: App Dev
* started originally on C++
* now has java, python, and Javascript libraries (multiple js one)

## Modern AI Developer Mindset
* Traiditional (Logic First): Imperative Functional Programming Paradigm
* Data First
    * Operations on Data
    * Better Data = Better Accuracy
* AI (Hard Problems): Experimental Approach (Natural Scientist)
    * Observation - Experimentation - Test Cycle for Model Building
    * Artificial Neural Network is the program and the programmer
* It's all Math
    * Statistics: Probability and Approximation
    * Linear Algebra
## Why DL on the Browser (JavaScript) ?
* Advantages:
    * Ubiquitous: Web, Open Platform, Accessible to billions of users
    * Edge / CLient Computing: No complex setup/installation required
    * Edge / Client Computing: Run Offline
    * HTML5 API's: Camera via WebRTC, Sensors, Speech etc
    * High performance: WebGL, WebAssembly*, WebGPU*
* Challenges: 
    * Single Threaded Environment
    * Cross Browser Compatibility
## Machine (Deep Leraning Approaches)
* Supervised Learning
    * classification 
    * regression
* Unsupervised Learning
    * clustering
    * dimensionality
* Reinforcement Learning
## Typical Machine Learning Workflow
    * Define problem
    * Build neural net architecture
    * Collect (or add more) data
    * Train for an epoch
    * is error on training data decresing?
        * yes -> is error on validation data decreasing
        * no ->
    * perform well on training data?

## ML Goal: Improve Cost/Loss Function aka Minimize Error
* Gradient Descent Algorithm
* Parameter Optimization
* Algorithms Efficiency
* Improve DataSets

## Simple Linear Function: Linear Regression Model
* Goal: Predicting a response on Continuous Linear Data order to find the "Best Fit Line"
* Human Brain is like a highly complex, non linear and massively parallel computer

## Probabilistic Interpretation: There is No Black or White
* Optimization
* Generalization
* Data Set

## Tensor Basics
* Tensor Object consists of
    * data type
    * shape
### ML Common Tasks on the Browser
* Classification: assign a category for each item EG email classification
* Regression: predict real value for each item
* Ranking: order items according to some criterions EG google page rank
* Clustering: partition data into homogeneous regions EG Amazon Personalization
* Dimensionality Reduction: Find lower dimensional manifold while preserving some properties of data EG 3D Graphics Models as 2D Vector Images

# Challenges for AI Practitioners
1. Data
    * accessibility
    * quality, integrity
    * distribution (training, validation, test)
    * computation time
2. Algorithms
    * accuracy: overfitting, undercutting
    * miscliassifcation: testing vs validation
3. Ethical
    * biases, morals as decided and judged by AI
    * privacy / consent
    * abuse of power
4. Existential
    * machine consciousness and robot rights
    * transhumanism