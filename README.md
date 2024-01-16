# Lab 1: Hello Streamlit

## Goal

The goal of this lab is to build a personal website using Streamlit and deploy the website to Azure App Services.

## Instructions

### Streamlit App

1. **Create a New GitHub Repository:**
   - Create a new GitHub repository for your Streamlit app.

2. **Clone the Repository:**
   - Clone the newly created repository to your local machine.

3. **Create a Streamlit App:**
   - Develop a Streamlit app for your personal website.
   - Refer to the [Streamlit Documentation](https://docs.streamlit.io/) for guidance.

4. **Update .gitignore:**
   - Add the following lines to your `.gitignore` file:

     ```bash
     venv
     *.pyc
     ```

5. **Add Requirements:**
   - Create a `requirements.txt` file with the following content:

     ```bash
     # requirements.txt
     streamlit
     ```

6. **Set Up Virtual Environment:**
   - Activate a virtual environment and install the required dependencies:

     - **Windows:**
       ```bash
       python -m venv venv
       source venv/Scripts/activate
       pip install -r requirements.txt
       ```

     - **Mac:**
       ```bash
       python -m venv venv
       source venv/bin/activate
       pip install -r requirements.txt
       ```

7. **Build Your Personal Website:**
   - Use [Text elements](https://docs.streamlit.io/library/api-reference/text) and [Media elements](https://docs.streamlit.io/library/api-reference/media) to create sections for:
     - A profile picture
     - About
     - Education
     - Work Experience
     - Hobbies and Interests
     - Interesting Projects

### Azure

1. **Log into Azure Console:**
   - Log in to the Azure console.

2. **Create a Resource Group:**
   - Create a new Resource Group in the region `West US`.

3. **Create App Service:**
   - Go to App Service and create a new App Service with the following details:
     - Name: `<uw username>-techin510-lab1`
     - Resource Group: Use the one created in step 2
     - Region: West US
     - Plan: Create a new one with the F plan (free).

   

4. **Open App Service:**
   - Open the newly created App Service.


   - Click "Deployment > Deployment Center".
     - Connect to your GitHub account.
     - Connect to your GitHub Repository for Lab1.
     - Click "Save" (This will make a new commit and push to your repo).


   - Click "Settings > Configuration".
     - In "Application settings", click "New application setting" to add the following setting:
       - PORT → 8501

## Example

If you want to see an example, check out [this GitHub repository](https://github.com/ianchen06/techin510-lab1).

## Contributing

If you'd like to contribute to this project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


