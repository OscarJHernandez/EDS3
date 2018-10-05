# EDS3 Project

## Project Task
Dataset: http://host.robots.ox.ac.uk/pascal/VOC/voc2007/  
Task: create a predictive model that solves a learning problem of your choice (classification, localization or segmentation) 
on Pascal VOC dataset. You can use resized images or subset of a dataset in order to reduce the computational complexity. 
 Complete and submit the project until *23:59, 17th of October, 2018".

## Project Specifications  
 
1. A completed project should comprise of the following:  
* A report on the learning problem. The report ideally should answer the following questions:  
* What problem is solved by your intended predictive model? E.g. helping human doctors to avoid mistakes via automation of part of diagnosis.  
* Why is it important to solve your particular problem? E.g. there are currently 10000 patients who are suffering due to misdiagnosis, which is a considerable issue.   
* How is the data representative of the learning problem? E.g. you should not train a cancer prediction model on population of age up to 20 in Germany, but use the model in USA on population above 60.  
* How would the estimations of the model be used? E.g. Shown to the doctor via user interface, program API for developers, etc.  
* What preprocessing did you apply to the data and why? E.g. Removed uninformative columns, as they could lead to overfitting.  
* What classes of learning algorithms you have used, and why? E.g. decision trees, as they can be used through a simple visualization without internet or computer by doctors in rural areas, or linear models, as they allow to gain insights into the "thinking" of learning algorithm, which is important for verification in medical applications.  
* How did you evaluate the learning algorithm? E.g. for financial forecasting, records from 2018.03 to 2018.09 were used for testing, and rest for training, in order to avoid a "Look-Ahead" bias.  

2. A code which can be used to reproduce your results.  
Make sure that your results are reproducible. E.g. if you make everything in a notebook, make sure that if you restart the kernel and run all the cells in notebook, you do not get any mistakes, and you get same results every time. np.random.seed is useful if you wish to fix random number generator.
Please submit code written in Python 3. If this is not possible, contact Iaroslav.Shcherbatyi@dfki.de .

Try to be concise with the code and reports.  
You can submit project as a plaintext .py files and pdf files of report, as a standalone jupyter notebook with report beside code, or as a public Kaggle kernel. If you use Kaggle kernel, make sure that all the datasets that you upload or use are public.  

3. Receive feedback about your project latest on 30th of October, 2018.  
