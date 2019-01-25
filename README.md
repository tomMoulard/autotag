# autotag

auto taging tool to generate and tag commits in git

## How To

```
$ git log
<hash> (HEAD -> master, origin/master, origin/HEAD) <commit message>
$ autotag base
$ git log
<hash> (HEAD -> master, tag: base-42, origin/master, origin/HEAD) <commit message>
```

## install

```
$ git clone https://github.com/tomMoulard/autotag.git
<git log>
$ ./autotag hello
```
