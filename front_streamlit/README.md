# The user interface

In the <b>front_streamlit</b> package, create a simple user-interface in the app.py file using Streamlit framework. The code below includes:

- A title for the UI
- A short description of the project
- Six interactive elements the user will use to input information about a car
- Class values returned by the API
- A submit button that, when clicked, will send all data collected from the user to the machine learning API service as a post request and then display the response from the model

The only framework required for this service is Streamlit. In the <b>requirements.txt</b> file, note the version of Streamlit to install when creating the Docker image.

Add the <b>Dockerfile</b> to create the docker image for this service
