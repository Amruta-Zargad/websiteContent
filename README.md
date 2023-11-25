
# Welcome to Our World of Automation Testing
"Boost Your Software Quality with Automation Testing"
Have you ever wondered how to make your software testing more efficient, reliable, and, well, automated? You've come to the right place!
Hi there, we're all about making your life easier when it comes to testing software. But before we dive into the nitty-gritty, let's have a friendly chat about what automation testing is all about.

## What's Automation Testing?
In the world of software, automation testing is all about creating scripts and using specialized tools to run tests on your applications automatically. It's like having a trusty software which checks your application for issues and tells you what's good and what needs a little extra.

## With automation testing, you can:
<ul>
<li>Speed Up Things: Automated tests run lightning-fast, saving your time and money.</li>
<li>Increase Reliability: Say goodbye to inconsistent results. Automation provides consistent and precise feedback.</li>
<li>Cover More Ground: Automated tests can explore multiple scenarios, ensuring comprehensive coverage.</li>
</ul>

## Our Expertise in Automation Testing
At "Neuro Spark Work Soloutions Pvt Ltd", we're passionate about automation testing. We'll help you set up the right tools, create effective test scripts, and automate your testing process. There are many tools for automation testing eg:- Playwright, Selenium, Cypress, Katalon, SoapUI etc. In our projects we are using Playwright & Selenium
Ready to experience the magic of automation testing with us? Let's take your software quality to the next level. Get in touch, and let's get started!

Playwright is a modern automation framework for web testing.
With Playwright and TypeScript, you can write efficient and maintainable end-to-end tests for web applications, covering a wide range of browsers and scenarios. 

Selenium with Java allows you to create and execute tests that interact with web applications, automate tasks, and validate user scenarios. It offers compatibility with a wide array of browsers, making it a valuable tool for cross-browser testing.

Both Playwright with TypeScript and Selenium with Java have their unique advantages, and the choice between them often depends on your specific project requirements, your team's expertise, and your preference for the language and ecosystem you're more comfortable with. These combinations empower automation engineers to ensure the quality and reliability of web applications across various platforms and scenarios.

<p align="center">
<img width="646" alt="cycle" src="https://github.com/Amruta-Zargad/websiteContent/assets/149228649/f20e438e-d3a9-41c2-81ad-d7710057adea">
</p>

## Here are some common use cases of Playwright & Selenium in a project:
1. End-to-End Testing (E2E): Playwright is widely used for automating end-to-end tests, ensuring that an application behaves as expected from the user's perspective. It can simulate user interactions, such as clicking buttons, filling out forms, and navigating through pages to validate the application's functionality.
2. Regression Testing: Playwright can be employed to automate regression tests, which help ensure that recent code changes or updates haven't introduced new defects or negatively impacted existing features. By running automated tests regularly, you can catch regressions early in the development cycle.
3. Performance Testing: While not a dedicated performance testing tool, Playwright can be used to measure web performance indirectly. You can track page load times, monitor resource loading, and capture performance-related metrics to assess your application's speed and efficiency.
4. UI and Visual Testing: Playwright enables UI testing by automating interactions with UI components. It also supports visual testing by capturing screenshots or comparing the appearance of page elements against expected visuals. This helps ensure the correct rendering of your application.
5. Accessibility Testing: Playwright includes features for accessibility testing. You can use it to assess your application's compliance with web accessibility standards like WCAG and identify potential accessibility issues that could affect users with disabilities.
6. Continuous Integration (CI) and Continuous Deployment (CD): Playwright can be integrated into your CI/CD pipelines to run tests automatically when code changes are committed. This ensures that the application works as expected after each build and deployment, helping maintain a high level of quality.
7. Data-Driven Testing: Playwright can be used for data-driven testing, where you feed different sets of data to your test scripts to validate the application's behavior under various conditions and scenarios.

<p align="center">
<img width="543" alt="benifits" src="https://github.com/Amruta-Zargad/websiteContent/assets/149228649/eea3ea27-da8a-46b9-8003-0db1dc59778b">
</p>

# Unlocking the Power of Playwright tool

Hey there, tech enthusiast! If you're in the business of building or testing web applications, you've probably heard about this cool tool called Playwright. But if you're new to the game, don't worry; we're here to break it down for you.

In simple terms, Playwright is an open-source automation tool that lets you write scripts to control web browsers, interact with web pages, and validate how they work. It's like having a robot assistant that can navigate websites and report back with valuable insights.

## Why you should use playwright?
<ul>
<li> Cross-Browser Magic: Playwright works with Chrome, Firefox, and WebKit (Safari). Test your app across multiple browsers with ease. </li>
<li> Reliable and Fast: It's super reliable, and its speedy performance saves you time and money. </li>
<li> Endless Possibilities: You can automate tasks, test user interactions, and even take screenshots or capture performance data - all with Playwright. </li>
</ul>

<p align="center">
<img width="661" alt="playwright" src="https://github.com/Amruta-Zargad/websiteContent/assets/149228649/18a97198-bf63-4304-83a2-edc0b81f5a40">
</p>

## Exploring the Magic of Playwright: 
Hello there! If you're a tester seeking a robust solution for automating browser tasks, you're in for a treat. Allow us to introduce you to Playwright, the browser automation tool that can do wonders for your web projects. Let's take a look at some of its most compelling features:
<ul>
<li> Cross-Browser Compatibility :- Think of Playwright as a master of disguise. It can work seamlessly with three major browsers: Chrome, Firefox, and WebKit (the engine behind Safari). No more cross-browser testing headaches - with Playwright, you can ensure your web app works smoothly on all of them. </li>
<li> Speed and Reliability :- Playwright is like the "Flash" of the automation world (without the red suit). It's incredibly fast and reliable, ensuring your tests and automations run smoothly and swiftly. Say goodbye to flaky tests and slow automation processes. </li>
<li> Endless Automation Possibilities :- With Playwright, you're not limited to just one task. You can automate a wide range of activities, from navigating websites and filling out forms to capturing screenshots and recording performance data. </li>
    <li> Headless Mode :- You can run Playwright in "headless" mode, which means it operates without a visible browser window. This is perfect for running your automations or tests in the background, saving resources and avoiding distractions. </li> </ul>

  ## Setting Up and Installing Playwright
Welcome to our step-by-step guide for setting up and installing Playwright, the powerful browser automation tool. Whether you're a developer or a tester, Playwright can make your life easier. Let's get started!
#### Step 1: Prequisites
You'll need Node.js (version 14 or higher) installed on your system. If you don't have it, download and install it from [node.js](https://nodejs.org/en)
#### Step 2: Initiate Project
Create a New Project: Start by creating a new directory for your Playwright project. Open your terminal or command prompt and run: 
`npm init playwright@latest`
<ul>
<li>Choose between TypeScript or JavaScript (default is TypeScript) </li>
<li>Name of your Tests folder (default is tests or e2e if you already have a tests folder in your project) </li>
<li>Add a GitHub Actions workflow to easily run tests on CI </li>
<li>Install Playwright browsers (default is true) </li>
</ul>

#### Step 3: Add depecdency in exsisting project 

Now, it's time to install Playwright as a dependency in your project. Run: `npm install playwright`
#### Step 4: Select the Browsers
 You can choose which browsers to install. By default, Playwright installs Chromium, Firefox, and WebKit (Safari). If you want to install a specific browser, run one of the following:
- For Chromium: `npm playwright.chromium`
- For Firefox: `npm playwright.firefox`
- For Safari: `npm playwright.webkit` 


#### Step 5: Example
``` 
import { test, expect } from '@playwright/test';

test('has title', async ({ page }) => {
  await page.goto('https://playwright.dev/');

  // Expect a title "to contain" a substring.
  await expect(page).toHaveTitle(/Playwright/);
});

test('get started link', async ({ page }) => {
  await page.goto('https://playwright.dev/');

  // Click the get started link.
  await page.getByRole('link', { name: 'Get started' }).click();

  // Expects page to have a heading with the name of Installation.
  await expect(page.getByRole('heading', { name: 'Installation' })).toBeVisible();
});

```
#### Step 6: Running Test
Running the Sample Test Script: `npx playwright test`

#### Step 7: Report
Show report of the test suite locally: `npx playwright show-report`

Feel free to customize and style these steps to match your website's design and branding. Providing a clear and concise guide on setting up Playwright will be valuable to your website's visitors who are looking to get started with this automation tool.

# Unlock the Power of Automation with Selenium
 If you're passionate about web applications and quality assurance, you're about to embark on an exciting journey with Selenium. Let's take a stroll through some of the core features that make Selenium a star in the world of web automation.

 Imagine Selenium as a set of tools and libraries designed to automate web browsers. It's like having a super-smart robot that can mimic human interactions with a web page. Selenium can click buttons, fill out forms, navigate through websites, and even validate the results, just like a real user.

 ## Why you should use selenium
- Cross-Browser Testing: It allows you to test your web app on various browsers, ensuring a consistent user experience for all your visitors, whether they're using Chrome, Firefox, Safari, or more.

- Multiple Programming Languages: Whether you're a Python lover, a Java enthusiast, or prefer JavaScript, Selenium supports multiple programming languages. Choose the one that makes you most comfortable.

- Automation: With Selenium, you can automate repetitive tasks, which means less manual work and faster, more reliable testing. It's a game-changer in terms of efficiency.

- Versatile Locators: Selenium provides a range of ways to find and interact with elements on a web page, making it flexible and adaptable to different scenarios.

- Headless Testing: Don't want to see the browser window while testing? Selenium can run in "headless" mode, behind the scenes, saving resources and time.

- Selenium Grid for Scalability: Need to speed up testing? Selenium Grid lets you run tests in parallel across multiple machines and browsers. It's like having a testing army at your disposal.

- Rich Ecosystem: Selenium comes with a variety of helpful tools and extensions like Selenium WebDriver and Selenium IDE, which enhance its capabilities and adaptability.

- Active Community: With a thriving community of developers and testers, you'll always find support and resources to navigate the world of web automation.

Selenium supports multiple programming languages, making it flexible and easy for testers to use. With Selenium, testers and developers can write test scripts in a language they are comfortable with. Selenium supports the following programming languages:
Java
C#
Ruby
Python
JavaScript (Node.js)

Each browser and language has its own dedicated drivers and bindings that enable seamless interaction between the Selenium framework and the browser or programming environment. This extensive support empowers teams to create robust and flexible automated testing suites tailored to their project requirements.

So, whether you're a seasoned developer or just starting your journey into web testing, Selenium is your go-to companion. It's all about elevating the quality of web applications. Ready to dive into the world of Selenium? Let's explore and automate the web together!

<p align="center">
<img width="407" alt="selenium" src="https://github.com/Amruta-Zargad/websiteContent/assets/149228649/fa778353-2527-4da9-8a68-3d15a6bac990">
</p>

## Installation process of Selenium with Java
Installing Selenium with Java involves several steps. Selenium is a popular tool for automating web applications, and it integrates well with Java. Here's a step-by-step guide to install Selenium with Java:

#### Step 1: Install Java Software Development Kit (JDK)
Selenium requires Java to run. If you don't already have Java installed, you can download and install it from the official website: [JDK](https://www.oracle.com/java/technologies/downloads/)
#### Step 2: Install Eclipse IDE
Here we can use Eclipse IDE or IntelliJ IDEA. We are using Eclipse to write the automation test scripts. Download the latest version of “Eclipse IDE for Java Developers” [Eclipse](https://www.eclipse.org/downloads/)

- You should be able to download an exe file named “eclipse-inst-win64” for Setup.
- Double-click on a file to Install the Eclipse. A new window will open. Click Eclipse IDE for Java Developers.
- After that, a new window will open which click button and change path to “C:\eclipse”. Post that Click on the Install button.
- After successful completion of the installation procedure, a window will appear. On that window click on Launch.
#### Step 3: Selenium WebDriver Installation
You can download Selenium Webdriver for Java Client Driver. You will find client drivers for other languages there, but only choose the one for Java [Selenium Webdriver](https://www.selenium.dev/downloads/)
#### Step 4: Configure Eclipse IDE with WebDriver & Create new Java or Maven project
Open Eclipse IDE and create a new Java project where you'll write your Selenium scripts.
#### Step 5: Add Selenium JAR to Your Project:

In your Java project, you should include the Selenium WebDriver JAR file as an external library:
- In Eclipse, right-click on your project, then go to "Build Path" -> "Configure Build Path."
- Click the "Libraries" tab and then click "Add External JARs."
- Select the Selenium WebDriver JAR you downloaded and click "Open."
#### Step 6: Set Up WebDriver Executables:

To automate different browsers like Chrome or Firefox, you need the respective WebDriver executable files. You can download these executables from the following links:

- ChromeDriver (for Chrome): [ChromeDriver Downloads](https://sites.google.com/chromium.org/driver/)
- GeckoDriver (for Firefox): [GeckoDriver Downloads](https://github.com/mozilla/geckodriver/releases)

Download the correct version for your browser, and ensure the executable is in your system's PATH or provide the path to the executable in your Selenium code.
#### Step 7: Write your test script
Sample script
```
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

public class SeleniumSampleScript {

    public static void main(String[] args) {
        // Set the path to the ChromeDriver executable
        System.setProperty("webdriver.chrome.driver", "path_to_chromedriver_executable/chromedriver.exe");

        // Initialize the ChromeDriver
        WebDriver driver = new ChromeDriver();

        // Navigate to a website
        driver.get("https://example.com");

        // Find a web element by its CSS selector and click it
        WebElement linkElement = driver.findElement(By.cssSelector("a"));
        linkElement.click();

        // Perform additional actions or assertions as needed

        // Close the browser
        driver.quit();
    }
}
```
#### Step 8: Run your test script
As playwright seperate comments are not required. You can run your Selenium tests directly from your IDE or by using build automation tools like Maven.

<p align="center">
<img width="790" alt="new" src="https://github.com/Amruta-Zargad/websiteContent/assets/149228649/0e69f1e3-0a88-4e81-81b4-b039be58bc20">
</p>



<p align="center">
<img width="565" alt="run" src="https://github.com/Amruta-Zargad/websiteContent/assets/149228649/fcab4f6f-e5f5-49f6-97fd-830566753a7e">
</p>

#### Step 9: Use TestNG or JUnit to run the test script
Choose a testing framework like TestNG or JUnit to manage your test cases. These frameworks help in grouping, prioritizing, and running your tests.
TestNG: TestNG is a testing framework inspired by JUnit and NUnit but introduces some new functionalities and is designed to be more flexible and easier to use.
How to install and Add TestNG in Eclipse
 1: Navigate to Eclipse Marketplace


 2: Search for TestNG and click on install.

Note: After the plugin is installed, restart the Eclipse IDE

Install TestNG Plugin in Eclipse
As the plugin is installed, you can see Options like Run All, Run | Debug in the editor itself, and clicking on Run above the TestNG Test will execute the test likewise Debug will allow debugging the test.

After TestNG Plugin is Installed and Configured
Adding a TestNG plugin within the Eclipse IDE helps in making the test execution easier by directly running the tests inside the Text Editor itself. Hence, it is recommended to configure the TestNG Plugin in Eclipse to run Unit Tests.

Creating Sample Maven Project by adding TestNG dependency

JUnit: JUnit is a widely used testing framework for Java. Selenium can be integrated with JUnit to perform testing.


That's it! You've successfully installed Selenium with Java and are ready to start automating your web testing. Remember that Selenium is a powerful tool with a variety of functionalities, so you may need to explore its documentation and other resources to create more advanced test scenarios.

## Thank you for being a part of our journey. 
