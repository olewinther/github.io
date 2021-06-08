# github_winther


### Change
When you want to change something or update the website:

* First time: clone the repo on your laptop

```bash
git clone https://github.com/georgosgeorgos/update_winther
```

* If you already have the repo on your laptop

```bash
cd update_winther
git pull
````

* change something

```bash
git add .
git commit -m "Change something"
git push origin main
```

now your changes are online. If you host your website with `github.io`, stop here.

### Server

If your website is on another server, `ssh` in the server

* First time you copy the content on the server:

```bash
git clone https://github.com/georgosgeorgos/update_winther
```

The `index.html` should be recognited automatically.


If the repo is already on the server
* `cd` in the folder and `pull`

```bash
cd update_winther
git pull
```

then follow the same procedure for updating.