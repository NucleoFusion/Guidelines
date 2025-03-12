# Sourceware Labs
  **Introduction**
  Welcome to Sourceware Labs.
  <br /><br /> 
  We are collaborative community where individuals from all backgrounds and experience come together to learn and build projects. 
  We believe and promote our motto, "Learning by Doing", emphasizing hands-on experience over passive learning. 
  Whether you're a beginner or an expert, Sourceware Labs provides a space to explore, experiment, and grow through real-world projects and 
  find like minded people who are just as passionate as you.

---

  **Prerequisites**
  To keep it simple, there are no prerequisites.
  <br /><br />
  While there are no prerequisites, an individual may need to utilize tools such as Git, Github etc to be able to
  contribute. The reason these are not mentioned as a prerequisite is because we are always there 
  to help you. You can ask questions in the community, or, if you have some specific question, pertaining to
  a project, or tool, feel free to ping the Project Leads (@project-lead) or Admins (@admin) and theyll be able to help you.

  **How to Get Started**
  Getting started is simple, you can browse the #project-hub channel to find a project, or submit one of your own ideas there.
  Once you find a project you are suitable with, you can go to the github repository of that respective project and fork it.
  Some things to keep in mind while forking, make sure you disable the "Fork main branch only" option. You will see why
  this is important in the next section.
  <br /><br />
  Our repositories generally have the format of having 2 branches, we have the main branch, and the dev branch. The dev branch holds 
  the latest commits and changes, while the main branch holds the stable releases. The benefit of seperating them as such is that this allows
  us to have a CI/CD pipeline, which in leymann terms, means that whenever the code on the main branch changes, all active deployments of
  that respective project switch to the new version. This allows us to develop and work on the project beside the deployments without hindering it.

  **Submitting Contributions**
  We love contributions from everyone! Whether you're fixing a bug, adding a new feature, or improving documentation, your help is always appreciated.
  Here's how you can contribute:
  Follow the steps below to contribute effectively:
  1. **Fork the Repository:** Start by forking the repository to your own GitHub account.
  2. **Clone the Repository:** Clone the forked repository to your local development environment.
  `git clone https://github.com/your-username/GlaDOS-bot.git`
  3. **Create a New Branch Locally:** Create a branch for your feature or fix. Name your branch in a way that describes the purpose of your changes. For example:
  - `feature/feature-name`
  - `bugfix/bug-description`
  - `docs/clarify-setup-instructions`
  4. **Make Your Changes:**
  - Add your code, features, or bug fixes.
  5. **Commit Guidelines:** When committing changes to your branch, please follow this naming scheme to keep commit history clean and readable:
    
  Commit message format: `<type>:<short-description>`

  Types:
   
  feat: A new feature or functionality added to the project.
  fix: A bug fix.
  docs: Documentation changes.
  style: Code style changes (e.g., formatting, missing semicolons).
  refactor: Code changes that neither fix a bug nor add a feature, but improve the structure.
  test: Adding or modifying tests.
  chore: Changes to the build process or auxiliary tools.
  Example Commit Messages:
  feat: add user authentication to the website
  fix: resolve issue with missing image on homepage
  docs: update README.md with contribution guidelines
  style: format code according to ESLint rules
  test: add unit test for login function
  chore: update dependencies to latest version

6. **Push and Create a Pull Request:** Once you're ready, push your changes to your forked repository and open a pull request to the `dev` repository.
**Note:** open a pull request per feature and don't forget to link the corresponding issue by writing the `#issue-number`.

7. **Follow Up** We will review your changes and may provide feedback. Please address any comments or requested changes, and we’ll merge your contribution!

**Licensing and Attribution**
To keep it simple, there are no prerequisites.
While there are no prerequisites, an individual may need to utilize tools such as Git, Github etc to be able to
contribute. The reason these are not mentioned as a prerequisite is because, in Sourceware Labs, we are always available
to help you. You can ask questions to all the members of the community, or, if you have some specific question, pertaining to
a project, or tool, feel free to ping the Project Leads (@project-lead) or Admins and theyll be able to help you.
