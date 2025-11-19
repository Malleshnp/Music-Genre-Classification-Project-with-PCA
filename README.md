

🎯 Objective

primary task is to:

→ Predict the genre of music tracks using Principal Component Analysis (PCA) and Logistic Regression.

To achieve this:

Apply PCA to reduce the dimensionality of the dataset.

Music data contains numerous features, many of which are correlated.

PCA transforms these correlated features into independent principal components, removing redundancy and noise.

Use Logistic Regression as your supervised machine learning algorithm.

After PCA transformation, logistic regression will classify tracks into their respective genres.

The reduced feature space makes the model faster, clearer, and more stable.

This workflow allows you to uncover hidden patterns in musical data and classify songs effectively without requiring deep audio engineering knowledge.

Use PCA (Principal Component Analysis) to reduce the number of features.

Use Logistic Regression to classify music tracks into genres.

Predict the missing genres in the dataset.

Understand how feature reduction helps improve model performance and clarity.

🌟 Principal Component Analysis (PCA)

Music tracks contain many features, and many of them are correlated.
For example:

Rock and Blues may share similar rhythm features

Jazz and Classical may have overlapping tonal patterns

PCA helps by:
✔ Reducing noise
✔ Removing redundant features
✔ Keeping only the most important patterns
✔ Making the dataset easier to use
✔ Improving model speed and accuracy

PCA turns many complex features into a few principal components that still capture most of the information.
