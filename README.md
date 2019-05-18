# Disease-prediction-using-Java\n

System Requirements:
+I was using Netbeans 8.0.2, and I wish even you are using the same.
+Install Oracle SQL and set your username and password.
+Assuming you are in C:\Users\prajwalj\Documents\NetBeansProjects i.e. you have NetBeansProjects folder inside Documents, Create a new project named pyscriptInJava inside NetBeansProjects folder.
+Add the files 
              1.  box.java 
              2.  box.form
      inside the folder C:\Users\prajwalj\Documents\NetBeansProjects\pyscriptInJava\src\pyscriptinjava i.e. inside       NetBeansProjects\pyscriptInJava\src\pyscriptinjava. 
+Add the files 
              1.  dec_tree.py
              2.  nai_bayes.py
              3.  rand_forest.py
      inside the folder C:\Users\prajwalj\Documents\NetBeansProjects\pyscriptInJava i.e. inside pyscriptInJava folder.
+I had installed python 3.7.3 and had it's environment variables set.
+Install opencsv-4.5.jar and odbc8.jar
  from https://sourceforge.net/projects/opencsv/  and https://www.oracle.com/technetwork/database/features/jdbc/jdbc-ucp-122-3110062.html respectively.
+Add these 2 above .jar files in the Libraries section in NetBeans IDE.
+Make necessary source path changes in box.java file to use the appropriate files.
+For accessing your database, use your username and password. 
+To run the project, run the box.java file i.e. Shift+F6 on box.java
+Make a relation "symdis" with following description.
 Name                                      Null?    Type
 ----------------------------------------- -------- ----------------------------
 TOPIC                                              VARCHAR2(30)
 DESCRIPTION                                        VARCHAR2(500)
 +Insert the necessary information with TOPIC containing the disease or symptom name, and DESCRIPTION containing description related to the particular disease or symtom.
 +Make a relation "account" with following desciption.
  Name                                      Null?    Type
 ----------------------------------------- -------- ----------------------------
 USERNAME                                           VARCHAR2(30)
 PASSWORD                                           VARCHAR2(30)
