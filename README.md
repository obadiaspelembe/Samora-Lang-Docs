# [Samora Lang](https://github.com/GraHms/Samora-Lang) Docs

## Getting started
Samora Lang is simple a interpreted programing language just for educational purposes. Samora Lang was originally created by Ismael GraHms as a fun programming language for educational purposes.


### Installation

#### Windows
You can install Samora Lang on your Windows system by running the [Windows Installer](https://github.com/obadiaspelembe/samora-lang-installers) powershell script. Download the script and simply run the following command to install:

````
C:\Downloads> .\installer.ps1
````
After the installation completes you can test by simply running the following command:

````shell
C:\Workspace> samora hello.sml
````

#### Arch Linux
You can install Samora Lang interpreter by using the Arch user repository with the following command

````sh
$ yay -S samora-lang 
````
#### Debian Based Distros
For debian based distros, execute the following commands:

* curl
````sh
$ sudo curl -sSL https://raw.githubusercontent.com/obadiaspelembe/samora-lang-installers/main/Unix/installer.sh | bash
````

* wget
````sh
$ sudo wget -O - https://raw.githubusercontent.com/obadiaspelembe/samora-lang-installers/main/Unix/installer.sh | bash
````


## Samora Lang Paradigm

Samora Lang is a general purpose programming language based on procedural programming.

### Syntax 
Samora Lang was originally built to be simplier to `Write` and `Read`. Lets have a quick example of a hello world program.

````go
print("Hello, World!");
````

Reading this example you easily understand that this program prints a message `Hellom, World!` in your console.

Samora Lang programs are written in a `.sml` extension files so that interpreter can run the program. Create `hello.sml` file to write our program. After creating the file we can execute by calling the `samora` interpreter.


````sh
$ samora hello.sml
Hello, World!
````

#### Variables 

Samora Lang variables are declared via the keyword `let` + `variable name`. Example:

````go
let name = "Samora"

````

Variables in Samora Lang support the following primary data types:

* `Integers`
* `Floats`
* `String`
* `Boolean`

NOTE: Variables in Samora Lang are not strongly typed.

#### Numeric Types
For numeric types Samora Lang provides two different data types `Integers` and `Floats`.

````go
let age = 8
let heightInMeters = 1.8
````

##### Arithmetic Operators
The following arithmetic operators are available for numeric types:


|Operator   |Name           |Example   |
|-----------|---------------|----------|
|`+`	    |Addition	    |x + y     |	
|`-`	    |Subtraction	|x - y     |	
|`*`	    |Multiplication	|x * y     |	
|`/`	    |Division	    |x / y     |	
|`%`	    |Modulus	    |x % y     |	
|`**`       |Exponentiation	|x ** y	   |
|`//`       |Floor division	|x // y    |

Examples:

````go
let m1 = 8
let m2 = 7
let sum = m1 + m2
````

## Contributions
PR are welcome to the Open-Source project hosted under github project [Samoral-Lang](https://github.com/GraHms/Samora-Lang).
