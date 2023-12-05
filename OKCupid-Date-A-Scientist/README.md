# OKCupid-Date-A-Scientist

There are popular apps that enable their users to meet other people and find love. Because they provide vast information about users and their preferences, they are ideal candidates for user experience optimization using Machine Learning. Sophisticated data science techniques can be used to recommend possible matches with high compaatibility.

This project will analyze data from OKCupid, an app that focuses on using multiple choice and short answers to match users.

The findings and details of the can be found in the notebook named `date-a-scientist.ipynb`.

### Recommendation engine
The Machine Learning model built in this project outputs suggestions using a _collaborative filtering_ algorithm. The approach of this kind of algorithms relies on the assumption that if two users like similar things and make comparable decisions, they will agree on future commitments and thus build rapport. For example, if a user wants to have pets, it is very likely that the user will get along with another one that also likes pets.

### Dataset
Consists of anonymous information gathered from questions asked to users of OKCupid. All questions are optional, and their answers yield structured data such as age, gender, orientation and education, the dataset also includes unstructured text derived from open-ended questions.
