# 300 - Make Your Changes

Edit the files and make your changes. Once done, add the changes to staging and commit them.

- Replace COMMIT_MESSAGE by the message you want the commit to contain for documentation purposes. Make sure to surround the message by quotes ("").

```
$ git add .
$ git commit -m "COMMIT_MESSAGE"
```

For example, add the following line to README.md:

```
cat <<EOF >> ./README.md
Hello, world!
EOF
```

TIP: Use [cat](https://phoenixnap.com/kb/linux-cat-command) command.
