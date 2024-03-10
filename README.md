# Food Image Classification using Apple's CreateML

### *What is Create ML?*
Create ML is a framework within Apple's Xcode suite that allows developers to
build custom machine learning models directly on their devices. 
It provides a user-friendly interface for various machine learning tasks, including image classification.

### *Image Classification with Create ML:*
Image classification involves training a model to recognize and categorize objects within images.

### *Dataset Used:*
***Food-11 image dataset from EPFL (grouped by ALEKSANDR ANTONOV in kaggle)***
This is a dataset containing 16643 food images grouped in 11 major food categories. 
The 11 categories are Bread, Dairy product, Dessert, Egg, Fried food, Meat, Noodles/Pasta, Rice, Seafood, Soup, and Vegetable/Fruit. 
Out of these 11 classes only 2 classes were used for this project.

Here's a breakdown of the process using Create ML:

- #### *STEP 1:*
  Pre-Processing Data and organizing it into Training and Testing.
  <img width="1032" alt="1" src="https://github.com/BharathK05/Coding-Raja-Internship-Project-2/assets/139679369/dc42eb6e-a69c-4ed5-98db-8a8461e1a937">

- #### *STEP 2:*
  Setup the CreateML environment and locate and load the dataset.
  <img width="1512" alt="2" src="https://github.com/BharathK05/Coding-Raja-Internship-Project-2/assets/139679369/a8bc6656-b1a0-45a1-9698-af7a031e5a3b">

- #### *STEP 3:*
  Click Train and let the model get trained by the dataset.

- #### *STEP 4:*
  Checking the final result accuracy.
  <img width="1512" alt="4" src="https://github.com/BharathK05/Coding-Raja-Internship-Project-2/assets/139679369/3f814336-fe6a-4fdc-8fde-835f5e975b2a">
  <img width="1512" alt="3" src="https://github.com/BharathK05/Coding-Raja-Internship-Project-2/assets/139679369/39bee551-4cb3-41ea-9eb0-a3f39ecbe01a">

- #### *STEP 5:*
  Testing the Model with a Random Image of a Food (here Bread) from Internet and accuracy of it:
  <img width="1316" alt="5" src="https://github.com/BharathK05/Coding-Raja-Internship-Project-2/assets/139679369/76cb6f9d-7d84-4f8c-adf3-a790a51fec2a">
- ***Accuracy:***
  <img width="1468" alt="6" src="https://github.com/BharathK05/Coding-Raja-Internship-Project-2/assets/139679369/2bd78bf1-08bf-4f3c-beb2-444e58a87baf">

  - Here CreateML is 100% confident that this image is bread from the training which we did it before from the Food-11 dataset.
 
### Benefits of using Create ML for Image Classification:
- Ease of Use: Create ML offers a user-friendly interface, making it accessible even for developers with limited machine learning experience.
- On-device Processing: Models can run directly on Apple devices, enabling real-time image analysis without relying on internet connectivity. This also keeps user data private.
- Customization: Create ML allows for customization of the model architecture and hyperparameters for specific use cases.

### Things to Consider:
- Data Quality and Quantity: The quality and quantity of your training data significantly impact the model's effectiveness. Ensure a diverse and well-balanced dataset for optimal performance.
- Class Imbalance: If certain object categories have significantly fewer images compared to others, consider data augmentation techniques to create a more balanced dataset.
- Testing and Refinement: Continuously test your model with new images to identify weaknesses and areas for improvement. You can retrain the model with additional data or adjust hyperparameters to enhance its accuracy over time.



### By leveraging Create ML's capabilities, you can build creative and effective image classification models for various applications within your iOS development projects.



  
  
