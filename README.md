
# Wayfarer

# What it does ❓
Wayfarer automates the entire trip planning process by generating a full travel itinerary based on three major prompts entered by the user. The user inputs a sentence including their city of destination, trip dates, and budget. Our program than generates a travel itinerary displayed as a timeline with images and descriptions of the attractions showcased to the user. The user can than drag and drop the timeline as desired to fit their schedules and needs.

# How we built it 🔨
- Front-end was designed and built with React
- API endpoints and request handling was done with FastAPI 
- SerpAPI and Cohere's Entity Extraction API was used for data extraction from user and google

# Try it out 🏗
Set up the repository
```bash
  git clone https://github.com/Sung-En-Huang/Wayfarer-.git
  cd /Wayfarer-
```

Set up the back-end server
```bash
  pip install Flask
  cd /server
  uvicorn main:app --reload
```

Set up front-end client (separate console window)
```bash
  cd /client
  npm install 
  npm start
``` 
## Images/Demo
Link - https://devpost.com/software/wayfarer-qus0gm

<center> <img width="500" alt="Search Bar" src="https://user-images.githubusercontent.com/105095206/218372493-67756440-8876-414d-992c-9a033811f8d9.png"> </center> 

<center> <img width="600" alt="output trip plan" src="https://user-images.githubusercontent.com/105095206/218372458-612f98ca-0e96-450e-bb59-ccfa8be8adbc.png"> </center>


