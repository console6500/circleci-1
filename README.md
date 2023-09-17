# 02_03 CircleCI

## Reccommended Resources
- [Quickstart guide](https://circleci.com/docs/getting-started/)

## Prequisites
Having the following items in place before starting this lab will help you have a smooth experience.

1. A [GitHub account](https://github.com/join) is required to host the code for the sample application. *NOTE: You may need to be an admin for any repositories you want to integrate with CircleCI.*
2. A [CircleCI account](https://circleci.com/signup/).
3. An [Amazon Web Services account](https://aws.amazon.com/free) is needed to deploy and host the sample application used for the deployment target.
4. The sample application should be in place before starting.  See [00_06 About the Exercise Files](../../ch0_introduction/00_06_about_the_exercise_files/README.md) for steps to deploy the sample application.
5. The exercise files for the course should be downloaded and accessible on your local system.

## Create a GitHub repo for the sample application code
Because this course covers multiple tools, a dedicated repo is need for each tool to prevent unexpected deployments to the sample-application.

1. Create a new GitHub repo. Give the repo a name and description.  Please select **Public** for the repo visibility to simplify access.  Select the option to add a README file and select **Python** when adding a `.gitignore` file.
2. From ther repo home page, select **Add file -> Upload files**.
3. Select **choose your files** and browse to the exercise files for this lesson on your local system.
4. Select all of the files and then select **Open**.
5. After the files have been uploaded, enter a commit message and select **Commit changes**.

## Configure your CircleCI account, repo connection, and project parameters
### 1. Set up your CircleCI account
### 2. Repo connection and project parameters
### Run the pipeline by creating the CircleCI configuration file