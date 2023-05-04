Download Link: https://assignmentchef.com/product/solved-csci804-lab9-string-stream
<br>
<h1>Task One: String Stream</h1>

Use <strong>ostringstream </strong>and <strong>istringstream </strong>to implement the following <strong><em>two functions </em></strong>in a file <strong>stringIO.cpp</strong> by assuming that the operators &lt;&lt; and &gt;&gt; have been overloaded for type T.  template&lt;class T&gt; string toString (T value); // convert a value into a string

template &lt;class T&gt;

T toValue(string str); // extract the value from a string

Defined a class <strong>Student</strong> in a file <strong>Student.h</strong> and implemented the member functions  in a file

<strong>Student.cpp</strong>. The class Student can be defined like following class Student { private:

string firstname; string lastname; int id; // student number float gpa;

public:

// all necessary functions to be defined here … …

};

Implement a main() function in <strong>stringIO.cpp</strong> to test the two functions in the cases where T is <strong>integer</strong>, <strong>double </strong>and <strong>class Student. </strong>




You need to define and implement the student class properly in order to test the two template functions and assume the input string for the student class is in the following format.




First-name:last-name:student-number:gpa




For example:

John:Anderson:1234567:6.35




Testing:




Compile the program in this task by:

CC –o task1 stringIO.cpp Student.cpp




Run the program (You may use different values)

./task1

Input an integer: 12345678

Integer to string: 12345678

String to integer: 12345678

Input a double: 3214.654

Double to string: 3214.65

String to double: 3214.65

Input a student record (first-name:last-name:number:gpa): David:Smith:1234567:3.65 Student to string:  David:Smith:1234567:3.65 String to Student:

David:Smith:1234567:3.65

<strong> </strong>

<strong>Note:</strong> The outputs above indicate different types of data.

<strong> </strong>

<h1>Task two: Compare two vectors</h1>

The program <strong>vectorCompare.cpp</strong> intends to implement and test a predicate function:

bool same_elements(vector&lt;int&gt; a, vector&lt;int&gt; b)

that checks whether two vectors have the same elements with the same multiplicities. For example, “1 4 9 16 9 7 4 9 11” and “11 1 4 9 16 9 7 4 9” would be considered identical, but “1 4 9 16 9 7 4 9 11” and “11 11 7 9 16 4 1” would not.

And a function that removes duplicates from a vector:

void remove_duplicates(vector&lt;int&gt;&amp; a)

Complete the implementation of these two functions in the given <strong>vectorCompare.cpp</strong> file . You will probably need one or more helper functions for the implementation. Place the helper functions in the specified place. Complete the main function and test your implementation.


