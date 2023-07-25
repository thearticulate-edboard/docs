# Development setup

You should have installed the following in your system.
  - hugo
  - nodejs
  - npm
  - git


Clone the repo.

```bash
git clone https://github.com/thearticulatemagazine/vol1.git thearticulatemagazine
```

Install the npm dependencies and run hugo and tailwind servers with `watch` flag set. (Fair warning: Might be taxing on the system if you run couple of more electron apps.)
Read `package.json` for other scripts.

Husky is in place for pre-commit hook of prettier. So you do not have to set `format on save`. 