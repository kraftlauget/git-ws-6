# Present your work with Git and Rebase

## Exercise 6 - Rebase and edit a commit

Scenario:

- You're not too happy with the placeholder TODO for the menu.
- You want to make it look just a little bit more like an actual menu using `ul` and `li` elements

Instructions for exercise:

- Checkout branch `start`.
- Create a new branch `exercise`.
- Have a look at the commits in `solution` branch.
- Rebase the `exercise` branch and choose to edit the layout commit
- replace the TODO paragraph with:

```html
<ul>
  <li>TODO</li>
  <li>ADD</li>
  <li>MENU</li>
  <li>ITEMS</li>
  <li>HERE</li>
</ul>
```

- Add a line to #menu style to make the text a bit larger:

```cs
font-size: 1.5rem;
```

- Stage the changes (don't commit!)
- Continue rebase.
- Notice how there was no merge conflicts this time. With the squash approach from previous exercise there would have been.

Tips:

- [Rebase](https://git-scm.com/docs/rebase) the `exercise` branch and choose edit option.
- Use a GUI client such as [GitExtensions](http://gitextensions.github.io/) (Win), [Fork](https://git-fork.com/) (Mac + Win) or [GitKraken](https://www.gitkraken.com/) (Linux, Mac, Win) so that you don't have to figure out the git cli commands for doing the above.
- I've written a bit about editing commits using GitExtensions on [my blog](https://blomholm.no/posts/how-i-git-it-more-rebase/#pause-the-replay-and-make-changes-to-a-commit)

[Click here for next exercise](https://github.com/kraftlauget/git-ws-7)
