## [Lesson02](../readme.md) > Exercise04:

1. Open class [Main](../app/src/main/java/org/dii/oop/Main.java) in package `main.java.org.dii.oop` and edit the code to call Lesson.run() method from `exercise04`.


2. Create your own Student class inside package `main.java.org.dii.oop.exercise04`  with the following requirements.
    * Instance your student object by getting the student attributes from the command line.
      ```
      // Command for getting the input from a keyboard using `Scanner` class
      ...
      import java.util.Scanner;
      ...
      Scanner in = new Scanner(System.in);
      ...
      String inputDate = in.nextLine();
      student.xxxx = inputDate;
      ...
      ```
    * Create a student object one by one and store it in the collection by using the Vector class.
      ```
      ...
      Vector<Student> students = new Vector<>();
      ...
      students.add(student);
      ...
      ```
    * Display all student objects in the collection by using the following code:
      ```
      for (Student student : students) {
        System.out.println("Student xxxx: " + student.xxxx);
        ...
      }
      ```
    * Use a loop to run the program until the user decides to exit the program.
   

3. Write the code in class [Lesson](../app/src/main/java/org/dii/oop/exercise04/Lesson.java) of package `main.java.org.dii.oop.exercise04`. An example of the running program:
```
// suppose your Student class is
class Student {
   String xxxx;
   String yyyy;
}
```

An example of the program execution:

```
1. Add new student
2. Display all students
3. exit
Select the number [1-3]: 1

Input the xxxx: value-xxxx
Input the yyyy: value-yyyy

1. Add new student
2. Display all students
3. exit
Select the number [1-3]: 2

List of student:
    xxxx: value-xxxx, yyyy: value-yyyy
    xxxx: value-xxxx, yyyy: value-yyyy
    xxxx: value-xxxx, yyyy: value-yyyy
    ...
```
