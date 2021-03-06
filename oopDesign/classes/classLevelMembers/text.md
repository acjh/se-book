<link rel="stylesheet" href="{{baseUrl}}/css/textbook.css">

<div class="website-content">

<div id="title">

#### Class Level Members :two:

</div>

<div id="body">

While all objects of a class has the same attributes, each object has its own copy of the attribute value.

<tip-box>

Example:

All `Person` objects have the `Name` attribute but the value of that attribute varies between `Person` objects.

</tip-box>

However, some attributes are not suitable to be maintained by individual objects. Instead, they should be maintained centrally, shared by all objects of the class. They are like ‘global variables’ but attached to a specific class. Such **variables whose value is shared by all instances of a class are called ==_class level_ attributes==**.

<tip-box>

Example:

The attribute `totalPersons` should be maintained centrally and shared by all `Person` objects rather than copied at each `Person` object.  

</tip-box>

Similarly, when a normal method is being called, a message is being sent to the receiving object and the result may depend on the receiving object.

<tip-box>

Example:

Sending the `getName()` message to `Adam` object results in the response `"Adam"` while sending the same message to the `Beth` object gets the response `"Beth"`.

</tip-box>

However, there can be methods related to a specific class but not suitable for sending message to a specific object of that class. Such **methods that are called using the class instead of a specific instance are called ==class-level methods==**.

<tip-box>

Example:

The method `getTotalPersons()` is not suitable to send to a specific `Person` object %%because a specific object of the `Person` class should not know about the total number of `Person` objects%%.

</tip-box>

**Class-level attributes and methods are collectively called ==_class-level members_==** (also called _static members_ sometimes because some programming languages use the keyword `static` to identify class-level members). **They are to be accessed using the class name rather than an instance of the class**.

<dynamic-panel src="../../../uml/classDiagrams/classLevelMembers/what/full.md" header=":mortar_board: UML &rarr; Class Diagrams &rarr; Class Level Members" />

<p/>

:package: A `Student` class with a class-level attribute and a method:

<img src="{{baseUrl}}/oopDesign/classes/classLevelMembers/images/person.png" height="100" />
<p/>

</div>

<div id="extras">

<include src="exercises.md" />

</div>

</div>
