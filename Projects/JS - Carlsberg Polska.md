
Carlsberg Polska
https://www.thedroidsonroids.com/portfolio/carlsberg-product-distribution-app

### Result
75% faster Operations
1 Excel file instead of dozens
80% shorter billing time

### Key Features
## Mobile App
# Individual & Group Tasks
Distributors can choose the tasks they want to take on. Once completed, they earn points that can be redeemed for cash.
# Field Tasks
Map-based tasks enable dealers to see where they can complete a task near their location, wherever they are.
# Task validation
Users can quickly and conveniently confirm a completed task directly in the app. For example, by completing surveys and adding photos.
# E-learning
Distributors can enroll in courses of their choice and improve their skills. After completing a course, they earn additional points.
# News
The app gives users access to the latest news and important announcements, such as Carlsberg Polska's awards.
# Activity History
Users can view a log of all their tasks, including completion and billing details. They can also see the number of points earned for each task.
# Real-time notifications
Notifications alert users to new tasks, their current status, and when points have been awarded or are about to expire.
# In-App Store
Users can view their earned points and convert them into money through the IgoriaCard platform, which can be easily connected to Hoppy.
# Bonus Allocation
Team managers have a points budget that they can easily award to users for completing tasks, all of which can be done directly from the app.
# Profile Set-up
Users can quickly start using the Hoppy app with an easy profile setup that includes their role, billing details, store orders, consents, and regulations.
# Contact
Users can quickly find contact information in the app to report technical issues, questions, or feedback about Hoppy.
# Admin Panel (Web APp)
Managers can control what distributors see in the application and handle various aspects, including: manage user groups and add new users, create new individual and group tasks, monitor bonus budgets and award points, and more.
## Admin Panel (WEB)
# User management
Managers can add new users and manage user groups, ensuring everyone has the right access in the app.
# Task Creation and Monitoring
Easily create tasks for individuals or groups, monitor progress, and manage bonus budgets by awarding points to users.
# Content Publishing and reporting
Publish important news and bylaws directly in the app, and receive detailed reports on user activity to stay informed.

How a rewards-driven experience can transform your opeartions
## Challenges
Replace outdated methods with the latest in app technology
From the outset, the project aimed to develop an application that would streamline operations for Carlsberg Polska distributors and their managers. There was a pressing need to move away from outdated and error-prone methods, such as managing hundreds of emails and numerous Excel sheets.

Our client also wanted to simplify and speed up the user billing process. To meet these needs, the new system had to be user-friendly, automated, and reliable.

However, when Carlsberg Polska first approached us, they were recovering from releasing an unsuccessful app that failed to meet user expectations and was withdrawn. Meanwhile, competitors had seized the opportunity and launched their own applications, which were well received in the marketplace.

So our challenge was twofold: to keep pace with established competitors and to create an easy-to-use and reliable system that would significantly improve operations.

The goals of the Hoppy project for Carlsberg Polska:

- Replace outdated email and Excel methods with an automated solution to improve existing market processes.
- Use the application to reduce the operation time and the organization’s manual effort.
- Ensure products are delivered quickly and efficiently to retail stores. Keep products visible to potential customers.
- Enable users to conveniently access and complete tasks in the field, increasing engagement.
- Have a world-class product that provides an edge over the competition.

## Solution - Key strategies for improving user interaction
# How clear initial goals set us up for success
From the beginning, our team focused on gathering and analyzing feedback from the previous version of the app. This step was critical to ensuring that the new version would meet users’ needs and improve their day-to-day experience. We also held workshops to determine the full scope of the project and plan it in phases that made financial and strategic sense.

# Lower costs, faster development with Flutter
Technologically, we opted for Flutter for its cross-platform capabilities, allowing us to launch simultaneously on iOS and Android. This choice guaranteed lower project costs and a faster app release.

# Rewards-driven app: Improved UX for streamlined operations
Hoppy is designed to offer a rewards-driven experience in order to make the distribution process simple and fun. While redesigning the app, we focused on simplicity and functionality to streamline daily operations for both distributors and managers. Here’s what we’ve introduced.

# For distributors:
- Ease of use: Distributors can easily select and complete tasks directly from their smartphones.
- On-the-go functionality: A user-friendly interface, tasks with a map and timely reminders make it easy for dealers to use on the road.
- New features: The app allows users to register for new tasks, approve completed ones, read news, participate in e-learning modules, and more.
- Bonus cash out: Users can easily convert their earned points into cash through the in-app store.

# For managers:
- Admin panel: Streamlines task management by enabling managers to create tasks, add users, upload documents, and distribute points.
- Advanced dashboard: Provides complete visibility into distributor activity with real-time updates on tasks and key metrics.
- Enhanced coordination: The interface simplifies administrative tasks, ensures compliance, and enhances managers’ ability to respond quickly to changes, improving team coordination and decision-making.

## Results
# 75% less time spent on operations
- Hoppy is a huge time saver: Before Hoppy, it took 15-20 hours a week to manage a distribution project. Now that time has been reduced to just 5 hours per week. This saves 75% of the time.
- Faster user billing: Hoppy helped us to reduce user billing time by 80% thanks to the automatic transfers we implemented.
- Streamlined and automated workflow: With Hoppy, we’ve streamlined the process to just one Excel file and one required PDF document, significantly reducing the previous clutter of dozens of Excel files and hundreds of emails.
- Strategic task management: Hoppy simplifies the process of assigning tasks to sales reps and provides the flexibility to stop tasks when they’re no longer needed, resulting in cost savings.
- Increased user engagement: Hoppy streamlines task completion and management, improving the overall experience. Both sales reps and their managers have given positive reviews of the new version of the app.
- Here are some of the quotes from our survey of users of the new version of the Hoppy app:

## How we did it
# Mobile App
Techs: Flutter, Dart, BLoC, Dio, Firebase Messaging, Bitrise, Mockito, Intl
We developed a versatile app for both Android and iOS using a single codebase with the Flutter framework and Dart language, utilizing the BLoC architecture pattern for robust management of the app’s state.

For real-time notifications, such as alerting users about new tasks or rewards, we integrated Firebase Messaging. This ensures users are promptly updated about important actions and changes within the app.

To understand user behavior and refine our business and marketing strategies, we incorporated Google Analytics. This tool provides essential insights that inform our decision-making processes, enhancing user engagement and app functionality.
# Web App
Techs: TypeScript, React, Singe Page Application, React-query (Sync state with API), Material UI, Firebase, Sentry
We developed a web application using React with the Vite bundler to accelerate development, using Material UI for quick design implementation. A significant challenge was designing a task creation form that could handle various task configurations while adhering to business rules. This included conditional fields that would appear or adjust based on other entries. We addressed this complexity by using react-hook-form to manage form state and Zod for validation.

The application heavily relies on API data, which serves as the primary source of truth. We used the react-query library for effective state synchronization and React’s context mechanism for managing the global state.

We organized the application into modules to keep the code manageable, employed ESLint for static code analysis, and Prettier for code formatting. Additionally, the application integrates Firebase for behavior analysis and Sentry for error reporting, enhancing the overall functionality and user experience.
# Backend
Techs: REST, TypeScript, NestJS, PostgreSQL, TypeORM, AWS S3, Jest, SendGrid, Sentry, lgoria Trade, SaleOn
We developed our API using Node.js with the NestJS framework, which expedited our development by providing numerous built-in features. We adopted clean architecture as our guiding principle, ensuring that our business logic remained independent of external dependencies, frameworks, and databases. This architecture not only facilitated the creation of clear and efficient acceptance tests but also provided robust protection against bugs.

The business requirements necessitated integration with a variety of external services, ranging from commonly used ones like Sendgrid for email services and AWS S3 for file storage, to more complex systems such as e-learning platforms and virtual credit card money transfers.

We meticulously reviewed the documentation and enhanced communication with these services to develop robust abstractions that concealed the implementation details without losing critical information. This was especially crucial with services like Igoria Trade, which uses a SOAP communication architecture. To ensure data integrity, we utilized the Zod library for response validation, confirming that the data received was in the correct format.

For code quality and consistency, we used the same tools we used for web application (ESlint & Pretier). The application is containerized using Docker and deployed on AWS infrastructure, ensuring reliable and scalable operation.
# App Redesign
Techs: Miro, Figma
We kicked off the app project with product discovery workshops where we defined the scope and divided it into versions to meet the budget requirements and business goals. Throughout all design phases, starting with wireframes, designers were part of the SCRUM team, ensuring constant communication with the client and product team. During weekly design reviews, we refined the output along with the component library to meet the client’s vision. All work was done in Figma.

In the first version of the application, we provided users with convenient access to group tasks, earning points and the ability to exchange them for real money.

After the first release, we received positive feedback from users. The application achieved its goals and helped to centralize tasks and earn rewards. Users identified tasks as the most important feature, so we added other types of individual tasks, such as surveys, educational tasks, distribution tasks, and sales tasks. In addition, we integrated a database of retail stores, giving users access to tasks via a map for greater convenience.

In future versions of the application, we plan to continue gathering feedback from users and improve the gamification features while expanding the store.
# Quality Assurance
Techs: JIRA, Xray, Browserstack STF, Crashlytics, Postman, Insomnia, Alice, Firebase
To ensure the application meets the highest standards of quality and reliability, we use a mix of manual testing and advanced tools. We use test management tools such as JIRA and Xray to design test plans, manage defects, and track test case results, facilitating effective collaboration and progress tracking across the development team.

For device compatibility testing, we use services such as Browserstack and STF (Smartphone Test Farm), which provide access to a wide range of real devices, emulators and simulators. This enables us to rigorously test the app across multiple platforms and configurations. For crash and bug reporting, we use Crashlytics for detailed diagnostics and troubleshooting, which helps us maintain a stable and high-quality application.

API testing is performed using tools such as Postman and Insomnia, which are essential for verifying backend interactions and ensuring that our APIs deliver correct results and handle errors effectively. We also use Alice, an HTTP inspector tool built specifically for Flutter, to debug HTTP requests within the application.

Finally, Firebase Performance Monitoring helps us track and optimize app performance by providing key metrics on startup times, network latency, and user interactions. This holistic set of QA strategies and tools ensures that the Hoppy project delivers a robust and user-friendly mobile application.