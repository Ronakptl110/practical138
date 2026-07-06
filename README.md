# BMI Calculator

## Features
- Enter Age
- Select Gender
- Enter Height (cm)
- Enter Weight (kg)
- Calculate BMI
- Show BMI Category
- Reset Button

## Technologies
- HTML
- CSS
- JavaScript
- Docker

## Run Project

Open index.html in browser.

## Docker Commands

### Build Docker Image
docker build -t bmi-calculator .

### Run Container
docker run -d -p 8080:80 --name bmi-app bmi-calculator

### Pull Image
docker pull <username>/bmi-calculator

### Create Container
docker create --name bmi-container bmi-calculator

### Start Container
docker start bmi-container

### Stop Container
docker stop bmi-container

### Remove Container
docker rm bmi-container
