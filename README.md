## Web-based Customer Service Chatbot for Insurance Companies 


![Screenshot 2024-05-18 163410](https://github.com/user-attachments/assets/f02bce73-970c-41c4-b100-ddb3de946dbf)

The chatbot provides customers with quick access to information about insurance policies, such as coverage, premiums, and policy terms. The chatbot guides insurance-related issues and 
responds to frequently asked inquiries regarding insurance services, terms, and procedures.


## System Installation Guide: 

Step 1 - Install Anaconda - Download the Anaconda using this link, and install it.
https://www.anaconda.com/download 


Step 2 - Create a Conda Environment - Open the Anaconda prompt from the start menu and run the following command to create a new environment.

conda create --name myenv python=3.8


Step 3- Activate the Environment - Run the following command to activate the environment.

conda activate myenv


Step 4 - Install these libraries one by one.

Once you activate the environment, install these libraries one by one.

1. pip install tensorflow==2.10.0
2. pip install torch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1
3. pip install scikit-learn
4. pip install matplotlib
5. pip install nltk
6. pip install opencv-python
7. pip install pandas
8. pip install wordcloud
9. pip install seaborn
10. pip install openpyxl
11. pip install transformers


Step 5 - Install XAMP, Compose,  VS code.




## Run the app 

Step 1 - To Connect the Database

Open the XAMPP and start Apache and MySQL modules by clicking the “start” button next to their names. 
Then click on the admin button next to the MySQL module. It will open the MySQL database. After that, import the given database into the AssurancePlus folder.



Step 2 - To Run the application 

After installing the above frameworks, open the project folder and the AssurancePlus folder, and open that folder in VS code. Before running the AssurancePlus, you must start the XAMPP server.
And open insurance-chatbot folder in VS code in a separate window. Before running insurance-chatbot folder, you must activate the Environment using the Anaconda prompt.


Step 3 - In AssurancePlus, open a new terminal and run the following command to run the website.

php artisan serve


Step 4 - In the insuarance-chatbot, Open the 01-agent-executor-basics file.

Step 5 -Activate the environment using the anaconda prompt, run the following command for that,

conda activate myenv


Step 6 - Click on the run all
