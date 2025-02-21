# ** Website Components Overview**

### ** Admin panel pages**
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

### ** Client site pages**
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

### ** Partner admin panel & Partner client site **
- Same admin panel ( With the addition of games, sections, articles, and virtual front-end content )
- Controll RESET APIs for his clients
- Controll subdomain or his domain

    #### **Note: 
    - Once the partner registers on the partner panel, he will obtain all the default data and can modify it later, such as changing the shipping price, -  - articles, or rest API settings for customers who will register in his subdomain.

### ** Partner client site **
- Same base client site ( With changed data by this partner )
- Each client in this subdomain site can also obtain a REST API 

## summary :
- Admin panel: to manage all data, such as various types of users, chat, games, charging, and external connection points 
- The website: It contains articles, sections, games, customer login, profile, portfolio, and rest api for each customer.
- Partners website: Register the partner and he will get a panel like the admin panel that contains all the default data and he can modify it
- The partner website: It is the same as the original website, but with a subdomain and it contains the partner’s sections and games.

- when customers register on any of the partner sites, they can also ship within the site or obtain an external API for shipping via the API. Any order placed on the partners’ domains on the platform will have a commission that will be determined by the admin on the panel, and a special commission can be added for each partner or a specific group of partners.
