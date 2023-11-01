# Menu
Accomplish a series of functions of study information management
1. Accomplish MENU function and display inoformations:
   ```print("****************************************")
   print("*                                学生管理系统                         *")
   print("*              1. 添加新学生信息              *")
   print("*             2. 通过学号修改学生信息                 *")
   print("*                3. 通过学号删除学生信息                 *")
   print("*                4. 通过姓名删除学生信息                 *")
   print("*             5. 通过学号查询学生信息          *")
   print("*                6. 通过姓名查询学生信息          *")
   print("*                7. 显示所有学生信息             *")
   print("*                8. 退出系统                                           *")
   print("****************************************")
    select_op = input("输入编号选择操作：")```
2. Accomplish CONTROL function to control menu's output and part selection until end program when user input "8"
3. Accomplish STUDENT function. Parameters are serial number, name, age and gender, return whether success or not. Seriasl number cannot be repeated.
4. Accomplish MODIFICATION function. Parameters are student ID. Function display notification if ID not existed and do modification if ID existed, return whether success or not
5. Accomplish DELETE function. Parameters are student ID. Function delete student if ID existed and display notification if student ID not existed, return whether success or not
6. Accomplish DELETE function. Parameters are name. Function delete all student with same name and display notification if name not existed, return whehter success or not
7. Accomplish SEARCH function. Parameters are student ID. Function display student's information if student ID existed and display notifcation if ID not existed, return success or not
8. Accomplish SEARCH function. Parameters are student name. Function display student's information if name existed and display notifcation if ID not existed, return success or not
9. Accomplish function to display all student's information
