Task 1 – Understand the Problem and Identify the Data

name:suvetha.s
reg no : 1921260208
python version : python 3.12

Milk Payment Calculation System

Objective

The objective of this task is to understand the milk payment system and identify the required inputs, outputs, constraints, data types, validation rules, and assumptions.

1. Inputs

- Farmer ID – Identifies each farmer.
- Litres – Quantity of milk supplied.
- Fat Percentage – Fat content of milk.
- SNF Percentage – Solid-Not-Fat content of milk.
- Shift – Morning or evening collection.

2. Outputs

- Rate per litre.
- Total payment.
- Ten-day payment total.

3. Constraints

- MIN_FAT = 2.0
- MAX_FAT = 7.0
- DAYS = 10

4. Data Types

Data| Data Type
Farmer ID| Integer or String
Litres| Float
Fat Percentage| Float
SNF Percentage| Float
Shift| String
Rate per litre| Float
Amount| Float
Ten-day total| Float

5. Validation Rules

1. Milk quantity must not be negative.
2. Fat percentage must be between 2.0% and 7.0%.
3. SNF must be within the permitted range.
4. Farmer ID must not be empty.
5. Shift must be morning or evening.
6. Payment must be non-negative.
7. Invalid inputs must be rejected.

6. Assumptions

- Each farmer has a unique ID.
- Milk quantity and quality are recorded for every collection.
- Payment rates follow the dairy's predefined pricing rules.
- Ten-day total includes all valid payments.
- Payment amounts are displayed to two decimal places.

7. Complexity Analysis

- Time Complexity: O(n)
- Space Complexity: O(n)

Structured data and loops help process multiple farmers efficiently.

Conclusion

The milk payment system requires clearly defined inputs, outputs, data types, constraints, and validation rules. Using structured data and loops makes the program easier to maintain and efficient for handling multiple farmers.
