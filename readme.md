
# Selenium WebDriver

This is where I keep some notes for Selenium WebDriver automation testing.

# To make Chrome work without closing imediatly






```sh
  from selenium.webdriver.chrome.service import Service
  from selenium.webdriver.chrome.options import Options
  from webdriver_manager.chrome import ChromeDriverManager
  options = Options()
  options.add.experimental_option("detach", True)
  driver = webdriver.Chrome(service=Service(ChromeDriverManager().install()), options=options)
```
    