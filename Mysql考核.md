##Mysql考核作业    
* 使用navicat建立了school数据库，在school数据库中分别建立三个表，命名为college，class，student。对应要求的学院，班级，学生三个表。
  1.college表有两个字段：college_id字段为int型，并作为主键，college_name字段为varchar型，保存学院名称。
  2.class表有三个字段：class_id为int型，做为主键；class_name字段为varchar型，保存班级名；college_id字段为int型，是连接college表的外键。
  3.student表有五个字段：student_id为int型，作为主键;student_name,student_sex为varchar型，保存对应学生信息；studen_age为int型，保存学生年龄；class_id为int型，作为连接class表的外键。
* 通过两个外键将三个表分层连接，构成school数据库。 
