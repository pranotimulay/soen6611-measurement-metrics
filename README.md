# Software Measurement Metrics Correlation Analysis
The aim of this project is to measure different projects with respect to various metrics and analyze the correlation between these metrics. The metrics being studied are enlisted below, followed by the open-source projects they are being applied on.

#### Metrics
1. **Statement Coverage:** measurement procedure wherein the number of lines of code covered under certain circumstances is calculated based on the inputs from the users.
2. **Branch Coverage:** Branch coverage is a measurement to calculate the number of branches executed per user input.
3. **Mutation Score:** Mutation score is a testing practice wherein we check the accuracy or precision of the test cases.
4. **Cyclomatic Complexity:** Cyclomatic Complexity is the measure number of linearly independent paths that can be executed in a program.
5. **Adaptive Maintenance Effort Model (AMEffMo)**: a model for estimating adaptive maintenance effort
6. **Software Defect Density**: the number of defects per size of the software or application area of the software

#### Projects
1. **Apache Commons Logging** - [*documentation*](https://commons.apache.org/proper/commons-logging/) , [*source-code*](https://github.com/apache/commons-logging) 
2. **Apache Commons Lang** - [*documentation*](https://commons.apache.org/proper/commons-lang/) , [*source-code*](https://github.com/apache/commons-lang)
3. **Apache Commons Net** - [*documentation*](https://commons.apache.org/proper/commons-net/) , [*source-code*](https://github.com/apache/commons-net)
4. **Apache Commons Math** - [*documentation*](http://commons.apache.org/proper/commons-math/) , [*source-code*](https://github.com/apache/commons-math)

#### File Structure
    ├── correlation                               # Documents used to calculate correlation between metrics
    ├── data analysis                             # Documents containing general analysis of the data collected for each metric
    ├── data                                      # Contains source codes of the projects under study 
    ├── result                                    # Contains data obtained for each metric
    ├── presenation                               # Documents related with presentation and final paper format
    └── README.md

# Tool Requirements and Pre-requisites 
#### EclEmma (JaCoCo)
1. Prerequisites : <br/>
    1.1 Eclipse 3.8 or higher <br/>
    1.2 Java 1.5 or higher. <br/>
    1.3 Eclipse installation must have the Java development tools (included in the default SDK installation) <br/>
2. Installation Steps: 
```
    Step 1. Go to Help → Eclipse Marketplace in Eclipse
    Step 2. Search for "EclEmma".
    Step 3. Select Install option for "EclEmma Java Code Coverage".
    Step 4. Follow the further steps in the installation wizard.
```
3. Verification : The Coverage launcher is visible in the toolbar of the Java perspective

#### PIT Testing
1. Java 5 or above
2. JUnit or TestNG on the classpath.
3. Add the below plugin to build/plugins in pom.xml
```
<plugin>
    <groupId>org.pitest</groupId>
    <artifactId>pitest-maven</artifactId>
    <version>LATEST</version>
 </plugin>
 ```
 3.  Mutation Coverage: Run directly from the commandline
 ```
 mvn org.pitest:pitest-maven:mutationCoverage
```

#### CLOC
1. Below installation commands may work for you according to your Operating System:
```
  npm install -g cloc                    # https://www.npmjs.com/package/cloc
  sudo apt-get install cloc              # Debian, Ubuntu
  sudo yum install cloc                  # Red Hat, Fedora
  sudo pacman -S cloc                    # Arch
  sudo pkg install cloc                  # FreeBSD
  sudo port install cloc                 # Mac OS X with MacPorts
```  
2. To run cloc on Windows computers, <br/>
    2.1 Open up a command prompt (aka DOS) <br/>
    2.2 invoke cloc.exe
```
prompt> cloc
Usage: cloc [options] <file(s)/dir(s)> | <set 1> <set 2> | <report files>
Input Options :
               --diff <set1> <set2>
               --csv  :  Write the results as comma separated values.
               --out=<file>  :  Synonym for --report-file=<file>.
```

# Group J
| Name                       | ID       | Email                         |
|----------------------------|----------|-------------------------------|
| Suruthi Raju               | 40084709 | suruthi77@gmail.com           |
| Pranoti Mulay              | 40129435 | opranoti@gmail.com            |
| Avinash Damodaran          | 40078258 | avinashdamu323@gmail.com      |
| Niralkumar Hemantkumar Lad | 40080612 | niralhlad.concordia@gmail.com |
| Shalin Rohitkumar Patel    | 40088004 | shalinpatel610@gmail.com      |
