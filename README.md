# Career Recommendation Engine

A local start up asked for a job and skills recommendation engine to help give users an idea of what they can do to change their career.

Text scrubbing and cleaning was followed by TFIDF vectorization to extract relevant text features from user job descriptions and skills. In this case we are comparing the text features between different unique job titles. The job titles are first clustered using agglomerative hierarchical clustering in order to loosely represent industries. A new user is assigned to a cluster using multinomial logistic regression and then recommended job titles from each of the clusters using cosine similarity comparison. We are also able to suggest the most common skills necessary for that job title.

Parts of the code have been purposely left out for legal reasons.

If you would like to see our presentation slide deck see Pitch.pdf above or visit this link: https://docs.google.com/presentation/d/1WVKsxtuPchFBn5foV0bCIa-f6DKy-i_-7MDue69OedU/pub?start=false&loop=false&delayms=3000&slide=id.ge9090756a_1_58
