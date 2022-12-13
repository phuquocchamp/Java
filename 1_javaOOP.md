# 1. JAVA OOP

- OOP stands for Object-Oriented Programing.
  - Procedural programming.
  - Object-Oriented programming.
- ***Object-Oriented programming*** has several advantages over ***Procedural Programming***

---
# 2. OOP
1. Encapsulation
   ``` 
   - Tính đóng gói : ẩn giấu các thông tin không liên quan và hiển thị các thông tin liên quan. 
   - Giúp bảo vệ và tăng sự bảo mật của ứng dụng.
   - Kiểm soát đối với dữ liệu (EX : Số tháng trong một năm [1:12]).
   --> private, geter, setter. 
   ```
   
    ``` Java
    public class Student {
      private String name;
   
      public String getName() {
          return name;
      }
   
      public void setName(String name) {
          this.name = name;
      }
    }
    ```
   
2. Inheritance
    ```
    - Kế thừa     : là sự liên quan giữa 2 class với nhau trong đó class cha (Super Class) và class con (Sub Class).
    - Khi kế thừa : Khi kế thừa thì class con (Sub Class) được thừa hưởng tất cả các thuộc tính (Attributes) 
                    và Phương thức (method) của class cha. Tuy nhiên Sub class chỉ có thể truy cập được các 
                    thuộc tính và phương thức của Super class có Access modifier là protected và public của Super Class. 
                  
    ```
    
- Systax
  ``` Java
    class Subclass-name extends Superclass-name {  
       //methods and fields
    } 
  ```   
  
- Example
   ``` java
    class Employee {
       float salary = 1000;
    }

    class Programmer extends Employee {
    int bonus = 150;
    }
      
    public class InheritanceSample1 {
      public static void main(String args[]) {
        Programmer p = new Programmer();
        System.out.println("Programmer salary is: " + p.salary);
        System.out.println("Bonus of Programmer is: " + p.bonus);
      }
    }
  ```


3. Abstraction


































4. Polymorphism

---
# 3. Access Modifier

- Có 2 loại Access Modifier : 
  - Access Modifier 
    1. Private
    2. default
    3. protected
    4. public
  - Non-Access Modifier
    1. static
    2. abstract
    3. ...
- Access Modifier : dùng để định nghĩa phạm vi truy cập của biến, contructor, method.
---

  ![img_4.png](img_4.png)