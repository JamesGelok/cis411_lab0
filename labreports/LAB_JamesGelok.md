# Lab Report Template for CIS411_Lab0
Course: Messiah College CIS 411, Fall 2018<br/>
Instructors: [Joel Worrall](https://github.com/tangollama) & [Trevor Bunch](https://github.com/trevordbunch)<br/>
Name: James Gelok<br/>
GitHub: [JamesGelok](https://github.com/JamesGelok)<br/>

# Step 1: Fork this repository
- The URL of my forked repository: https://github.com/JamesGelok/cis411_lab0
- The accompanying diagram of what my fork precisely and conceptually represents: ![my diagram](https://image.ibb.co/m0G9UK/GELOK_JAMES_DIAGRAM.png "git fork")

# Step 2: Clone your forked repository from the command line
- My GraphQL response from adding myself as an account on the test project
```
{
  "data": {
    "mutateAccount": {
      "id": "f80d4a01-60cb-40de-93c3-c1498eeffc87",
      "name": "James D Gelok",
      "email": "jdgelok@gmail.com"
    }
  }
}
```

# Step 3: Creating a feature branch
- The output of my git commit log
```
d2ddea5 (HEAD -> master, origin/master, origin/HEAD) Version 0.0.1 of the lab instructions
ab312fc more progress
62fb0a5 more progress
fe1937b more in the lab instructions
3e807fb first section
9ae6b83 remove LAB.md
e429c1a lab instructions
968099e remove test db
7362cd1 working
44ce6ae Initial commit
```
- The accompanying diagram of what my feature branch precisely and conceptually represents ![feature branch](https://image.ibb.co/bGuhGz/feature_branch.png "feature branch")


# Step 4: Setup a Continuous Integration configuration
- What is the .circleci/config.yml doing?

It is storing the config information for circleci.

- What do the various sections on the config file do?

"version" specifies the version number.

"jobs" nests many folders underneath it.

"build" contains build information.

"docker" contains information for the docker and circle ci image.

"working_directory" specifies the working directory.

"steps" specifies the steps that run for circle ci to behave properly, with many sections underneath it.


- When a CI build is successful, what does that philosophically and practically/precisely indicate about the build?

It indicates the types of things we wish to update about our build at the same time indicating how to start our build. It should be the same each time we update it so that we can continuously update our build.

- If you were to take the next step and ready this project for Continuous Delivery, what additional changes might you make in this configuration (conceptual, not code)?

# Step 5: Merging the feature branch
* The output of my git commit log
* A screenshot of the _Jobs_ list in CircleCI

# Step 6: Submitting a Pull Request
_Remember to reference at least one other student in the PR content via their GitHub handle._

# Step 7: [EXTRA CREDIT] Augment the core project
PR reference in the report to one of the following:
1. Add one or more unit tests to the core assignment project. 
2. Configure the CircleCI config.yml to automatically build a Docker image of the project.
3. Configure an automatic deployment of the successful CircleCI build to an Amazon EC2 instance.
