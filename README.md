# Git-hub-Actions-Simple

What is Github Actions
How to use - step by step demo
A demo workflow file - how to create, run and check results
Terms : Workflows, Events, Jobs, Steps

Github Actions is a feature in Github to create a custom automated workflows
Automate SDLC WORKFLOWS
Implement CI CD Deveops

Coding -> Build -> Deploy -> Testing -> Release

Demo : 
Step 1 : SignUp and Login to github.com
Step 2 : Create a new Repository
Step 3: Create a folder .github inside / workflow
Step 4: In the Folder Create a YAML File with .yml extension
Step 5: Add the content of the workflow in the file
Step 6: Commit and push the changes
Step 7: Go to Repo main page and click Actions Tab
Step 8: Select the workflow from left sidebar and check the logs and results

Terms:
 WORKFLOW : collection of jobs, defined in a YAML file
 name:
 EVENTS : any activity in the repo that can trigger a workflow 
 on:
 JOBS : collection of steps
 jobs:
 STEPS : actions to be taken, commands, scripts
 steps:
 Chain Jobs - :needs

name: hello-world
on: push
jobs:
  my-job:
    runs-on: ubuntu-latest
    steps:
      - name: my-step
        run: echo "Hello World!"



