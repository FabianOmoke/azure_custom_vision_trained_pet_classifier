# azure_custom_vision_trained_pet_classifier

To run the image classification web app on your computer: I have excluded the train images due to huge size (Dataset used OXFORD PET III DATASET)

1. Open a Terminal / Command Prompt (CMD)
2. Use the CMD to navigate to the "src" folder 
e.g. C:\Users\user\path\to\src
3. Use Python from the CMD to create a web server on localhost. This will serve the contents of index.html to the web app
e.g. python -m http.server
4. Open your web browser and enter the following in the URL bar: localhost:8000
5. Click on the "Browser..." button and upload your favorite cat or dog image
6. Click on the "Predict" box and wait for 1-3 seconds to receive the model's predictions.
