## Hello! 😄

Thanks for visting my github! I am passionate Software Developer and student of Brigham Young University.

### What's interests me?
I am passionate about learning new technologies and using them to solve problems. In particular, I love developing solutions using cloud computing services such as Amazon Web Services. In both my school work and personal projects, I work hard to fully understand the topics I am tackling, rather than just doing enough to get by.

### What do I value?
> Educating the mind without educating the heart is no education at all.
> -- Aristotle

As I strive to be successful, my goal is to always be mindful of my peers. Inviduals who can empathize with others are not only more likely to succeed, but they can also help others do well.

# My Projects

## Dreamojob
<summary>Click to expand!</summary>

<details>
Over the summer of 2021, I have been working on a full-stack project to increase my skills in a variety of areas. This has culminated in the "dreamjob" project, which is a basic app that allows the user to save jobs on the website, as well as make a "timeline" of their career using those jobs to visualize how their career could look like. The webapp is optimized for both desktop and mobile (with more extensive testing done on Windows and iOS).

### The Stack:
Each stack is deployed individually using the AWS CDK in a "deploy" folder.

**Front-end**: HTML, CSS, JavaScript, Vue.js, Vuetify

**Back-end**: Node.js running on a docker container connected to a MySQL database (Objection.js was used as a ORM for an "model-first" approach to the database)

**Infrastructure**: Built on AWS. Almost all of the infrastructure was developed using the Typescript AWS CDK.

- S3/Cloudfront (For static hosting of the site)
- Cognito (For registering users)
- ECS/Fargate (For the Node.js container)
- VPC (For separating services into public and private subnets)
- Amazon RDS (For the MySQL database)
- Other miscellaneous services to support the stack (Secrets Manager, Lambda, etc.)

### Related Repos (placeholders, fix later):

- Frontend: https://github.com
- API: https://github.com
- Database: https://github.com
</details>

##

<details>
<summary>Click to expand!</summary>

I completed this project Fall 2020. It's purpose was to learn more of Python, and to use a variety of data structures in a console based application. The project is a simple game where the user manages their space fleet and sends it on cargo missions. A fleet can be attacked, and the majority of the programming for the project focused on the battle simulation that happens in the console using some formatting and loading bars to show the status of each fleet. Primarily the simulator uses a queue to process the guns of each ship so that they are all able to fire once during an iteration.

It should be noted that while the battle simulator and some other features work, the project is not finished as I stopped once I was satisifed with what I had learned.

**Repo**: https://github.com/justintlaw/SpaceFleet
</details>

<!--
**justintlaw/justintlaw** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
