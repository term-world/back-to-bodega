
| Date              |          |
|:------------------|:---------|
| 24 October 2022 | Assigned |
| 30 October 2022    | Due      |
| Status            | See original `bodega` repository |

# ENTERTAINMENT ENNUI: BODEGAS BECOME BORING BOROUGH BUSINESS; ONLY GAMES WILL MAKE GREATER GAINS!

**Reported by `Official Mayor-Endorsed News` on `24 October 2022`**

Citizens in the world _must be amused_ in order to stay happy. As the Mayor commented with clear intent for O.M.E.N. to report, "the people of `term-world` are only of any value to me if they are complacent. We want prestiege; we want popularity; we want...PIZZAZZ!"

So get your doo-dads, gadgets, and widgets underway, folks; it's time to engage in some _entertainment_. Since built, the once-promising neighborhood bodegas have experienced marginal business. To reap the full benefit of the Mayor's original economic stimulus plan, the `bodega`s strewn throughout `term-world` need a few landmark draws to keep kids spending their easily-obtained quarters, and the people generally distracted.

Citizens await the latest crop of cool new games to emerge from the latest effort to excite local economies. Will yours be the next big thing to come from `term-world`? Will it fill that hard-to-define, missing niche in citizens' souls only quenchable by playing past the _next_ level? Will it have, dare we write, PIZZAZZ?

## Overview

In this activity, you'll:

* learn more about `import`ing packages
* use packages to extend program functionality
* practice developing a moderately complex concept in the form of a game

Here, you must:

* _copy_ (we **stress** _copy_) the `AmusementTemplate.py` file to your `bodega` department
* _rename_ (we also **stress** _rename_) the file `Amusement.py`
* develop a concept for a department- or bodega-themed game
* use any (or all) of the following `3` modules:
  * `random`
    * you're going to want to make a casino game; I implore you to reconsider
  * `json`
    * if using this library, each `bodega` departmnet has a `data` folder with _tons_ of fun data
    * you _may_ choose to create your own data file; if choosing this option, place the file in the `bodega` folder in `data`
    * this will likely require at least a brief conversation with a TL or the instructor
  * `rich`
    * this was not covered by the video, but has documentation [found here](https://rich.readthedocs.io/en/latest/)
* use at least `2` additional `if` statements
* use either a `for` or `while` loop
* use at least `2` additional `function`s
* add a post (see `site/_posts`) to your `bodega` site which is dated correctly and ends in `game.md`
  * for example, if we made our post _today_: `2022-10-24-games.md`

The above outlines _minimum_ requirements. It's very likely that you'll need to go beyond that to create the game you've planned.

As with previous assignments, there are plenty of opportunities for improvements to items and the larger `bodega` structure. Some, however, will be more apt for future weeks. I'll let you know in our discussion if that's true, but you may feel free to improve the larger `bodega` as well.

The Mayor reserves the right to deem an improvement too small and to request changes.

### Supporting media

[![YouTube thumbnail](http://img.youtube.com/vi/X0zly7l_6Jo/hqdefault.jpg)](https://youtube.com/playlist?list=PLJvBsjwXNdlGnzDIdu8CCZhxl4vgsTdfa)

## Accessing bodega Content

In order to complete the workload for the `bodega` you'll first need to `clone` the `bodega` repository into your `workshop`.

When you `clone` a repository you're duplicating its contents and adding them to your local workspace. Since you'll be working collaboratively with your neighbors, you'll each need your own copy of the `bodega` to work with.

In order to keep some of the magic (read: somewhat convoluted code) that makes `term-world` work the way it does, **you are required to clone all additional repositories within the `workshop`, located within your `garage`.**

Head to GitHub and:
* click on the green `Code` button
* ensure that `SSH` is selected
* copy the link that appears in the window below

It might look something like `git@github.com:term-world/bodega-Ix`.

Once you've copied this link, navigate to your terminal window and ensure you're still in the appropriate place (in this case, the topmost level of your `workshop`). Then, enter the command:

```
git clone COPIED-LINK-HERE
```

Be sure to replace the fragment `COPIED-LINK-HERE` with the link you copied. In the example regarding `bodega-Ix`, the full command would look like:

```
git clone git@github.com:term-world/bodega-Ix
```

While `pull` is used to *update* the contents of a repository that already exists in your local workspace, `clone` is used to *replicate* the contents of a repository from GitHub and copy them to your local workspace.

## Completing `bodega` content

Summary here.

## Submitting `bodega` Content

Considering that the work you're doing for the `bodega` will be in a particular `branch` of the repository, there's a small adjustment that has to be made to our normal `add`, `commit`, `push` process.

When you're ready to push to GitHub, do the normal `add` and `commit` routines. Recall:

```
git add NAME_OF_FILE_OR_DIRECTORY_TO_ADD
```

You may need to do this for either:

* Individual files (i.e. `git add Thingamajig.py`)
* Directories (i.e. `git add Thingamajig`)

```
git commit -m "Descriptive commit message"
```

### Pushing to a branch

However, when it comes to push, run this slightly expanded command:

```
git push origin YOUR_BRANCH_NAME
```

We're still using `git push`, but this time we're adding an extra layer of information to the command; to be precise, we're specifically instructing `git` to push our changes to a particular branch of the repository (*your* branch). In the example regarding the `gadgets` department, the command to run would look like:

```
git push origin gadgets
```

### A "Pull Request"

Once you've completed this step, you'll now need to create a **pull request** on GitHub. This is a formal request to other collaborators on your project to review the code you've submitted--an important step when working together on the same project.

In a web browser, navigate to the repository page on GitHub (for the repository that you've just submitted new changes for). Towards the upper-left corner you'll see a dropdown that will have `main` selected as default (`main` being one of the branches for your repository, this is the "production-ready" branch). Select your branch from the dropdown, and you may see a yellow box prompting you to create a pull request; click that if you see it, or navigate to `Pull Requests` at the top and subsequently click the green `New pull request` button.

Now, in the top left corner select the branch you wish to add your updated changes to, or the "base" branch--generally speaking this will likely be `main`, the aforementioned "production-ready" branch. In the bar on the righthand side, add Reviewers to the pull request (this should be all of your neighborhood collaborators). Finally, click `Create pull request`.

You'll also be responsible for responding to and reviewing pull requests created by other collaborators on your team. Comment on each other's work about changes you'd like to see made to code submitted, and be sure to keep all communication both specific and professional.

## Merging `bodega` Content on GitHub

After all collaborators have had a chance to weigh in on a new pull request, if the work is up to snuff and ready to join the "production-ready" `main` branch, then your designated neighborhood team lead will have to merge that work into the `main` branch.

If you *are* said team lead, you'll need to navigate to the pull request on GitHub. If there are no "conflicts" (i.e., differences that can't be automatically handled by GitHub) between the pull request's branch and the `main` branch, simply click the `Commit merge` button and the merge is complete!

In some cases however, you'll have to specify what parts of a pull request make it into the `main` branch. If that's the case, you'll instead see a `Resolve conflicts` button. Click that and you'll be presented with a proposed merged copy of the code, with some extra lines added in. Something akin to:

```
<<<<<<
x = "this_is_a_line_of_code"
=======
x = "this_is_a_different_line_of_code"
>>>>>>
```

To resolve said conflicts, you'll need to delete the portion of code you don't want to appear in the final product, as well as any `<<<<<<`, `======`, or `>>>>>>` lines.

Once complete, click `Mark as resolved` followed by `Commit merge`, and the changes on the branch will be joined with the `main` branch!

## Updating `bodega` Content in Your Local Workspace

At some point you may wish to update the content in your local workspace with the changes being implemented by your teammates. 

To do so, `git checkout main` (or other collaborative branch) and run the command:

```
git pull
```

This will update your local workspace with the content stored in the `main` branch.

### `checkout` other folks' branches

It's _very_ likely that you'll run into the need to `checkout` a branch that GitHub has, but you don't. Here's a reminder of the steps to do that.

First, `fetch` all of the changes from the `remote` (GitHub):

```
git fetch --all
```

Once you've received this information, to `checkout` the `gadgets` branch (for example):

```
git checkout --track origin/gadgets
```

This will copy that branch from GitHub to your local workspace. You'll now also be able to `push` and `pull` to/from it.