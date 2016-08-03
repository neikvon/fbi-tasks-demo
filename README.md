# fbi-tasks-demo
Tasks demo for fbi

### Clone
```bash
$ git clone git@github.com:neikvon/fbi-tasks-demo.git
```

### Install dependencies locally
```bash
$ npm install
```

### Add
```bash
$ fbi ata *

# output:
# FBI => task 'run' added
# FBI => task 'serve' added
```

### Check
```bash
$ fbi ls

# output:
# Tasks:

#   run             <global>
#   serve           <global>
```

### Test
```bash
$ fbi serve

# output:
# FBI => Running global task "serve"...
# FBI => Server runing at http://localhost:8888
# FBI => Server root: ./
```

### Update
```bash
$ fbi ata serve.js

# output:
# FBI => task 'serve' updated
```

### Install dependencies globally
```bash
$ fbi i

# ouput:
# FBI => npm install
#       global-npm@^0.3.0
#       koa@^2.0.0
#       koa-static@^3.0.0
#       --save-dev
#    to:/Users/.../fbi/data/tasks
# ...
# FBI => All Dependencies Installed
```

now you can use tasks you just added everywhere.