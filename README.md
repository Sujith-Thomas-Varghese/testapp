# WELCOME

This repo was setup to learn React at your own pace :yum:

## After cloning this repo

```javasript
cd testapp/
npm install
npm start
```

# Rules :eyes:

* **Create** a branch `app/<yourName>`, This will be you Main branch.

  - **Create** a branch `feature/<featureName>` on each new addition to your project that you're working on. Which will be merged to `app/<yourName>` on completion.
  

  
* **Don't** merge directly. Commit and Push your changes to your `feature/<featureName` and then create a pull request from it to your `app/<yourName>` branch. You can assign a reviewer at this step but can be ignored if you chose to do so.

_This is to encourage a pull request workflow_ :sweat_smile:

### Sample flow

* `git checkout -b app/<yourName>` this creates your main branch and checksout to it.
* `git push -u origin app/<yourName>` this pushes your newly created local branch to remote.
* `git checkout -b feature/<featureName>` this creates your feature branch and checksout to it.
* _Work on feature and commit your changes_.
* `git push origin feature/<featureName>` this pushes your changes to remote.
* Goto the Github and create a pull request from your`feature/<featureName>` to `app/<yourName>`. 
* Merge after checking your changes.


That's about it :tada::confetti_ball::confetti_ball::tada:


Refer the wiki for more details
