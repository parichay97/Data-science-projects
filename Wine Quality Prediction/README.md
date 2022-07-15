# Wine Quality Dataset

### Introduction

Wine is an alcoholic beverage made from fermented grapes. Yeast consumes the sugar in the grapes and converts it to ethanol, carbon dioxide, and heat. It is a pleasant tasting alcoholic beverage, loved cellebrated . It will definitely be interesting to analyze the physicochemical attributes of wine and understand their relationships and significance with wine quality and types classifications. To do this, We will proceed according to the standard Machine Learning and data mining workflow models like the CRISP-DM model, mainly for:

- Predict if each wine sample is a red or white wine.
- Predict the quality of each wine sample, which can be low, medium, or high.

The dataset are related to red and white variants of the "Vinho Verde" wine. Vinho verde is a unique product from the Minho (northwest) region of Portugal. Medium in alcohol, is it particularly appreciated due to its freshness (specially in the summer). This dataset is public available for research purposes only, for more information, read Cortez et al., 2009. . Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

### Attribute Information:

1. fixed acidity - Primary fixed acids found in wine are tartaric, succinic, citric, and malic
2. volatile acidity - Volatile acidity is the gaseous acids present in wine.
3. citric acid - It is weak organic acid, found in citrus fruits naturally.
4. residual sugar - Amount of sugar left after fermentation
5. chlorides - Amount of salt present in wine
6. free sulfur dioxide - So2 is used for prevention of wine by oxidation and microbial spoilage
7. total sulfur dioxide
8. density
9. pH - In wine pH is used for checking acidity
10. sulphates - Added sulfites preserve freshness and protect wine from oxidation, and bacteria
11. alcohol -  Percent of alcohol present in wine</br>

Output variable (based on sensory data):</br>
12. quality (score between 0 and 10)

### UCI Notes About the Dataset:

- The classes are ordered and not balanced (e.g. there are munch more normal wines than excellent or poor ones).
- Outlier detection algorithms could be used to detect the few excellent or poor wines.
- Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

### Source of the data: [Wine Quality Dataset](https://www.kaggle.com/datasets/rajyellow46/wine-quality)
