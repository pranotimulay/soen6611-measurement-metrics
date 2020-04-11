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
    ├── docs                                      # Presentation, IEEE Report, and Project Proposal
    └── README.md

# Tool Requirements and Pre-requisites 
#### EclEmma (JaCoCo)
Installation Steps: 
```
    Step 1. Go to Help → Eclipse Marketplace in Eclipse
    Step 2. Search for "EclEmma".
    Step 3. Select Install option for "EclEmma Java Code Coverage".
    Step 4. Follow the further steps in the installation wizard.
```
#### PIT Testing
Plugin to be added in pom.xml
```
<plugin>
    <groupId>org.pitest</groupId>
    <artifactId>pitest-maven</artifactId>
    <version>LATEST</version>
 </plugin>
 ```
#### CLOC
Installation
```
  npm install -g cloc                    # https://www.npmjs.com/package/cloc
  sudo apt-get install cloc              # Debian, Ubuntu
  sudo yum install cloc                  # Red Hat, Fedora
  sudo pacman -S cloc                    # Arch
  sudo pkg install cloc                  # FreeBSD
  sudo port install cloc                 # Mac OS X with MacPorts
```  
Running on Windows    
Invoke cloc.exe as shown below
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
