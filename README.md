# KLH_2026-27_T1_PSPJ_-Municipal-Waste-Collection-Optimizer

DESCRIPTION
The Municipal Waste Collection Optimizer is a Java-based system designed for intelligent waste bin management and collection routing. It monitors bin fullness, categorizes waste as organic, plastic, or metal, and helps optimize daily collection routes.

PROBLEM
Municipal waste collection can be inefficient when it is handled manually and based on guesswork. The project addresses:
- Inefficient/manual collection processes.
- Blind routes where drivers have no visibility into which bins need pickup.
- Wasted resources such as fuel and driver time from unnecessary truck routes.

FEATURES
- Monitors the fullness percentage of waste bins.
- Categorizes waste into organic, plastic, and metal.
- Determines pickup priority using fullness thresholds.
- Assigns specialized trucks according to waste type.
- Processes multiple bins using loops.
- Produces an optimized daily collection plan.

HOW IT WORKS
1. The program asks for the number of bins to monitor.
2. Java Scanner is used to collect the fullness percentage and waste type for each bin.
3. If/else conditional logic checks the bin fullness:
   - Below 50%: No pickup needed.
   - 50–80%: Schedule pickup soon.
   - Above 80%: Urgent pickup required.
4. A switch statement assigns the appropriate specialized truck:
   - Organic waste: Organic waste truck.
   - Plastic waste: Plastic waste truck.
   - Metal waste: Metal waste truck.
5. A loop processes all bins and consolidates the information into an efficient daily collection plan.

TECHNOLOGIES/CONCEPTS USED
- Java
- Scanner class
- If/else conditional statements
- Switch statement
- Loops

INPUT
The program uses Java Scanner for console-based input:
- Number of bins to monitor.
- Fullness percentage of each bin.
- Waste type of each bin: organic, plastic, or metal.

OUTPUT
The system produces:
- Pickup Priority: Each bin is identified as requiring no action, a scheduled pickup, or an urgent pickup.
- Truck Assignment: The correct specialized truck is assigned according to the waste type.
- Optimized Daily Route: Bin information is consolidated into an efficient collection plan for the day.

CONCLUSION
The Municipal Waste Collection Optimizer provides a Java-based approach to making municipal waste collection more organized and data-driven. By checking bin fullness, classifying waste types, assigning specialized trucks, and processing bins through loops, the system helps reduce unnecessary collection routes and wasted resources.
