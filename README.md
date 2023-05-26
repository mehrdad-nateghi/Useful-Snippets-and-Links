# Useful-Snippets-and-Links

1. [How to make Powershell remember the SSH key passphrase.](https://gist.github.com/danieldogeanu/16c61e9b80345c5837b9e5045a701c99)

2. Ignore files that have already been committed to a Git repository
`git rm -r --cached .`

3. [Configure Xdebug in Phpstorm](https://www.jetbrains.com/help/phpstorm/configuring-xdebug.html)
4. To refresh the `.gitignore` file with cache in Git, you can use the following command:

```
git rm -r --cached .
git add .
git commit -m "Refreshed .gitignore cache"
```

This will remove all the cached files from the Git index and then add them back again with the updated `.gitignore` rules. The `-r` flag is used to remove directories recursively, so that all the files that were previously ignored by Git would be removed from the index.

After running these commands, your `.gitignore` file will be refreshed with the latest cache.

5.
