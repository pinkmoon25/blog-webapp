### Blog App 📝

A Ruby on Rails blog application featuring robust user and permissions management through CanCanCan. The app allows users to create, manage, and interact with blog posts and comments, with role-based access control.

### Features:
- **User Authentication and Authorization:**
  - **Public Access:** All users can read any post.
  - **Authenticated Users:** Can create and manage their own posts and comments.
  - **Admin Users:** Have full control over all posts and comments, including management of other users’ content.

- **Post Management:**
  - **Create, Edit, and Delete Posts:** Users can manage their own posts, while admins can manage all posts.
  - **Categorization:** Supports categorizing posts based on user-defined criteria.

- **Comment Management:**
  - **Create and Manage Comments:** Users can create comments on posts. Authors can manage their own comments, while admins can manage all comments.

- **Role-Based Access Control:**
  - Uses CanCanCan for defining user permissions, allowing fine-grained control over what users can do based on their role.

- **Responsive Design:** Designed with a focus on user experience across different devices.

### Built With:
- Ruby on Rails
- PostgreSQL
- CanCanCan for authorization

---

## Getting Started

To get a local copy up and running follow these simple example steps.

### 🛠 Installation & Set Up

If you dont have Ruby installed on your computer, you can download it from [here](https://www.ruby-lang.org/en/downloads/).
Once you have installed ruby, you can follow this list:

#### 1. Clone this repository or download the Zip folder:"

```bash command
$ git clone https://github.com/PinkMoon25/blog-webapp.git
```
#### 2. Navigate to the location of the folder in your machine:
```bash command
you@your-Pc-name:~$ cd <folder>
```
#### 3. Press Enter to navigate to your local clone and install gems.

```bash command
bundle install
```

#### 4. From the terminal run the app with the following command
```bash command
rails s
```

## Authors

👤 ***Tushar Singh***

- GitHub: [@PinkMoon25](https://github.com/PinkMoon25/)
- Twitter: [@twitterhandle](https://twitter.com/TusharS90674484)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/meet-tushar-singh/)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/PinkMoon25/blog-webapp/issues).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./LICENSE) licensed.
