```
public class StudentDerivationFromPerson {
    public static void main(String[] args) {

        //create new object  of class 'student'
        Student courseStudent = new Student();
 
        /* Your solution goes here  */
        //pass expected output values into object as parameters to update its value
        courseStudent.setName("Smith");
        courseStudent.setAge(20);
        courseStudent.setID(9999);

        //print
        courseStudent.printAll();
        System.out.print(", ID: ");
        System.out.println(courseStudent.getID());

        //printAll: System.out.print("Name: " + lastName);
        //getID: System.out.print(", Age: "  + ageYears);
    }
}

//Expected output: Name: Smith, Age: 20, ID: 9999

``` 
