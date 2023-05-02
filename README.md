Download Link: https://assignmentchef.com/product/solved-cop2337c-project-version-2
<br>
For version 2 you will add the concept of Inheritance.

Features:

<ul>

 <li>A subclass called <em>PartTimeEmployee, </em>to be inherited from the <em>Employee</em> class<em>. </em>

  <ul>

   <li>pts) This class will inherit all of the fields and methods of an <em>Employee</em>, and will include the following additional private fields:

    <ul>

     <li><em>weeklyHoursWorked </em>o <em>hourlyRate </em></li>

    </ul></li>

  </ul></li>

</ul>

The PartTimeEmployee class will also include the following methods:

<ul>

 <li>(10 pts) Constructors:</li>

 <li>Default constructor that initializes the two private fields to zero in addition to calling the superclass default constructor.</li>

 <li>Parameter Constructor that sets the two private field values in addition to calling the superclass parameter constructor. o (5 pts) Include mutator methods for the two new member fields. o  (5 pts) Include accessor methods for the two new member fields.</li>

 <li>(10 pts) Include the following public method called <em>CalculateWeeklyPay(). </em>This method should calculate and <em>return</em> the weekly pay based on the following:</li>

</ul>

If 40 hours or less are worked:

weeklyPay = weeklyHoursWorked * hourlyRate

If over 40 hours are worked:

Regular pay for the first 40 hours plus an additional amount of 1.5 the hourlyRate for all hours worked over 40.

<ul>

 <li>A subclass called <em>FullTimeEmployee, </em>to be inherited from the <em>Employee</em> class<em>. </em>

  <ul>

   <li>pts) This class will inherit all of the fields and methods of an <em>Employee</em>, and will include the following additional private field: o <em>annualSalary </em></li>

  </ul></li>

</ul>

The FullTimeEmployee class will also include the following methods:

<ul>

 <li>(10 pts) Constructors:</li>

 <li>Default constructor that initializes the private field to zero in addition to calling the superclass default constructor.</li>

 <li>Parameter Constructor that sets the private field value in addition to calling the superclass parameter constructor. o (5 pts) Include a mutator methods for <em>annualSalary</em>. o  (5 pts) Include accessor methods for <em>annualSalary</em>.</li>

 <li>(10 pts) Include the following public method called <em>CalculateWeeklyPay(). </em>The weekly pay will be based on a 52-week year.</li>

</ul>

(10 pts) Update your UML diagram to represent the Employee Hierarchy.

o (20 pts) Create a driver class called <em>EmployeeTester</em>.  Be sure to fully test your class.