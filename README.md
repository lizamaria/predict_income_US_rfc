*to predict the income of every US citizen?*
to discuss and implement various ways to get a correct prediction from a machine learning model

### Must-have features

- Baseline accuracy
- Multiple evaluation metrics
- Hyper parameter tuning
- Some time of validation strategy

### Miscellanous information

The datasets `data_train.csv` and `data_test.csv` have already been downloaded (and cleaned) for you in here:

- [../../../additional_resources/datasets/US Income/cleaned/data_train.csv](../../../additional_resources/datasets/US%20Income/cleaned/data_train.csv)
- [../../../additional_resources/datasets/US Income/cleaned/data_test.csv](../../../additional_resources/datasets/US%20Income/cleaned/data_test.csv)

Also, make sure to check the README files for the attribute information :

- [README 1](../../../additional_resources/datasets/US%20Income/README.md)

 - 48842 instances, mix of continuous and discrete (train=32561, test=16281) 45222 if instances with unknown values are removed (train=30162, test=15060)
 - Duplicate or conflicting instances : 6
 - Prediction task is to determine whether a person makes over 50K a year.
 - People with similar demographic characteristics should have similar weights. There is one important caveat to remember about this statement. That is that since the CPS sample is actually a collection of 51 state samples, each with its own probability of selection, the statement only applies within state.
 
age: continuous.

workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

fnlwgt: continuous. final weight. In other words, this is the number of people the census believes the entry represents

education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

education-num: continuous.

marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

sex: Female, Male.

capital-gain: continuous.

capital-loss: continuous.

hours-per-week: continuous.

native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.


- [README 2](../../../additional_resources/datasets/US%20Income/cleaned/README.md)


### Constraints

- You must use `RandomForestClassifier()` from `sklearn`. We want you to focus on model evaluation, not on the model choice nor on the data preprocessing.
- Create **functions**, do **not** create a single huge script
- Each **function or class** has to contain a docstring in a [consistent format](https://stackoverflow.com/a/24385103).
- Your code should be **commented**.
- Your code should be **cleaned of any commented unused code**.

## Deliverables

1. Publish your source code on the GitHub repository.
2. **Small presentation (5 minutes) about your findings**
3. Pimp up the readme file:
   - What, Why, When, How, Who.
   - Pending things to do
   
## Bibliograf

http://cseweb.ucsd.edu/classes/sp15/cse190-c/reports/sp15/048.pdf

receiving operating characteristic
   