
# requirements:
- numpy
- scikit-learn
- request
- pycryptodome



Title: AI Data Poisoning Challenge

Description: In this Python-based Capture The Flag (CTF) challenge, participants will be required to perform a data poisoning attack on a machine learning model to compromise its performance.

Challenge Scenario:

You are provided with a Python script that trains a simple machine learning model to classify images of cats and dogs. The script uses a dataset of labeled images for training.

Objective: Inject poisoned data into the training dataset to compromise the model's classification accuracy.

Challenge Steps:

Step 1: Understanding the Model
Review the provided Python script to understand how the machine learning model is being trained. Note the structure of the model, the dataset loading process, and the training loop.

Step 2: Injecting Poisoned Data
Your goal is to inject a small number of poisoned data points into the training dataset. These poisoned samples should be carefully crafted to lead the model to misclassify images.

Step 3: Data Poisoning Strategy
Decide on a data poisoning strategy. You could alter the labels of certain images, manipulate the pixel values subtly, or introduce perturbations that the model would learn from.

Step 4: Implement the Attack
Modify the Python script to include your poisoned data samples during the model training process. Ensure that the poisoned samples are indistinguishable from the original data.

Step 5: Testing the Attack
After adding the poisoned data, run the training script and observe the model's performance. Test whether the poisoned data has successfully compromised the model's accuracy.

Step 6: Flag Retrieval
To complete the challenge, discover the specific flag string that indicates your successful execution of the data poisoning attack.

Flag Format: The flag for this challenge will be in the format "CTF{...}".

Note: This challenge is for educational purposes only and is designed to highlight the potential vulnerabilities of machine learning models. Make sure to follow ethical guidelines and use the provided environment for your experiments. Unauthorized activities outside the scope of the challenge are not permitted.

