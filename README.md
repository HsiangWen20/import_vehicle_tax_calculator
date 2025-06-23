# Used Car Import Cost Calculator - US2Taiwan
## Overview
This is an interactive web-based tool designed to provide a comprehensive and realistic estimate of the total "landed cost" for importing a used vehicle from the United States to Taiwan.

-----------------------------------------------------------------------
Importing a car into Taiwan involves a complex and often confusing series of cascading taxes, fees, and valuation rules. This calculator demystifies the process by implementing the official calculation methodology used by Taiwan Customs. It allows potential importers, enthusiasts, and small-scale dealers to make informed financial decisions before committing to a vehicle import.

------------------------------------------------------------------------
The tool is built as a single-page application using HTML, Tailwind CSS, and vanilla JavaScript for a clean, responsive, and easy-to-use experience.


#### Key Features
Official Valuation Method: Implements the official Taiwan Customs "Lesser Of" principle, using both the KBB Dealer Invoice Price (with depreciation) and the N.A.D.A. Average Trade-In value to determine the correct tax base.

Accurate Cascading Tax Calculation: 
Correctly calculates Taiwan's "tax-on-tax" system in the legally required order:

1. Import Tax (17.5%)
2. Commodity Tax (25% or 30% based on engine size)
3. Business Tax (5%)
4. Luxury Tax Trigger: Automatically checks if the vehicle's value surpasses the ~TWD 3 million threshold and calculates the additional 10% Luxury Tax if applicable.

#### Comprehensive Cost Breakdown: Includes all major cost components beyond the vehicle's value:

1. All applicable taxes and fees.
2. International logistics and shipping.
3. Variable ARTC inspection fees (with and without an authorization report).
4. First-year license and fuel taxes.

#### Interactive Results: Presents the final estimated cost with a dynamic donut chart for a clear visual breakdown of where the money goes.

#### Transparent and Sourced: Provides a direct link to the official Taiwan Customs Administration regulations, so users can verify the methodology.

-------------------------------------------------------------------------
#### How to Use

1. Gather Vehicle Data: Before using the tool, you will need to find two key prices for your vehicle from US sources:

2. KBB Dealer Invoice Price: Found on KBB.com. This is the new car invoice price for that model year.

3. N.A.D.A. Average Trade-In Value: Found on JDPower.com (formerly NADAguides). This is the used car trade-in value.

4. Fill Out the Form: Enter the KBB and N.A.D.A. values, along with the vehicle's engine size (cc), model year, and other import details into the form on the left.

5. Calculate: Click the "開始計算" (Start Calculation) button.

6. Review Results: The tool will display the total estimated cost on the right, along with a detailed line-item breakdown and an interactive chart.

---------------------------------------------------------------------------
### Disclaimer
This tool is for estimation purposes only. All calculations are based on the regulations published by the Taiwan Customs Administration at the time of development. The final, official, and binding costs will be determined by Taiwan Customs upon the vehicle's arrival and inspection. Tax rates and regulations are subject to change.
