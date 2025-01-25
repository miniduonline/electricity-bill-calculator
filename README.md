# Electricity Bill Calculator Web App

This web app helps users calculate their electricity bill based on their usage. It is designed to be simple and user-friendly, providing real-time calculations of electricity charges based on the selected unit price.

### **Demo**
You can view the live demo of the calculator at: [Electricity Bill Calculator - Live Demo](https://miniduonline.github.io/electricity-bill-calculator/)

## How It Works

The Electricity Bill Calculator works by taking the following inputs:

1. **Previous Month Reading (PMR)**: The reading from the previous month on your electricity meter.
2. **Current Month Reading (CMR)**: The current reading from your electricity meter.

The calculator then calculates the total units consumed and the total bill based on Sri Lankan electricity pricing. The pricing follows this structure:

| Electricity Consumption (kWh) | Old Rate (LKR) | New Rate (LKR) | Fixed Charges (LKR) |
| ----------------------------- | -------------- | -------------- | ------------------- |
| 0 - 30                         | 6              | 4              | 75                  |
| 31 - 60                        | 9              | 6              | 200                 |
| 61 - 90                        | 18             | 14             | 400                 |
| 91 - 120                       | 30             | 20             | 1000                |
| 121 - 180                      | 42             | 33             | 1500                |
| 180+                           | 65             | 52             | 2000                |

## Features

- Input fields for user details (e.g., units of electricity consumed)
- Real-time calculation of electricity bill based on the user's input
- User-friendly interface with clear instructions
- Responsive design for mobile and desktop views

## Technologies Used

- HTML
- CSS
- JavaScript

## Setup

To run this project locally on your machine:

1. Clone this repository:
   ```bash
   git clone https://github.com/miniduonline/electricity-bill-calculator.git
