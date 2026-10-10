\# Java SE JAR Kit



A categorized collection of Java libraries for manual use without Maven or Gradle.



\## Contents



\- PostgreSQL JDBC and database connection pooling

\- JSON processing with Jackson

\- XML processing with JDOM

\- Excel processing with Apache POI

\- PDF processing with Apache PDFBox

\- Apache Commons utilities and logging

\- Lombok for compile-time code generation

\- JSP tags in a separate Java Web section



\## Usage



Copy the required JARs and their dependencies into your project's `lib` folder.



Compile:

javac -cp "lib/\*" Main.java



Run on Windows:

java -cp ".;lib/\*" Main



Run on Linux/macOS:

java -cp ".:lib/\*" Main



\## Notes



\- Use only the libraries needed by your project.

\- Check each library's Java version requirements.

\- Avoid adding multiple versions of the same library to the classpath.

\- Some included versions are old; review updates before production use.

\- JSP tags require a compatible JSP/Servlet environment.



\## Licenses



All libraries belong to their respective owners and retain their original licenses.

Refer to each library's LICENSE and NOTICE files.

