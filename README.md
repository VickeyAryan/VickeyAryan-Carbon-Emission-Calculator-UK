# Carbon Footprint Calculator for Logistics

This web-based tool calculates the carbon emissions for logistics fleets based on fleet size, average distance per vehicle, vehicle type, and fuel type. It provides an estimated total daily emissions value in kg CO₂, helping logistics companies understand and monitor their environmental impact.

## Features
- Calculates carbon footprint for different vehicle types: **Small Van**, **Medium Vehicle**, and **Large Truck**.
- Supports three fuel types: **Diesel**, **Petrol**, and **Electric**.
- Provides instant emission calculations based on fleet size and average distance traveled.

## Usage
1. Clone this repository to your local machine or download the HTML file.
2. Open the HTML file in a web browser to use the calculator.

## Instructions
1. Enter the **Fleet Size** (number of vehicles in the fleet).
2. Input the **Average Distance per Vehicle per Day** (in miles).
3. Select the **Vehicle Type** from the dropdown menu (Small Van, Medium Vehicle, or Large Truck).
4. Choose the **Fuel Type** (Diesel, Petrol, or Electric).
5. Click **Calculate Emissions** to display the estimated total daily emissions in kg CO₂.

## How It Works
The calculator uses predefined emission factors for each combination of vehicle and fuel type. The formula used to calculate emissions is:

   **Total Emissions** = Fleet Size × Average Distance × Emissions Factor

where the emissions factor varies by vehicle and fuel type.

## Emission Factors
Here are the emission factors (in kg CO₂ per mile) for each vehicle and fuel type:

| Vehicle Type   | Diesel  | Petrol  | Electric |
|----------------|---------|---------|----------|
| Small Van      | 0.37268 | 0.3433  | 0.09179  |
| Medium Vehicle | 0.80078 | 0.73765 | 0.19722  |
| Large Truck    | 0.97838 | 0.90125 | 0.24097  |

## Project Structure
- **HTML**: Provides the structure for user input and result display.
- **JavaScript**: Handles the calculation logic and dynamically updates the results.
- **CSS**: Styles the form and result display for a better user experience.

## Future Improvements
- Add options for more vehicle types and fuel options.
- Allow users to save and track their emissions over time.
- Add unit conversion to support different distance units (e.g., kilometers).
