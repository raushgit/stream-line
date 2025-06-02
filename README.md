
# Stream-Line

Streamline is a machine learning-based movie recommendation system designed to suggest the
most relevant movies based on user-provided keywords. The system utilizes a comprehensive
movie dataset sourced from Kaggle to train its recommendation engine, ensuring that each movie
suggestion closely aligns with user preferences. By harnessing a robust set of technologies—
including NumPy for numerical computation, Pandas for data manipulation, JSONSchema for
data validation, Matplotlib for visual insights, PyArrow for efficient data processing, Pillow for
image handling, Scikit-learn and SciPy for machine learning development, and Streamlit for
building an interactive user interface—Streamline delivers fast, accurate, and intuitive movie
recommendations.
## References

This SRS draws upon multiple documents and resources, including:

(1) Kaggle Movie Dataset Documentation: Detailed information about the source and
structure of the movie dataset.
  
(2) Documentation for NumPy, Pandas, JSONSchema, Matplotlib, PyArrow,
Pillow, Scikit-learn, SciPy, and Streamlit: Official guides and reference materials
that have informed system design choices.

(3) Published Research Papers: Relevant 
literature on recommendation systems and
content-based filtering in machine learning.  

(4) Internal Project Documents: Previous proposals, design reviews, and system
architecture diagrams that helped shape the final product.

This information may be provided by reference to an appendix or to another document.
## Software Interfaces

Required software components include:

• Python 3.8+  
• Required Python libraries: NumPy, Pandas, JSONSchema, Matplotlib, PyArrow, Pillow,
Scikit-learn, SciPy, Streamlit  
• Web Browser: Chrome, Firefox, Edge (latest versions recommended)
## Design Constraints

• Limited Dataset:
The system depends only on the movie data we have from Kaggle. If the dataset is
outdated or missing movies, recommendations might not be perfect.

• Single Language Support:
The system currently works best with English keywords and English movie data.
• Limited Computational Resources:
The system is designed to run smoothly on normal laptops. It doesn’t require highend servers or GPUs.

• Fixed Technology Stack:
We must use the libraries already decided:
(NumPy, Pandas, Scikit-learn, SciPy, Streamlit, etc.).
We can’t randomly add new technologies.

• Real-time Recommendations:
Recommendations should be generated quickly (within a few seconds). So very
heavy or complex models are avoided.

• Streamlit UI Only:
The user interface will be built using Streamlit only — no other web frameworks
like Django, Flask, or React.

• No User Login System:
For now, the system does not have user accounts or profiles — it gives suggestions
based on input only, without saving history.

• Internet Dependency:
If we display movie posters using online URLs, a working internet connection will
be required.
