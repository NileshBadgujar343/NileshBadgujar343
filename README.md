
#8 daily-report
## Daily Reporting Software datbase name reporting;

## Table Name-login_details
| Name    | Type        | Null | Default | 
|----------|-------------|------|--------------|
| id       | bigint(255)     | No |   None   |      
| emp_code      |varchar(20) | No  |      None     |       |
|timeat     |timestamp     |  No   |      current_timestamp()    |       
| modifiedat   | timestamp | No  |     current_timestamp()  |     
|name | varchar(20)     | No |None   |       |
|pswd| varchar(10) | No |None    |       |
| type| varchar(20) | No   |    None|    |  
| dept| varchar(10) |  No  |  None |    

## Table Name-task

| Name    | Type        | Null | Default | Extra |
|----------|-------------|------|--------------|-------|
| id       | bigint(20)     | NO   |   NONE   | AUTO_INCREMENT      |
| assign_date      |date  | YES  |      NULL    |       |
|target_date     |date      | YES  |      NULL    |       |
| proj_name   | varchar(50) | NO  |     NONE    |       |
| task  | varchar(50)     | NO  |NONE   |       |
|description | varchar(255) | NO |NONE    |       |
| status| varchar(10) | YES  |    NONE |    |   

## Table Name-issue
| Name    | Type        | Null | Key | Default | 
|----------|-------------|------|-----|---------|
| id       | bigint(255)     | No   | FK| NULL    |       
| title    | varchar(255) | No  |     | NULL    |       
| description    | varchar(255)     | No |     | NULL    |       
| status     | varchar(15) | No  |     | NULL    |       






<!--
**NileshBadgujar343/NileshBadgujar343** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
