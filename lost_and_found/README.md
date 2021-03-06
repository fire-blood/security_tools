![lost_and_foundlogo](https://user-images.githubusercontent.com/53983340/90346437-568da780-dfff-11ea-8ec8-8de7b5f4d885.png)

<p>
 <img src="https://img.shields.io/badge/lost_and_found-v.0.1-yellow" />
 <img src="https://img.shields.io/badge/python-v.3.7.7-blue" />
 </p>
 
### Objective

Lost_and_Found is a tool to search specific files in Windows and Linux Files System.
The goal is found specific files quickly in a wide file system. 

### Prerequisites

```
- Python 3.7.7 or later. <https://www.python.org>
```

### Modules

```
- os
- argparse
- datetime
- pyfiglet
```

### Quick Start

1. Clone the latest version of security_tools from git clone command:

 ```
    git clone https://github.com/carineconstantino/security_tools/
 ```
    
 2. Access security_tools folder, list it and choose **lost_and_found** folder:
 
 ```
   cd security_tools
   ls -l
   cd lost_and_found
 ```
 
 3. Choose **--location** to set path and **-e** for specific file extension:
 
 ```
   python3 lost_and_found.py --location C:\\ -e .exe
 ```

