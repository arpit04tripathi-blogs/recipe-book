# recipe-book

# Running on local
1. start server - `sh scripts/localhost.sh`
   1. This will open chrome browser or you can visit [localhost:9999/my-repo](http://localhost:9999/my-repo)
   2. Initially, you will see error page `This site can’t be reached`
   3. after some time when container has started, you will see the site running
2. stop server - `sh scripts/localhost.sh --stop`

# Troubleshooting

Official documentation for jekyll is [here](https://jekyllrb.com/)

## Port already used
```bash
# find process_id using the port
netstat -vanp tcp | grep 9999
# kill the process based on process_id
kill -9 <PROCESS_ID>
```

# Useful git commands

```
git fetch --all -p; git pull; git status;
git merge origin/main;
git push;
```

This is based on jekyll-theme [bulma](https://jekyllthemes.io/theme/bulma)
