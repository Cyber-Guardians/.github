


  <h1>
    👋 Welcome to our team project
  </h1>
  <h4>
    We are 🛡️ Cybersecurity professionals 🔥 studying at Code Fellows. Cyber Guardians is our midterm course presentation where we demonstrate our skills and knowledge we have learned in our Cybersecurity and Ops 🙌. 
    </h4>
    <div id="header" align="center">
  <img src="https://github.com/Cyber-Guardians/.github/blob/main/Screenshot%202023-05-15%20090526.png"  width="30%" height="30%">
</div>


<p align="center">
  <a href="https://fb.watch/kDZQZWXpJZ/?mibextid=cr9u03">
    <img src="https://github.com/Cyber-Guardians/Documentation/blob/main/facebook-logo-0.png" alt="Facebook" width="50px">
  </a>
  View our presentation CyberGuardians
</p>

## 🤝 Connect with us 👨‍💻👩‍💻👩‍💻👩‍💻

<a href="https://www.linkedin.com/in/alexander88echols/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Alexander | LinkedIn" width="100px"/></a>
<a href="https://github.com/R00sterGuy"><img align="left" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Alexander  | GitHub" width="100px"/></a>
<p align="left"> ${\color{red}Alexander \space Echols }$ </p> 
<p align="left"> Army Veteran </p>
<a href="https://www.linkedin.com/in/genevaknott/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Geneva | LinkedIn" width="100px"/></a>
<a href="https://github.com/GenevaKnott"><img align="left" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Geneva  | GitHub" width="100px"/></a>
<p align="left"> ${\color{red}Geneva \space Knott }$ </p> 
<p align="left"> USMC Veteran </p>
<a href="https://www.linkedin.com/in/dericus-horner/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Dericus | LinkedIn" width="100px"/></a>
<a href="https://github.com/Dhorner4"><img align="left" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Dericus | GitHub" width="100px"/></a>
<p align="left"> ${\color{red}Dericus \space Horner }$ </p> 
<p align="left">Veteran
 </p>
<a href="https://www.linkedin.com/in/your-new-associate/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Dylan | LinkedIn" width="100px"/></a>
<a href="https://github.com/DylanDempsey1"><img align="left" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Dylan | GitHub" width="100px"/></a> 
<p align="left"> ${\color{red}Dylan  \space Dempsey}$ </p> 
<p align="left"> Veteran </p>
<a href="https://www.linkedin.com/in/anthony-wall-a2783019/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Anthony | LinkedIn" width="100px"/></a>
<a href="https://github.com/Anthony098626"><img align="left" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Dylan | GitHub" width="100px"/></a> 
<p align="left"> ${\color{red}Anthony  \space Wall}$ </p> 
<p align="left"> USMC Veteran </p>


💾 Description of our project 🚧
**Our company:** Cyber Guardians is a team of security professionals contracted to improve the cybersecurity processes and systems for a client company. Our focus is on logging, monitoring, and detecting adversarial activity on cloud infrastructure.

<a href="https://github.com/Cyber-Guardians/Documentation/blob/main/Screenshot%202023-05-15%20121944.png"><img align="left" img src="https://github.com/Cyber-Guardians/Documentation/blob/main/Screenshot%202023-05-15%20121944.png" width="50%" height="50%"/></a>
<p align="left">
  
  
<a href="https://github.com/Cyber-Guardians/Documentation/blob/main/Group%204%20OPS401%20Mid%20Project%20Deck%20%20(1).jpg"><img align="right" img src="https://github.com/Cyber-Guardians/Documentation/blob/main/Group%204%20OPS401%20Mid%20Project%20Deck%20%20(1).jpg" width="45%" height="45%"/></a>
<p align="right">
  
   <br>
  <br>
   <br> 
   <br> 
   <br>
    <br>
     <br> 
     <br>
      <br>
       <br>
        <br>
 <br>
  

<p align="left"> ${\color{blue}WHAT \space WE \space DID}$ </p>  Utilizing two AWS EC2 instances, one Windows and one Linux base, we created a virtual private gateway for each instance to connect using a site-to-site VPN. We deployed each instance with their respective private subnets. The site-to-site VPN allows for secure communication. We will log and monitor using AWS CloudTrail and AWS GuardDuty.
</p>






<p align="left"> ${\color{blue}OUR \space SOLUTION}$ </p> 

  
AWS Identity and Access Management (IAM)

IAM is responsible for managing user identities and their permissions within the AWS environment. It ensures that only authorized users have access to AWS services, helping to maintain a secure environment.

AWS Guard Duty

Guard Duty is a threat detection service that continuously monitors various AWS services for potential security issues. It identifies and alerts you about suspicious activities or policy violations, enabling you to respond quickly to any potential threats.

AWS Virtual Private Cloud (VPC)

VPC provides a private and isolated network environment for your AWS resources. It allows you to define and control network settings, such as IP addressing, subnets, and routing tables. By utilizing a private subnet and VPN tunnels, you enhance the security of your resources and establish secure connections between users and Windows Server DC.

AWS CloudTrail

CloudTrail captures and logs API activity within your AWS account. It helps with governance, compliance, and auditing by providing detailed information about user actions, resource changes, and more. Storing the logs in S3 allows for further analysis and integration with third-party services like Splunk.

AWS CloudWatch

CloudWatch is a comprehensive monitoring service that collects and tracks various metrics related to your AWS resources. It enables real-time monitoring of metrics like CPU usage, latency, and error counts. By setting up alarms and triggering AWS Lambda functions based on predefined thresholds, you can respond to security threats or abnormal resource usage promptly.




## 💻PM Tools used 🧰
- [Trello Board](https://trello.com/b/NjbABYRP)
