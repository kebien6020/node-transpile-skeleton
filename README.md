# Node transpile skeleton

Skeleton to bootstrap node projects with transpiling (using babel) and some polyfills (babel-polyfill and util.promisify).

## Usage

Clone this repo. Install dependencies. Use dev script to start transpiling and running simultaneously.

```sh
git clone https://github.com/kebien6020/node-transpile-skeleton <projectName>
cd <projectName>
yarn
yarn dev
```

When some file inside `/src` changes the program will recompile and run again.
