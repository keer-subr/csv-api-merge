Instructions
------------
Files included in WPEngine-Coding.zip:
1. README file
2. wpengine file to run the program. Rename this file to wpengine.jar
3. wpe_merge file to invoke the jar file. Rename this file to wpe_merge.bat
4. wpengine-coding-exercise.zip file with the solution. Please open this in Eclipse IDE to review the source code for solution and tests.The following location has the source code files: wpengine-coding-exercise.zip\wpengine-exercise\src\main\java\com\wpengine\app

How to run
----------
Invoke the wp_merge.bat file with the following command:
wpe_merge.bat <input-file> <output-file>
Please use the full file path location to the files

Constraints
------------
If a line does not contain ',' it is considered invalid
If a line has only space or ',' it is considered invalid
A blank line or a line with only space characters is considered invalid.
A line which contains only characters other than A-Z, a-z and 0-9 is considered invalid.
If there is more than one record with the same account ID it considered valid.
Running the application each time, rewrites the output file. It does not append to the existing output.

Dependencies
----------------
JSON Library: Jackson Databind 
Logging framework: slf4j 
Testing Frameworks: Junit, Hamcrest
OS: Windows
