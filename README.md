# Python
**Electric Vehicle Data Analysis Project**
Project Overview
In this project, you will analyze a dataset related to electric vehicles (EVs). The dataset contains
various features such as electric range, energy consumption, price, and other relevant
attributes. Your goal is to conduct a thorough analysis to uncover meaningful insights, tell a
compelling story, conduct hypothesis testing and provide actionable recommendations based on
the data.
Dataset: FEV-data-Excel.xlsx
Dataset Overview
Car full name: The full name or designation of the vehicle, often combining make, model, and
variant.
Make: The brand or manufacturer of the car.
Model: The specific model or version of the car.
Minimal price (gross) [PLN]: The minimum retail price of the car, in Polish złoty (PLN).
Engine power [KM]: The car's engine power, measured in horsepower (KM in Polish).
Maximum torque [Nm]: The peak torque the engine can produce, measured in Newton-meters
(Nm).
Type of brakes: The braking system used, such as disc or drum brakes.
Drive type: The drivetrain configuration, like FWD (front-wheel drive), RWD (rear-wheel drive),
or AWD (all-wheel drive).
Battery capacity [kWh]: Total energy capacity of the car’s battery, measured in kilowatt-hours
(kWh).
Range (WLTP) [km]: Estimated driving range on a full charge under WLTP standards, in
kilometers.
Wheelbase [cm]: The distance between the front and rear axles, in centimeters.
Length [cm]: The overall length of the car, in centimeters.
Width [cm]: The car’s width, in centimeters.
Height [cm]: The car’s height, in centimeters.
Minimal empty weight [kg]: The car’s minimum weight when empty, measured in kilograms.
Permissible gross weight [kg]: Maximum legally allowed weight, including passengers and
cargo, in kilograms.
Maximum load capacity [kg]: The maximum weight the car can carry, in kilograms.
Number of seats: The number of passenger seats in the car.
Number of doors: The number of doors on the car.
Tire size [in]: The tire size, measured in inches.
Maximum speed [kph]: The top speed of the car, in kilometers per hour.
Boot capacity (VDA) [l]: Trunk or cargo space capacity, measured in liters according to VDA
standards.
Acceleration 0-100 kph [s]: Time taken to accelerate from 0 to 100 kilometers per hour, in
seconds.
Maximum DC charging power [kW]: The highest charging power supported when using a DC
fast charger, in kilowatts (kW).
Mean - Energy consumption [kWh/100 km]: Average energy consumption per 100 kilometers,
in kilowatt-hours (kWh).
Instructions
● Use Python and libraries such as Pandas, NumPy, SciPy, Matplotlib, and any other tools
you find necessary.
● Focus on clear, structured code and explanations to guide readers through your thought
process.
● Every task requires both a coding solution and a written analysis section explaining your
findings.
Task 1: A customer has a budget of 350,000 PLN and wants an EV with a minimum range
of 400 km.
a) Your task is to filter out EVs that meet these criteria.(2 Marks)
b) Group them by the manufacturer (Make).(6 marks)
c) Calculate the average battery capacity for each manufacturer. (8 Marks)
Task 2: You suspect some EVs have unusually high or low energy consumption. Find the
outliers in the mean - Energy consumption [kWh/100 km] column.(16 Marks)
Task 3: Your manager wants to know if there's a strong relationship between battery
capacity and range.
a) Create a suitable plot to visualize.(8 Marks)
b) Highlight any insights.(8 Marks)
Task 4: Build an EV recommendation class. The class should allow users to input their
budget, desired range, and battery capacity. The class should then return the top three EVs
matching their criteria. (8+8 Marks)
Task 5: Inferential Statistics – Hypothesis Testing: Test whether there is a significant
difference in the average Engine power [KM] of vehicles manufactured by two leading
manufacturers i.e. Tesla and Audi. What insights can you draw from the test results?
Recommendations and Conclusion: Provide actionable insights based on your analysis.
(Conduct a two sample t-test using ttest_ind from scipy.stats module) (16 Marks)
