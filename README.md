Download Link: https://assignmentchef.com/product/solved-utcn-lab9-adding-security-on-an-api-and-consuming-the-api-in-a-desktop-application
<br>
The objective of this assignment is to extend the second assignment by adding security on an API and consuming the API in a desktop application.

2. Application Description

Use JAVA Spring/C# Web API in combination with JAVA Swing/.NET WinForms to design and implement an application for tracking the laboratory activity for the Software Design laboratory. The requirements of the application are provided in Assignment 2. Additional requirements are:

<ul>

 <li>Create a desktop application to consume the APIs. Have screens for login, teacher side: register students, laboratory, assignments, attendance and grading; student side: first time register, login, laboratory, assignments, post attendance and grading. Nice to have: view attendance for students. Any additional feature that you consider helpful is highly appreciated. [8 points]</li>

 <li>Secure all APIs with an authorization header that contains an Email and a Password. First, you will have to check that the password is correct and then find out the role (Teacher/Student) for that given user. Do <strong>not do this logic in every controller method, </strong>this logic is common for all controllers, so it has to be at a higher level<strong>.</strong> Depending on the roles, some APIs might be accessed only by the teacher (for example: add student, add laboratory), only by the student (submit assignment) or by both (view laboratories).</li>

 <li>Encrypt the password from the UI with a one direction algorithm and then work with the password encrypted. [1 point] Nice to have:</li>

 <li>Create a system that notifies by email all students when a new assignment is posted by the teacher.</li>

 <li>When a new user is added by the teacher, the token is sent by email. [extra points]</li>

</ul>




<h2>3. Requirements</h2>

<ul>

 <li>Extend on the analysis and design document (see the template).</li>

 <li>Implement and test the application.</li>

</ul>

<strong> </strong>

<h2>4. Deliverables</h2>

–    GIT/TFS link with:

<ol>

 <li>Analysis and design document.</li>

 <li>Source files.</li>

 <li>SQL script for creating and populating the database with initial values.</li>

 <li><strong>Deadline – 2 weeks </strong></li>

 <li><strong>Resources: </strong></li>

</ol>

<strong> </strong>

<strong>Web Api: </strong>

<a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">https://app.pluralsight.com/library/courses/implementing</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">–</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">restful</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">–</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">aspdotnet</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">–</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">web</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">–</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">api/table</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">–</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">of</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">–</a><a href="https://app.pluralsight.com/library/courses/implementing-restful-aspdotnet-web-api/table-of-contents">contents</a> <strong>Spring Boot: </strong><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">https://javabrains.thinkific.com/courses/take/springboot</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">–</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">quickstart/multimedia/2784009</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">–</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">adding</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">–</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">a</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">–</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">rest</a><a href="https://javabrains.thinkific.com/courses/take/springboot-quickstart/multimedia/2784009-adding-a-rest-controller">controller</a>

<strong> </strong>