# ParkNPlate

**ParkNPlate** is a smart License Plate Recognition (LPR) system designed to manage car park entries and exits efficiently. Utilizing a combination of socket programming, JSON data parsing, and a Flask-based web interface, ParkNPlate automates the process of vehicle tracking within a parking facility. The system can identify vehicles entering and exiting, keep track of the number of cars currently parked, and update the count in real-time.

## Key Features

- **Real-Time LPR Processing**: Receives and processes license plate data from the V2008B-LPR camera in real-time.
- **Automated Vehicle Tracking**: Adds new vehicle entries and removes exiting vehicles, ensuring an accurate count of cars in the parking lot.
- **Web Interface**: Displays the current count of parked cars, accessible via a user-friendly web interface.
- **Logging and Monitoring**: Maintains detailed logs of all activities for monitoring and troubleshooting.
- **Scalability**: Designed to handle large volumes of data and support multiple cameras.
- **Configurable Alerts**: Set alerts for when the parking lot is near full capacity.

## Technologies Used

- **Python**
- **Flask**
- **HTML/CSS/JavaScript**: Front-end.
- **JSON**
- **Logging**.

[Watch the video on YouTube](https://youtu.be/OcdofV20Z78)


## Setup and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AdrianInfante/ParkNPlate.git
   ```

2. **Install Dependencies**: 
   Navigate to the project directory and install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Server**: 
   Start the LPR server and the Flask web server.

4. **Access the Web Interface**: 
   Open a web browser and go to `http://localhost:5000` to view the current parking status.

## Coming soon Enhancements

- **Enhanced Security**: Integrate advanced security features for data protection.
- **Mobile App**: Develop a mobile application for on-the-go access.
- **Analytics Dashboard**: Add an analytics dashboard to visualize parking trends and statistics.
