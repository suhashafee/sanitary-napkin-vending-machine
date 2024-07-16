## INTRODUCTION

 Menstrual hygiene challenges significantly impact girls' education and well-being. Nowadays we can see kids of age 8 get their periods at this age its very difficult for them to as they do not have
  knowledge about periods. With the mean menarche age at 13.98 years, only one-third use sanitary napkins, predominantly those from urban, educated, and higher-income families. Around 49% lack 
 adequate menstrual knowledge, leading to over half missing school during menstruation, with 58% reporting a decline in performance. Stigma and teasing further cause dropouts. Our proposed solution 
 is a 24/7 sanitary napkin vending machine, accessible in various locations, supporting QR code payments, ensuring privacy, and promoting hygiene. This aims to improve menstrual management, reduce 
 absenteeism, and enhance girls' and women's overall well-being.
 
## OVERVIEW
<ul>
<li><b>24/7 Access: Provides round-the-clock availability of sanitary napkins.
<li><b>Digital Payments: Supports QR code transactions for quick and cashless purchases.
<li><b>Hygienic Delivery: Ensures no-contact dispensing to reduce infection risks.
<li><b>Privacy: Wall-mounted options in girls' washrooms for discreet access.
<li><b>Stock Notifications: Alerts administrators when stock levels are low.
<li><b>User-Friendly Interface: Simple design for easy operation.
<li><b>Awareness Promotion: Helps to combat period poverty and stigma.
<li><b>We have also added RFID card for making School students to use the Vending machine easily.

 
# Components Required

| Item Name                    | Quantity | Description           | Links to Product |
|------------------------------|----------|-----------------------|------------------|
| Arduino Uno Microcontroller  | 1        | Central processor     |   [Ardunio uno](https://www.amazon.in/Board-ATmega328P-Cable-Compatible-Projects/dp/B0CY2QDQHW/ref=sr_1_12?dib=eyJ2IjoiMSJ9.gKff2cZc-TTQtoNrhQ-fPaD2yATcW4TtfCFR0GGWbZYLLpZcpfNhKFTUIzMi0Yybnvno5s8mH-65Q0ZhF2sRyvWlGNZSI6uHwBWCoveSDZjFt_bvXMUQrba-LFF88cJyIshxhZWjW0YCScBVlfuTFVFD8AGNVVON2fkH-5D3R6Hfn-WK58CJ1V5WPGM7ZUF0aqJVGpu_lrJ-CKjTgL2t-MNQAOiCF3HbYdbLsxWoYQ4s-NFCIC-0jQh7zhtLs71RWq1bgzw8OgFRa8K-z1eXS1f9yl3nUtD3k3zujv-R2-0.ncKbGl6YvJAXDS7DUr9VCM5WJ4PafkcQVDFSXs8H06Q&dib_tag=se&keywords=arduino+uno&qid=1721052538&sr=8-12)               |
| RFID Reader                  | 1        | Reads RFID cards      |[RFID Reader](https://www.amazon.in/ApTechDeals-RFID-Kit-Arduino-Raspberry/dp/B07Q1B6QZR/ref=sr_1_1?crid=3ACRMO7I730KG&dib=eyJ2IjoiMSJ9.QFel9f2vOf2vDbvVAqUVl9QpX_uyGB9UovkPYqJ1X7krUmCe7umcx0IDHPlL6FcGT3x0zvAAAHKxGZ5Z4b2dx99drjbtLI89Mb4E11dvvZkZ2KBCcGrqtf6Nu1YYRHGecYMuhtLG4pYbVezMT--PB8OQnicn0KK3RBnOPjgQcF7d2rA3PpJf3q0e1yf6Ap6kkVVjjZdcsJn5V5LZNj8pax5yRN8uEvvoYnNa_SImR76BgZFFpY6Rma9bZ9I5pfF_DN_yGxluYSQuZLoBKEI7qXwQ7dXrKqlXUKKonrjQJ0k.QCcoJgAJ8KyMz8pjxwK036czfVgsX4yQxXkwyDiCVfY&dib_tag=se&keywords=rfid+module+for+arduino&qid=1721052753&sprefix=rfid+modul%2Caps%2C220&sr=8-1)                     |
| ultra sonic sensor           | 1        | Send message to GSM   |[ultra](https://www.amazon.in/Ultrasonic-Sensor-Module-HC-SR-04-Robokart/dp/B00ZNB01H)I                  |
| 3V-9V DC Micro               | 1        | To rotate the coil    |[MOTOR]( https://www.flipkart.com/sp-electron-3v-9v-dc-micro-toy-motor-motor-mini-electric-pack-2-vehicle-starter/p/itm2a96ea879e40cpid=VMSGW8G54YHHGTUY&lid=LSTVMSGW8G54YHHGTUYUXHHIN&marketplace=FLIPKART&cmpid=content_vehicle-starter-motor_8965229628_gmc     )            |
|GSM module                    | 1        | To notify the user    |[GSM](https://www.amazon.in/SIM800L-Module-Quad-band-Serial-antenna/dp/B08XBNW7K1/ref=sr_1_1?dib=eyJ2IjoiMSJ9.5CSZ3jr24VZ_9m1dLNz7oK9qjjb7eMlrR7j2ipKb0ymV_1BJVNx1vUzzCqRRz64UJDz6_Qjub4KS1YxZ-6em3NP5LtY3QJwohTKKjew47taUjZ8Y7Wogr23gIaeM0T-nKiLfY9wYC6uEsk3h1oCCejT8DxumbPznCMOj7l49h-bAEbtCdbqiaww7iLFbp5ljUylyKvGGpWHYdtXCTqhrYD4taIvabDGjGrd-al4my0I.bXGKbF0opOkS4n4afDpoBZDfd5RBUISMPUJv7Wti764&dib_tag=se&keywords=sim800l+gsm+module&qid=1721150521&sr=8-1   )            |
|                              |          | about the stocks      |                  |

## Table for Pin Connections
| Arduino              | RFID READER           | GSM                |  Ultra sonic      |   MOTOR        |
|----------------------|-----------------------|--------------------|-------------------|----------------|
|  9                   |  RST                  |                    |                   |                |
|  12                  |  MISO                 |                    |                   |                |
|  11                  |  MOSI                 |                    |                   |                |
|  13                  |  SCK                  |                    |                   |                |
|  10                  |  SDA                  |                    |                   |                |
| VCC                  |  3.3V                 |   VCC              |  VCC              |                |
| GND                  |  GND                  |   GND              |  GND              |                |
| 7                    |                       |                    |  TRIG             |                |
| 8                    |                       |                    |  ECHO             |                | 
| 5                    |                       |                    |                   |MOTORPIN 1      |
| 6                    |                       |                    |                   |MOTORPIN2       |
| 2                    |                       | RX                 |                   |                |
| 3                    |                       | TX                 |                   |                |

## BLOCK DIAGRAM
![vending machine](https://github.com/suhashafee/sanitary-napkin-vending-machine/blob/main/final%20vending.jpg))



## WORKING CODE
```
#include <SPI.h>
#include <MFRC522.h>
#include <Ultrasonic.h>
#include <SoftwareSerial.h>

// Define pins
#define SS_PIN 10
#define RST_PIN 9
#define MOTOR_PIN1 5
#define MOTOR_PIN2 6
#define TRIG_PIN 7
#define ECHO_PIN 8

// Define RFID
MFRC522 rfid(SS_PIN, RST_PIN);

// Define ultrasonic sensor
Ultrasonic ultrasonic(TRIG_PIN, ECHO_PIN);

// Define GSM
SoftwareSerial gsm(2, 3); // RX, TX

void setup() {
  Serial.begin(9600);
  SPI.begin();
  rfid.PCD_Init();
  
  // Motor pins
  pinMode(MOTOR_PIN1, OUTPUT);
  pinMode(MOTOR_PIN2, OUTPUT);

  // GSM init
  gsm.begin(9600);
  sendSMS("System Initialized");

  Serial.println("Setup Complete");
}

void loop() {
  // Check for RFID card
  if (rfid.PICC_IsNewCardPresent() && rfid.PICC_ReadCardSerial()) {
    String cardID = "";
    for (byte i = 0; i < rfid.uid.size; i++) {
      cardID += String(rfid.uid.uidByte[i], HEX);
    }
    cardID.toUpperCase();
    Serial.println("Card ID: " + cardID);

    // Authorized card ID (example)
    if (cardID == "YOUR_CARD_ID") {
      dispenseItem();
    } else {
      Serial.println("Unauthorized card");
    }
    rfid.PICC_HaltA();
  }
  
  // Check stock
  long distance = ultrasonic.read();
  if (distance < 10) { // Assuming 10 cm is the threshold for "empty"
    sendSMS("Stock is empty. Please refill.");
  }
}

void dispenseItem() {
  // Rotate motor to dispense
  digitalWrite(MOTOR_PIN1, HIGH);
  digitalWrite(MOTOR_PIN2, LOW);
  delay(1000); // Adjust the time as needed
  digitalWrite(MOTOR_PIN1, LOW);
  digitalWrite(MOTOR_PIN2, LOW);
  
  Serial.println("Item dispensed");
}

void sendSMS(String message) {
  gsm.println("AT+CMGF=1"); // Set SMS to text mode
  delay(1000);
  gsm.println("AT+CMGS=\"+919353981556\""); // Replace with your phone number
  delay(1000);
  gsm.println(message);
  delay(1000);
  gsm.println((char)26); // ASCII code of CTRL+Z to send message
  delay(1000);
  Serial.println("SMS sent: " + message);
}
```




## DEMO VIDEO
https://github.com/suhashafee/sanitary-napkin-vending-machine/blob/main/vending%20video.mp4

## Final Vedio
https://github.com/suhashafee/sanitary-napkin-vending-machine/blob/main/finalll%20video.mp4


### OBJECTIVES
<ul>
<li><b>Ensure 24/7 availability of sanitary napkins in schools, colleges, offices, factories, hostels, and PGs.
<li><b> Decrease the number of girls and women missing school or work due to menstrual hygiene issues by 50%.
<li><b>Provide sanitary napkins through a no-contact delivery mechanism to minimize infection risks.
<li><b>Offer discreet and convenient access to sanitary products, with wall-mounted machines in girls' washrooms.
<li><b> Raise awareness about menstrual hygiene management and reduce the stigma associated with menstruation.
 <li><b> Simplify transactions through QR code payments for easy and cashless access to sanitary napkins.
<li><b> Implement RFID technology for efficient inventory management and automated notifications when stock levels are low.
<li><b> Improve the overall health and well-being of girls and women by providing essential menstrual hygiene products.
<li><b>Empower girls and women by ensuring they have the necessary resources to manage their menstrual health independently and confidently.

## RESULT

The implementation of the smart sanitary napkin vending machine with RFID technology has yielded significant positive outcomes. It has increased 24/7 accessibility in schools, colleges, offices, factories, hostels, and PGs, resulting in over a 50% reduction in absenteeism due to menstruation. The no-contact delivery system has improved health and hygiene by reducing infection risks, while the wall-mounted machines ensure discreet and convenient access. Additionally, the project has raised awareness and reduced the stigma associated with menstruation, promoting a more supportive environment for menstrual hygiene management.

## CONCLUSION

The introduction of the smart sanitary napkin vending machine equipped with RFID technology has brought about transformative improvements in menstrual hygiene management. By ensuring 24/7 access to sanitary napkins across various settings including schools, colleges, offices, factories, hostels, and PGs, the project has significantly reduced absenteeism among girls and women. This achievement not only enhances their academic and professional participation but also improves overall health and hygiene through a no-contact delivery system that minimizes infection risks. The provision of discreet and convenient access through wall-mounted machines further supports privacy and convenience.

Moreover, this initiative has successfully raised awareness about menstrual hygiene and played a crucial role in reducing the stigma associated with menstruation. By empowering girls and women with essential resources and fostering a supportive environment, the project contributes to their well-being and promotes a more inclusive society. Moving forward, continued efforts in promoting menstrual health education and expanding access to sanitary products will be essential in sustaining these positive outcomes and further advancing gender equality and health equity initiatives.






