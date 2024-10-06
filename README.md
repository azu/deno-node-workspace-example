## Deno + npm workspaces

https://docs.deno.com/runtime/fundamentals/workspaces/#migrating-from-npm-workspaces

### Run

Run code with Deno

```bash 
$ deno task dev
Task dev deno run main.ts
Hi, friend!
```

### Compile

Compile code to single executable file

```
$ deno task compile
./deno-node-workspace-example # not work
error: Could not find constraint '@deno/log' in the list of packages.
```
