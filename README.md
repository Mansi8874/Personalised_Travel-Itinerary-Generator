# Personalised Travel Itinerary Generator
***

Effortlessly plan your dream trip with the Travel Itinerary Generator, your go-to companion for creating seamless travel experiences. Whether it's a road trip, city adventure, or international journey, this powerful tool simplifies every step of the planning process.

## Sample:
https://github.com/Mansi8874/Travel-Itinerary-Generator/assets/62820550/d55374a9-41bd-4454-8c2b-4f037b1f010b


<p align="center">
Make your travel dreams a reality. Start planning your next adventure with the Travel Itinerary Generator today!
</p>
<p align="center">
<i>Explore, discover, and make every trip unforgettable.*</i>
</p>

## Table of Contents

- [Travel Itinerary Generator](#travel-itinerary-generator)
  - [Sample:](#sample)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Limitations \& Future Work](#limitations--future-work)
  - [Features](#features)
  - [Requirements](#requirements)
  - [Setup and Installation](#setup-and-installation)
  - [API Keys](#api-keys)
  - [Usage](#usage)
  - [Screenshots](#screenshots)
  - [License](#license)

## About

Travel Itinerary Generator is a computer program that empowers travelers to effortlessly create personalized travel itineraries. By considering users' interests, budgets, and travel dates, this application generates comprehensive lists of activities, attractions, and accommodations. Whether you're an experienced traveler or a novice, the Travel Itinerary Generator is your key to saving time and ensuring an enriching and well-rounded travel experience.

## Limitations & Future Work
- The Travel Itinerary Generator works only based on the user's source and destination and time of travel.

## Features

- **Weather Forecast:** The Travel Itinerary Generator provides a weather forecast of the destination for the whole travel time.
- **Travel Itinerary:** The Travel Itinerary Generator provides a travel itinerary for the whole travel time in an optimum budget.
## Requirements

- Python 3.11
- Flask
- Flask-SQLAlchemy
- google-generativeai==0.2.2

## Setup and Installation

1. Clone the repository:

   ```shell
   https://github.com/Mansi8874/Personalised_Travel-Itinerary-Generator.git
   cd Personalised_Travel-Itinerary-Generator
2. Install required packages:

   ```shell
   pip install -r requirements.txt
   ```

## API Keys
- Visual Crossing Weather API Key: [Sign up](https://www.visualcrossing.com/weather-api) for a free account and get your API key.
- Google Palm API: [Sign up](https://makersuite.google.com) for a free account and get your API key.

## Usage
- Please follow the instructions below to run the application locally.

Write API keys: In a `.env` file.
```shell
WEATHER_API_KEY='Your Visual Crossing Weather API Key'
PALM_API_KEY='Your Google Palm API Key'
```
and save it in the root directory of the project.

Run the following command to start the application:
```shell
python wsgi.py
```

## Screenshots

**Home Page of Travel Itinerary Generator without Login.**
<img width="1274" alt="Screenshot 2024-10-05 at 5 27 15 PM" src="https://github.com/user-attachments/assets/a295a4b4-3bab-4e57-8e45-b4faed861052">

**Register Page / Sign Up**
<img width="921" alt="Screenshot 2024-10-05 at 5 28 54 PM" src="https://github.com/user-attachments/assets/65388bfe-93f9-4b0c-b91b-f635e7760191">


**Login Page**
<img width="924" alt="Screenshot 2024-10-05 at 5 29 19 PM" src="https://github.com/user-attachments/assets/b21e6355-6174-4e33-91e3-8977410a9e27">


**For Testing, I have taken Source Point as Varanasi & Destination as Mumbai, Starting Date of Journey: 06/11/2023, Return Date: 10/11/2023**
<img width="1175" alt="Screenshot 2024-10-05 at 5 29 48 PM" src="https://github.com/user-attachments/assets/9f660ded-9db0-4552-9b29-acdc0380bada">


**Itinerary Page**
<img width="572" alt="Screenshot 2024-10-05 at 5 30 16 PM" src="https://github.com/user-attachments/assets/ad8b7022-8ba2-4085-998f-f1e13cf133d1">

## License

This project is licensed under the [Apache License 2.0](LICENSE) - see the [LICENSE](LICENSE) file for details.

