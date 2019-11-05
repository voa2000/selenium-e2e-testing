# Selenium

### Selenium is a portable framework for testing web applications. Selenium provides a playback tool for authoring functional tests without the need to learn a test scripting language.

A brief history of Selenium
Selenium was born in 2004 when Jason
Huggins, an engineer at ThoughtWorks,
was working on an application that
required lots of manual testing. He
developed JavaScript code that could
automate control of the browser, greatly
streamlining the test process. This code
came to be called “Selenium Remote
Control” and was open-sourced later
that year. Over the next few years, other
developers got involved in the project
and a few Selenium-related projects
were spawned, including Selenium Grid,
Selenium IDE, and Selenium WebDriver.
This increasingly powerful set of tools
is, as of now, essentially one fully
coordinated test framework.

“Selenium automates browsers. That's it!” - SeleniumHQ

• Test scripts can be written in any of these programming languages: Java, Python, C#, PHP, Ruby, Perl & .Net.

• Tests can be carried out in any of these OS: Windows, Mac or Linux.

• Tests can be carried out using any browser: Mozilla Firefox, Internet Explorer, Google Chrome, Safari or Opera.

• It can be integrated with tools such as TestNG & JUnit for managing test cases and generating reports.

• It can be integrated with Maven, Jenkins & Docker to achieve Continuous Testing.

### But there surely has to be shortcomings right?

• We can use Selenium only to test web applications. We cannot test desktop applications or any other software.

• There is no guaranteed support available for Selenium. We need to leverage on the available customer communities.

• It is not possible to perform testing on images. We need to integrate Selenium with Sikuli for image based testing.

• There is no native reporting facility. But we can overcome that issue by integrating it with frameworks like TestNG or JUnit.

It’s really that simple. Obviously, in practice, there’s a little more to it than that, and we’ll touch on some of
the issues and quirks related to making good use of Selenium. However, the bottom line is that Selenium is
a set of tools that allow you automate web testing. It has evolved a bit over the years; as of 2018, there are
3 main components that comprise the Selenium platform.
1) Selenium IDE - Firefox/Chrome extensions that allow recording and playback of user actions
2) WebDriver (aka Selenium 2.0) - an API that allows direct interaction with browsers, offering
 wider browser support and more complex browser interactions (WebDriver basically supplanted
 Selenium Remote Control by expanding and improving on it in many ways)
3) Selenium Grid - a tool which allows spreading tests over multiple physical or virtual machines,
 allowing for parallel testing and scaling.
 
Download Chrome Driver 
• https://chromedriver.storage.googleapis.com/index.html?path=78.0.3904.70/

.° https://www.seleniumhq.org/download/

# WebDriver.IO

WebDriver.IO is the leading WebDriver binding for Node.JS. The framework basically
sends requests to the Selenium server via the WebDriver protocol and manages the
responses. The requests are wrapped in useful commands for ease of development,
re-use for multiple test scenarios of your web site and more.
The integrated test runner let you write asynchronous commands in a synchronous
way so that you don’t need to care about how to handle a Promise to avoid racing
conditions. Additionally, it takes away all the cumbersome setup work and manages the
Selenium session for you.
Working with elements on a page is very easy due to its synchronous nature. When fetching or
looping over elements you can use just native JavaScript functions. With the $ and $$functions
WebdriverIO provides useful shortcuts which can also be chained to move deeper in the DOM tree
without using complex xPath selectors.
The WDIO framework is easily integrated to many tools, therefore, during the config file setup,
test automation engineers, can specify their tool stack (Cucumber, Mocha, Jasmine), local vs. cloud
Selenium grid and more.
### https://martinfowler.com/bliki/PageObject.html
# Selenium Documentation
https://selenium.dev/selenium/docs/api/javascript/
