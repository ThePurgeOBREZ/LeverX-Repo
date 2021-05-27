Instructions to create .jar file:
  
  cd C:/Users/Asus/IdeaProjects/LeverX-first/src
  
  javac Main.java
  
  jar -cf Main.jar Main.class

To run the file:
  
  javac Main.java
  
  java -classpath . Main

The result will be:
  Hello, LeverX!

To import a new lib:
javac -d bin -classpath bin:libs/apache-commons.jar -sourcepath src src/LeverX/Main.java
