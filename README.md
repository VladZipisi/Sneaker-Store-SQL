# Sneaker-Store-SQL
Management of a sport shoes store (pl/sql blocks, cursors, functions, procedures)
Univeristy Database Management Systems Class Project
The purpose of the project is to manage a sports shoe store, using internal information. Thus, in the database there are recorded information about: department, employees, the boxes of each pair of shoes, the model of each pair of shoes and the receipts, in total there are 5 data tables.
For each department we know:
-cod_d; the department to which the employee belongs, which in the primary key of the table;
-denumire; the department name;
-etaj; floor
-nr_camera; room number;
For each employee the table has:
-cod_a; employee unique identifier also primary key
-cod_d; the department where the employee works, which is the foreign key for this table;
-varsta; the age of the employee;
-nume; the name of the employee;
-vechime; time period worked;
For the table box we know:
-cod_c; unique identifier for the box;
-culoare; the color of the box;
-cod_bare; barcode present on the box;
For the table model we have informations about:
-cod_m; primary key;
-cod_c; foreign key and it represent the box of each model;
-brand; the brand of each model;
-marime; the size of the model;
-pret; the model retail price;
And lastly the table receipt has informations about:
-cod_b; primary key;
-cod_m; foreign key;
-data_emitere; the date when the receipt was issued;
<img width="603" alt="Screenshot 2023-02-02 at 11 13 08" src="https://user-images.githubusercontent.com/124059871/216281978-32d75c7d-6a6b-49b3-97d8-98b1899bb8e6.png">

<img width="603" alt="Screenshot 2023-02-02 at 11 11 41" src="https://user-images.githubusercontent.com/124059871/216281868-bd2195dc-f0f5-46dd-8cbb-330765e90282.png">

<img width="538" alt="Screenshot 2023-02-02 at 11 14 10" src="https://user-images.githubusercontent.com/124059871/216281905-b8ff3c1d-b06e-4e66-b72e-e4eb3f33de93.png">

<img width="603" alt="Screenshot 2023-02-02 at 11 13 26" src="https://user-images.githubusercontent.com/124059871/216281934-e34e253a-0cfb-48c3-ad79-1c383cc7e6a5.png">





