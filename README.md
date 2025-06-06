Its primary purpose is to allow users to input details about their vehicle's travel distance, Octane mileage, and current fuel prices for both Octane and LPG. Based on this input, it calculates and compares the total running costs for both fuel types, highlighting the potential monetary savings if LPG is used. It also provides a detailed breakdown of these calculations.

**Objective:** The calculator clearly displays the potential monetary savings achieved by using LPG for a given distance.

**User Inputs:**
1. Total Kilometers Traveled: The total distance the car will travel.
Type: Numeric (e.g., 1000)
Example Label: "Total Distance (km)"
2. Car Mileage on Octane: The fuel efficiency of the car when running on Octane.
Type: Numeric (e.g., 10 for 10 km per liter)
Example Label: "Octane Mileage (km/L)"
3. Octane Price per Liter: The current price of Octane per liter.
Type: Numeric
Default Value: 122 (tk)
Example Label: "Octane Price (tk/L)"
4. LPG Price per Liter: The current price of LPG per liter.
Type: Numeric
Default Value: 67 (tk)
Example Label: "LPG Price (tk/L)"

**Calculation Logic:**

1. Octane Cost Calculation: Calculate liters of Octane needed: octane_liters = total_km_traveled / car_mileage_on_octane
Calculate total cost for Octane: total_octane_cost = octane_liters * octane_price_per_liter
LPG Mileage Calculation:

2. LPG provides 15% lower mileage than Octane.
Calculate LPG mileage: lpg_mileage = car_mileage_on_octane * (1 - 0.15) or lpg_mileage = car_mileage_on_octane * 0.85
LPG Cost Calculation:

3. Calculate liters of LPG needed: lpg_liters = total_km_traveled / lpg_mileage
Calculate total cost for LPG: total_lpg_cost = lpg_liters * lpg_price_per_liter
Savings Calculation:

4. Calculate the savings from using LPG: savings = total_octane_cost - total_lpg_cost


