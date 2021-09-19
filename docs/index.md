### COSC2083 Semester B, 2021
## Introduction to IT
## The IT World- Assignment 2
#### Gayeong Lee  (S3891958)

I declare that in submitting all work for this assessment I have read, understood and agree to the content and expectations of the Assessment declaration.




 


# Table of Content
 
**1.Team Profile**   
-Team Name  
-Team Profile  

**2.Tools**
 
**3.Project Ideas**  
-Overview    
-Motivation  
-Description (Restaurant owner /Customer)  
-Tools and Technologies  
-Skills Required  
-Outcome  
**4.IT Technologies**
-What does it do?  
-What is the likely impact?  
-How will this affect you?  
**5.IT Work**
 
**6.Feedback**
 
 
 
 
 
 
# Team Profile

**Team Name**

I'd like to name the group Logic of Legends (LOL for short). It has a similar name to the world famous game League of Legends, so IT employers will be intrigued, and the LOL we use when we laugh in chat will give them a positive image.

**Team Profile**

My MBTI is an ENFP, so I can communicate with my teammates for the first time without awkwardness. What is certain is that my team members will not feel hurt or fight because of me. And, my learning style is auditory and tactile, so if I talk to my teammates on the phone or meet in person, and organize the key points on the spot, I will be able to focus more on my assignments and remember important content. If I have a team plan, I stick to it strictly, but when I'm alone, I'm not very good at planning. So, if my team member is a J-type who likes to make plans and distribute assignments, I will be able to follow those plans well, continue to share opinions, and work more effectively. I believe that if our team members also follow the plan well, we will be able to complete a successful project. Therefore, I like to work with team members who are active and energetic but focused as much as they do on our assignments.
 
# Tools
 https://gayeonglee21.github.io/S3891958-IIT-A2/  
 https://github.com/GayeongLee21/S3891958-IIT-A2/blob/main/docs/index.md
# Project Ideas

https://balsamiq.cloud/szgomtp/packhsm (This is a simple prototype showing the process of ordering a restaurant customer.)

**Overview**

By attaching a QR code to each restaurant table and when customers scan the QR code with their smartphone, a screen appears where they can select a menu. Customers can use real-time services such as ordering, payment through the pay function, and viewing various information on the spot. In addition, the restaurant provides more convenient service to customers and simplifies work. The service is provided by using an application(Android and IOS).

**Motivation**

It is not easy to order through the staff when placing an order in a place where there are multiple orders, such as large restaurants and cafes. Also, due to the high volume of orders, we don't know how long the food we ordered will take, and sometimes we have to wait in line to check out. Besides, it is difficult to know the details of the store, such as closing time and opening time. The function using QR code scanning can solve these problems, and both customers and restaurants can use the service conveniently.

**Description**

What I see in Vietnam is that there are relatively many young people, and most of them are familiar with how to use a smartphone. When it was locked down due to Covid-19, I saw that most people use the QR code without difficulty when using taxis or convenience stores. Also, they used a lot of E-Wallets that do not need to carry cash or cards, such as MomoPay or Zalo Pay. So I thought that Vietnamese people would be able to use this system naturally without any hesitation. Incidentally, since smartphones are used by most people, they already have an infrastructure, so this can be adapted to the IT market faster than other ideas. Also, unlike kiosks, which are cumbersome to replace devices, users continue to upgrade and replace their smartphones by themselves. Therefore, it is effective in terms of finance as it can reduce maintenance cost, installation cost, and space. In addition, restaurants can avoid ordering and payment errors because they receive orders automatically, and they can also save costs and labor costs for consumables such as vibrating bells. Furthermore, order information is recorded in the database, which is convenient for sales analysis, and reviews and ratings left by customers after using table orders can help business owners improve menus and store operations, as well as can attract new customers.
I named this system 'Pocketsk', a combination of 'pocket' and 'kiosk'. It literally means a kiosk that users can conveniently carry in their pocket. Users of this system are divided into restaurant owners and customers.(The application will support Android and IOS)

**Restaurant owner**

Restaurant owners can link Pocketsk and existing POS devices, or receive orders with smart devices such as smartphones, laptops, and tablets, and use restaurant information and menu CRUD functions.
1. The restaurant owner enters the restaurant's menu, price, and restaurant information in Pocketsk.
2. Attach the QR code to each table.
3. When a customer orders and pays with Pocketsk, the order arrives on the restaurant's    device.
4. When an order is received, a notification of the start of cooking is automatically sent to the customer.
5. The customer's waiting order is entered automatically, and the restaurant enters services such as cooking time.
6. When cooking is complete and confirmation is made, a receipt notification is automatically sent to the customer.
 
 
**Customer**

1. The customer turns on the camera and scans the QR code on the table.
2. If the customer has a Pocketsk application, it will automatically go to the application.
3. Select menu and quantity through application.
4. Rather than the hassle of paying by card or cash directly, customers can connect their accounts or pay with E-Wallets such as MomoPay or Zalo Pay.
5. When the payment is completed and the order is received, the customer will receive a notification of the start of cooking.
6. Customers can receive services such as their waiting order and waiting time in real time.
7. When cooking is complete, the customer will receive a notification of receipt.
8. They can also view the store's information, opening hours and closing times.
 
**Tools and Technologies**

In order to develop applications on both Android and IOS platforms, each requirement is different. Therefore, rather than native apps, it is possible to develop using hybrid development platforms such as Phone Gap, Cordova, ionic, and react native that can be linked with mobile devices such as camera, GPS, and NFC. However, when using a hybrid, there is a high probability of being rejected if implemented only as a web view on the iPhone, so it would be better to implement the splash screen, login, and member registration screen as a native app when making an iPhone app. In addition, to manage data on the server, it must be linked with database programs such as web hosting, phpmyadmin, and FTP programs.

**Skills Required**

First, by using the functions of the hybrid app development framework, the screen is implemented in HTML, CSS, and js web app development methods and compiled for each OS to complete the app for Android and iOS. In addition, functions that are difficult to implement on a website (such as a QR code) or functions for iPhone are implemented by using Java and Objective-C in a native app. Next, I need to be able to handle xml and Json and have knowledge of SQL and FTP to manage the server.Realistically, it is impossible to professionally handle these technologies alone, so I have to share roles with other developers.

**Outcome**

Customers can order more conveniently and have better accessibility, making it easier to provide services and easier to process in the store. In addition, customers can receive information on new services such as waiting order and waiting time in real time. If restaurants attach food pictures and add an explanatory translation function, it is effective for foreigners who do not know Vietnamese. Furthermore, Poketsk already uses popular smartphones to reduce maintenance, installation costs, and space.  It would be good to lower user fees by linking with existing devices in restaurants, increase accessibility, and market well. This can also help prevent coronavirus by reducing queues and enabling visitor tracking.

# IT Technologies

**What does it do?**

Among the technologies related to application development, AR technology is one of the technologies related to QR code scanning that overcomes the industrial crisis in the face of the recent slowdown in the global ICT industry, and the world is paying attention to the VR/AR industry as a keyword for sustainable growth. In particular, convergence services that apply VR/AR to existing industries are spreading rapidly as they spread not only to games but also to various industries such as manufacturing, defense, medical care, and construction. Recently, Google developed AR Glass and the world is paying attention. AR can be used to expand the senses of touch and smell so that the disabled can receive vocational training, thereby expanding the employment market for the disabled and helping various industries. In addition, by using AR technology in the education field, the level of student understanding can be informed to the teacher, and questions can be asked using a smartphone, enabling quick communication between students and teachers. In addition, in the field of tourism, it is possible not only to see, but also to walk and take motions with hands, so you can experience as if you are seeing cultural heritage directly on site. Although AR has not yet been generalized and commercialized, I think it has a high potential for development in the future. Next, natural language processing and chatbot features that can be secondary to my project. If there are many complaints or requests from users, common questions or requests can be answered through the chatbot. Chatbots require machine learning and deep learning skills. In the financial industry such as banks and securities companies, AI chatbots can be used not only for simple chatting technology, but also to issue various certificates and repay principal and interest. We can provide more convenient services to users. These chatbots can listen to people's general concerns and can be a companion for the lonely elderly living alone. In addition, chatbot applications such as 'Karma' or 'Fortune', which are well known in the East, are also popular in Korea. As the amount of time spent at home increases due to COVID-19, these entertainment chatbots will attract more attention from people.

**What is the likely impact?** 

If AR technology is commercialized, it can have a positive effect on the disabled and patients as mentioned above. In the medical field, AR glasses are used for rehabilitation treatment of stroke patients. Various trainings such as climbing stairs and snowboarding were performed in a virtual environment for stroke patients, and it was confirmed that their walking ability was statistically improved compared to the case of classical training. In addition, chatbot technology goes beyond simple chatting technology and is applied to various fields to make daily life more convenient. Of course, there will be jobs that will disappear due to the development of AR technology and chatbots, such as translators, consultants, and reporters. However, side effects will follow. To solve this problem, demand from related industries such as artificial intelligence and information security experts will increase.

**How will this affect you?** 
The public, including myself and the people around me, will definitely have a more convenient life in various fields with the development of AR and chatbot technology in the future. For me, this technological development can be advantageous in the job market from the standpoint of studying related technologies as the demand in the IT field increases. But because there are so many skilled professionals, I have to increase my competitiveness myself. I have some of my friends who are studying jobs that are considered to be extinct in the future, but even if they do, they will definitely use their skills to find new jobs related to them.

# 5. IT Work

**What kind of work is done by the IT professional?**

IT, also known as information technology, refers to the transfer of information or use for other purposes through computers or computer systems. IT professionals do a variety of tasks. They are people who test, build, install, repair or maintain hardware and software associated with complex computer systems at one or more locations. Therefore, the jobs related to IT and the jobs performed by each job are different and varied. As the type of IT, starting with programming, it can be classified into server, network, and database. Furthermore, there is information security.
First of all, programming-related jobs can be broadly classified into back-end developers and front-end developers. In the case of a front-end developer, it is a developer who composes and develops the screens visible to us on platforms such as Google, Microsoft, and Facebook. On the other hand, back-end developers develop, maintain, and repair parts that are invisible to our eyes, such as server management on these platforms. Next, as a server-related job, there is a job called a server administrator. A person who manages, maintains, and repairs the server that has been built. A server administrator does not only manage servers in a specific field, but manages systems in various fields. Knowledge of various operating systems such as Windows, Linux, etc. is required to manage server-related management and to find solutions when errors occur in the server, and additional knowledge requires minimal network knowledge. However, a new job called cloud architecture appeared here, and cloud architecture is a job that manages, develops, maintains, and repairs servers called cloud. As a network related job, there is a network engineer. Network engineers work on analysis, design, and construction of network systems related to various hardware and software related to computer networks. Analyze and evaluate the structure of the overall network system to prepare problems and improvement measures, and build the structure based on functionality, stability, scalability, changeability, and ease of management for a basic network system that can meet user requirements and expectations. Design. Next, there is a job as a database administrator as a database related job. Database administrators use computers to systematically collect, organize, process, and input various types of data to build, manage, and analyze databases. It analyzes the database, and manages user registration and data access scope, read/write permission, and user login and password management. When a database system failure or usage problem occurs, we quickly identify the cause and recover quickly, or we provide training and technical support for users. Finally, information security related occupations include information security experts. Information security experts professionally secure and maintain computer networks in preparation for hacker intrusions and various viruses. It solves and prevents future security problems based on the server's hardware and software technologies. To become an information security expert, knowledge of operating system, database, system management, C language, network programming, etc. is required, and they must have ethics.
 
**What kinds of people does the IT professional interact with? Are they other IT professionals? Clients? Investors? The general public?**

IT Engineers can interact with everyone, including other IT professionals, colleagues, customers, investors, and the general public, depending on their profession. You will also be interacting with many other people who do not understand the technical aspects of marketing, sales, products and business. Therefore, the soft skills associated with it are critical to the business success of any employer. After all, all business tasks in companies and organizations require employees to engage in ongoing interactions or interactions with other members in one way or another. Therefore, in any profession, members of an organization must learn how to communicate and collaborate with others—a level of soft skills. Another reason employers look for candidates with soft skills is that soft skills are transferable skills regardless of occupation. If a manager with soft skills is hired, it means that the soft skills can be transferred to the team members working together through the manager. Unlike hard skills that can be acquired by investing a certain amount of time, such as classes or training programs, soft skills are acquired over time with experience, so people with soft skills often diversify and diversify their company. It is regarded as a human asset, or talent, with a unique and broad background that can operate more efficiently. Soft skills are especially important for companies that provide customer service. In general, employees who have direct customer contact need to listen to customers and require a number of soft skills to provide helpful and courteous service to customers.

**Where do the IT professionals spend most of their time?**

It depends on the job, but a common problem is security. All software has vulnerabilities and it is time consuming to fix them. As more businesses rely on a greater number of applications, their environment becomes more vulnerable. In addition, due to the threat of targeted attacks, most of IT professionals' time is spent resolving application vulnerabilities. The daily demands of hackers do not allow them to deal with the myriad ways in which compromises can be made. Due to the accelerated IT security, there are few related jobs in the security industry that do not change. Practitioners face an average of 5,000 to 7,000 new software vulnerabilities each year. Every year, tens of millions of unique malware programs threaten the IT environment and the attackers who use them to attack. In a world of constant threats, a single mistake can damage a company's reputation, cause the company's name to go viral in the media, slash revenues and fire people.

**What aspect of their position is most challenging?**  

First of all, like a snowball, it's just a small thing at first, and then it becomes a project. It is a form of adding various details or functions to a simple work presented at the beginning. If they add various functions and add functions that may take some time, there is a possibility of overlapping with other projects. Because of this, web freelancers will have to charge a reasonable fee, but in this case, if there is no trust in each other, it should be formatted through a contract.
Next, the 'can't afford' project.
These types are basically projects that require large competencies, or are large enough to solve these problems on their own.
All freelancers are a little adventurous. But the work goes in, and after a day they realize it's too hard and they can't afford it. They simply give up on the project, or they have to work on this project for tens of hours day and night.
Next is the budget.
If you receive a request from a famous corporation. However, there are times when the project is over and the money is not received. If the 100% deferred payment method takes a longer period, unexpected costs may be higher than the initial budget, so 'we can't afford to pay now' or 'contact itself is lost'. In this case, you should make a formal proposal quickly and promise to take legal action according to the contract.
Finally, it is a multi-project.
At one time, you may be dealing with a large project involving two or more freelancers. In this case, he was selected as an expert in one field, so he was selected among freelancers in the same industry to some extent. However, in this case, we need to see clearly and clearly how the manpower cost is handled. If multiple freelancers are involved in the same technical aspect, communication is the most important thing, and you should pursue the ideal. Technically, if freelancers from different industries are involved, each person can do the specified work efficiently, but it is also a part to deal with whether the cost will be distributed according to the contribution of the project in the future or whether it will be distributed evenly.

 
# 6. Feedback

I got feedback on my ideas from a total of 5 of my friends and parents.  

**Q1.** Yoon Se-yeon (21)- What will you do if you play a prank on the order with the QR code?  
**Q2.** Joo Young-eun (21) - How do you consider people's ability to adapt to a new culture?  
**Q3.** Seo Min-seok (24)- Momo Pay and Zalo Pay are also using the QR payment system in some restaurants. How would you differentiate them from them?  
**Q4.** Lee Yong-gwan (56 My Dad)- Is there any possibility of personal information leakage due to QR code?  
**Q5.** Park So-yeung (51 My Mom)- How about adding a discount system such as promotions or coupons?  
 
**A1**- Introduce a prepayment system by linking the consumer's account and e-wallet with the application. Poketsk can prevent abuse by linking only one terminal to one QR server.
 
**A2**- In order to lower the service accessibility and technical threshold, various notices should be installed at the store site and store owner service training should be conducted. In addition, in order to minimize the technological marginalization at the app level, the service is designed as easily as possible by improving text, brightness, and images more intuitively to facilitate adaptation.
 
**A3**- Momo pay and Zalo pay used in some existing restaurants are simple payment systems. The biggest difference with Poketsk is that by linking each e-wallet and account, customers can choose the payment method they want, and customers can order directly from their desk using a mobile phone using a QR code.
 
**A4**- Personal information such as payment information linkage, location tracking, name, number, etc. is required, but will be used only for each function. At Poketsk, the guide to personal information will be specified in the agreement when you sign up for the first time, and if you do, you will be held legally responsible. In addition, Poketsk will strengthen security through thorough server management.
 
**A5**- I will add various promotions and coupon functions such as first-time users of the Poketsk app, frequent users, birthdays, anniversaries, etc.
I agree with all the feedback comments I have received.Various feedback comments helped me to identify problems that I hadn't thought of. We also learned how to make the application more accessible and effective for consumers to use.
 
# 7. Reference
1.James”What is an IT Professional and What Does One Do?” https://dynamixsolutions.com/what-is-an-it-professional-and-what-does-one-do/#:~:text=IT%20professionals%20do%20a%20number,in%20one%20or%20more%20locations.  
2.Richard “IT (INFORMATION TECHNOLOGY) Interview Questions And Answers!” Https://www.youtube.com/watch?v=ISkcAaHn-CM  
3.Kacy “It’s 10 o'clock – do you know what your IT security team is doing?” https://www.csoonline.com/article/2983813/its-10-oclock-do-you-know-what-your-it-security-team-is-doing.html  
4.Global Knowledge “12 Challenges Facing IT Professionals” https://www.globalknowledge.com/us-en/resources/resource-library/articles/12-challenges-facing-it-professionals/#gref  
5.Indeed Editorial Team “21 Different Types of IT Jobs To Explore” https://www.indeed.com/career-advice/finding-a-job/types-of-it-jobs  
6.ALISON “Important Soft Skills for Information Technology (IT) Jobs” https://www.thebalancecareers.com/top-information-technology-it-soft-skills-2063781  
7.Gandhie “Communication Skills – How Important Is It in the IT Industry?” https://www.thebalancecareers.com/top-information-technology-it-soft-skills-2063781  
8.Telusko “5 Skills Every IT Professional Should Have” https://www.youtube.com/watch?v=ssPWDsSHpHQ



