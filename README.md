# Assignment1
Assignment1 Repository
	
1) Sum, Count, Average:	
	• What is the total price of all products in the dataset? - 10100 - Used SUM function and selected range - =SUM(G2:G35)
	• How many products are there in the dataset? - 21 - Used COUNTA function and UNIQUE function inside and selected range. - =COUNTA(UNIQUE(E2:E35))
	• Calculate the average price of the products. - 297.05 - Used AVERAGE function and selected range - =AVERAGE(G2:G35)
	
2) Min and Max:	
	• Determine the minimum price among all products. - 30 - Used MIN function. - =MIN(G2:G35)
	• Find the maximum price among all products. - 1000 - Used MAX function. - =MAX(G2:G35)
	
3) IF Function:	
	• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
 - Used If function as follows - =IF(G2>=500,"High Price","Standrard Price")
	
5) SUMIF and COUNTIF:	
	• Calculate the total price for products in the 'Electronics' category using the SUMIF function. - 8050 - Used this -> =SUMIF(J2:J35,"Electronics",G2:G35)
	• Determine the count of products with a price less than $100 using the COUNTIF function. - 11 - Used this -> =COUNTIF(G2:G35,"<100")
	
6) Text Formatting - LEFT, RIGHT, MID:	
	• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function. - Used this --> =LEFT(A2,2)
	• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function. - Used this --> =RIGHT(A2,2)
	• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function. --> Used this --> =MID(A2,4,3)
<img width="1094" height="547" alt="image" src="https://github.com/user-attachments/assets/1185c5db-d96c-45a2-ad4c-2e1384f92e66" />
