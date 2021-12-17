<img src='https://upload.wikimedia.org/wikipedia/commons/7/77/Logo_HEC_Lausanne.png' width="250">

# Data Mining and Machine Learning Project : Team Nestle
## *Topic: Detecting the difficulty level of French texts*<br><br>
------------------------------------------------------------------------------------------------------------------------- 
### *Project Description:*<br><br>

Our semester project is about **predicting the difficulty of a French text regarding the norms A1-C2**. 
This can be useful for universities or courses aiming at giving language courses.
So, to achieve this goal, first, we have trained different models (such as Linear Regression, KNN, Decision Tree, Random Forest, etc.)
without cleaning any data,to find the best. Second, with the best model, we have done some cleaning and improvements to optimize the accuracy.
We won't tell you more, just follow us on the adventure!

------------------------------------------------------------------------------------------------------------------------- 
### *Team Members:*<br><br>

 <img src='https://media-exp1.licdn.com/dms/image/C4E03AQENgU7XBBwQAg/profile-displayphoto-shrink_200_200/0/1604746692682?e=1643846400&v=beta&t=6zG4C4tpfufYKRMC-Cd2vX6qTyWCx9T38YfipqgWsr0' width="150">
 
 #### Alexandre Bonicel, user name: Alex314159265, e-mail: alexandre.bonicel@unil.ch
    I am Alexandre Bonicel, I come from Bretagne (France). I am an exchange student for one term, and I study Actuarial Science.
    I like boats, traveling, meeting new people and of course Data Mining!
    
    
<img src='data/IMG-0449.JPG' width="170"> 
 
#### Karel Gloria Sidnomwendé Kaboré, user name:KKGS06, e-mail: karelgloriasidnomwende.kabore@unil.ch 

   
    I am Karel Kaboré, I come from Burkina Faso (West Africa), but I am studying at Lyon. I am an exchange student like 
    Alexandre, and we come from the same school and the same class.I like reading, traveling, and challenges!


<img src='data/WhatsApp Image 2021-12-12 at 19.01.02.jpeg' width="170"> 

#### Nathalie Fröhlich, user name:NFroehl, e-mail: nathalie.frohlich@unil.ch 


### *Results obtained without cleaning:*<br><br>



|                     | Logistic regression |       KNN        |   Decision Tree      |   Random Forest     |Doc2Vec with Log Reg|
| ------------------- | ------------------- |----------------- | -------------------- |-------------------- | -------------------|
| Precision           | 0.4430              | 0.3507           | 0.4229               |  0.4236             |  0.7506            |
| Recall              | 0.4425              | 0.3462           | 0.3990               |  0.4277             |  0.7481            |
| F1-Score            | 0.4366              | 0.3438           | 0.3967               |  0.4248             |  0.7486            |
| Accuracy            | 0.4448              | 0.3479           | 0.4010               |  0.4313             |  0.7479            |
