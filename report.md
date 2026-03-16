# How to deploy this chatbot into production

## main steps:

* update and make necessary changes to code
* choose a deployment provider
* make a github repository and push code into it
* linking the github repo with the hosting provider
___

# Step 1: update the code

* i added 2 extra intents "field_training" and "volunteer_work" in the intents dictionary and in the responses
* i added a template folder with an index.html page to view the bot and interact with it
* i changed the `debug = True` into `debug = False` so make it ready for production

# Step 2: choosing a hosting provider

* i chose Azure app service as i used it in the past
* created a new project with the name PPU_chatbot_deployment
* chose the run time language to be python
  
# Step 3: Pushing code into github

* i created a repository in my github account
* i used git for version control
* i pushed my code into github using these commands `git add .` then `git commit -m "first commit"` then `git push -u origin main`
  
# Step 4: Linking my repo into Azure

* in my azure project a chose deploy from github, then link my account then choosing the repo
* i now got a working link displaying the chatbot at this link:
`link`