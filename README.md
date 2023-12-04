
# Resume Screening Assistance App

## Overview
This Streamlit-based web application assists HR professionals in the resume screening process. It allows users to upload multiple resumes in PDF format and uses Pinecone, a vector database, to retrieve and display relevant documents based on a provided job description.

## Features
- **Job Description Input**: Paste the job description to which the resumes will be compared.
- **Resume Upload**: Upload multiple resumes in PDF format.
- **Analysis**: The app processes the uploaded resumes, creating embeddings and pushing them to Pinecone for analysis.
- **Results Display**: View a list of resumes ranked based on their relevance to the job description, along with a match score and summary for each.

## Installation and Setup
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Install the required Python packages using `pip`:
    ```bash
    pip install -r requirements.txt
    ```
3. **Environment Variables**: 
    - Create a `.env` file in the root directory.
    - Add your Pinecone API key:
      ```
      PINECONE_APIKEY=your_pinecone_api_key_here
      ```
4. **Running the App**:
    - Run the Streamlit app:
      ```bash
      streamlit run app.py
      ```

## Usage
- Start the application and navigate to the provided local URL.
- Enter the job description in the designated text area.
- Specify the number of resumes you want the app to return.
- Upload the resumes (PDF format only) using the file uploader.
- Click 'Help me with the analysis' to process the resumes.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License
[MIT License](LICENSE)

## Disclaimer
This project is for demonstration purposes only and is not intended for use in production environments.

## Contact
For any queries or feedback, please reach out to [Your Email/Contact Information].

