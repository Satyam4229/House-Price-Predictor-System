# **House Price predictor system**
The house price predictor system is a machine learning model developed in Python, specifically designed to predict the prices of houses in Boston. The system is trained on historical data of real estate transactions in Boston, including features such as the number of rooms, crime rate, neighborhood demographics, and other relevant factors that impact house prices.

## Here's a general description of the components and steps involved in building the house price predictor system:

1. Data Collection: Historical data on house prices in Boston is collected from reliable sources such as real estate databases or public datasets. The data typically includes various features or attributes that describe each house, such as the number of rooms, crime rate, accessibility to amenities, etc.

2. Data Preprocessing: The collected data is then preprocessed to clean and transform it into a format that can be used for training the machine learning model. This may involve tasks such as handling missing values, normalizing numerical features, and encoding categorical variables.

3. Feature Selection: The most relevant features that impact house prices are selected from the preprocessed data. This step helps to reduce noise and improve the accuracy of the model.

4. Model Selection: A suitable machine learning algorithm is chosen based on the characteristics of the data and the problem at hand. Commonly used algorithms for house price prediction include linear regression, decision trees, random forests, and support vector machines, among others.

5. Model Training: The selected machine learning algorithm is trained on the preprocessed data using a training dataset. The data is divided into training and validation sets to evaluate the model's performance during training and prevent overfitting.

6. Model Evaluation: The trained model is evaluated using performance metrics such as mean squared error (MSE), root mean squared error (RMSE), and coefficient of determination (R-squared), to assess its accuracy and generalization ability.

7. Model Optimization: The model is fine-tuned by adjusting hyperparameters, such as learning rate, regularization strength, and model architecture, to optimize its performance.

8. Model Deployment: Once the model is optimized and meets the desired accuracy threshold, it can be deployed in a production environment to predict house prices for new, unseen data.

9. User Interface: A user-friendly interface is created to allow users to input relevant features of a house, and the trained model uses these inputs to generate a predicted house price.

The above steps collectively form the house price predictor system, which is built using Python and machine learning techniques to predict house prices in Boston.


## Software and Tools Required

1. [Github Account](https://github.com)
2. [Render Account](https://render.com)
3. [VS Code IDE](https://code.visualstudio.com)
4. [Git CLI](https://https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

## Steps to generate whole model and deploment

1. ### Generate model and do the analysis of the model at any platform

2. ### Atlast do the pickling

    ```text
    import pickle

    pickle.dump(model, open('FileName', 'wb')) # To generate the pickle file

    pickle_model = pickle.load(open('FileName, 'rb')) # to load the pickle file
    ```

3. ### create a repository of that model with readme file and gitignore

4. ### Now create a folder in your system, open cmd here and clone that repository there

    ```text
    git clone LINK
    ```

5. ### Now open VS Code from that same location after adding .pynb file and model.pkl

6. ### Create a new Environment

    ```text
    conda create -p venv python==3.7 -y
    ```

7. ### Get into the environemnt by typing

    ```text
    git activate venv/
    ```

8. ### Very Important - Create Requirements.txt where we just write all the libraries

    1. Flask
    2. numpy
    3. pandas
    4. sklearn
    5. scikit-learn
    6. matplotlib
    7. gunicorn

    ```text
    pip install -r requirements.txt
    ```

9. ### Configure your UserName and Email ID

    ```text
    git config --global user.name "name"

    git config --global user.email "email"
    ```

10. ### For adding files into git

    ```text
    git add FileName

        or

    git add .   (For whole files)
    ```

11. ### Checking the git status

    ```text
    git status
    ```  

12. ### After this we have to commit that all

    ```text
    git commit -m "Message"
    ```

13. ### After all that we have to push the files into the github

    ```text
    git push origin main
    ```

14. ### After all that we have to create the app.py app which act as a main app behind all that with the help of Flask.

15. ### Then we have to create a html page for frontend and visualization.

16. ### Now after all that we have to go on to render.com and deploy our app with the instructions.
