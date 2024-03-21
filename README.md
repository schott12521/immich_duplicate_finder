# Immich Duplicate Finder

## A Comprehensive Solution for Identifying and Managing Duplicate Photos in Immich

![image](https://github.com/vale46n1/immich_duplicate_finder/assets/36825789/dcb00a2f-947b-4855-bc77-cd6d8dd50537)

The "Immich Duplicate Finder" is an tool designed to seamlessly be integrated with the Immich API, targeting the efficient detection and management of duplicate images through hashing (and future incorporation of machine learning technologies). Leveraging hashing algorithms, this project aims to enhance storage optimization and organization within the Immich ecosystem.

### Features:

- **Highly Accurate Detection:** Utilizes state-of-the-art algorithms to identify duplicates with precision, considering various attributes like metadata, content similarity, and more.
- **Flexible Management Options:** Offers users multiple ways to handle detected duplicates, including auto-deletion, manual review, and archival solutions.
- **Easy Integration:** Designed to be effortlessly integrated with existing Immich installations, ensuring a smooth user experience without disrupting the workflow.
- **Performance Optimized:** Engineered for minimal resource consumption, ensuring fast and efficient duplicate detection even in large datasets.
- **User-Friendly Interface:** Comes with a simple and intuitive interface, making it accessible to both technical and non-technical users, further enriched by the comparison slider for an enhanced visual interaction.

## Getting Started

"Immich Duplicate Finder" is built as a Streamlit app in Python, making it easy to deploy and use with just a few steps. Follow these instructions to get up and running:

### Clone the Repository

Begin by cloning this repository to your local machine. You can do this by running the following command in your terminal or command prompt:

```bash
git clone https://github.com/yourusername/immich_duplicate_finder.git
```

### Install Dependencies

Navigate to the cloned repository's directory and install the required dependencies using the provided `requirements.txt` file:

```bash
cd immich_duplicate_finder
pip install -r requirements.txt
```
This command installs all necessary Python packages that "Immich Duplicate Finder" relies on.

### Launch the App
With the dependencies installed, you can now launch the Streamlit app. Execute the following command:
```bash
streamlit run app.py
```
This will start the Streamlit server and automatically open your web browser to the app's page. Alternatively, Streamlit will provide a local URL you can visit to view the app.

## Initial Configuration

After launching the app, you'll need to complete a simple initial configuration to connect the "Immich Duplicate Finder" with your Immich server:

1. **Specify Immich Server Address:** Upon first launching the app, you'll be prompted to enter the address of your Immich server. This ensures that the "Immich Duplicate Finder" can communicate with your Immich installation.

2. **Generate an API Key:** Next, generate an API key within your Immich app. This is a critical step for authenticating and securing communication between the "Immich Duplicate Finder" and the Immich server.

3. **Enter the API Key into the Program:** Once you have your API key, enter it into the designated field in the "Immich Duplicate Finder" app. This links your specific Immich instance to the duplicate finder.

4. **Data Persistence:** To streamline your experience, the server address and API key are securely saved in a database. This means you won't need to re-enter this information every time you use the app, making future interactions quicker and more seamless.

### Data Security

Your server address and API key are stored securely, ensuring your data remains safe and private. We prioritize your security and privacy, employing robust encryption methods to protect your information.

Enjoy exploring and managing duplicates in your Immich ecosystem with ease! If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.