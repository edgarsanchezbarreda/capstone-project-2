# Project Proposal

1. The tech stack that I will be using for this project would be React for the **front-end** and Node.js for theh **backend**. I will be using **Tailwind CSS** for styling the UI, with the plugin **daisyUI** for faster development, and cleaner HTML. Also, I will be incorporating the react animation library **Framer-Motion** to create a smoother and more aesthetic user experience. For routing, I will be using **React Router v6** to utilize serer-side rendering.

2. Although the project will be a full-stack app The front-end UI is going to be the focus of the project, creating using CSS and animation to create an aesthetic and smooth UX/UI.

3. The app will be a website, hosted on a site like vercel or render.com

4. The goal of the project is to create an app where people who are new to the world of fitness or strength training can have a place to give them a sense of direction or a starting point to their fitness journey.

5. The demographic of the users to use the app will likely be people that are new to fitness or strength training, and have no knowledge of how to get started in accomplishing their fitness goals.

6. I plan on using the ExerciseDB api to fetch the necessary data, being exercises and information regarding each exercise such as target muscle, equipment needed, exercise description, exercise gif, etc.

7. **Project Outline**:
    1. The database schema will consist of a **users** table, that will contain username, email, and password for authentication, and other personal information such as height, weight, fitness goal, etc. A **macros** table consisting of a user's recommended macronutrient profile according to their personal information. A **user workout** table consisting of a user's specific workout plan according to their responses the initial questionnaire. One user can have multiple user workouts. And a **exercise** table consisting of individual exercises, and information related to each exercise such as equipment type, target muscle, exercise gif, description etc.
    2. The main issue that I will run into while working with the api is that it does not have all the data that I would need to implement every feature of the app, so I would need to supplement that data myself.
    3. I will need to secure user authentication data like email and password.
    4. The app will have a few features, such as creating an account, recommending a macronutrient profile, creating and saving multiple workout routines, editing their generated workout routine as the user wishes, the ability to watch video tutorials for each exercise, and an interface where users can track their progess and write notes regarding their workout for each day.
    5. The user flow will consist of creating a profile, answering the fitness questionnaire which consists of questions regarding fitness goals and style of workout routine they are looking for, then viewing their workout routine and having the option to edit or leave the program as is, and having an interface where the user can track their progress and write notes when they work out.
    6. The
