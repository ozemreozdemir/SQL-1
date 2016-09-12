SQL Excercise
===============================
1. {a, b, c} is a relation that contains the tuples a, b, and c.   In the following cases the tuples have arity of 
1. Calculate the following: 
a. ({1, 2, 3} ? {5, 7, 11}) n {2, 4, 6, 8, 10} 
b. ({1, 2, 3} n {2, 4, 6, 8, 10}) ? ({5, 7, 11} n {2, 4, 6, 8, 10}) 

2. Use formal notation to write an algebraic example of the following SQL:   
a. SELECT Column1, Column3 FROM MyTable WHERE Column2 = Column3 
b. Reverse the order of projection and selection in your algebraic formulation.  
What happened? 

3. pc1, c2(s?1(s?2(pc1, c2, c3, c5(R))))  
Where 
• ?1: C1 = C5; 
• ?2: C5 = “Test”; 
• R:  MyTable; 
a. Write a SQL statement that declares the intent of the algebraic notation 
b. Simplify the algebraic statement.  Simplification means minimize the number of parentheses and terms. 

4. SELECT * FROM T1 JOIN T2 ON T1.C1 = T2.C1 
a. Write out an equivalent in relational algebra using the join operator 
b. Write out an equivalent in relational algebra without using the join operator 

5. pS.C1, R.C2(s?1(R) ??2 S)     
where  • ?1  = (R.C2 = ‘A’) • ?2 = (R.C1 = S.C2) 
• Write out equivalent SQL and test this SQL using relations R and S that you create for this example.  
The relations R and S in RelationalAlgebraAndSQL.pdf and RelationalAlgebraAndSQL.sql don’t quite work because their column types do not match for this assignment.