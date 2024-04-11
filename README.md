# CSGo Project
![counter-strike](https://github.com/nayanbajpai1/Counter-Strike-Project-Python-/assets/166288028/8650469a-b0a4-4971-b7d9-f2258dc324f3)

- Counter-Strike (CS) is a popular series of tactical first-person shooter (FPS) video games that have been enjoyed by gamers worldwide for many years. The series originated as a modification for the popular game Half-Life and quickly gained its own dedicated following. Here's an overview of Counter-Strike:

### Gameplay Overview:

- Counter-Strike is primarily a multiplayer game where two teams, the Counter-Terrorists (CTs) and the Terrorists (Ts), compete against each other.

- The objective of each round varies based on the game mode, but the primary goals include:

- Counter-Terrorists: Prevent the Terrorists from achieving their objectives, such as defusing a bomb or rescuing hostages. Terrorists: Achieve their objectives, which may include planting a bomb at a designated site or holding hostages. Rounds are relatively short, typically lasting a few minutes, and players have only one life per round. When a player is eliminated, they must wait until the next round to respawn.

# Problem Statement:
- The objective of this project is to utilize Linear Discriminant Analysis (LDA) on a dataset with 97 columns to efficiently reduce its dimensionality and subsequently build predictive models.

- # Steps :
- Imported necessary libraries.
- Conducted data cleaning by handling null values and dropping duplicates.
- Generated a statistical summary of the dataset.
- Performed label encoding for object type data.
- Split the data into train and test sets.
- Split the data into train and test sets for model training.
- Standardized the data.
- Applied Linear Discriminant Analysis (LDA) to reduce the dimensionality of the dataset due to its large number of dimensions. Given the low number of classes, feature selection using LDA was preferred over the conventional method of selecting components based on class separability.
- Checked coefficients to determine important features.
- Extracted the top 22 columns based on coefficient importance.
- Created x_train and x_test datasets according to the important columns.
- Built a logistic regression model.
- Made predictions using the logistic regression model.
- Concluded that the logistic regression model achieved an accuracy of 75%.
- Implemented a random forest model.
- Obtained the same accuracy with the random forest model.
### The project aims to implement Linear Discriminant Analysis (LDA) on a dataset comprising 97 columns to reduce its dimensionality effectively and construct predictive models. This README provides detailed steps outlining data preprocessing, feature selection, model training, and evaluation.





  
