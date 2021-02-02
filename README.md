# 📽 ReelLecture

A tool for running lectures in the era of virtual and remote learning. Creates a video presentation space where the instructor can get feedback on their user's emotions and attention. Developed by Sabhya Raju (https://www.linkedin.com/in/sabhya-raju/), Amanda Tran (https://www.linkedin.com/in/amanda-tran/), Chris Vanderloo (https://www.linkedin.com/in/chris-vanderloo/), and myself.

## 👨🏼‍💻 Installation
First,  install MongoDB (reference [here](https://docs.mongodb.com/manual/installation/)). Type `mongo` in a terminal, then 'use ReelLecture' to create a database.

Next, run:

```
git clone https://github.com/aram10/reellecture.git
cd reellecture
npm install && npm start
```

The React project listens on port 3000, and the server runs on port 8080.

## 🛠 Building

Run `npm run build` from the frontend directory to generate a build of the project. This will also copy the build folder over to "public" in `./backend`. So, when you run just the backend, it will serve your built React project.
