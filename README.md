# codingTasks

In this program, I used the titanic.csv file to create. a decision tree to predict the survival of passengers on the Titanic.
The programs plots several decision trees (pruned and unpruned) with different parameters to compare their accuracies.
I've plotted a line graph of training and development accuracies and analysed it.
The program, then, highlights the accuracy of the the final model.
In the 2nd part of this coding task, I created a bagged model, a random forest and a boosted model for the Titanic dataset and tuned hyperparameters some parameters, to increase accuracy.
The program aims to determine the featture that contributes the most for passenger survival.
Lastly, the program compares the accuraccy of the models.



Lybrary installation

Run the following code on the terminal.

- Instal PIP:
  - Download PIP: curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
  - Install PIP: python get-pip.py
- Install Pandas: pip install pandas
- Install Numpy: pip install numpy
- Install Matplotlib: pip install matplotlib
- Install Seaborn: pip install seaborn
- Install Scikit-learn on a virtual environment:
  - python -m venv sklearn-env
  - sklearn-env\Scripts\activate
  - pip install -U scikit-learn
- Install Tabulate: pip install tabulate



Usage section

- To run the code, click on the "Run" tab and click on "Run all cells". Proceed to navigate through the code.

Heatmaps analyse correlation between variables:
![Screenshot 2024-06-01 094102](https://github.com/DavSilvs/codingTasks/assets/163030229/285465f3-88ac-4786-ad2c-016f1e6dc3cf)

Confusion matrices help to evaluate model performace:
- ![Screenshot 2024-06-01 094121](https://github.com/DavSilvs/codingTasks/assets/163030229/a3ba34f2-f684-4e25-8c63-6641c3639861)

Decision trees show the end result of the models:
![Screenshot 2024-06-01 094135](https://github.com/DavSilvs/codingTasks/assets/163030229/ba336e7d-5f45-4d5e-aa57-87c7dbe7d5c8)

This lineplot allow to pinpoint the best depth for the model:
![Screenshot 2024-06-01 094147](https:/github.com/DavSilvs/codingTasks/assets/163030229/8d8df52f-01af-4301-9da8-93e1fe7d5872)

Plot of Accuracy vs Alpha for traing and validation sets:
![Screenshot 2024-06-01 094217](https://github.com/DavSilvs/codingTasks/assets/163030229/f8f1b613-5e5f-401f-aaf9-20b9fe6d6359)

Barplot to analyse features by Gini Importance:
![Screenshot 2024-06-01 094243](https://github.com/DavSilvs/codingTasks/assets/163030229/53dd1fbb-81f4-4acb-bc4f-5313c6ce29d9)

Comparing the accuracy of models:
![Screenshot 2024-06-01 094258](https://github.com/DavSilvs/codingTasks/assets/163030229/9096b533-35f9-4e2b-bb92-c0dd17694ad2)




Credits

Author: 
Vitor David Anjos


