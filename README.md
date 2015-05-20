# poirot

A simple repo to showcase private repository deployment.

To access the private module, set the contents of `deploy_key` to the environment variable `GIT_SSH_KEY`, and then run `npm install`.

```
export GIT_SSH_KEY=`cat deploy/deploy_key`
npm install
```

As featured here: http://fiznool.com/blog/2015/05/20/an-alternative-to-npm-private-modules/
