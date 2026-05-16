# Iot-based-Autonomous-smart-shopping-trolley


# 7.1 Introduction

The proposed **IoT-Based Autonomous Smart Shopping Trolley using Human Following and Automated Billing System** integrates embedded systems, sensors, Raspberry Pi processing, barcode scanning, and digital payment technology to provide a smart shopping experience. The system combines autonomous trolley movement with automated billing and QR payment generation.

The architecture consists of two major modules:

1. **Human Following and Navigation Module**
2. **Smart Billing and Payment Module**

Both modules communicate independently to provide a complete smart retail solution.

---

# 7.2 Overall System Architecture

<img width="491" height="313" alt="image" src="https://github.com/user-attachments/assets/42ecfa28-b48f-4a91-8416-5f7d417c26b1" />


Use the block diagram you created earlier:

```text
Customer
   ↓
IR Sensors + Ultrasonic Sensor
   ↓
Arduino UNO
   ↓
L298N Motor Driver
   ↓
DC Motors → Human Following Trolley

Barcode Scanner
   ↓
Raspberry Pi 4
   ↓
Touchscreen GUI
   ↓
Bill Calculation
   ↓
QR Payment Generation
```

---

# 7.3 System Flowchart

Insert flowchart image.

Flow:

```text
START
   ↓
Power ON trolley
   ↓
Initialize Arduino + Raspberry Pi
   ↓
Detect Human Using Sensors
   ↓
Move trolley (Forward/Left/Right/Stop)
   ↓
Scan Product Barcode
   ↓
Display Product + Price
   ↓
Update Total Bill
   ↓
Generate QR Payment
   ↓
Payment Successful
   ↓
STOP
```

(Insert flowchart image here)

---

# 7.4 Explanation of Each Component / Subsystem

---

## 1. Raspberry Pi 4

Function:

* Acts as main processing unit for GUI
* Runs Python Tkinter dashboard
* Controls barcode billing interface
* Generates QR code payment

Purpose:
Provides user interaction through touchscreen display.

---

## 2. Arduino UNO

Function:

* Reads sensor values
* Executes human-following logic
* Controls motor driver

Purpose:
Handles autonomous movement of trolley.

---

## 3. IR Sensors

Function:
Detect customer position.

Purpose:
Enable trolley to follow the user.

---

## 4. Ultrasonic Sensor

Function:
Measure distance and obstacle detection.

Purpose:
Prevent collisions.

---

## 5. L298N Motor Driver

Function:
Controls direction and speed of motors.

Purpose:
Provides motor actuation.

---

## 6. DC Geared Motors

Function:
Drive trolley movement.

Purpose:
Forward, reverse, left, and right motion.

---

## 7. Barcode Scanner

Function:
Reads product barcode numbers.

Purpose:
Adds products to billing dashboard automatically.

---

## 8. Touchscreen Display

Function:
Displays:

* Product name
* Product price
* Total bill
* QR payment

Purpose:
User interface.

---

## 9. Battery & Power Supply

Function:
Supply power to:

* Arduino
* Motors
* Sensors
* Raspberry Pi

Purpose:
Portable operation.

---

# 7.5 Application Workflow / Demo Flow

### Step 1:

Switch ON trolley

↓

### Step 2:

Sensors detect user

↓

### Step 3:

Trolley follows customer

↓

### Step 4:

Product scanned using barcode scanner

↓

### Step 5:

Dashboard displays:

* Product name
* Price
* Total bill

↓

### Step 6:

QR generated

↓

### Step 7:

Customer completes payment

↓

### Step 8:

Payment confirmation displayed

7.6 Screenshots / Demo Images

Insert screenshots:

Screenshot 1:
<img width="457" height="211" alt="image" src="https://github.com/user-attachments/assets/285e3db2-b7fe-41d8-885f-db0179319475" />

Explain:
Displays products and total bill.

Screenshot 2:

<img width="452" height="176" alt="image" src="https://github.com/user-attachments/assets/0d7069d9-9a92-4d93-ab53-954c6131d407" />

Explain:
Allows digital payment.

Screenshot 3:

<img width="514" height="664" alt="image" src="https://github.com/user-attachments/assets/c3294e48-8f0c-443e-b420-9d8cbc9c7537" />


Explain:
Shows sensor-based trolley movement.

Screenshot 4:

<img width="1537" height="1023" alt="image" src="https://github.com/user-attachments/assets/939e3e59-46fd-4aaf-8e8d-447c570be9e8" />


Explain:
Complete hardware integration.
---


Conclusion

The proposed architecture integrates autonomous navigation, smart billing, and digital payment into a single embedded system. The combination of Raspberry Pi, Arduino, sensors, and barcode technology enables an intelligent and cost-effective smart shopping solution suitable for future retail automation.


