# PackageBased

This is a repo was created to demonstrate an issue with lerna link on nx during builds.

## Steps to reproduce

```bash
npm install
npm run build
```

Then you can run lerna link and see that the package is linked.

```bash
npx lerna link --force-local
```

If you run the build again, you will see that the package is no longer linked.
