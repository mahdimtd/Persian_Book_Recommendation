### Persian Book Recommendation 📚🔎
## Book Recommendation based on description

This project is a Persian-language book recommender system that suggests books based on summaries provided by users. 
By analyzing the summary or a brief description entered by the user, the system leverages natural language processing 
techniques to find and recommend the most relevant Persian books from its database. The aim is to help Persian-speaking 
readers discover new books that closely match their interests or the topics they’re looking for.

# The steps of the work are as follows:
1-Scraping data from www.taaghche.com (title,author,description,cover)

2-Feature engineering and cleaning data.

3-Using langChain framework to facilitate advanced natural language processing workflows

4-Using the **PartAI/Tooka-SBERT-V2-Large** model to convert the data into vector space.

5-Creating dashboard using gradio

------


## How to Run the Project

1. Clone the Repository
First, clone the repository to your local machine

2. Set Up a Virtual Environment (Optional but Recommended)
It's advisable to use a virtual environment to manage dependencies:
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

4. Install Required Packages
Install the necessary Python packages.
pip install pandas numpy Langchain gradio

6. Prepare the Dataset
Ensure that the dataset files (book_extracted.csv, books_db.zip, cleaned_data.csv) are present in the project directory. If the data is compressed, extract it accordingly.

7. Create the Index
Run the creating_index.ipynb notebook to process the data and create the necessary index for recommendations. You can use Jupyter Notebook or any compatible environment to execute the notebook cells sequentially.

8. Launch the Gradio Interface
After creating the index, run the gradio_dashboard.ipynb notebook to launch the Gradio-based user interface. This interface allows users to input Persian book summaries and receive recommendations.

9. Interact with the Application
Once the Gradio interface is running, it will provide a local URL (e.g., http://localhost:7860) in the notebook's output. Open this URL in your web browser to interact with the application.



