# Load

Load simulation

Program what emulate loading with status bar

***Requires Java version 8 or higher installed***

Enter the commands one by one:

#### Linux:

```
sudo apt install git

git clone https://github.com/remumaru/Load.git

cd Load

javac load.java

java load <long period (millisec:optional)> <String symbol (char:optional)> <String symbol_end (char:optional)> <int process_bar_length (num:optional)>

```
#### Windows:

```
javac load.java

java load <long period (millisec:optional)> <String symbol (char:optional)> <String symbol_end (char:optional)> <int process_bar_length (num:optional)>

```
#### Example: 
```
java load 400 "=" ">" 20
```
