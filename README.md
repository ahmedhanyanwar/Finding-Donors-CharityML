# Data Scientist Nanodegree  
## Supervised Learning  
### Project: Finding Donors for CharityML  

### Overview  

This project is my customized version of the **Finding Donors for CharityML** project, completed as part of my Data Scientist Nanodegree. Using supervised learning techniques, I built a predictive model to identify potential donors for CharityML, a fictional nonprofit organization. The goal was to use a modified census dataset to accurately classify individuals likely to donate, optimizing model performance and interpretability.  

### Installation  

This project requires **Python 3.x** and the following libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

To execute the code, an installation of [Jupyter Notebook](http://jupyter.org) is also necessary. An easy way to obtain all required packages is by installing [Anaconda](https://www.anaconda.com/products/individual), a pre-packaged distribution of Python that includes these libraries and Jupyter Notebook.

### Code  

The project is implemented in the `finding_donors.ipynb` Jupyter Notebook. Additionally, the project uses two supplementary files: 
- `visuals.py` - for data visualization functions.
- `census.csv` - containing the dataset used to train and evaluate the models.

### Run  

To run this project, navigate to the project's directory in your terminal and use one of the following commands:

``` bash
jupyter notebook finding_donors.ipynb
```

### Data

The project utilizes a modified version of the census income dataset, containing about 32,000 data points with 13 features each. This dataset is based on the original dataset from the paper, *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid"* by Ron Kohavi. You can access the original dataset [here](https://archive.ics.uci.edu/ml/datasets/Census+Income).

### Features

- **age**: Age  
- **workclass**: Working Class  
  - (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- **education_level**: Level of Education  
  - (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- **education-num**: Number of educational years completed  
- **marital-status**: Marital Status  
  - (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- **occupation**: Work Occupation  
  - (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- **relationship**: Relationship Status  
  - (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- **race**: Race  
  - (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- **sex**: Sex  
  - (Female, Male)
- **capital-gain**: Monetary Capital Gains  
- **capital-loss**: Monetary Capital Losses  
- **hours-per-week**: Average Hours Per Week Worked  
- **native-country**: Native Country  
  - (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinidad&Tobago, Peru, Hong Kong, Holand-Netherlands)

### Target Variable

- **income**: Income Class  
  - (<=50K, >50K)

### Model Results

In my customized implementation, the following results were achieved:

- **Final Model trained on full data**
  - Accuracy on testing data: 0.8485
  - F-score on testing data: 0.7118
- **Final Model trained on reduced data**
  - Accuracy on testing data: 0.8446
  - F-score on testing data: 0.7020


### License

Copyright © 2012 - 2020, Udacity, Inc.

Udacity hereby grants you a license in and to the Educational Content, including
but not limited to homework assignments, programming assignments, code samples,
and other educational materials and tools (as further described in the Udacity
Terms of Use), subject to, as modified herein, the terms and conditions of the
Creative Commons Attribution-NonCommercial- NoDerivs 3.0 License located at
[http://creativecommons.org/licenses/by-nc-nd/4.0](http://creativecommons.org/licenses/by-nc-nd/4.0) and successor locations for
such license (the "CC License") provided that, in each case, the Educational
Content is specifically marked as being subject to the CC License.

Udacity expressly defines the following as falling outside the definition of
"non-commercial":
(a) the sale or rental of (i) any part of the Educational Content, (ii) any
    derivative works based at least in part on the Educational Content, or (iii)
    any collective work that includes any part of the Educational Content;
(b) the sale of access or a link to any part of the Educational Content without
    first obtaining informed consent from the buyer (that the buyer is aware
    that the Educational Content, or such part thereof, is available at the
    Website free of charge);
(c) providing training, support, or editorial services that use or reference the
    Educational Content in exchange for a fee;
(d) the sale of advertisements, sponsorships, or promotions placed on the
    Educational Content, or any part thereof, or the sale of advertisements,
    sponsorships, or promotions on any website or blog containing any part of
    the Educational Material, including without limitation any "pop-up
    advertisements";
(e) the use of Educational Content by a college, university, school, or other
    educational institution for instruction where tuition is charged; and
(f) the use of Educational Content by a for-profit corporation or non-profit
    entity for internal professional development or training.

THE SERVICES AND ONLINE COURSES (INCLUDING ANY CONTENT) ARE PROVIDED "AS IS" AND
"AS AVAILABLE" WITH NO REPRESENTATIONS OR WARRANTIES OF ANY KIND, EITHER
EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT. YOU
ASSUME TOTAL RESPONSIBILITY AND THE ENTIRE RISK FOR YOUR USE OF THE SERVICES,
ONLINE COURSES, AND CONTENT. WITHOUT LIMITING THE FOREGOING, WE DO NOT WARRANT
THAT (A) THE SERVICES, WEBSITES, CONTENT, OR THE ONLINE COURSES WILL MEET YOUR
REQUIREMENTS OR EXPECTATIONS OR ACHIEVE THE INTENDED PURPOSES, (B) THE WEBSITES
OR THE ONLINE COURSES WILL NOT EXPERIENCE OUTAGES OR OTHERWISE BE UNINTERRUPTED,
TIMELY, SECURE OR ERROR-FREE, (C) THE INFORMATION OR CONTENT OBTAINED THROUGH
THE SERVICES, SUCH AS CHAT ROOM SERVICES, WILL BE ACCURATE, COMPLETE, CURRENT,
ERROR- FREE, COMPLETELY SECURE OR RELIABLE, OR (D) THAT DEFECTS IN OR ON THE
SERVICES OR CONTENT WILL BE CORRECTED. YOU ASSUME ALL RISK OF PERSONAL INJURY,
INCLUDING DEATH AND DAMAGE TO PERSONAL PROPERTY, SUSTAINED FROM USE OF SERVICES.

