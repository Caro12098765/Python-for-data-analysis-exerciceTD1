# Python for data analysis - Exercice TD1

Dataset Kaggle 'COVID19 Tweets' https://www.kaggle.com/gpreda/covid19-tweets

## DATASET READING
Download 'covid19_tweets.csv' and upload it in the jypiter notebook 

```python
tweets = pd.read_csv("covid19_tweets.csv",sep=",")
```

## DATASET DESCRIPTION

count, head, tail, describe, columns, dtypes

## DATASET ANALYSE

### 3 questions
- Quel est le pourcentage de tweet sans hashtag publié entre le 25 juillet et le 30 août 2020 ?
- Quel est le nombre (pourcentage) d'utilisateurs verifiés ayant posté un tweet entre le 25 juillet et le 30 aout 2020 ?
- Quelles sont les 10 plateformes les plus utilisées par les utilisateurs pour poster un tweet ?

### 3 plots
- Quelles sont les 5 plateformes les plus utilisées pour poster un tweet ?
- Quels sont les 5 utilisateurs teweetant le plus ?
- Total of verified users per location

## ANALYSE SUPPLEMENTAIRE
- Emplacement du plus grand nombre l'utilisateurs postant des tweets
- Liste des utilisateurs ayant plus de 20 millions de follower
