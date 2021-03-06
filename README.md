# CalendarAutomation-Selenium

Calendar automation test. 
		 * target day, month, year
		 * current day, month, year
		 * jump to the month
		 * increment or decrement

# Gif
![](https://github.com/FahirL/CalendarAutomation-Selenium/blob/master/calselenium.gif)

# selenium-webdriver

Selenium is a browser automation library. Most often used for testing
web-applications, Selenium may be used for any task that requires automating
interaction with the browser.

## Installation

Selenium may be installed via npm with

    npm install selenium-webdriver

You will need to download additional components to work with each of the major
browsers. The drivers for Chrome, Firefox, and Microsoft's IE and Edge web
browsers are all standalone executables that should be placed on your system
[PATH]. Apple's safaridriver is shipped with Safari 10 for OS X El Capitan and
macOS Sierra. You will need to enable Remote Automation in the Develop menu of
Safari 10 before testing.


| Browser           | Component                          |
| ----------------- | ---------------------------------- |
| Chrome            | [chromedriver(.exe)][chrome]       |
| Internet Explorer | [IEDriverServer.exe][release]      |
| Edge              | [MicrosoftWebDriver.msi][edge]     |
| Firefox           | [geckodriver(.exe)][geckodriver]   |
| Opera             | [operadriver(.exe)][operadriver]   |
| Safari            | [safaridriver]                     |
