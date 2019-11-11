# hackNJIT2019

Developed this Project as part of NJIT Hackathon 2019 (https://www.hacknjit.org/)

Project Title - Healthcare system to monitor Pressure Ulcer Patient(s) data

Inspiration

One of our teammates had read an article online about Pressure ulcer disease. In this disease patients develop bedsores which are injuries to the skin and underlying tissue resulting from prolonged pressure on the skin. Bedsores most often develop on skin that covers bony areas of the body, such as the heels, ankles, hips, and tailbone. People most at risk of bedsores are those with a medical condition that limits their ability to change the positions or those who spend most of their time in a bed or chair. This is our team's attempt to use IoT devices and provide a solution to tackle this disease.

What it does?

We are detecting the pitch roll yaw movements of the patient and keeping track of the position he was in for a certain amount of time. That suggests that the countdown timer has expired for that patient to rest in a particular position and now he/she must change the position in order to stay safe from bedsores.

How we built it?

We used MPU6050 with RaspberryPi over WiFI and connected it to the IoT dashboard to send data through the cloud. We displayed it on to our personal website specifically designed for nurses. Nurses can track the patient movements & duration in that position. This will allow them to be more efficient in serving patients.

As per Google search, every year around 200,000 people die due to pressure ulcer and the solution promises to save the lives of 90% of the patients suffering from Pressure Ulcer. This practice can cure the patients within 2-3 years and they can start to lead a normal life. We used ultrasonic, gyroscope, accelerometer, etc sensors along with Fitbit watch data to detect the patient's movements

Challenges we ran into

• Deployment of FitBit libraries in Azure functions 
• HCSR04 Distance Sensor burnt due to wiring issue 
• Fitbit SDK usage tutorial was not well documented so had a tough time using its API
• Dynamically creating the table in the HTML webpage from the patient reading data (JSON) file received from Cloud.

Accomplishments that we're proud of
We were able to develop a POC for this critical health issue. 
We were able to use IoT devices (sensors) to accomplish this project.

What we learned ?

How to create an Azure function How to trigger Azure function using an HTTP request? 
How to install Windows 10 IoT core in RaspberryPi ? 
How to AJAX to load the JSON data on the webpage in real-time without refreshing the page

What's next for Healthcare System for Pressure Ulcers Patients ?

Notification on the Mobile app (Android/iOS) to the Nurse's phone and patient's relatives/caretaker to change the patient's position.

Built With

ajax
api
arduino
azure
css
fitbit
html
iot
javascript
python
raspberry-pi

DevPost Link - https://devpost.com/software/healthcare-system-for-pressure-ulcers-patients
