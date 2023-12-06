# PlantDoctor_52013
# Plant Doctor - Intelligent Plant Leaf Disease Detection

## Table of Contents

- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Technology Stack](#technology-stack)
- [Diagrams](#diagrams)
- [Test Cases](#test-cases)
- [User Manual](#user-manual)
- [Future Enhancements](#future-enhancements)
- [Conclusion](#conclusion)
- [Bibliography / References](#bibliography--references)

## Introduction

In a world where agriculture is crucial for sustenance, Plant Doctor emerges as a revolutionary solution to combat plant diseases. This project aims to empower farmers and enthusiasts with an intelligent tool for early disease detection, fostering sustainable practices and ensuring crop health.

## System Requirements

### Hardware Requirements

- Android Device: Smartphone or tablet (minimum Android version required)
- Camera: Good-quality camera for leaf image capture
- Sufficient Storage: Adequate space for app and data

### Software Requirements

- Android Studio: IDE for Android app development
- Teachable Machine Model: Train the disease detection model
- TensorFlow Lite: Framework for mobile deployment
- Android SDK: Libraries and tools for app development
- Programming Language: Java or Kotlin
- Image Loading Library: (e.g., Glide or Picasso)
- Permissions: Handling access to camera and storage
- User Interface Components: XML for UI design
- Connectivity: Network features if required
- Version Control System: (e.g., Git) for code management

## Technology Stack

### Key Technologies

- Android Development (Java or Kotlin)
- Android Studio: IDE for development
- XML: UI layout specification
- Teachable Machine: ML model training platform
- TensorFlow Lite: Mobile-optimized ML framework
- Android Camera API: Access and control camera
- Glide or Picasso: Image loading libraries
- Firebase (Optional): Backend services
- IoT Integration (Optional): Real-time monitoring
- Security Measures: Data protection & encryption
- CI/CD Tools: Automating testing & deployment

## Diagrams

### Database Design

![Database Design]('https://drive.google.com/file/d/1qJR8Z79Srirn6IEPh-WvebVN1WDQBR-Y/view?usp=sharing')

*Description*: A structured database for storing plant, disease, user, image, and report information.

### Analytical Report

*Insert analytical report description or image here.*

## Test Cases

### Test Case Table

| Test Case ID | Test Case Description    | Test Steps                                  | Expected Result                              | Pass/Fail |
|--------------|--------------------------|---------------------------------------------|----------------------------------------------|-----------|
| TC001        | Verify User Registration | 1. Navigate to registration page             | Registration page is displayed               | Pass      |
|              |                          | 2. Enter valid user details                  | User is successfully registered               |           |
|              |                          | 3. Submit the registration form              | Redirect to the login page with a success message | Pass  |
| TC002        | Verify User Login        | 1. Navigate to the login page                | Login page is displayed                      | Pass      |
|              |                          | 2. Enter valid login credentials             | User is logged in successfully               |           |
|              |                          | 3. Click on the login button                 | Redirect to the dashboard                    | Pass      |
| TC003        | Upload Plant Image       | 1. Navigate to the upload page               | Upload page is displayed                     | Pass      |
|              |                          | 2. Upload an image of a plant leaf           | Image is uploaded successfully               |           |
|              |                          | 3. Click on the submit button                | Redirect to the image analysis page          | Pass      |
| TC004        | View Plant Information   | 1. Navigate to the plant information page    | Plant information is displayed               | Pass      |
|              |                          | 2. Click on a specific plant                | Detailed plant information is shown          | Pass      |
| TC005        | Diagnose Plant Disease   | 1. Navigate to the diagnose page            | Diagnose page is displayed                   | Pass      |
|              |                          | 2. Select a plant image for analysis        | Disease diagnosis results are displayed      | Pass      |
|              |                          | 3. Verify the accuracy of the diagnosis    | Diagnosis matches expected disease           | Pass      |
| TC006        | Generate Report          | 1. Navigate to the report generation page   | Report generation page is displayed          | Pass      |
|              |                          | 2. Select a diagnosed image                 | Report with detailed information is generated | Pass      |
|              |                          | 3. Download the report                      | Report is downloaded successfully            | Pass      |
| TC007        | User Logout              | 1. Click on the logout button               | User is logged out and redirected to the login page | Pass |


## User Manual

### Installation

- Install Plant Doctor from Google Play Store.
- Grant camera access permissions.
- Capture a plant leaf image for disease detection.

### Future Enhancements

- Integration with additional plant databases
- Real-time collaboration features
- Advanced analytics for disease prevalence
- Support for diverse crops and species
- Integration with smart farming devices

### Conclusion

Plant Doctor revolutionizes disease detection, promoting early intervention and sustainable farming. Your feedback helps us improve and cater to plant enthusiasts and farmers.

### Bibliography / References

- Author, A. (Year). *Title of the Paper*. Journal Name, Volume(Issue), Page Range. DOI
- Smith, B. (Year). *Book Title*. Publisher.
- [Teachable Machine Documentation](https://teachablemachine.withgoogle.com/train)
- [TensorFlow Lite Documentation](https://www.tensorflow.org/lite)


Group Member Name :
Pavan Chaudhari    
Pratiksha Sonawane
Bhagyshree Atre
Sahil Wagh
Vaishnav Sable
Shubham Ainapure
Mohit Dambale
Tejashree Sakunkhe
