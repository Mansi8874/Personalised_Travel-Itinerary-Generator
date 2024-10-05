# Personalised Travel Itinerary Generator

***

Effortlessly plan your dream trip with the Travel Itinerary Generator, your go-to companion for creating seamless travel experiences. Whether it's a road trip, city adventure, or international journey, this powerful tool simplifies every step of the planning process.

## About

The Travel Itinerary Generator is a user-friendly application that enables travelers to effortlessly create personalized itineraries tailored to their interests, budgets, and travel dates. Ideal for both seasoned explorers and newcomers, this program generates comprehensive lists of activities, attractions, and accommodations, saving you time and ensuring a well-rounded and enriching travel experience.


## Features

- **Weather Forecast:** The Travel Itinerary Generator provides a weather forecast of the destination for the whole travel time.
- **Travel Itinerary:** The Travel Itinerary Generator provides a travel itinerary for the whole travel time in an optimum budget.
  

## Limitations & Future Work

- The Travel Itinerary Generator operates by utilizing the user's specified source, destination, and travel dates.


## Table of Contents

- [Travel Itinerary Generator](#travel-itinerary-generator)
  - [About](#about)
  - [Features](#features)
  - [Limitations \& Future Work](#limitations--future-work)
  - [Table of Contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Setup and Installation](#setup-and-installation)
  - [API Keys](#api-keys)
  - [Usage](#usage)
  - [Sample:](#sample)
  - [Screenshots](#screenshots)
  - [License](#license)


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

## Sample:
https://github.com/Mansi8874/Travel-Itinerary-Generator/assets/62820550/d55374a9-41bd-4454-8c2b-4f037b1f010b


<p align="center">
Make your travel dreams a reality. Start planning your next adventure with the Travel Itinerary Generator today!
</p>
<p align="center">
<i>Explore, discover, and make every trip unforgettable.*</i>
</p>


## Screenshots

**Home Page of Travel Itinerary Generator without Login.**

<img width="718" alt="Screenshot 2024-10-05 at 5 41 04 PM" src="https://github.com/user-attachments/assets/bac77280-7d00-4c49-a1b3-0a5617f175fe">



**Register Page / Sign Up**

<img width="921" alt="Screenshot 2024-10-05 at 5 28 54 PM" src="https://github.com/user-attachments/assets/65388bfe-93f9-4b0c-b91b-f635e7760191">



**Login Page**

<img width="924" alt="Screenshot 2024-10-05 at 5 29 19 PM" src="https://github.com/user-attachments/assets/b21e6355-6174-4e33-91e3-8977410a9e27">



**For testing purposes, I have set the source point as Varanasi, the destination as Mumbai, with a journey starting on 06/11/2023 and returning on 10/11/2023.**

<img width="1175" alt="Screenshot 2024-10-05 at 5 29 48 PM" src="https://github.com/user-attachments/assets/9f660ded-9db0-4552-9b29-acdc0380bada">



**Itinerary Page**

<img width="572" alt="Screenshot 2024-10-05 at 5 30 16 PM" src="https://github.com/user-attachments/assets/ad8b7022-8ba2-4085-998f-f1e13cf133d1">


## License

This project is licensed under the [Apache License 2.0](LICENSE) - see the [LICENSE](LICENSE) file for details.

