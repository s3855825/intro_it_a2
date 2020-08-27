# **Clouds, Services, and Servers**


##  **What can they do?**
- Cloud computing services provide users with different computer resources, with storage and computing power being the most popular options. Current popular cloud computing options include a wide array of services from AWS or Azure, ranging from EC2 where clients can rent a virtual machine to run as server for their applications, to more recent technologies like Rekognition which provides image recognition services.

- Cloud services can be categorized into [three groups][1]:
    1. *Software as a Service (SaaS)*: is a model in which software providers host their applications and make them available to users on the Internet. A few popular examples are Google's G Suite (Docs, Sheets, Slides, ...), DropBox, AWS S3 ...

    1. *Platform as a Service (PaaS)*: is a model where you, as users, can host your applications without the need for dedicated infrastructure (servers and storages), which will be provided by PaaS service providers. Customers does not have control over the provided infrastructure or platform, only their applications. In this model, users develop their software, and deploy them on cloud platform. Examples of PaaS include AWS Beanstalk, , ...

    1. *Infrastructure as a Service (IaaS)*: is where users are provided with infrastructure (processing power, storage, network, ...), which they can 'rent' from service providers. These infrastructures are virtual machines (similar to what Oracle VirtualBox or VMWare offers) with customizable components (users can select how much resource they requires for their infrastructure, e.g. how much RAM they need, ...) and they can be customized and accessed remotely to create users' own IT platform. The biggest IaaS services offered include AWS EC2, ..

The main difference between these three cloud computing models is in what component you can control, illustrated by the following figure.

![Cloud Computing Services Comparison](https://blogs.bmc.com/wp-content/uploads/2017/09/saas-vs-paas-vs-iaas-810x754.png)

- Compared to traditional dedicated servers, cloud storage does not require users to have physical storage server. By using cloud storage, users only need to pay for operational cost for the storage they need instead of having physical storage space where they also need to account for storage space growth. Current popular cloud storage options include AWS S3, Microsoft Azure Storage, ...


### *What can be done now?*
- Cloud services providers are currently offering a wide array of services: from business applications (AWS Chime, WorkMail, ...) to analytics services (AWS Athena, Kinesis, CloudSearch, ...), and even more recent techonologies like AR/VR (AWS Sumerian). If you can think of a service, that service is likely already offered.

### *What is likely to be done soon?*
- The industry is currently focused on making green technologies, and cloud computing is not an outlier. Researches are being conducted on designing efficient data storage centers, by either coming up with more efficient resource pooling methods, or by lowering devices' power consumption rate.
- According to [this article](https://www.flexera.com/blog/industry-trends/trend-of-cloud-computing-2020/), most of the current trend focus on public adoption of cloud computing. Especially with current pandemic situation, as people working remotely is becoming more common, cloud computing adoption rate is only expected to keep growing, with relational databases-as-a-service at 63% adoption rate. Certainly we can expect a lot more focused development in this area, with services like Amazon DynamoDB getting more features with better support and storage fee.

### *Technological developments*
- At the moment, most of cloud computing services require interaction with the resources on the cloud via internet connection. With upcoming 5G technologies significantly improves data transfer speed, improvement in streaming technologies and platforms is only to be expected.

---

## **Impact**
- Since cloud computing services remove the need for physical infrastructure, they have a great a impact upon traditional IT resources. Furthermore, it also makes data synchronization across multiple devices simple and easy to automate. This results in a push for office workers to continue their work communication and sometimes even their duties after working hours, away from their office by using applications like Google G Suite.

- We can also see the impact on smaller computing devices. With cloud storage services effectively reducing the need for physical storage, we should see a trend of customers gearing toward devices with smaller storage capacity which cost less. However, due to security concern, people are discouraged from moving to cloud storage.

- Security is still a great concern when it comes to using cloud storage. Over the last 10 years, there were various breaches in security, resulting in leaks of personal information and data from some of the largest cloud storage services. The most high-profiled victims of these breaches are Apple's iCloud, DropBox, ... Data of millions of users are stolen, suggesting there should be a change in how large cloud storage providers approach security and protecting customers' data.

- Along with security, privacy of data is also of concern when it comes to using cloud storage. While using private cloud storage services may protect users' data from government surveillance, it does not mean the data is completely private as it can be used for analytics by storage service providers or even sold to third party.
---

## **How this will affect me**
- Personally, I take great advantage of free storage offered by Google Drive. Having cloud storage space means I can work on personal projects from multiple computers and not worry about carrying physical storage devices to access those files.

- For my education, having a GitHub account is extremely convenient. GitHub is a cloud-based source code management service, which falls into the SaaS category of cloud computing. With GitHub to manage projects' version, I can easily roll back to a previous version if my update breaks the project, or decide whether to merge a certain branch or feature into my project.


## Feedback
-Duc: I have some individual feedback for my teammates and myself:
    - I think I should be more clear in my communication (I talk too quietly) and push harder for what I think is better for our team (I think we should be more consistent with deadline and commit our changes on GitHub more often).
    - About Quang, his communicating skill is excellent, and he is the one that get our team to agree on a deadline and decide who do what. 
    - About Minh, he is very engaging in our assignment, and is not afraid to ask for clarification or assistance, which is quite intimidating for me. 
    - About Vĩnh, it can be hard to reach him sometimes to discuss our assignment when we don't see each other after classes. However, I find his work done really well written and there is much to learn from him.

## Group reflection
- Duc: I agree with Quang that we are currently behind our schedule to make a prototype for our final project. Since I was the only member of the team that took Web Programming last semester, we have a lot to work on as a team to make a working prototype. We will focus on the prototype when assignment 2 is done. At the moment, we only finished planning our project, about what features it may have, what we need to do, who handle which part of the prototype, ... so no surprise happened yet. However, I do expect a lot more to happen when we put all of our effort on the project.
---

## **References**
[1]: <https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7035932> "Cloud Computing: State Of The Art Reseach Issues"
[2]: <https://azure.microsoft.com/en-us/overview/what-is-iaas> "Microsoft Azure Overview"
[3]: <https://www.bmc.com/blogs/saas-vs-paas-vs-iaas-whats-the-difference-and-how-to-choose> "SaaS vs PaaS vs IaaS: What’s The Difference and How To Choose"
[4]: <https://www.infoworld.com/article/3223434/what-is-paas-software-development-in-the-cloud.html> "What is PaaS? Platform-as-a-service explained"
[5]: <https://www.ibm.com/blogs/cloud-computing/2013/04/04/how-cloud-computing-is-impacting-everyday-life> "How cloud computing is impacting everyday life"
[6]: Lynn, Theodore & Weber, Arnd & Leimbach, Timo & Nielsen, Rasmus Øjvind & Nentwich, Michael & Strauß, Stefan & Hunt, Graham & Hallinan, Dara & Bachlechner, Daniel & Jaglo, Maggie & Hennen, Leonhard. (2014). Potential and Impacts of Cloud Computing Services and Social Network Websites. Accessed August 2020.
[7]: <https://blog.storagecraft.com/7-infamous-cloud-security-breaches> "7 Most Infamous Cloud Security Breaches"