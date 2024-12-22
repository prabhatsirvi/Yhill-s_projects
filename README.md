Projects Summary :-
### **Project 1: Vulnerability Assessment of a Web Application**
**URL Assessed:** [http://testphp.vulnweb.com](http://testphp.vulnweb.com)  
**Objective:** Identify security vulnerabilities in the target website and provide remediation strategies.  

**Key Discoveries:**
- **Cross-Site Scripting (XSS):** Found in the homepage search input, potentially enabling attackers to execute malicious scripts.
- **Remote File Inclusion (RFI):** Allowed malicious file inclusion via URL parameters.
- **Sensitive Information Disclosure:** Exposed usernames and passwords in URLs.
- **Brute Force Vulnerability:** Login page vulnerable to automated attacks.
- **Insecure Connection:** Lack of HTTPS led to data exposure risks.

**Tools Used:**  
Nmap, Dirb, Nikto, Burp Suite, SQLMap, Hydra, and manual inspection tools.  

**Outcomes:**  
Comprehensive remediation strategies provided, such as implementing HTTPS, input sanitization, and disabling remote file inclusions.  

--------------------------------------------------------------------------------------------

### **Project 2: Network Penetration Testing of a Windows Virtual Machine**
**Objective:** Assess vulnerabilities in a Windows VM to enhance network security.  

**Key Findings:**
- **MS17-010 Vulnerability (EternalBlue):** Critical exploit allowing remote code execution.
- **Open Ports:** Identified multiple open ports (e.g., 135, 139, 445), exposing services to potential attacks.
- **Weak SMB Configuration:** Accessible SMB shares posed data exposure risks.

**Tools & Techniques:**
- **Nmap:** Network discovery and vulnerability assessment.  
- **Metasploit Framework:** Exploitation of EternalBlue vulnerability.  
- **Enum4linux:** SMB enumeration for sensitive information retrieval.  

**Results:**  
Highlighted the need for patch management, service configuration, and regular vulnerability assessments to mitigate risks.

--------------------------------------------------------------------------------------------

### **Project 3: Nmap Enumeration and Vulnerability Analysis**
**Target:** [http://zero.webappsecurity.com](http://zero.webappsecurity.com)  
**Objective:** Perform enumeration and vulnerability analysis using Nmap.  

**Key Findings:**
- **Open Ports:** Detected HTTP (80) and HTTPS (443) ports.  
- **Interesting Directories:** Revealed paths such as `/admin/` and `/manager/html`, some unauthorized.  
- **TLS Vulnerabilities:** Identified issues like Logjam, POODLE, and SSL/TLS CCS Injection.  
- **CSRF Vulnerabilities:** Found in the search forms.  

**Recommendations:**  
Upgrade TLS configurations, restrict directory access, and implement CSRF protections.  

**Platform & Tools:**  
Performed on Parrot OS using Nmap v7.94SVN.  

--------------------------------------------------------------------------------------------
