MANZI KEITH.
ID:28799 GROUP:D
SQL JOINS AND WINDOW FUNCTION PROJECT.

Business scenario:

An electronic device shop that wants to check for sales performance.

Data challenge: The company problem is that it has customers, devices, and sales data but no data on products, customers, and sales growth to help analyze business growth.

Expected outcome: the expected outcome is to identify the top selling devices, understand sales growth, and understand customers for better decision making.

Success Criteria GOALS:  
1.	Identify top 5 products per region or quarter using RANK()
2.	Run monthly sales totals using SUM() OVER()
3.	Measure month-over-month sales growth using LAG()
4.	Segment customers into quartiles based on spending using NTILE(4)
5.	Compute three month moving average sales using AVG() OVER()

Database Schema Design:
ER diagram
<img width="1920" height="820" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/88f0a561-5b17-4a47-80ed-4a609cdfe84e" />

SQL JOINs Implementation
1. INNER JOIN
<img width="1920" height="841" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/92dc2405-13e8-48e8-9549-947c732ccd0b" />

3. LEFT JOIN
<img width="1920" height="985" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/fb579f9e-ca83-4da7-a443-6091285cc650" />

5. RIGHT JOIN
<img width="1920" height="691" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/2fe17bfd-b0b7-4483-b28c-88d373c137b8" />

7. FULL OUTER JOIN
 <img width="1920" height="815" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/a1e153fb-2176-4b46-8d7b-a73dbd6b5f9d" />
  
9. SELF JOIN
 <img width="1920" height="815" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/a1e153fb-2176-4b46-8d7b-a73dbd6b5f9d" />

Window Functions Implementation
1. Ranking Functions
<img width="1920" height="818" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/a312ca1c-6044-427f-92e4-a04e05c4f51c" />
2. Aggregate Window Functions
<img width="1920" height="811" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/ba958a51-0b81-4c4d-beec-e4752870217d" />
3. Navigation Functions
<img width="1920" height="815" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/965db765-7923-427d-b22a-232f5d471e47" />

5. Distribution Functions 
<img width="1920" height="779" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/9f767c88-9310-4500-948e-2796aa8d1d4b" />

 
REFERENCES:
W3 schools for query studying.
youtube tutorials for github mastering.
