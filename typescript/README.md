typescript debug setting.

https://github.com/TypeStrong/ts-node/issues/46#issuecomment-296895962

install typescript and ts-node locally.

without -g.

```
npm install typescript ts-node
```

```
{
      "type": "node",
      "request": "launch",
      "name": "Launch Program",
      "runtimeArgs": ["-r", "ts-node/register"],
      "args": ["${workspaceFolder}/index.ts"]
    }
```
