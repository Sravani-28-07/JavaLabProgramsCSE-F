#EXPERIMENT 3
##EXP 3a)Title:Constructor overloading
```java

class Student {
int id;
String name;
int age;
Student() {

}

Student(int i,String n,int a){
id=i;
name=n;
age=a;
}
void display(){
System.out.println("name:"+name);
System.out.println("age:"+age);
System.out.println("id:"+id);
System.out.println();
}
}
public class Main{
public static void main(String[] args)
{
Student s1=new Student();
Student s2=new Student(102,"Anita",20);

s1.display();
s2.display();
 }
}

```

#OUTPUT:
![EXPERIMENT 3A OUTPUT](exp3a.png)

