# Accelerator
Accelerate the process of learning full stack, quick setup of tools required for fullstack development

## Section 1: Install Git

### Steps to Install Git Bash
1. Download Git from [Git official website](https://git-scm.com/downloads).
2. Run the installer and follow the on-screen instructions.
3. Choose Git Bash as the default terminal.
4. Verify the installation by running:
   ```sh
   git --version
   ```

### Examples of Git Commands
#### Clone a Repository
```sh
git clone https://github.com/example/repo.git
```

#### Commit and Push Changes
```sh
git add .
git commit -m "Initial commit"
git push origin main
```

#### Pull the Latest Changes
```sh
git pull origin main
```

---

## Section 2: Install Node.js

### Steps to Install Node.js
1. Download Node.js from [Node.js official website](https://nodejs.org/).
2. Run the installer and follow the instructions.
3. Verify the installation by running:
   ```sh
   node -v
   ```

### Create a Simple Node.js Console Program
Create a file `app.js` and add the following code:
```js
console.log("Hello, Node.js!");
```

### Run the Program
```sh
node app.js
```

---

## Section 3: Install Java JDK

### Steps to Install Java JDK
1. Download JDK from [Oracle JDK official website](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Install it and set up the environment variables.
3. Verify the installation by running:
   ```sh
   java -version
   ```

### Create and Run a Java Program
Create a file `HelloWorld.java` with the following content:
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

#### Compile and Run the Program
```sh
javac HelloWorld.java
java HelloWorld
```

---

## Section 4: Install Notepad++

### Steps to Install Notepad++
1. Download Notepad++ from [Notepad++ official website](https://notepad-plus-plus.org/downloads/).
2. Run the installer and follow the instructions.
3. Open Notepad++ and verify the installation.

---

## Section 5: Install Visual Studio Code

### Steps to Install VS Code
1. Download VS Code from [Visual Studio Code official website](https://code.visualstudio.com/Download).
2. Run the installer and follow the instructions.
3. Open VS Code and verify the installation.
4. Install extensions for better development experience (e.g., JavaScript, Node.js, Java, Git support).

## Section 6: First Fullstack application

### Using AI - ChatGPT
1. Create folder "my-fullstack-application" and create two files index.html and index.js
2. Go to ChatGPT and give prompt: "Create Node JS App which uses file module to read the index.html from same directory and uses http module to serve the html content on the port 9999"
3. Copy the javascript code provided by ChatGPT into index.js file
4. Again go to ChatGPT and give prompt: "Create good looking web page with title My First Full stack Webpage using bootstrap 5 to demonstrate different sections of website to contain header section to display site name and navigation menu, left avigation section, main section, footer section and right advertisement section"
5. Copy complete html code provided by ChatGPT into index.html
6. Run the appliation using below node command

```sh
node index.js
```

7. Navigate to http://localhost:8080 in your browser
8. Great Job! We have successfully created our first fullstack app using HTML and Node JS
