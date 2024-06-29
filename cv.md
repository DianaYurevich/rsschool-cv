# CURRICULUM VITAE
![My photo](https://img.cataloxy-by.ru/upload/resume/241/4/30821.jpg)
## Name&family name: YUREVICH DIANA
## Mobile phone: +375297133642
## E-mail: E-mail: diana_yurevich@rambler.ru
## My lifes goals in work:
    - _I want to learn how to create mobile applications, website._ 
    - _For my goal and, first of all, my dream, I am trying to take courses, study literature, which will help me study this field and become a good specialist in this field. At the moment, unfortunately, I have no experience in this field. But I'm not giving up hope and I'm trying to find a job and apply my skills and improve them as well._

## Key skills:
    - **Programming languages:** Python, I also started learn Java and C++
    - **Frameworks:** Selenium, Pytest, Allure
    - **Tools:** PyCharm, Postman, Dev Tools, Jmeter, Visual Studio Code, API Testing
    - **Version control:** Git
    - **Database:** MySQL
    - **Management tools:** Atlassian Jira,  Atlassian Confluence,  Agile Project Management, Aspro. Agile
    > *I have the skills of manual and automatic testing. In the course of training, I was engaged in testing online stores.I know and understanding SDLC - software development lifecycle and STLC - software testing lifecycle. In process of training, I learned smoke testing, testing of ?Critical path, testing of Extended test, Performance testing, UI Testing, Functional Testing, Regression Testing, Checklist, Test Case, Bug Reports.*
    - **Other programs:** Autodesk 3ds Max,  V-Ray,  AutoCAD, ArchiCAD,  Artlantis Render, Adobe Photoshop, Electronic Form Module.

## Example of my code:
    from selenium.webdriver.common.by import By
    from selenium.webdriver.support.wait import WebDriverWait
    from selenium.webdriver.support import expected_conditions as EC
    import allure
    from base.base_class import Base
    from utilities.logger import Logger

    class Finish_page(Base):
        def __init__(self, driver):
            super().__init__(driver)
            self.driver = driver
        # Locators
        # Getters
        # Actions
        # Methods
        def finish(self):
            with allure.step("Finish page"):
                Logger.add_start_step(method="finish")
                self.get_current_url()
                self.assert_url('https://www.saucedemo.com/checkout-complete.html')
                self.get_screenshot()
                Logger.add_end_step(url=self.driver.current_url, method="finish")


## Work experience:
    - **Municipal design and production Unitary Enterprise "Vitebsk Architecture"**
    > **_Position Engineer_** As an engineer: Preparation of requests for technical specifications for the engineering and technical support of the object. Preparation of contracts, acts of completed works, preparation of estimates for the preparation
    of permits for construction projects. Collection and preparation of permits for construction projects. Execution of schemes for the placement of construction objects.
    - **Limited Liability Company "Vitebsk Technical Center"**
    > **_Position  Architect - Engineer_** As an architect: developed projects of individual residential buildings in the programs: Autocad, Archicad+ Artlantis, Autodesk 3ds Max+ Vray, Adobe Photoshop.
    As an engineer, I performed: development of a package of documents on labor protection for enterprises in Excel, Word format and subsequent transfer and filling of data into the program "Electronic Form Module", work with a variety of databases (for each organization). Work in AIS Monitoring of working conditions at work (Web application on the website of the Ministry of Labor, with filling in, making changes and sending data on labor protection)

## Education, Higher:
    - **Polotsk State University**
    > **_Architecture_**, 
    *Аrchitect (Specialist)*
    - **Polotsk State University**
    > **_Faculty of Finance and Economics, Accounting, Analysis and Audit._**, 
    *Accountant (1st course finished of education)*
## Electronic certificates:  
    - **2022.Software testing from scratch to a Specialist**
    [Link ti certificate] (https://stepik.org/cert/1667420)
    - **2023.Software Testing: Automation and Programming. Python. Selenium**
    [Link ti certificate] (https://stepik.org/cert/1987427)

## Languages: 
    - Russian — Native
    - English — B1 — Intermediate
    - Chinese — A1 — Basic



