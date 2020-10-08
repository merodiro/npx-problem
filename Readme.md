# npx problem in windows

running `npx https://gist.github.com/merodiro/a20a979f1a76dcc7aafd8b6e8cb127ae` directly works as expected

but running `npm run setup` outputs this error

```log
$ npm run setup

> npx-problem@1.0.0 setup C:\Users\Amr\Desktop\Projects\npx-problem
> npx https://gist.github.com/merodiro/a20a979f1a76dcc7aafd8b6e8cb127ae

npm ERR! code 1
npm ERR! Command failed: git submodule update -q --init --recursive
npm ERR! C:/Program Files/Git/mingw64/libexec/git-core\git-submodule: line 22: .: git-sh-setup: file not found
npm ERR!
```
