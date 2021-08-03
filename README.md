# Drug-recommendation-system
## Why this system ?
Since coronavirus has shown up, inaccessibility of legitimate clinical resources is at its peak, like the shortage of specialists, healthcare workers, lack of proper equipment and medicines. Due to unavailability, people started taking medication independently without appropriate consultation, making the health condition worse than usual. So, we need a system that can drastically reduce specialists heap. Tired of waiting in a queue? Too weak to go down and buy medicines? This system provide exhaustive information to choose your medicine, can consult with doctor as well and order the medicine online.
## What this system provide?
We make these sections easy to navigate within the module, enhancing clinical decision support, as a result, reducing decision fatigue and medication administration errors.
System that uses patient reviews to predict the sentiment which can help recommend the top drug for a given disease by different classification algorithms with great accuracy.
## Features
- Predict disease from symptoms
- Recommend medication 
- Patient-centric drug usage and safety information
- Scenarios in which patients should consult a doctor
- Better health insights for patient education
- Chat module to consult with doctor 
- Appointment with verified doctor
- Nearest hospital that facilitate the patient 
- Cart and payment
## Application of ML and DM:
More than 42% medication errors are caused by doctors because experts write the prescription according to their experiences which are quite limited.
Applications of machine learning and data mining can change the available data to valuable information that can be used for recommending appropriate drugs by analyzing symptoms of the disease. In this work, a machine learning approach for multi-disease with drug recommendation is proposed to provide accurate drug recommendations for the patients suffering from various diseases. This approach generates appropriate recommendations for the patients suffering from cardiac, common cold, fever, obesity, optical, and ortho, etc.
## We know the limitations:
We are aware of that this recommendation system will not be 100% accurate since we are not specialist to say one medicine can indeed be recommended instead of another, nor can an performance test be conducted at this time. In addition, there is the limitation on data avabliable, for instance, there is no patient information, true diagnosis, cost of medicine, etc.
our model is thought as a basis in the right direction, and with more data, the better the recommendation can become.
## Approach:
Supervised machine learning approaches such as Support Vector Machine (SVM), Random Forest, Decision Tree, and K-nearest neighbors were used for generating recommendations for patients. The experimentation and evaluation of the study was carried out on a sample dataset created only for testing purpose and is not obtained from any source (medical practitioner). This experimental evaluation shows that the Random Forest classifier approach yields a very good recommendation accuracy of <b>96.87%</b> than the other classifiers under comparison. Thus, the proposed approach is considered as a promising tool for reliable recommendations to the patients in the health care industry.

## Steps:
1) Data preparation 
2) Modeling
3) Evaluation
4) Recommendation

<br>
Applied standard Data preparation techniques like checking null values, duplicate rows, removing unnecessary values, and text from rows in this research because Machine learning algorithms can’t work with text straightforwardly.

## How to accomplish more Accuracy:
After evaluating all the models, the prediction results:
<br>
- Perceptron
- LinearSVC 
-	LGBM
-	Random Forest
<br>
was   added   to   give combined  model  predictions.  The  main  intention  is  to  make sure  that  the  recommended  top  drugs  should  be  classified correctly by all four models. If one model predicts it wrong, then the drug’s overall score will go down.

score of each drug = Predictions * normalized useful count

The overall score is divided by the total number of drugs per condition to get a mean score,  which is the final score 





