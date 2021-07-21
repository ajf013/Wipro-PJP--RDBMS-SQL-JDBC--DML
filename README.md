## Wipro-PJP--RDBMS-SQL-JDBC--DML

## **DML**

**1.**

```
 Run the below script
Create table MY_EMPLOYEE 
as
Select employee_id,first_name,last_name,department_id,salary from EMPLOYEES where 1=2;
```

**2.**

```
 Test the table creation by viewing the structure using describe command

Name                           Null     Type                                                                                                                                                                                          
------------------------------ -------- ------------------------------
EMPLOYEE_ID                             NUMBER(6)                                                                                                                                                                                     
FIRST_NAME                              VARCHAR2(20)                                                                                                                                                                                  
LAST_NAME                      NOT NULL VARCHAR2(25)                                                                                                                                                                                  
DEPARTMENT_ID                           NUMBER(4)                                                                                                                                                                                     
SALARY                                  NUMBER(8,2)                                                                                                                                                                                   
5 rows selected
```

**3.**

```
Insert one record without listing the column names in the insert statement. Check whether data is inserted
Eg:
employee_id    first_name    last_name    department_id     salary
201             Michael       Hartstein      20          13000
```

**4.**

```
 Insert one record without listing the column names in the insert statement where salary value remain undetermined. Check whether data is inserted
Eg: 
employee_id first_name last_name  department_id salary
201         Michael     Hartstein   20         13000
202         Pat            Fay       20         (null)
```

**5.**

```
 Insert one record with listing the column names avoiding salary column in the insert statement where salary value remain undetermined. Check whether data is inserted
employee_id first_name last_name department_id salary
201       Michael        Hartstein   20          13000
202       Pat             Fay          20         (null)
203       Susan           Mavris        40        (null)
```

**6.**

```
 Use the above Script to insert the below given records
employee_id first_name last_name department_id salary
205        Shelley        Higgins       110      12000
100        Steven         King            90       24000
101        Neena          Kochhar       90         17000
102        Lex De         Haan            90       17000
111        Ismael         Sciarra        100        7700
112        Jose Manuel    Urman         100        7800
204        Hermann        Baer           70       10000
```

**7.**

```
 Create a query to increase salary by 10% for all employees in dept 90.
```

**8.**

```
 Create a query to update Last_name of emp 202 to Higgins.
```

**9.**

```
Delete employees whose name either first or last name has char seq of ‘man’
```

## You can reach out 😊😊
Feel free to contact me about the problems. I will try to help as much as I can 😉

[![Linkedin Badge](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajf013-francis-cruz/)
[![Mail Badge](https://img.shields.io/badge/email-c14438?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:furkanozbek1995@gmail.com)](mailto:cruzmma2021@gmail.com)
[![Twitter Badge](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Itsme_Ajf013)
[![Github Badge](https://img.shields.io/badge/github-333?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ajf013)

## 🙏 Any one wish to Support

  <a href="https://www.buymeacoffee.com/ajf013" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="23" width="100" style="border-radius:2px" />
</p>
