# Verizon ThingSpace API Sample Application

Welcome to the Verizon ThingSpace API Sample Application! This interactive application allows you to explore the capabilities of the Verizon ThingSpace API using its official Python SDK.
 - **Create Your Own Application:** Feel free to modify and extend this sample application to suit your needs. The code is open-source and available for you to build upon.

---

## About This Sample Application

This application demonstrates how to use Verizon ThingSpace APIs to manage and interact with IoT devices. It offers a step-by-step workflow to interact with the APIs in both **Sandbox** and **Production** environments.

This application is built using Flask, a lightweight web framework for Python, and utilizes the Verizon ThingSpace SDK to interact with the API. The application is designed to be easy to set up and run locally, allowing developers to quickly test and explore the API's features. Whether you're testing your application or managing live operations, this demo provides a simple and intuitive way to explore key API features which you can use to build your own applications.

This sample application is designed to help developers understand how to interact with the Verizon ThingSpace API using Python. It provides a user-friendly interface to test and explore the API's capabilities, making it easier to integrate into your own projects.

### Key Features

- **Environment Selection:**  
  Choose between:
  - **Sandbox:** For testing purposes with predefined credentials.
  - **Production:** For live operations (no default credentials provided).

- **Access Token Generation:**  
  Generate secure tokens to communicate with the API.

- **API Endpoints Exploration:**  
  Interact with three key API endpoints:
  1. **Start Session:** Initiate a session for managing IoT connectivity.
  2. **Manage Devices:** Query or update device configurations.
  3. **End Session:** Cleanly terminate a session to ensure security and avoid unnecessary charges.

- **Interactive Interface:**
  A user-friendly web interface to call API endpoints.

- **Application Foundation**:  
  Built using Flask and the Verizon ThingSpace SDK, this application serves as a foundation for your own projects.

---

## How to Use This Sample Application

### Step-by-Step Instructions

1. **Select Your Environment:**
   - Choose **Sandbox** for testing or **Production** for live operations.
   - Note: The **Sandbox** environment uses predefined credentials, while the **Production** environment requires your own credentials.

2. **Generate an Access Token:**
   - After selecting an environment, you'll be guided to generate an access token to establish secure API communication.

3. **Explore API Endpoints:**
   - Use the interactive interface to call the three supported endpoints and view their real-time responses.

4. **Modify and Extend:**
   - Feel free to modify the code to suit your needs. This sample application is open-source and can be used as a foundation for your own projects.

---

## Additional Notes

- **Important:** Ensure you have valid credentials for the selected environment. While the **Sandbox** environment comes with predefined credentials, the **Production** environment requires you to input your own.
- This demo provides a hands-on way to familiarize yourself with the Verizon ThingSpace API's functionality, making it easier to integrate into your projects.
- **Documentation:** For detailed API documentation, refer to the [Verizon ThingSpace API Documentation](https://thingspace.verizon.com/documentation/api-documentation.html#/http/quick-start/getting-started-with-the-verizon-api).
- **Security:** Always handle your API credentials securely. Avoid hardcoding sensitive information in your codebase.
- **Best Practices:** Follow best practices for API usage, including rate limiting and error handling.
- **Disclaimer:** This application is for demonstration purposes only. Always follow best practices when handling sensitive information and API credentials.
- **Support:** If you encounter any issues or have questions, please refer to the official Verizon ThingSpace API documentation.
- **Create Your Own Application:** Remember you can use this code as a base to create your own Application!


---

## Ready to Start?

1. Ensure Python is Installed
Verify that Python 3.7 or higher is installed:
`python3 --version` or `python --version`
If Python is not installed, you can check the official Python website for installation instructions.

2. Set Up a Virtual Environment
Create a virtual environment in the project directory:
```bash
python3 -m venv venv
```
Activate the virtual environment:
On macOS/Linux:
```bash
source venv/bin/activate
```
On Windows:
```bash
venv\Scripts\activate
```
3. Install Dependencies
This will install the necessary packages, including the Verizon ThingSpace SDK.
Make sure you are in the project directory where the `requirements.txt` file is located.
Install the required dependencies from requirements.txt:

```bash
pip install -r requirements.txt
```

4. Run the server using the command `python main.py` and start exploring!
Start the Flask server:

```bash
python main.py
```
or
```bash
python3 main.py
```

5. Open Your Browser 
and navigate to:
http://127.0.0.1:5000/

The server will run in debug mode and should be accessible at in your browser to start using the Verizon ThingSpace API demo.

5. Troubleshooting
If you encounter the ModuleNotFoundError: No module named 'verizon' error:
Ensure the sdksio-verizon-apis-sdk package is installed correctly by running the following command:
If not installed, reinstall it using the following command:
`pip install --force-reinstall sdksio-verizon-apis-sdk`
If the issue persists, ensure you are running the application within the virtual environment.

6. Deactivate the Virtual Environment
When you're done testing, you can deactivate the virtual environment by running:
```bash
deactivate
``` 


---

## Create Your Own Application!

Now that you've ran the application, please feel free to modify and extend this sample application to suit your needs. The code is open-source and available for you to build upon. You can use this code as a base to create your own application! Thank you again for taking the time to explore the Verizon ThingSpace API. We hope you find this sample application helpful in your development journey. Happy coding!
