#WebStorm EcmaScript6 Live Template

## install

`ln` or `cp` all the xml files to `\config\templates`(Windows/Linux) or `/templates`(Mac) 

for WebStorm11 on Macos

`ln -s ~/codes/webstorm-es6-livetpls/EcmaScript6.xml \
 ~/Library/Preferences/WebStorm11/templates/EcmaScript6.xml`

----------

## templates
+ `cls` - A new ES6 class with constructor.
```javascript
class $CLASS_NAME$$EXTENDS$ {
    constructor($CLASS_PARAM$) {
        $END$
    }
}
```

+ `af` - A new arrow function.
```javascript
($PARAM$) => {
  $END$
}
```

+ `gf` - A new generator function.
```javascript
function* $FUNCTION_NAME$() {
  $END$
}
```

+ `imp` - A new module import statement.
```javascript
import $MODULE_VAR$ from '$MODULE_NAME$'$END$
```

+ `itor` - Loop 'for...of'.
```javascript
for (let $VAR$ of $ARRAY$) {
  $END$
}
```

+ `pr` - A new ES6 native promise.
```javascript
new Promise((resolve$REJECT$) => {
    $END$
})
```

+ `ts` - A new template string.
```javascript
`$STRING$${$PARAM$}$END$`
```

