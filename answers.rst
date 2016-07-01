Here are the anwsers for the excercises. These command are guidelines
on how to achieve the results of the exercises and are the only correct
answers.

Excercise 1::

    git checkout develop
    git checkout -b feature/my-story-idea-4567
    git push origin HEAD

Excercise 2::

    # Edit some
    git add --all
    git commit -m "Added first line"

    # Edit some
    git add --all
    git commit -m "Added second line"

    # Edit some
    git add --all
    git commit -m "Added third line"

    git push origin HEAD

Excercise 3::

    rbt post -g

Excercise 4::

    rbt post -r 1234

Excercise 5::

    git rebase -i origin/develop
    # Use 'r' on the first commit to reword it and use 'f' on all other commits
    # to squash them.

Excercise 6::

    git push -f origin feature/my-story-idea-4567

Excercise 7::

    git checkout develop
    git pull --rebase
    git merge --no-ff feature/my-story-idea-4567

Excercise 8::

    # Close the review in the webinterface
    git push origin :feature/my-story-idea-4567
    git branch -d feature/my-story-idea-4567 (optional local branch)
