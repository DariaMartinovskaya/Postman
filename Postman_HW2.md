http://162.55.220.72:5005/first
1. Send a request.
2. Status code is 200
3. Check that the right string is received in body.

http://162.55.220.72:5005/user_info_3
1. Send a request.
2. Status code is 200
3. Parse response body into json.
4. Check that name in response is equal to name in request (enter name by hand)
5. Check that age in response is equal to age in request (enter age by hand)
6. Check that salary in response is equal to salary in request (enter salary by hand)
7. Спарсить request.
8. Check that name in response is equal to name in request (name should be taken from request)
9. Check that age in response is equal to age in request (age should be taken from request)
10. Check that salary in response is equal to salary in request (salary should be taken from request)
11. Print to console the parameter family from response.
12. Check that u_salary_1_5_year in response is equal to salary*4 (salary should be taken from request)

http://162.55.220.72:5005/object_info_3
1. Send a request.
2. Status code is 200
3. Parse response body into json.
4. Parse request.
5. Check that name in response is equal to name in request (name should be taken from request)
6. Check that age in response is equal to age in request (age should be taken from request)
7. Check that salary in response is equal to salary in request (salary should be taken from request)
8. Print to console the parameter family from response.
9. Check that the parameter dog has name parameters.
10. Check that the parameter dog has age parameters.
11. Check that the parameter name is Luky.
12. Check that the parameter age is 4.


============================================================================
http://162.55.220.72:5005/object_info_4
1. Send a request.
2. Status code is 200
3. Parse response body into json.
4. Parse request.
5. Check that name in response is equal to name in request (name should be taken from request)
6. Check that age in response is equal to age in request (age should be taken from request)
7. Print into console the parameter salary from request.
8. Print into console the parameter salary from response.
9. Print into console 0th element of parameter salary from response.
10. Print into console 1st element of parameter salary from response.
11. Print into console 2nd element of parameter salary from response.
12. Check that 0th element of parameter salary is equal to salary from request (salary should be taken from request)
13. Check that 1st element of parameter salary is equal to salary*2 from request (salary should be taken from request)
14. Check that 2nd element of parameter salary is equal to salary*3 from request (salary should be taken from request)
15. Create name variable in the environment
16. Create age variable in the environment
17. Create salary variable in the environment
18. Send name variable to the environment
19. Send age variable to the environment
20. Sage salary variable to the environment
21. Write a loop that will output to the console in order the elements of the list from the salary parameter.

=============================================================================

http://162.55.220.72:5005/user_info_2
1. Fill in the parameter salary from the environment to request
2. Fill in the parameter age from the environment to age
3. Fill in the parameter name from the environment to name
4. Send a request.
5. Status code is 200
6. Parse response body into json.
7. Parse request.
8. Check that json response имеет параметр start_qa_salary
9. Check that json response имеет параметр qa_salary_after_6_months
10. Check that json response has the parameter qa_salary_after_12_months
11. Check that json response has the parameter qa_salary_after_1.5_year
12. Check that json response has the parameter qa_salary_after_3.5_years
13. Check that json response has the parameter person
14. Check that the parameter start_qa_salary is equal to salary from request (salary should be taken from request)
15. Check that the parameter qa_salary_after_6_months is equal to salary*2 from request (salary should be taken from request)
16. Check that the parameter qa_salary_after_12_months is equal to salary*2.7 from request (salary should be taken from request)
17. Check that the parameter qa_salary_after_1.5_year is equal to salary*3.3 from request (salary should be taken from request)
18. Check that the parameter qa_salary_after_3.5_years is equal to salary*3.8 from request (salary should be taken from request)
19. Check that 1st element from u_name in the parameter person is equsl to salary from request (salary should be taken from request)
20. Check that the parameter u_age id equal to age from request (age should be taken from request)
21. Check that the parameter u_salary_5_years is equal to salary*4.2 from request (salary should be taken from request)
22. ***Write a loop that will output to the console in order the elements of the list from the person parameter.
