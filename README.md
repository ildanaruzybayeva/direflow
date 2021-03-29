# Direflow - creating web components from react.js

# How to use:

1. Use a ready made react app boilerplate to build whatever you want as one component (Sample-component):

Once done, build it by running - npm run build. This generates a direflowBundle.js file which can be used in another project as a web component

2. Applying that component to another project (Testing):

index.html file which consumes sample component. Simply copy direflowBundle.js to the same dir and consume it

```javascript
<script src="./direflowBundle.js"></script>
<sample-component></sample-component>
```

