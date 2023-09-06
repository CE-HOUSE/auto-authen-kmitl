# Auto-authen-KMITL

A **_Python script_** that let you automatically authenticate into KMITL network


| :warning: **Warning:** This project is only an experiment on KMITL authentication system and it does not provided a bypass for login system |
| --- |

## Getting started
### Prerequisites
* Python 3.x
* Git
* The static IP on your device must be configured.

### Installation
1. Clone repo 
```
git clone https://github.com/CE-HOUSE/auto-authen-kmitl.git
```
2. `cd` into project directory
```
cd auto-authen-kmitl
```
3. Install python packages
```
pip install -r requirements.txt
```

### Usage

```
python3 authen.py
```

For more information
```
python3 authen.py --help
```



### Config
| Alias | Name | Description |
|:-----:|:----:|-------------|
| `username` | Username | Username to login _(without **@kmitl.ac.th**)_ |
| `password` | Password | Password to login |
| `ipAddress` | ipAddress | Your public IP  |

## Credit
* **_assazzin & CSAG_** for original [Auto-authen-KMITL](https://github.com/assazzin/Auto-authen-KMITL) written in Perl language
* **_Network Laboratory_** for original [Auto-authen-KMITL](https://gitlab.com/networklab-kmitl/auto-authen-kmitl) written in Python language Before CSC-KMITL Upgrade Authen Website
* **_ISAG Laboratory_** for nice space to improve our productivity!
