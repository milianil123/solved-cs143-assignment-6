Download Link: https://assignmentchef.com/product/solved-cs143-assignment-6
<br>
This programming exercise is based on the material presented in chapter 19.1 of the 3rd edition of the class textbook. Specifically, the section titled, “Introduction to the Java Collections Framework”.

The Java collection ArrayList implements the Iterable&lt;E&gt; interface, which provides two methods that can be used to iterate through a collection.  These two methods are:

·        forEach()

·        removeIf()

The parameter to these two methods can be a lambda expression to be applied to each element, one after another across the entire collection. An example of using the forEach() method with an ArrayList is shown in Code List 19-1 of the 3rd edition of the text book in a source file named, ForEachDemo.java. A copy of this source file is included in the Canvas module titled, “Week 6 – Chapter 19”. Note that the chapter number is different in newer editions of the text. However, in all cases, the chapter is titled, “Collections and the Stream API”.

CaseChanger

There are two source files to be used for this assignment. They are located under the the Canvas module titled, “Week 6 – Chapter 19”. The two source files are:

·        java

·        java

The CaseChanger class has four public static methods:

·        ArrayList&lt;String&gt; mangleToUpperCase( ArrayList&lt;String&gt; stringList )

·        ArrayList&lt;String&gt; mangleToLowerCase( ArrayList&lt;String&gt; stringList )

·        ArrayList&lt;String&gt; mangleCapitalize( ArrayList&lt;String&gt; stringList )

·        ArrayList&lt;String&gt; mangleToUpperLowerCase( ArrayList&lt;String&gt; stringList )

All four of these methods take a single ArrayList&lt;String&gt; parameter, and return a modified (mangled) version incoming ArrayList&lt;String&gt;.

mangleToUpperCase changes all the strings in the ArrayList to upper case.

mangleToLowererCase changes all the strings in the ArrayList to lower case.

mangleToCapitalize changes all the strings in the ArrayList to be capitalized (i.e., the first letter of each string is upper cased, the letters after the first character of each string are lower cased).

mangleToUpperLowerCase changes all the even numbered characters to upper case, and the odd numbered characters to lower case (e.g., abcdefg becomes AbCdEfG).