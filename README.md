# Using_Retinal_Images_Predict_EyeDiseases

## About the project:
1. In this projet I have detected eye diseases using retinal images. The model will predict an output from the following classes:
```
Normal, Cataract, Diabetic Retinopathy, Glaucoma
```
2. The model will also give us a confidence level.
3. The model is made using CNN.
4. I have used FastAPI and ReactJS to build the web app.
5. [Downlaod the Dataset](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification)

## Software and Tools Requirements:
1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

## Setup:
1. Open VS Code. Clone this repo. Install Python.
2. Change the current directory to api.
3. Activate the venv environment using ```activate venv``` and execute the given command:
```
pip install -r requirements.txt
```

## Setup for ReactJS:
1. [Install Nodejs](https://nodejs.org/en/download/package-manager/)
2. [Install NPM](https://www.npmjs.com/get-npm)
3. Install Dependencies (change current directory to frontend)
```
npm install --from-lock-json
npm audit fix
```

## To run the web app follow the steps:
1. Do all the setups given above in this readme file.
2. Open command prompt.
3. Change the current directory to frontend.
4. Run the following command: ```npm run start```
5. The web app will start automatically. (But it'll not work. We need to perform a few more steps!)
6. In the vs code terminal, in your environment 'venv' run the following command: ```python main.py```
7. Refresh the webapp and Predict the Retinal Images!!

## For any queries, contact me at:

1. [EMail](mailto:anuragpacholi2000@gmail.com)
2. [LinkedIn](https://www.linkedin.com/in/anurag-pacholi)
