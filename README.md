# Detecting deepfakes with opencv

Live Project from Manning Publications. 
Oryginal description:

"It has become increasingly easy to automatically replace the face of one person in a video with the face of another person by using a pre-trained generative adversarial network. Recent widely publicized scandals involving celebrity faces and pornography have made people question whether or not this can happened to anyone. Online social platforms are part of the everyday life of many people, making it easy to upload and share personal videos and images. These videos and images can be used to train an adversarial network model that would allow the generation of deepfake videos. That means almost anyone can be the target of a malicious attack by a deepfake video in which they would appear to be talking or behaving in a way that never happened.

Now, a group of criminals is taking advantage of deepfake technology and has organized an online scam that targets young people with large online presences. The criminals first record a video where an actor makes inappropriate comments and behaves in an abhorrent way. Then, they train a adversarial network using images of a target person who has posted many online videos. Using a this model, the criminals replace the face of the actor in their pre-recorded video with target’s face. Then, they blackmail the target with this deepfake video, threatening to send it to relatives, neighbors, and other kids in school. Since it takes less than 20 hours to train such model on one graphics processing unit (GPU), the criminals, renting online GPUs for a couple of dollars an hour, can target many kids at the same time. The scam is spreading online like wildfire.

There have been reports of the scam and, you, as an expert forensics consultant, are recruited to develop a method that can detect these deepfake videos efficiently. The method should also be very fast and run without a GPU, because GPUs are a limited resource that cannot be used to search on such a massive scale. They want to deploy your method to search for deepfakes in a huge set of online videos that social networks (including Facebook, Twitter, and Youtube) have provided.

Your goal is to develop a machine learning-based method that can distinguish between deepfake videos and non-altered original videos in a simple and efficient way. To succeed, you will need to perform the following steps:

  - Get a database of videos that contains both deepfakes and originals. This database will be used to train and test the method.

  - Since your method should be fast and efficient, you decided not to use neural networks, which require GPUs for detecting deepfakes. You need a simpler and a more classical approach. You will analyze and compare the genuine non-altered videos with their deepfake counterparts to find the artifacts that make the difference between them.

  - You will use measures of these visual artifacts for detection.

  - Using these deepfake measures, you will train a support-vector machine (SVM) classifier, which will be the main brain your deepfake detection system.

  - By putting the face detection, feature extraction, and a classifier together in one pipeline, you will create a detection system, which you will then train and evaluate on the downloaded deepfake database.

  - Using such system performance metrics as false accept and false reject rates and ROC curves, you will report the results of the system to demonstrate that your system can perform well."
  
 # The project consists of several main parts:

1. Processing videos and face detection

2. Feature extraction

3. Training the classifier

4. Evaluating the system

Each milestone corresponds to one step above.

