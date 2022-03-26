# Chelnakov Sergey 
![Photo](https://github.com/stanlys/rsschool-cv/blob/gh-pages/Screenshot_1.jpg)

# Contact 
* **Location:** Russia, Voronezh
* **E-mail:** Stanlys@yandex.ru
* **Phone:** +7 950 762-80-67
* **GitHub:** [@Stanlys](https://github.com/stanlys)
* **Discord:** [stanlys#9480](https://discord.com/channels/516715744646660106/846704784274751509)  

# About Me
I am 36 year old.I work as a department head in a land surveying company. In my work, I constantly have to deal with the automation of office operations. I feel burned out in this area, I want to develop in the field of web technologies, so I signed up for this course. Until 2010 worked as a Delphi programmer. 

# Skils 
* HTML
* JavaScript (Basic)
* Python (Basic)
* Visual Basic (Basic)
* Delphi 7-2010 () 

# Code Example 
```
from selenium import webdriver
import math
from selenium.webdriver.support.ui import Select
import os 

def calc(x):
  return str(math.log(abs(12*math.sin(int(x)))))

browser = webdriver.Chrome()
link = "http://suninjuly.github.io/redirect_accept.html"
browser.get(link)
button = browser.find_element_by_css_selector("button.btn")
button.click()
#swith to new window
browser.switch_to.window(browser.window_handles[1])
num1 = browser.find_element_by_css_selector("#input_value").text
browser.find_element_by_css_selector("#answer").send_keys(calc(num1))
button = browser.find_element_by_css_selector("button.btn")
button.click()
```

# Education 
* **Voronezh State Pedagogical University**
    + Teacher Informatic an Mathematic
* **Stepic**
    + Selenium and Python
    + Python
    + HTML & CSS

# Languages
* **Russian** - Native speak
* **English** - B1
* **Polish** - A2 (in progress...)

  
