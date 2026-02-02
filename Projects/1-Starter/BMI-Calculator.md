# BMI Calculator

**Tier:** 1-Beginner  

A BMI (Body Mass Index) calculator is a practical health tool that combines mathematical calculations with user-friendly interface design.  
In this project, you'll create a **BMI Calculator** that calculates BMI values and provides health insights based on the results.  

This project teaches **form validation**, **mathematical calculations**, and **data visualization** — important skills for building practical utility applications.


## Features

- **Height Input** – Enter height in feet/inches or centimeters.  
- **Weight Input** – Enter weight in pounds or kilograms.  
- **Unit Conversion** – Toggle between metric and imperial units.  
- **BMI Calculation** – Calculate BMI using standard formula.  
- **Health Categories** – Display BMI category (Underweight, Normal, Overweight, Obese).  
- **Visual Indicator** – Color-coded BMI scale showing where the user falls.  
- **Result History** – Track BMI calculations over time.  
- **Health Tips** – Provide personalized health recommendations.  


## User Stories

- [ ] User can **enter height** in feet/inches or centimeters.  
- [ ] User can **enter weight** in pounds or kilograms.  
- [ ] User can **toggle units** between metric and imperial systems.  
- [ ] User can click **"Calculate BMI"** button to get results.  
- [ ] User can see their **BMI value** displayed prominently.  
- [ ] User can view their **BMI category** (Underweight, Normal, etc.).  
- [ ] User can see a **visual BMI scale** showing their position.  
- [ ] User can view **health recommendations** based on their BMI category.  
- [ ] User can see **calculation history** of previous BMI measurements.  
- [ ] User can **clear history** and start fresh measurements.  


## Bonus Features

- **Ideal Weight Calculator** – Calculate ideal weight range based on height.  
- **BMI Chart** – Interactive chart showing BMI ranges and health risks.  
- **Progress Tracking** – Track BMI changes over time with graphs.  
- **Age & Gender Factors** – Include age and gender for more accurate assessments.  
- **Body Fat Percentage** – Estimate body fat percentage using additional measurements.  
- **Goal Setting** – Set target BMI and track progress towards goals.  
- **Export Reports** – Generate PDF reports of BMI history and progress.  
- **Dark Mode** – Toggle between light and dark interface themes.  


## Learning Outcomes

- **Form Validation** – Ensure user inputs are valid and within reasonable ranges
- **Mathematical Calculations** – Implement BMI formula and unit conversions
- **Conditional Logic** – Display different results based on BMI ranges
- **Data Visualization** – Create visual representations of BMI data
- **Local Storage** – Save calculation history for future reference
- **Unit Conversion** – Handle conversions between metric and imperial units
- **Responsive Design** – Build mobile-friendly health applications
- **Health Data Presentation** – Display sensitive health information appropriately


## Technical Concepts Covered

- HTML5 form elements and validation
- CSS Grid and Flexbox layouts
- JavaScript mathematical operations
- Local storage for data persistence
- Chart.js or custom data visualization
- Responsive design principles
- Accessibility for health applications
- Error handling and user feedback


## Project Structure

```
bmi-calculator/
├── index.html          # Main HTML structure
├── styles.css          # Styling and responsive design
├── script.js           # BMI calculation and app logic
└── README.md           # Project documentation
```


## Getting Started

1. Create the HTML structure with input forms and display areas
2. Style the interface with clean, medical-appropriate design
3. Implement BMI calculation formula: BMI = weight(kg) / height(m)²
4. Add unit conversion between metric and imperial systems
5. Include BMI category classification with color coding
6. Add visual BMI scale or chart
7. Implement calculation history with local storage
8. Add bonus features as you progress


## BMI Categories

Use these standard BMI ranges:
- **Underweight**: BMI < 18.5
- **Normal weight**: 18.5 ≤ BMI < 25
- **Overweight**: 25 ≤ BMI < 30
- **Obesity**: BMI ≥ 30


## Implementation Tips

- Use appropriate input types (number, range) for better UX
- Implement real-time calculation as user types
- Add visual feedback for validation errors
- Use color coding consistently (green for normal, red for risky ranges)
- Consider accessibility for users with visual impairments
- Add helpful tooltips and explanations for medical terms


## Health Disclaimer

Include a disclaimer that BMI is a screening tool and not a diagnostic instrument. Advise users to consult healthcare professionals for medical advice.


## Next Steps

After completing this project, you'll be ready for:
- Building more complex health applications
- Working with medical data and calculations
- Creating data visualization tools
- Building fitness and wellness applications
- Developing educational health platforms
