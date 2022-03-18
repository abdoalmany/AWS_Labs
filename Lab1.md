# Task_Day_1

#### 1- Create AWS account
   **DONE**

#### 2- Create 2 IAM Groups, Create 2 users one for each group with different permissions

![](https://i.imgur.com/BWcgNI3.png)

#### 4- Create EC2 instance with the given script in user data and try to access it from web browser.

![](https://i.imgur.com/rvPY0t9.png)

#### 5- Conect to your EC2 in (task 4) and download your static website (from github or local device) then add it to root directory of the apache server then access your website from your brows**db_sg and allow http requests only from SG(web_app) on port 3306.**er.

![](https://i.imgur.com/ldVu0kC.png)

#### 6- Create 3 SG:

- **web_sg and allow http requests from all to be access publicly.**

  ![](https://i.imgur.com/lz8QSCw.png)

- **app_sg and allow http requests only from SGs (web_app and db_app).**

  ![](https://i.imgur.com/C2FZIfG.png)

- **db_sg and allow http requests only from SG(web_app) on port 3306.**

  ![](https://i.imgur.com/7BfnNYi.png)

#### 7- Create 3 EC2 with one tag (Name) for each one (web_server, app_server, db_server) and attached each server with its respective SG.

![](https://i.imgur.com/gqdpItv.png)
 
