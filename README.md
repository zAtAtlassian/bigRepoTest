# bigRepoTest

first commit

Instructions on how to use submodules

1. have two repos you want to put together
2. go to the outer repo's root, in the terminal
3. run the command:

    git submodule add https://github.com/zAtAtlassian/littleRepoTest.git
    
    (using the repo's http address)

Instruction on how to "git pull" for the submodule

1. to update the inner repo, run:

    git submodule update --init --recursive