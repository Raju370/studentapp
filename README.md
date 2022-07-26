# studentapp


//Customised class

class Student{

String sname;
int sage;
int ssalary;

Student(String name, int age, int salary){
sname = name;
sage = age;
ssalary = salary;

}

}

//App class

class studentApplication{

public static void main(String args []){

Student obj = new Student("Ramana", 23, 20000);

System.out.println(obj.sname+" "+obj.sage+""+obj.ssalary);

}

}

