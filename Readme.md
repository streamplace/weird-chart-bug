
# weird-chart

Making this for a weird helm bug.

Repro:

```
npm install
helm install --name test .
```

This should give:

```
NAME:   test
Error: getting deployed release "test": release: not found
```
