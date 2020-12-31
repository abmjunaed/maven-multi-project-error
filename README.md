# maven-multi-project-error
From the parent folder: mvn clean
mvn compile
You will see there is an error in springBoot/src/main/java/ApiUtil.java

Now open springBoot/pom.xml and put the dependency to the com.example at the end of the dependencies

Now again from the parent folder: mvn clean
mvn compile
The error is gone!
