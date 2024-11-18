# AMLFinal
This is assignment which were to be completed according to course "Applied Machine Learning"(AML). As you can see, there are two .ipynb file only, that needs to be run. Github_model.ipynb is a model that where found in internet and used as a base for "baseline model". Enhanced model.ipynb is a file that has model which added some adjustment into Github_model.ipynb in order to improve it by any means possible. The dataset used is called "Sign Language MNIST"(link: https://www.kaggle.com/datasets/datamunge/sign-language-mnist) Github model was taken from Mohammedtanseer(path to code: https://github.com/Mohammedtanseer/Real-Time-Sign-Language-Recognition-Using-Machine-Learning/blob/main/Sign_Language.py). 

According to Mohammed, he managed to get "high accuracy of 95.7% for the recognition of the 26 letters of the alphabet". Same couldn't be said to me, as my accuracy were stuck at 85%.
![Screenshot 2024-11-19 023647](https://github.com/user-attachments/assets/4a3a89c4-0a3c-4231-877e-a979e65b9966)

![Screenshot 2024-11-19 023720](https://github.com/user-attachments/assets/a455b76d-9c8a-4cfa-a045-f30644b109fe)

Upon adjustments, such as adding Batch Normalization, changing hyperparameters and adding ImageDataGenerator for Data Augmentation, I was able to reach test accuracy of 93.7%.

![Screenshot 2024-11-19 025202](https://github.com/user-attachments/assets/859f48e7-b76d-4278-99cb-0d308711165a)

Although we had to sacrifice our training accuracy.

![Screenshot 2024-11-19 022631](https://github.com/user-attachments/assets/0116df35-e8d3-42e5-8c69-1f07ae6c4e73)

Also, additionally camera for detection couldn't label the signs correctly, unless the sign was placed perfectly in every aspect(horizontally, vertically, anglewise, shade of light).

![Screenshot 2024-11-19 023834](https://github.com/user-attachments/assets/690add4a-c108-4d44-92cc-627a28f91b9d)

In final run, I achieved much higher model accuracy, where we were allowed a bit more freedom in placement of sign.

![Screenshot 2024-11-19 024027](https://github.com/user-attachments/assets/fe15165a-6947-445e-8369-442ea86857fe)
