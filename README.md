To track installed packages as well, you will need to run:
```
apm list --installed --bare > package.list
```
And add that file to Git also. To restore, use:

```
apm install --packages-file package.list
``

You can do the same with config and either append or overwrite the `~/.atom/config.cson` file with your version controlled configurations.
