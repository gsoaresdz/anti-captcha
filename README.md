<h1 align="center">Anti-Captcha Project</h1>
<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/anti-captcha?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/anti-captcha?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/anti-captcha?color=56BEB8">
  <!--<img alt="License" src="https://img.shields.io/github/license/seu-usuario/projeto-anti-captcha?color=56BEB8">-->
</p>
<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execution">Execution</a> &#xa0; | &#xa0;
  <a href="#memo-important-notes">Important Notes</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/gsoaresdz" target="_blank">Author</a>
</p>
<br>

## **:dart: About**

The Anti-Captcha Project is a Python application developed to automate the bypassing of reCAPTCHA v2 on web pages. It uses the Selenium library for web browser interaction and the Anti-Captcha API to solve the captchas.

## **:memo: Business Rule**

The main goal of this project is to demonstrate the ability to automate the solving of reCAPTCHA v2 on a test site using the Anti-Captcha API. This can be useful for penetration testing, test automation, or studies related to captchas.

## **:sparkles: Features**

:heavy_check_mark: **Feature 1**: Opens the browser and navigates to a page with reCAPTCHA v2.

:heavy_check_mark: **Feature 2**: Uses the Anti-Captcha API to solve the captcha.

:heavy_check_mark: **Feature 3**: Takes a screenshot as evidence after solving the captcha.

:heavy_check_mark: **Feature 4**: Automatically closes the browser session.

## **:rocket: Technologies**

The following tools were used in this project:

- [Python](https://www.python.org/)
- [Selenium](https://www.selenium.dev/)
- [WebDriver Manager](https://pypi.org/project/webdriver-manager/)
- [Anti-Captcha API](https://anti-captcha.com/)
- [Pillow (Python Imaging Library)](https://pillow.readthedocs.io/en/stable/)

## **:white_check_mark: Requirements**

Before starting :checkered_flag:, you need to have [Python 3.6](https://www.python.org/downloads/release/python-360/) or higher installed.

## **:checkered_flag: Execution**

### Cloning the Repository

First, clone the project repository to your local machine.

```bash
$ git clone https://github.com/gsoaresdz/anti-captcha.git
```

### Installing Dependencies

To install the project dependencies, run the following command in the terminal:

```bash
$ pip install selenium webdriver-manager anticaptchaofficial pillow
```

### Configuring the API Key

You need to acquire an Anti-Captcha API key. Once obtained, replace **`'YOUR_API_KEY'`** with your actual key in the script.

### WebDriver Installation

WebDriver Manager will automatically handle the download of the necessary driver for your browser. Make sure you have the corresponding browser installed (Chrome by default).

### Running the Code

To run the project, open the script in your Python development environment and execute it. The script will automate the browser opening, access the reCAPTCHA test page, solve the captcha, and capture evidence of the captcha being solved.

### **Steps Performed by the Code**

1. **Opening the Browser**: Starts a Chrome browser session.
2. **Accessing the Web Page**: Navigates to the page with reCAPTCHA v2.
3. **Breaking the Captcha**: Uses the Anti-Captcha API to solve the captcha.
4. **Sending Evidence**: Takes a screenshot as evidence after solving the captcha.
5. **Closing**: Closes the browser session.

## **:memo: Important Notes**

- This project is for educational and research purposes only.
- Bypassing captchas on websites without permission may violate terms of service and local laws.
- It is important to use this script ethically and responsibly.

## **:memo: License**

This project is under the MIT license. For more details, see the [LICENSE](LICENSE) file.

Made with :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

<a href="#top">Back to top</a>
