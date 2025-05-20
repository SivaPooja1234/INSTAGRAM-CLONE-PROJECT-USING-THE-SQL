````markdown
# 📸 Instagram Clone

This project is an Instagram Clone focused on simulating core backend database functionality. The schema is implemented in SQL and models essential features such as users, posts, comments, likes, followers, and story functionalities.

## 🗂️ Project Structure

- `INSTAGRAM CLONE.sql`: SQL script containing the full database schema including table definitions, constraints, and relationships.

## 🧱 Features Modeled

The following components are included in the database schema:

- 👤 **Users**: Registration, profile info (username, bio, gender, profile image, etc.)
- 📸 **Posts**: Text-based captions, media attachments, timestamps.
- 💬 **Comments**: Users can comment on posts.
- ❤️ **Likes**: Like functionality per post.
- 🔁 **Followers**: Follower/following relationships between users.
- 🧾 **Reports**: Reporting users or posts for moderation.
- 🎯 **Stories**: Temporary content shared by users.

## 🧰 Technologies Used

- SQL (MySQL / MariaDB compatible)
- Relational database design
- Constraints: Foreign keys, cascading updates/deletes
- Datetime, Enum types, and Auto-Increment fields

## ⚙️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/instagram-clone.git
````

2. Import the SQL file into your database:

   ```sql
   SOURCE path/to/INSTAGRAM\ CLONE.sql;
   ```

   Or use a GUI tool like **phpMyAdmin** or **MySQL Workbench** to run the script.

3. The schema will create all necessary tables and establish the relationships.

## 🔮 Future Improvements

* Add triggers or stored procedures for features like notifications or auto-deleting stories.
* Expand to include messaging (DMs).
* Integrate with a front-end and backend (e.g., Flask, Django, Node.js).
