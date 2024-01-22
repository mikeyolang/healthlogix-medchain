# Nurse-Patient Management DApp

## Overview

The Nurse-Patient Management DApp is a decentralized application designed to streamline the workflow of nurses in a healthcare setting. This application provides a user-friendly interface for nurses to manage their assigned patients, record patient care activities, and access historical data.

## Features

- **User Authentication:**
  - Nurses can log in using their unique nurse number and select the hospital they are affiliated with.

- **Patient Management:**
  - Nurses can view a list of patients assigned to them.
  - Each patient entry includes information such as the patient's name, ward, and current medications.

- **Form Submission:**
  - Nurses can select a patient and fill out a form to record the details of the care provided.
  - Form entries include a timestamp and a description of the care activities.

- **Form History:**
  - Nurses can view a history of the forms they have submitted, providing a record of past patient care activities.

## Technology Stack

- **Back-end:**
  - Motoko programming language.
  - Internet Computer platform for decentralized application deployment.

- **Front-end:**
  - HTML, CSS, and JavaScript for the user interface.
  - Integration with the Internet Computer's Motoko back-end through canister calls.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/nurse-patient-dapp.git
   cd nurse-patient-dapp
## Install Dependencies:

Follow the installation instructions for the DFINITY SDK and Motoko.
## Deploy the Back-end:

Use ```dfx deploy``` to deploy the Motoko canisters on the Internet Computer.
Run the Front-end:

Open the ```index.html``` file in your web browser.