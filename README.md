# Biofeedback-plant-guardian
The Biofeedback Plant Guardian, is an Interactive Plant Companion system designed to monitor a plant's environment and physiological state while providing automated care and communication.

It integrates three core functions:

Automated Life Support: Uses a Capacitive Soil Moisture Sensor to detect dryness and autonomously activate a 12V Peristaltic Pump (via a relay) for watering. It also includes humidity monitoring (via DHT11) for future misting.

Biofeedback & Interaction Monitoring: Uses the ADXL345 Accelerometer to detect physical stress (shake, bump) and the AD8232 Bio-potential Sensor to monitor the plant's electrical activity. It uses the MG90S Servo to deploy a shade when light levels (BH1750) are too harsh.

Data Logging & Communication: It uses the RTC (DS3231) for accurate timestamps and logs all environmental data, emotional states, and high-resolution stress events to an SD Card. The plant's status is displayed visually on an 8x8 LED Matrix and audibly via a Piezo Buzzer.
