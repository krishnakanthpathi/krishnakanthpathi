# 👋 Hi, I'm Krishna Kanth !

I'm a passionate **B.Tech student**, aspiring **Full Stack Web Developer**, and a problem-solver who loves to explore technology and write clean, efficient code. With a strong foundation in **Data Structures and Algorithms**, I aim to create impactful projects and share knowledge within the tech community.

[![LeetCode Stats](https://leetcard.jacoblin.cool/krishnakanthpathi?theme=dark&ext=heatmap)](https://leetcode.com/krishnakanthpathi/)

*Thank you for visiting my GitHub profile! Feel free to explore my repositories and connect with me!* 🚀
## Database Schema (ER Diagram)

```mermaid
erDiagram
    Organization {
        Integer id PK "Organization ID (PK)"
        String name
        String email
        String slug
        String status
        String contact
        String website
        String phone
        Text img
        String primaryAdminName
        String primaryAdminEmail
        String supportEmail
        String region
        String timezone
        String language
        Integer maxCoordinators
        Integer pendingRequests
    }

    User {
        Integer id PK "User ID (PK)"
        String name
        String role
        Integer organizationId FK "Organization ID (FK)"
    }

    Organization ||--o{ User : "has"
```

