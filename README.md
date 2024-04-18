Introducing ZAP 

The OWASP Zed Attack Proxy is a free security tool which acts as a proxy between browser and network,
(It is nothing  but the interface between the browser and network) find security issues in web applications & report them to the end user.

Zed Attack Proxy (ZAP) is a free, open-source penetration testing tool being maintained under the umbrella of The Software Security Project (SSP). ZAP is designed specifically for testing web applications and is both flexible and extensible. 

At its core, ZAP is what is known as a “manipulator-in-the-middle proxy.” It stands between the tester’s browser and the web application.

    
    
    
    
Features of ZAP:

    1. Spider: 
    2. Passive Scan.
    3. Active Scan.
    4. Fuzzing.


Spider:
    The spider can be used crawl the web application to automatically detect all the links and pages.
ZAP provides 2 spiders for crawling web applications, you can use either or both of the.
    A. Traditional ZAP Spider.
    B. AJAX ZAP Spider.

Passive Scan :
    It  examines the requests and responses which are sent between your browser and the application. Passive scanning is good at finding the vulnerabilities and give basic security state of your web application. 
Active Scanning:
    The main goal of an Active Scan is to detect and exploit potential security vulnerabilities in a web application by emulating real-world attack scenarios
  
    How it Works: During an Active Scan, ZAP sends crafted HTTP requests with payloads designed to exploit common vulnerabilities such as SQL injection, cross-site scripting (XSS), and more. It analyzes the responses from the application to identify vulnerabilities.
    
    This type of scanning attempts to find the other vulnerabilities by using known attack against the selected targets. Active scanning is a real attack.
