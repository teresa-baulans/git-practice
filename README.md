# git-practice

Welcome! This is a repository you can safely make commits to and play around with to learn how to
use git and github.

There are several tasks that we suggest you complete before starting your S2DS course to get some
practice working with others on the same files. This often happens when working as part of a group,
but is something that is hard to replicate when working on your own. In particular, we would like to
give you some experience in merging branches and dealing with merge conflicts.

The first part of this `README.md` markdown file will contain instructions, the second part of this
file will be the part that you edit. You can edit this file multiple times - doing so will give you more
practice, and help others out by creating merge conflicts.

Please do not edit any of this files contents above the section `Edit This`.

# Tasks

## 1. Setup

1. Clone this repo to your computer.
2. Checkout to a new branch using `git checkout -b your-name` eg. `git checkout -b alex-hampton`
3. Edit the section `Edit This`. Add your name to the first sentence, and then add 3-5 facts  - they can
be about you, or anything interesting. Please make them different to the version on your local
`master branch` - ie. if someone says what their favourite colour is, don't put your favourite colour.
We want these facts to be different from the previous person to create conflicts.
4. Add this file using `git add README.md`
5. Commit this file using `git commit -m "Added your-name facts"`
6. Push your branch using `git push --set-upstream origin your-name` eg. `git push --set-upstream origin alex-hampton`
7. Create a pull request on Github. Go to the `git-practice` Pivigo repo (https://github.com/Pivigo/git-practice). There should be a popup box saying that your branch as recent pushes a few minutes ago, and there will be a green box saying `Compare & pull request`. Click this. This will let you create a pull request and leave a comment - please put a short sentence saying what you have done (ie. updated the README with your information). Putting clear, descriptive comments is important to help others understand why you have made the changes. It is also where you would give any instructions required to run the code. When you have added a comment, click the `Create pull request` button. **DO NOT MERGE THIS IN**

## 2. Handling Merge Request on Github

8. Go to the Pull request section of this repo (https://github.com/Pivigo/git-practice/pulls).
9. Here you should see the pull request you have just created. If there is more than 1 open pull request, then merge the oldest (bottom) pull request and leave the rest. If there are not more than 1 open pull request, please come back later. 
10. If there are not conflicts, then click the green buttons to merge the branch and confirm this. If there is no conflict, then the branch can be deleted after. 
11. There may be a conflict that needs to be involved. This is because the version of the `README.md` you originally editted is now different to the version on the remote `master` branch. Click `Resolve conflicts` and the file should open in your browser. There will be a conflict in the `Edit this` - keep your facts, but delete the previous version. Make sure you delete any lines that start `<<<` or `====` - there should be no text higlighted in orange. Once finished, click the mark as resolved button at the top to complete the merge. **Please do not delete the branch** Congratulations, you have successfully dealt with a merge conflict in Github!

## 3. Handling Merge Request in your IDE

12. The next day (or after another pull request has been merged in) checkout to the master branch with `git checkout master`.
13. Pull the remote version of the branch with `git pull`.
14. Change to your version of the branch with `git checkout your-name`  - Note this is different to the code in step 2 as you are not making a new branch.
15. Merge the `master` branch into your branch using `git merge master`.
16. This will create a merge conflict - open `README.md` in your IDE of choice and deal with the merge conflict in a similar way as before.
17. Once the merge conflict has been handled, add the `README.md` file and create a new commit (look at previous steps if you are unsure of the code).
18. Push the branch and create another pull request - you have now handled a merge conflict in your local branch. This is the main way you will deal with merge conflicts.

# Edit This

The most recent person to merge into main is Alex Hampton - Tester

* His favourite colour is blue.
* Competitive art used to be in the Olympics.
* There is one sea in the world that does not have a land border.
* He loves cats, even though he has a dog.

**NOTE - Please try add different types of facts than the previous person has added**
