# Robogals Git Demo :)

## Demo

Make a folder with the naming convention below

```
{name}-{RoomID}
```

For example:

```
MemesLol-02
```

Then store anything inside that folder ( can be a simple hello world (＾▽＾) )

### What to do

Please fork this repo, by clicking on the fork button at the top left corner
Github will then take some time to copy this repository over to your account.

Your repo is now available on your account, to get the forked repo to your local machine, you may copy the https/ssh clone url then,


```bash
git clone {your url}
```

> Copy the url of the <b>FORKED</b> repo, not the one in my GitHub

> Please change {your url} to the url you copied before without the curly braces ({}).

> There is no need to create a new folder, as git clone will create a folder with the repo name!

Then you may do the neccesary changes,
then add the changes to your forked github repo.

run the following commands on your terminal/git bash

```bash
git add .
```

The command above prepare your files to be commited.

```bash
git commit -m "{message}"
```

> Please replace message with a propper commit message without curly braces for example git commit -m "example message"

Then you can push the repo to the server by running

```bash
git push
```
> Git may ask you password in this step, please provide the password for your github account.
> Git maay also ask the password set on ur SSH key when resetting ur connection to git. 

You may push changes a few times to the server, you may also do a few commits before pushing, remember that commits acts like a snapshot so that you can get back to a version of your code in the future.

If you think that all is good, you can create a pull request to merge your repo with the main repo in https://github.com/JaysM32/robogals-git-workshop.git

> Make sure your code doesn't interfere with your friend's and you don't delete any other part of the repo. Any pull request that doesn't comply with this rules will not be approved.

### Updating your repo (Pulling new changes)

If your repo is behind the master repo and you nees to update the repo,
You can run the following:

```bash
git remote add upstream <original repo>
```

> Replace original repo with https://github.com/JaysM32/robogals-git-workshop.git

> The code above is a one-time setup on every cloned repo, after that you just need to run the code below (every cloned repo means, if you re-clone the repo from your place, you'll need to rerun the command above).

Sometimes in the future, your repo in github may have more commits that the one on your local computer, this may be caused by someone contributing or you push changes from other machine, to refresh you local repo and get latest changes, please run:

```bash
git pull
```

If your local repo is not altered, you can run this:

```bash
git pull upstream master
```

Else, run this:

```bash
git rebase upstream/master
```

> !!! WARNING : By using git rebase upstream/master all of your current progress will be deleted!

## GooD LUck! ( ´ ω ` )