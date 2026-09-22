## 👥 Team Roles & Contributions
This project was developed collaboratively by a team of 4, with each member responsible for a core layer of the iWish application architecture (Client, Database, Server, Model).

| Team Member | ID | Role | Contribution |
| :--- | :--- | :--- | :--- |
| **Anan Mohamed** | 24102095 | Client / UI Developer | Designed and implemented the client-side layer, including LoginView, RegisterView, HomeView, FriendsView, FriendRequestsView, FriendWishlistView, WishlistView, NotificationsView, and their corresponding controllers (LoginController, RegisterController, WishlistController, NotificationController, FriendController), as well as the Navigator for screen navigation. |
| **Mohamed Khalid** | 24100619 | Database Developer | Built the persistence layer, including DatabaseConnection and all Data Access Objects (UserDAO, FriendDAO, ItemDAO, WishlistDAO, NotificationDAO, ContributionDAO), handling all CRUD operations and data storage logic. |
| **Youssef Mohamed** | 24100679 | Server / Backend Developer | Developed the server-side architecture, including ServerManager, ServerControlView, and ClientHandler, managing client-server communication and request handling. |
| **Nour-Eldien Medhat** | 24100654 | Model & UI Styling Developer | Designed the core domain/model classes (User, Item, Notification, FriendRequest) and handled application styling via style.css and shared resources. |

---

## Project Architecture Overview

* `client/` — UI Views and Controllers (MVC pattern)
* `database/` — Database connection and DAO layer
* `model/` — Core data models
* `server/` — Server-side logic and client-server communication
* `resources/` — Stylesheets and shared assets
