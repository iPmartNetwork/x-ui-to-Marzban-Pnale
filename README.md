
<p align="center">
<picture>
<img width="160" height="160"  alt="XPanel" src="https://github.com/iPmartNetwork/iPmart-SSH/blob/main/images/logo.png">
</picture>
  </p> 
<p align="center">
<h1 align="center"/>x-ui to Marzban Pnale</h1>
<h6 align="center">انتقال یوزر و دیتای پنل ایکس یو ای به پنل مرزبان 
<h6>
</p>


<p align="center">===========================================================================




## x-ui data and user convert and move to marzban panel




# [X-Ui](https://github.com/MHSanaei/3x-ui) To [Marzban](https://github.com/Gozargah/Marzban)


 کاربران خود را به سادگی از X-Ui به مرزبان منتقل کنید

## Table of Contents
- [About](#about)
- [Prerequisites](#prerequisites)
- [Linux](#Linux)
- [Windows](#windows)



<p align="center">===========================================================================


قبل از اجرای اسکریپت، اطلاعات پنل های خود را در فایل config.py به‌روزرسانی کنید:

#### راهنمایی : فایل را در یک نرم افزار کد ادیتور باز کنید و مشخصات را به مشخصات پنل های خودتون تغییر داده و ذخیره کنید .

```python

# Define Variables for Both Panels

# X-Ui Panel

X_DOMAIN = "YOUR_DOMAIN"
X_PORT = "YOUR_PORT"
X_USERNAME = "YOUR_USERNAME"
X_PASSWORD = "YOUR_PASSWORD"
X_HTTPS = False  # Set to True to use HTTPS, False to use HTTP
X_FORK = 1 # Set to 1 if you have MHSanaie, Set to 2 if you have Alireza (Default: MHSanaie)

# Marzban Panel

M_DOMAIN = "YOUR_DOMAIN"
M_PORT = "YOUR_PORT"
M_USERNAME = "YOUR_USERNAME"
M_PASSWORD = "YOUR_PASSWORD"
M_HTTPS = False  # Set to True to use HTTPS, False to use HTTP
```

<p align="center">===========================================================================



## About

This script is designed to simplify the transfer of user data from [X-Ui](https://github.com/MHSanaei/3x-ui) to [Marzban](https://github.com/Gozargah/Marzban)
 using the Marzban API. It securely logs into both panels, retrieves user data from X-Ui, and adds it to Marzban.

 
### Prerequisites
Python 3.0+ with the requests library is required. The script is not compatible with Python 2.0.
### Linux
```bash
# Clone the Repository
git clone https://github.com/ipmartnetwork/x-ui-to-Marzban-Panel.git

# Change Directory
cd x-ui-to-Marzban-Panel

# Install pip (if not already installed)
wget -qO- https://bootstrap.pypa.io/get-pip.py | python3 -

# Install Dependencies
python3 -m pip install -r requirements.txt

# Run the Script
python3 main.py
```
### Windows
```bash
# Clone the Repository
git clone https://github.com/ipmartnetwork/x-ui-to-Marzban-Panel.git

# Navigate to the Repository Directory
cd x-ui-to-Marzban-Panel

# Install Python3 (if not already installed)
# Download and install Python3 from https://www.python.org/downloads/
# Ensure you add Python to your system's PATH during installation

# Install Dependencies
pip install -r requirements.txt

# Run the Script
python3 main.py
```




# تلگرام

[@ipmart_network](https://t.me/ipmart_network)

[@iPmart Group](https://t.me/ipmartnetwork_gp)




 # حمایت از ما :hearts:
حمایت های شما برای ما دلگرمی بزرگی است<br> 
<p align="left">
<a href="https://plisio.net/donate/kB7QU7f7" target="_blank"><img src="https://plisio.net/img/donate/donate_light_icons_mono.png" alt="Donate Crypto on Plisio" width="240" height="80" /></a><br>
	
|                    TRX                   |                       BNB                         |                    Litecoin                       |
| ---------------------------------------- |:-------------------------------------------------:| -------------------------------------------------:|
| ```TJbTYV1fFo2485sYMyajxGPLFzxmNmPrNA``` |  ```0x4af3de9b303a8d43105e284823d95b4c600961a3``` | ```MPrkzFiNtw4Rg67bbZB6gCxa9LV87orABM``` |	

</p>	




<p align="center">
<picture>
<img width="160" height="160"  alt="XPanel" src="https://github.com/iPmartNetwork/iPmart-SSH/blob/main/images/logo.png">
</picture>
  </p> 



