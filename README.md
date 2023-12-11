# Course-Recommendation-System
The supplied code constitutes a course recommendation system crafted with Streamlit, a Python framework designed for constructing interactive web applications. This system empowers users to choose courses they have audited or completed and delivers personalized recommendations grounded in distinct recommendation models.

The code encompasses various functions and elements:

Loading Data: The system imports diverse datasets, encompassing ratings, course similarities, user profiles, course genre information, and the bag-of-words representation of courses.

Initializing the App: The __init__recommender_app() function kick-starts the recommender app by loading datasets and enabling users to select courses they have audited or completed through an interactive table.

Training: The system supports the training of diverse recommendation models. Currently, it includes models such as "Course Similarity," "User Profile," and "Clustering." The train() function takes charge of training the chosen model with the specified hyperparameters.

Prediction: Once the model undergoes training, the system generates course recommendations based on the chosen model and user inputs. The predict() function takes the model name, user IDs, and additional parameters as input and yields the recommended courses.

User Interface: The system's user interface is constructed using Streamlit, featuring a sidebar allowing users to select the recommendation model, fine-tune hyperparameters, train the model, and generate course recommendations. The chosen courses, model parameters, and recommendations are showcased in the primary content area.

The code furnishes a rudimentary implementation of the course recommendation system and offers the flexibility to expand with additional models and functionalities. It underscores the integration of Streamlit for constructing interactive web applications and the application of diverse recommendation techniques, such as course similarity, user profiling, and clustering.
