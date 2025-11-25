Data Visualization - Assignment 2: Interactive Scatterplot
Project Overview
Interactive scatterplot visualization for multivariate car data analysis using D3.js.

Project Description
This project implements an interactive scatterplot visualization that encodes four attributes of a car dataset:
X-axis: Retail Price
Y-axis: Horsepower
Size: Engine Size
Color: Car Type

Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- D3.js v7.8.5

### Running Locally
1. Clone this repository:
   git clone 

2. Open `index.html` in a web browser

3. Upload the `cars.csv` file using the file input

File Structure
datavis-assignment2/
├── index.html            
├── cars.csv              
├── README.md              # This file

Dataset
 Car data with 13 attributes for 42 models

Attributes:
- Name, Type, AWD, RWD
- Retail Price, Dealer Cost
- Engine Size (l), Cylinders
- Horsepower (HP)
- City Miles Per Gallon

Visual Design Choices

Encoding Strategy
| Attribute | Channel | Rationale |
|-----------|---------|-----------|
| Retail Price | X position | Most accurate for quantitative comparison |
| Horsepower | Y position | Natural performance vs. price relationship |
| Engine Size | Circle size | Intuitive magnitude representation |
| Car Type | Color | Effective categorical distinction |

Color Scheme
- 🔵 Sedan: Blue (#3498db)
- 🔴 SUV: Red (#e74c3c)
- 🟠 Sports Car: Orange (#f39c12)
- 🟢 Wagon: Green (#2ecc71)

Key Findings
- Strong positive correlation between price and horsepower
- Sports cars cluster in high-price/high-HP region
- Sedans dominate the mid-range market
- Sweet spot: $30-40k range for HP-to-price ratio

AI Tools Acknowledgment
laude (Anthropic) Used for D3.js syntax guidance, CSV parsing logic, and debugging and writin of the readme file
All design decisions and analysis are original work

References
- [D3.js Documentation](https://d3js.org/)
- [D3 Graph Gallery](https://d3-graph-gallery.com/)
- Course materials: Data Visualization lecture notes
