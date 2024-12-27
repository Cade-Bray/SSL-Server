**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**
***

  Artmis Financial is a institiuation adhering to the gramm-bliley-leach act among others and needed to ensure their data was being secured to industry standards. They primaryly wanted to address their concerns with data in transit, data at rest, and securing their webserver using SSL certificates that were selfsigned. 
  

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**
***

  I believe I performed well in ananlyzing Artmis Financial's dependcy checks using the OWASP dependcy checker with Maven. I was able to identify false reporting and supress them. It's important to code securely because large systems that have comprimised aspects could be treasure troves to malicious actors and could affect the client and users adversely. Software security adds to a companies overall well-being by creating a culture of producing well designed, optimally performing, and best practices code.
  

**Which part of the vulnerability assessment was challenging or helpful to you?**

  I believe getting to utilize a framework in my developement was very helpful for me because up until now I had only done coding assignments with built-in packages.


**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**
***

  I increased a layer of secruitity by introducing https protocols and intergrate the OWASP dependency checker for static testing. In the future I would continue to use the OWASP dependency checker plugin as well as manually using the NIST database for reviewing commonly reported vulnerabilities. 
  

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
***

  I ensured the application was able to excute free of errors from Spring boot and tomcat dependencies along with generating and deploying SSL certificates. I ensured my refactored code did not introduce new bugs by running a dependency check prior to and post refactoring while comparing the differences.
  

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
***

I used the vulnerability assement flow chart along with multiple online guides including the spring boot documentation page to help deploy this code.


**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**
***
With this assignment in mind I would be able to show employers I know how to integrate into an existing culture of secure coding. This shows the employer I am willing to go the extra mile to refine my work to the highest standard while consulting tools and peers to ensure deployments are smoothly laided out.
