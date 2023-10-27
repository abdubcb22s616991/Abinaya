import java.utill.ArrayList;
import java.utill.collections;
import java.utill.comparator;
import java.utill.list;

// Define a student class to represenst a student 
class student {
    String name;
    String rollnumber;
    double cgpa;

    public student(String name, String rollNumber, double cgpa) {
    this.name = name;
    this.rollNumber = rollumber;
    this.cgpa = cgpa;
  }
}

public class main {
    //comparator to compare student based on CGPA in descending order
     static class CGPAcomparator implements comparator<student> {
      @override
      public int compare(student student1, student student2) {
       //sort in descending order of cgpa
     return Double.compare(student2.cgpa,student1.cgpa);
  }
  }

     // function to sort a list of stident object based on CGPA in descending orded
    static void sortstudent(list<student>student) {
    // use the CGPA comparator to sort the list.
      colltions.sort(students,newCGPAcomparator());
  }

  public static void main (string[] args) {
     //create a list of student object
     list<student> students = new ArrayList<>();
     student.add(new student("Alice", "A123", 3.8));
     student.add(new student("Bob", "B456", 3.5));
     student.add(new student("Charlite", "C789", 3.9));
     student.add(new student("David", "D101", 3.2));
    student.add(new student("Eve", "E202", 4.0));

    //sort the list of student based on CGPA
    sortstudent (students);

    //print the sorted list
    system.out.println("sorted list of students.byCGPA(Descending order):");
    for(student student:students) {
        system.out.println("Name: " + student.name + ", Roll Number:" + student.rollNumber + ", CGPA " + student.cgpa);
  }
}
}
