INTRODUCTION

The primary objective of this project is to design and deploy a business solution capable of predicting customer behavior by analyzing relevant attributes through an ML pipeline. This solution will suggest marketing promotions optimized based on target market specifications. Business owners, as potential users of this project, can input attributes of their targeted customers for a promotion and receive suggestions for relevant parameters analyzed for that promotion.

![image](https://github.com/user-attachments/assets/3d426eea-5c99-467d-8165-a4c2570a31a8)

Consequently, obtaining the Starbucks loyalty app dataset became the primary focus during this period. The dataset incorporates three separate subsets as follows: portfolio.json, profile.json, and transcript.json. These files collectively provide comprehensive data on customer interactions and transactions, forming a robust foundation for the project's analytical work.

HOW TO USE

To run the python code, you should consider the steps as follows prior to start running the code:

1. Before running the code, please download the ZIP file (JSON_files.zip) in this repository, and extract it to access the .json files.

![image](https://github.com/user-attachments/assets/6bb1218e-7489-44ee-9acc-0e20211cb75a)

2. Now, open the Python code (web_app_15.ipynb) in this repository, and upload the 3 .json files from: Files --> Upload to session storage

![image](https://github.com/user-attachments/assets/0e52d976-7f1e-4a2a-8f9b-8847c0933527)

3. The result will be like this:

![image](https://github.com/user-attachments/assets/32cd2def-5d84-4124-b2d4-74afced1a811)

4. After that, run the whole code, and wait till this step is completed (it takes about 1 minute to run the whole code).

![image](https://github.com/user-attachments/assets/12a23e49-1bdc-4223-8d7c-7b4380fb5d26)

5. Now, the app is ready to use! Please click on the public URL generated in the first part of this document. The application will be ready then in a new window.

![image](https://github.com/user-attachments/assets/cedd72e4-6a50-4a09-bdc4-6c40f1bb4579)

THE ANALYTICS APP

The predictive module in this project is designed with two main layers: The Prediction layer, which clusters customers targeted for a business promotion, and the Suggestion layer, which analyzes customer behavior within that cluster and provides the optimal parameter intervals for the promotion. These parameters guide business owners in designing enhanced marketing offerings tailored to their customers.
