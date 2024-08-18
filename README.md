# <center>CS-499 | SNHU</center>
## Computer Science Capstone




## Table of Content
1. Professional Self-Assessment
2. Code Review
3. Software Design and Engineering: Artifact 1 Fitness Tracking App
4. Algorithms and Data Structure: Artifact 2 OpenGl 3d Render
5. Databases: Artifact 1 Fitness Tracking App

## Professional Self-Assessment
As I reflect on my journey through the Computer Science program at Southern New Hampshire University, I recognize the significant growth and development I have experienced both personally and professionally. My academic pursuits and practical projects have equipped me with the skills and knowledge necessary to excel in the fast-paced and ever-evolving field of technology.
Beginning my studies in 2020, I have spent the past 4 years immersed in computer science, gaining a comprehensive understanding of the field's theoretical and practical aspects. Throughout this program, I have delved into various subjects, including software design and engineering, algorithms and data structures, and database management. Each course has contributed to building a solid foundation in programming, problem-solving, and analytical thinking.
My coursework and projects have provided me with hands-on experience in multiple programming languages and development environments. I have become proficient in languages such as HTML/CSS, Javascript, Java, C++, Python, and SQL, and have developed a strong grasp of software development methodologies, including Agile and DevOps. These skills have enabled me to design, develop, and optimize complex software systems that are both efficient and maintainable.

## Software Design and Engineering: Atrifact 1 Fitness Tracking App
For the software engineering and design category, I have selected my fitness tracking app developed for the CS 360 course as the artifact. This app serves as a practical example of my skills in designing and implementing a complete software solution. To enhance my fitness tracking app in alignment with software engineering and design principles, I plan to focus on improving security, user-friendliness, and memory efficiency. For security, I will integrate new authentication for robust user authentication, ensuring that user data is protected by industry-standard protocols. 
### Flow chart for the Authentication process
![image](https://github.com/user-attachments/assets/c56b01d2-f83f-4f09-a399-62a972a3579c)

![image](https://github.com/user-attachments/assets/da69c8a5-815f-4f29-9534-a376b462b542) ![image](https://github.com/user-attachments/assets/9df688ad-794c-4c93-a313-f24916d04d85)




### List of Enhancements made
- Each file includes detailed comments explaining the purpose of the class and the functions within it.
- The app's UI has been completely revamped to improve user navigation and overall experience.
- Weight entries now display the current date, ensuring that users always have relevant and up-to-date information.
- Optimized AddWeight.java Class: This class has been refined to enhance user experience by delivering quick feedback and efficiently managing database interactions.
- Efficient Goal Insertion: Adding a new goal to the database is now a constant-time operation, ensuring swift and reliable updates.
- Proper error handling and data validation are implemented to ensure that only valid data is processed, minimizing the risk of application errors.
- Responsive LoginActivity.java Class: This class efficiently processes user input and provides immediate feedback, improving the login experience.
- Any unused or redundant code and variables have been removed to streamline the application's performance.
- Improved User Login Security: Security measures have been strengthened to better protect user login information

#### Course Outcome 1
In my work on the fitness monitoring app for the CS 360 course, I employed several strategies to build a collaborative environment that enabled diverse audiences to support organizational decision-making. One of the primary strategies was through the use of clear and inclusive communication. I made sure to document the app's development process thoroughly, providing detailed comments and explanations in the code. This approach ensured that all team members, regardless of their technical expertise, could understand the codebase and contribute effectively. This inclusive documentation was crucial in facilitating collaboration and ensuring that everyone involved could participate in discussions and decision-making processes.  By Utilizing collaborative tools like GitHub to manage version control and code reviews. This will allow the team to work together efficiently, tracking changes and providing feedback in real-time. By maintaining an open and transparent workflow, It will be possible to make collective decisions that reflect the diverse perspectives within a team. This approach not only improves the quality of our work but also fosters a sense of shared ownership and responsibility.
Through these strategies, I was able to create a collaborative environment that encouraged diverse input and supported informed decision-making. This experience highlighted the importance of clear communication and effective use of collaborative tools in achieving successful outcomes in software engineering projects.  
To improve user experience and performance, I've improved the AddWeight.java code, ensuring that data entries are current and pertinent. For users to receive accurate information that they can rely on when making decisions, effective data processing and error management are essential. These updates not only improve the functions of the app but also create a more effective and fruitful collaboration atmosphere by providing quick access to accurate and relevant information.

#### Course Outcome 4
 I also demonstrated the ability to use well-founded and innovative techniques, skills, and tools in computing practices to implement a solution that delivers real value and meets industry-specific goals. The app was designed with a focus on both front-end and back-end development, showcasing my proficiency in creating a complete software solution that is both functional and user-friendly. I applied industry-standard techniques in mobile development, such as implementing robust security measures including secure authentication and data encryption. These measures are essential for protecting user data and ensuring that the app meets industry standards for privacy and security. By incorporating these techniques, I demonstrated a clear understanding of the importance of security in software design, aligning with industry-specific goals to protect user information. I used industry-standard techniques to optimize the app's performance and memory efficiency. This involved profiling the application to identify bottlenecks, modifying data structures in the database(more on that in Artifact 3), and implementing lazy loading for non-essential components. These optimizations not only improved the app’s performance but also ensured that it could run smoothly on a variety of devices, thereby enhancing user experience and satisfaction. Also, I focused on user interface and user experience design by integrating accessibility features and refining the UI to be more intuitive and aesthetically pleasing. I learned that users typically interact with their phones using their right hand, so I redesigned the UI to be more right-hand friendly. I adjusted the placement of many buttons, lowering them to make them easier to reach with the right thumb. Additionally, I refined the color combinations to create a design that is both simple and visually appealing. These enhancements were guided by research into how users interact with mobile applications, allowing me to design a product that is not only technically sound but also aligned with user needs and industry trends.




## Algorithms and Data Structure: Artifact 2 OpenGl 3d Render
My OpenGL object for my artifact falls under the algorithms and data structures category. It was part of the computer graphics and visual computing course I took, CS-330. The artifact is a component of a project in which we developed a 3D scene manager that uses OpenGL to manage the rendering of different objects, textures, and materials. The main objective of the project was to manage resources including textures, shaders, and geometric data while implementing effective rendering algorithms. Because it demonstrates the application of sophisticated data structures—such as maps for quick lookups and algorithms for resource management and rendering optimization—this artifact is very pertinent.
![image](https://github.com/user-attachments/assets/c53b75e8-ccc0-4768-887e-c9996345e41e)

### List of Enhancements made
- Memory Management: improve memory safety, reduce the risk of memory leaks, and ensure proper resource deallocation.
- Rendering Performance: Optimized the rendering algorithms by reducing redundant state changes and minimizing OpenGL calls, resulting in a smoother and faster rendering process.
- Texture Loading: Applied efficient image processing techniques and minimized redundant texture binding to reduce the overhead of texture operations.
- Removed any unused library imports, functions, and codes.
- Added detailed analysis for key methods with specific time complexity
- Made sure i had an efficient memory deallocation using the DestroyGLTextures function.
- Made LoadSceneTextures function loads textures only once and binds them, minimizing the overhead of loading textures during runtime.
- Better Error handling is included to notify the user if any texture fails to load, which is essential for debugging and ensuring rendering consistency.
- Added the ApplyTransformations function to efficiently compose multiple transformations into a single operation, which reduces the overhead of applying transformations individually.

#### Course Outcome 3
Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices. In developing the SceneManager class, my approach was centered on several key areas to enhance its functionality and performance while adhering to these principles and practices. One crucial aspect was memory management. I explicitly deleted dynamically allocated memory, such as the m_basicMeshes pointer, to ensure resources were properly deallocated and to mitigate the risk of memory leaks. Additionally, I set pointers to NULL after deletion to prevent potential dangling pointer issues.

## Databases: Artifact 1 Fitness Tracking App
As a project for my CS 360 course, which concentrated on using database management methods and principles, I created the fitness tracking app. The main objective was to develop a system that could manage user data about fitness-related activities, such as tracking progress over time, keeping track of workouts, and offering data visualization insights. The database architecture of the program, which maintains user profiles, activity logs, and goal accomplishments, is essential to its operation.
![image](https://github.com/user-attachments/assets/e787908b-58c5-4d18-ad79-1da4ba9f1b37)



(https://github.com/FikrYemane/CS-499/tree/master)
