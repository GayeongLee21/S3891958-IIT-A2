### COSC2083 Semester B, 2021
## Introduction to IT
## The IT World- Assignment 2
#### Gayeong Lee  (S3891958)





 


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
How will this affect you? 
The public, including myself and the people around me, will definitely have a more convenient life in various fields with the development of AR and chatbot technology in the future. For me, this technological development can be advantageous in the job market from the standpoint of studying related technologies as the demand in the IT field increases. But because there are so many skilled professionals, I have to increase my competitiveness myself. I have some of my friends who are studying jobs that are considered to be extinct in the future, but even if they do, they will definitely use their skills to find new jobs related to them.

# 5. IT Work
 
# 6. Feedback

I got feedback on my ideas from a total of 5 of my friends and parents.

**Q1.** Yoon Se-yeon (21)- What will you do if you play a prank on the order with the QR code?
**Q2.** Joo Young-eun (21) - How do you consider people's ability to adapt to a new culture?
**Q3.** Seo Min-seok (24)- Momo Pay and Zalo Pay are also using the QR payment system in some restaurants. How would you differentiate them from them?
**Q4.** Lee Yong-gwan (56 My Dad)- Is there any possibility of personal information leakage due to QR code?
**Q5.**Park So-yeung (51 My Mom)- How about adding a discount system such as promotions or coupons?
 
**A1**- Introduce a prepayment system by linking the consumer's account and e-wallet with the application. Poketsk can prevent abuse by linking only one terminal to one QR server.
 
**A2**- In order to lower the service accessibility and technical threshold, various notices should be installed at the store site and store owner service training should be conducted. In addition, in order to minimize the technological marginalization at the app level, the service is designed as easily as possible by improving text, brightness, and images more intuitively to facilitate adaptation.
 
**A3**- Momo pay and Zalo pay used in some existing restaurants are simple payment systems. The biggest difference with Poketsk is that by linking each e-wallet and account, customers can choose the payment method they want, and customers can order directly from their desk using a mobile phone using a QR code.
 
**A4**- Personal information such as payment information linkage, location tracking, name, number, etc. is required, but will be used only for each function. At Poketsk, the guide to personal information will be specified in the agreement when you sign up for the first time, and if you do, you will be held legally responsible. In addition, Poketsk will strengthen security through thorough server management.
 
**A5**- I will add various promotions and coupon functions such as first-time users of the Poketsk app, frequent users, birthdays, anniversaries, etc.
I agree with all the feedback comments I have received.Various feedback comments helped me to identify problems that I hadn't thought of. We also learned how to make the application more accessible and effective for consumers to use.
 
# 7. Reference



