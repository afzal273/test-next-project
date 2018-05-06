# test-next-project

This is the error I'm seeing

```
 ERROR  Failed to compile with 1 errors                                                                                              23:43:26

 error  in ./node_modules/test-styled-jsx-comps-library/styles/buttons-working.js

Module build failed: Error: //testing/test-next-project/node_modules/test-styled-jsx-comps-library/styles/buttons-working.js: File to import not found or unreadable: variables.
    at Object.module.exports.renderSync (//testing/test-next-project/node_modules/node-sass/lib/index.js:439:16)
    at module.exports (//testing/test-next-project/node_modules/styled-jsx-plugin-sass/index.js:20:29)
    at //testing/test-next-project/node_modules/styled-jsx/dist/_utils.js:438:14
    at processCss (//testing/test-next-project/node_modules/styled-jsx/dist/_utils.js:484:119)
    at processTaggedTemplateExpression (//testing/test-next-project/node_modules/styled-jsx/dist/babel-external.js:64:44)
    at //testing/test-next-project/node_modules/styled-jsx/dist/babel-external.js:151:7
    at Array.forEach (<anonymous>)
    at PluginPass.ImportDeclaration (//testing/test-next-project/node_modules/styled-jsx/dist/babel-external.js:150:31)
    at newFn (//testing/test-next-project/node_modules/babel-traverse/lib/visitors.js:276:21)
    at NodePath._call (//testing/test-next-project/node_modules/babel-traverse/lib/path/context.js:76:18)
    at NodePath.call (//testing/test-next-project/node_modules/babel-traverse/lib/path/context.js:48:17)
    at NodePath.visit (//testing/test-next-project/node_modules/babel-traverse/lib/path/context.js:105:12)
    at TraversalContext.visitQueue (//testing/test-next-project/node_modules/babel-traverse/lib/context.js:150:16)
    at TraversalContext.visitMultiple (//testing/test-next-project/node_modules/babel-traverse/lib/context.js:103:17)
    at TraversalContext.visit (//testing/test-next-project/node_modules/babel-traverse/lib/context.js:190:19)
    at Function.traverse.node (//testing/test-next-project/node_modules/babel-traverse/lib/index.js:114:17)

 @ ./node_modules/test-styled-jsx-comps-library/dist/RdcButton.js 27:0-47
 @ ./node_modules/test-styled-jsx-comps-library/dist/index.js
 @ ./pages/index.js
 @ multi ./pages/index.js
```
