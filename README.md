# Internship-Project

Objective:

To build a classification model that classifies side effects of a particular drug by Age, Race and Gender.

Introduction:

For this project, a dataset of WebMD sourced from Kaggle has been used. As this dataset lacked ‘Name’ and ‘Race’ features, the two were randomly generated using Faker Python Module and then concatenated with it. The master dataset featured 14 columns and 362806 rows.

The dataset used for classification include reviews, conditions etc. of different users of the drugs. These can be analysed to find side effects of drugs with the help of machine learning algorithms. Here, the machine is trained with data using various algorithms. After training, the machine predicts the output against unseen inputs. Supervised machine learning classifiers are used in building the model and fitting the data into the model. 

Dataset description:

•	Name: Name of the patient

•	Race: Race of the patient

•	Age: Age of the patient

•	Condition: Condition/symptom from which the patient is suffering

•	Date: Date of usage

•	Drug: Name of the drug

•	DrugId: Identity/code of drug

•	EaseofUse: Patient's 10-Star rating on the ease of use of drug

•	Effectiveness: Patient's 10-Star rating on the effectiveness of drug

•	Reviews: Patient's review

•	Satisfaction: Patient's 10-Star rating on satisfaction

•	Sex: Gender of the patient

•	Sides: Side effects of the drug

•	UsefulCount: Number of users who found the review useful

Conclusion:

Created a dataset with 14 columns and 362806 rows. Performed various pre-processing steps and obtained a clean dataset for exploratory data analysis and modelling. Various visualizations were done on the dataset and selected a particular drug Topamax. Maximum users consume this drug for migraine prevention. 

The best classification model was obtained by fine-tuning hyper parameters of Random Forest Classifier. On performance evaluation, maximum accuracy of 58.06% has been achieved.

By race, Whites topped in the usage of this drug with a higher female ratio. Domination of female users were consistent across age groups above 12 and below 75 years. Also, people in the age groups 35 to 44, 45 to 54 and 25 to 34 accounted for maximum usage of Topamax. Most users found Topamax as highly effective, especially females. Most rated it highly for its ease of use as well. Side effects of the drug proved race neutral. Genderwise, side effects proved extreme in females.


