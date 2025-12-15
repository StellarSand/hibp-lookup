# hibp-lookup
A lightweight command-line tool that integrates with [Have I Been Pwned?](https://haveibeenpwned.com/) to help you verify whether your emails have been compromised in any publicly disclosed data breaches. 



## Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Available options](#available-options)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)




## Prerequisites
- [cURL](https://curl.se/)
- [jq](https://jqlang.org/)

Both of them can be installed from your distro's package manager.



## Installation
**1. Clone this repo:**
```
git clone https://github.com/StellarSand/hibp-lookup.git
```

**2. Move into the project directory:**
```
cd hibp-lookup
```

**3. Give executable permissions to the script:**
```
chmod u+x hibp-lookup
```



## Available options
```
  <email>             Check a single email address
  -f <file>           Check multiple email addresses from a text file (one per line).
  -c, --compact       Print data without details & additional links
  -h, --help          Show this help message
```



## Usage
```
hibp-lookup <email>
```
```
hibp-lookup -f <file>
```

**Examples:**
```
hibp-lookup johndoe@example.com
```

```
hibp-lookup -f /home/JaneDoe/Downloads/emails.txt
```




## Issues
If you find bugs or have suggestions, please report it to the [issue tracker](https://github.com/StellarSand/hibp-lookup/issues). 
- Please search for existing issues before opening a new one. Any duplicates will be closed.



## Contributing
Pull requests can be submitted [here](https://github.com/StellarSand/hibp-lookup/pulls).



## License
This project is licensed under the terms of [GPL v3.0 license](https://github.com/StellarSand/hibp-lookup/blob/main/LICENSE).
