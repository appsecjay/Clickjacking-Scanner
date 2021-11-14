# Clickjacking-Scanner
A Simple python script designed to check if the website is vulnerable of clickjacking and creates a poc.




## Usage

copy `python(3) clickjacking_Scanner.py <file_name>`

## Example
<copy-button>`python3 clickjacking_Scanner.py sites.txt`</copy-button>

### sites.txt [List of domain]

`www.google.com`
`www.demo.testfire.net`

## Output

[*] Checking www.google.com

 [-] Website is not Vulnerable!

[*] Checking www.demo.testfire.net

 [+] Website is Vulnerable!
 [*] Created a poc and saved to <Domain Name>.html

















All Credits goes to https://github.com/D4Vinci/Clickjacking-Tester
