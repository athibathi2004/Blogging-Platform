# Blogging-Platform
The "Blogging Platform" project is a robust web application enabling users to write, manage, and interact with blogs, providing all essential social and administrative features expected in a modern blogging system.
Core Features
User Authentication (JWT based): Users register and log in securely, with session state managed by JWTs for protected routes.

Blog Operations: Users can create, edit, and delete blogs using a rich text editor (React Quill), supporting formatted content and media.

User Profile: Each user has a profile displaying authored blogs and possibly user stats or profile images.

Comments & Likes: Engage with blogs using comment threads and like mechanisms, promoting interaction.

Search & Filtering: Search for blogs and filter by category or tags for discoverability.

Admin Dashboard: Admins manage users and posts, helping maintain platform quality.
Layer     |  Technology            |  Purpose                                  
----------+------------------------+-------------------------------------------
Frontend  |  React.js              |  SPA architecture and component-based UI  
          |  Redux                 |  Advanced state management                
          |  Tailwind CSS          |  Rapid and modern styling                 
          |  React Quill           |  Rich text blog editing                   
Backend   |  Node.js + Express.js  |  RESTful API, logic, JWT auth             
Database  |  MongoDB               |  Scalable document storage for blogs/users
Tools     |  GitHub                |  Version control and collaboration        
          |  Cloudinary            |  Image and media upload/storage           
          |  Postman               |  API testing and debugging                

Implementation Highlights
Frontend: React with Tailwind CSS enables a responsive single-page interface. Redux centralizes state, including user authentication, blog data, and UI feedback. React Quill allows rich content creation.

Backend: Express.js APIs implement CRUD operations for blogs, comments, likes, and user management. JWT secures endpoints, ensuring only authorized users can perform protected actions.

Image Handling: Cloudinary integrates for seamless uploading and embedding of images within blogs.

Admin: Admins access a custom dashboard for advanced moderation of both posts and users.
