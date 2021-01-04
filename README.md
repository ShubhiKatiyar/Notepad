# Notepad

![Screenshot (30)](https://user-images.githubusercontent.com/73656057/103506489-d3240400-4e82-11eb-84c0-9d14b790db8e.png)

![Screenshot (36)](https://user-images.githubusercontent.com/73656057/103506769-8a207f80-4e83-11eb-81be-7281e3f29d3b.png)

![Screenshot (31)](https://user-images.githubusercontent.com/73656057/103506788-9573ab00-4e83-11eb-8b08-8258725bb486.png)

![Screenshot (32)](https://user-images.githubusercontent.com/73656057/103506801-9f95a980-4e83-11eb-9375-504c8bdf65d1.png)

![Screenshot (33)](https://user-images.githubusercontent.com/73656057/103506820-aa503e80-4e83-11eb-9d6c-f954624a687a.png)

![Screenshot (34)](https://user-images.githubusercontent.com/73656057/103506882-d79cec80-4e83-11eb-9770-a91fa022c349.png)

![Screenshot (35)](https://user-images.githubusercontent.com/73656057/103506901-e7b4cc00-4e83-11eb-83f7-58593bbe6305.png)

![Screenshot (24)](https://user-images.githubusercontent.com/73656057/103506917-f26f6100-4e83-11eb-889f-230b41cbef2d.png)




IDE Used:-Netbeans
Concept Used:-Java,Swing,File Handling
Notepad is a simple text editor made by using Swing concept.


BUILD OUTPUT DESCRIPTION

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "Notepad.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
