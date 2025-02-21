**📌 Website Components Overview**

---

## **🔹 Overview**

### **🔹 Admin panel pages**
- Statistics
- Categories
- Sub Categories
- Games
- Coupons
- Orders
- Admins
- Partners
- Clients
- Partner's clients
- Settings
- Commissions
- Referrals
- Referrals Levels
- Content Management to manage frontend content
- Complaints
- Support Chat
- All Chats between Partners and Clients
- Blogs
- Comments
- Replies
- Reviews
- Reports
- Payment Getways
- Transactions
- Mails between admins

### **🔹 Client site pages**
- Home ( Header, Footer, Main categories sections contains game cards )
- Blogs ( All Blogs page, blog details, comments, replies, like, dislike )
- Chatbox ( fixed chat icon to chat with support )
- Help center
- Policy terms
- Categories
- Game cards
- Checkout ( choice number and payment, any another info .... )
- Profile ( info, wallet, settings, transactions, deposit, reviews, referrals )
- RESET API ( secret token for each client to use it in External API )

### **🔹 Partner admin panel & Partner client site **
- Same admin panel ( With the addition of games, sections, articles, and virtual front-end content )
- Controll RESET APIs for his clients
- Controll subdomain or his domain

    #### **🔹Note: 
    - Once the partner registers on the partner panel, he will obtain all the default data and can modify it later, such as changing the shipping price, -  - articles, or rest API settings for customers who will register in his subdomain.

### **🔹 Partner client site **
- Same base client site ( With changed data by this partner )
- Each client in this subdomain site can also obtain a REST API 

## ملخص :
- لوحة أدمن : لإدارة جميع البيانات مثل المستخدمين بأنواعهم والشات والالعاب والشحن ونقاط الاتصال الخارجية 
- موقع الفرانت : يكون فيه المقالات والاقسام والالعاب وتسجيل دخول العملاء والبروفايل والمحفظة و rest api لكل عميل
- موقع الشركاء : تسجيل الشريك وسيحصل على لوحة مثل لوحة الادمن وفيها جميع البيانات الافتراضية ويمكنه تعديلها
- موقع الفرانت الخاص بالشركاء : هو نفسه موقع الفرانت الاصلى ولكن مع دومين فرعى وفيه الاقسام والالعاب الخاصة بالشريك

- وطبعا عندما يسجل العملاء فى اى موقع من مواقع الشركاء يمكنهم ايضا الشحن داخل الموقع او الحصول على api خارجى للشحن عن طريق ال api واى اوردر هايتم على دومينات الشركاء المنصة هايكون له فيها عمولة هايحددها الادمن فى اللوحة ويمكن اضافة عمولة خاصة لكل شريك او مجموعة معينة من الشركاء
