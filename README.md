# challenge_Idoven
David's solution to Idoven's challenge for the job offer Data Scientist

The steps we are going to carry out are as follows:

1. The basic functions requested by Idoven

* Be able to read the ECG files and the corresponding annotations.
* Show how they will work on the signal and plot the signal in a way suitable to be read by a clinician

* Identify the beats in the signal, the average and total beats in the signal
* Identify the QRS complex in the signal and be able to annotate it.

2. Section for the free development

*Classify ECG signals between myocardial infarction and control patients, developing a classification method and taking advantage of the 15 leads integrated into the record. The implemented solution aims to use Fully connected neuronal networks (NN) to solve the classification task.

* The results after training with 448 records and each one with 15 leads and 32000 samples are 91% accurate. Spite of the results showed future lines are proposed for the improvement of the task.

3. Lessons learned

There are different approaches when we work with ECG signals that open up the possibility to solve the problems from different points of view. In this solution, we applied Deep Learning algorithms for the compound of the 15 leads giving as good results as machine learning techniques. This opens up the possibility to treat the signals as 2D images, allowing us to integrate powerful algorithms. 

The solution was fully developed on Google Colab.
