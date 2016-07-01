Goal of the excercises
======================
The goal of these exercises is to get a feeling about the workflow that is
used on a day to day basis for developing at Devhouse Spindle.

During this exercise the work that has to be done is to create a addition
to the fairytale in the README.md with the use of feature branches, reviews,
squashing and merging.

Before we start
===============

Make sure the reviewboard url is added to your git config with the following command::

    git config --add reviewboard.url https://rbcommons.com/s/VoIPGRID/

Excercises
==========
Let's start with the excercises!

Excercise 1: Creating a feature branch
--------------------------------------
Create a feature branch for your addition to the fairytale. The naming convention
used look like this::

    feature/my-awesome-ticket-name-1234

Go ahead and create a feature branch based on the develop branch and push the
new branch to the remote.

Excercise 2: Committing story lines
-----------------------------------
Commit nameing convention looks like this::

    PROJECT-1234: Ticket title

    Example: GRID-2345: Created readme file

Add lines to the story in the README.md and create a commit for each line added.
After adding 3 lines and commits push these commits to the remote.

Excercise 3: Publishing a review
--------------------------------
Create a review for the commits you made.

    **HINT: The command to create a review can be found on the wiki.**

Edit this review and update the information with the branch name, ticket number
and people who you would like to get reviews from. Publish this review so others
can start reviewing the changes.

If the review feedback does not contain a `Ship it` you are required to
update the review with the changes you made after the review feedback.

Excercise 4: Updating the review
--------------------------------
Create a commit for changes you made after review feedback and push them to remote.
Update the review afterwards.

    **HINT: The command for updating a review can be found on the wiki.**

Should you recieve a `Ship it` go to excercise 5 or repeat until you do :)

Excercise 5: Squashing commits and rename
-----------------------------------------
We like to keep our commit history clean so we need to squash the commits
made for the story + review feedback. This can be done by a interactive rebase.
This allows us to merge commits into 1 commit and change the message of the 1
commit to reflect the ticket.

Go and squash commits to 1 commit with a name that adheres to our naming convention.

    **HINT: Information about this can be found on the wiki.**

Excercise 6: Force pushing
--------------------------
By squashing commits we changed our history so the remote and our local
remote are nog in sync anymore. To make sure our local 1 commit is leading
we need to force push the branch to make the remote be the same as our local
branch.

Go ahead and force push your branch to the remote.

Excercise 7: Merging story lines
--------------------------------
Our addition to the story is now ready to be added to the develop branch!

Merge the feature branch in the develop branch.

    **HINT: Don't forget to use --no-ff to keep the merge commit.**

After merging push the updated develop branch to remote.

Excercise 8: Cleanup branches and review
----------------------------------------
The last step in the process is to delete your feature branch from atleast
the remote and close the review.

You can now close the review and delete te remote branch.
