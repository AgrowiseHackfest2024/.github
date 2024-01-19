# FortisFortunaAdiuvat

FortisFortunaAdiuvat is a group of people consisting of the best civilians on earth. We are an undergraduate student from Bandung Institute of Technology. FortisFortunaAdiuvat consists of 4 members :

- Abraham Megantoro Samudera
- Adrenalin Apprizal
- Ahmad Rizki
- Lie, Kevin Sebastian Sheva Tjahyana

Together, we are eager to make impactful changes in the world.

---

# AGROWISE

## About
Agrowise is an innovative agricultural platform that connects consumers with farmers implementing sustainable farming practices through the Community Supported Agriculture (CSA) concept. Consumers can choose farmers they want to support based on profiles and reviews. The application facilitates seed purchases and manages direct deliveries to farmers. Consumers can follow the progress of their farms through updates and photos from farmers, promoting transparency. During harvest, consumers and farmers celebrate the results together, strengthening engagement in sustainable agriculture.

## Features
1. Choose Farmers: Agrowise makes it easy and efficient for consumers to choose farmers.
2. Purchase Seeds: Agrowise facilitates seed purchases and manages direct deliveries to farmers.
3. Online Payments: To simplify transactions, we have included an online payment system. Consumers can pay directly through this platform.

## How to use
1. Access the Application: The Agrowise application has been successfully deployed and can be accessed at https://agrowise-hackfest-2024.vercel.app/
2. Simulate Payments: For payment simulation, you can use the [Midtrans Payment Simulator](https://simulator.sandbox.midtrans.com/) .

## Repository

There are 3 Repositories
- [agrowise-fe-hackfest](https://github.com/AgrowiseHackfest2024/agrowise-fe-hackfest)
- [agrowise-be-hackfest](https://github.com/AgrowiseHackfest2024/agrowise-be-hackfest)
- [agrowise-ml-hackfest](https://github.com/AgrowiseHackfest2024/agrowise-ml-hackfest)

## Running locally in development mode

### Frontend
1. git clone https://github.com/AgrowiseHackfest2024/agrowise-fe-hackfest.git
2. npm install
3. npm run dev

### Backend

1. git clone https://github.com/AgrowiseHackfest2024/agrowise-be-hackfest.git
2. create .env and paste [ENV Backend](https://docs.google.com/document/d/1TCn0Wzw1Ygz-x5eZMTqMIRpsduj7g7k9Q_9vaRX8sSs/edit?usp=sharing) to .env
3. go mod tidy
4. go run main.go

### Machine Learning

1. git clone https://github.com/AgrowiseHackfest2024/agrowise-ml-hackfest.git
2. create .env and paste [ENV Machine Learning](https://docs.google.com/document/d/1TCn0Wzw1Ygz-x5eZMTqMIRpsduj7g7k9Q_9vaRX8sSs/edit?usp=sharing) to .env
3. pip install -r requirements.txt
4. flask run
    
## Tech Stack

### Frontend
- **Framework**: [Next.js](https://nextjs.org/) 
  - Next.js is utilized for the frontend to provide a powerful and flexible React framework with server-side rendering capabilities.

### Backend
- **Language**: [Golang](https://golang.org/)
  - Golang is the chosen backend language for its efficiency, concurrency support, and excellent performance.
- **Web Framework**: [GoFiber](https://gofiber.io/)
  - Gofiber is used as the web framework for Golang, providing a lightweight and fast HTTP framework.
- **ORM**: [GORM](https://gorm.io/)
  - Gorm is the chosen ORM (Object-Relational Mapping) library for Golang, facilitating database interactions.

### Machine Learning
- **Web Framework**: [Flask](https://flask.palletsprojects.com/)
  - Flask is used for building the machine learning model serving API.
- **Machine Learning Libraries**: 
  - [Keras](https://keras.io/)
  - [Scikit-learn](https://scikit-learn.org/)
  - [TensorFlow](https://www.tensorflow.org/)
- **Data Visualization**: [Matplotlib](https://matplotlib.org/)
- **Data Manipulation**: [NumPy](https://numpy.org/)
- **Data Analysis**: [Pandas](https://pandas.pydata.org/)
- **Environment Variables**: [python-dotenv](https://pypi.org/project/python-dotenv/)

### Database
- **Database**: [CockroachDB](https://www.cockroachlabs.com/)
  - CockroachDB is employed as the database solution due to its distributed architecture, scalability, and strong consistency features.

### Payment Gateway
- **Payment Gateway**: [Midtrans](https://midtrans.com/)
  - Midtrans is integrated as the payment gateway to facilitate online transactions securely and efficiently.

### Additional Tools and Libraries
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
  - Tailwind CSS is chosen for styling to provide a utility-first CSS framework that is highly customizable.

This tech stack combines the efficiency of Golang for the backend, the flexibility of Next.js for the frontend, the distributed architecture of CockroachDB for data storage, and the secure payment processing capabilities of Midtrans for a robust and reliable agricultural platform.

## Screenshot Product

### Landing Not Login
<img src="./picture/Landing Not Login.png">

### Landing Login
<img src="./picture/Landing Login.png">

### Farmers
<img src="./picture/Farmers.png">

### Farmer Detail
<img src="./picture/Farmer Detail.png">

### Seed Detail
<img src="./picture/Seed Detail.png">

### Payment
<img src="./picture/Payment.png">

### History
<img src="./picture/History.png">

### Login
<img src="./picture/Login.png">

### Register
<img src="./picture/Register.png">

## Deployment

### Backend and Machine Learning
- **Container Orchestration**: [Google Cloud Platform (GCP)](https://cloud.google.com/)
  - Both the backend and machine learning applications are containerized using Docker and deployed on Google Cloud Platform for efficient container orchestration.

### Frontend
- **Hosting**: [Vercel](https://vercel.com/)
  - The frontend is hosted on Vercel for seamless deployment and scalability.

### Deployment Link
- [Frontend](https://agrowise-hackfest-2024.vercel.app/seeds)
- [Backend](https://agrowise-be-hackfest-uo3gxgwgea-et.a.run.app)
- [Machine Learning]( https://agrowise-ml-hackfest-uo3gxgwgea-et.a.run.app)
