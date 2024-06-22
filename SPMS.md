# CVE 2024-6212

**Researcher Name:** Guru Raghav Saravanan

**Product:** Service Provider Management System using PHP and MySQL

**Vulnerability:** **Cross Site Scripting**


**POC:**
The vulnerability is present in **system_info/index.php**. The input fields System Name and System short name does not sanitize the user input which leads to Cross Site Scripting.

**system_info/index.php**

![system_info/index.php](/assets/spms/pic1.png "system_info/index.php")

**Attack screenshots:**

![Website](/assets/spms/pic2.png "Website")

**XSS**

![XSS](/assets/spms/pic3.png "XSS")

![XSS](/assets/spms/pic4.png "XSS")
