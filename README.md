# SWAPSTER dev-conventions


-----------------------

## Coding conventions:

Use eslint to check your code. Extract of .eslintrc (more about the rules on http://eslint.org/docs/rules):

- capitalize-modules: Enforce capitalization of imported module variables.
- scope-start: Enforce a new line at the beginning of function scope.
- no-arrowception: Prevent arrow functions that implicitly create additional arrow functions.
- [no-underscore-dangle](http://eslint.org/docs/rules/no-underscore-dangle): Disallow Dangling Underscores in Identifiers.
- [no-undef](http://eslint.org/docs/rules/no-undef): Disallow Undeclared Variables.
- [no-unused-vars](http://eslint.org/docs/rules/no-unused-vars): Disallow Unused Variables.
- [no-lonely-if](http://eslint.org/docs/rules/no-lonely-if): Disallow if as the Only Statement in an else Block.
- [consistent-return](http://eslint.org/docs/rules/consistent-return): Require Consistent Returns.
- [vars-on-top](http://eslint.org/docs/rules/vars-on-top): Require Variable Declarations to be at the top of their scope.
- [one-var](http://eslint.org/docs/rules/one-var): Disallow One Variable Declaration per Scope.
- [no-constant-condition](http://eslint.org/docs/rules/no-constant-condition): Disallow use of constant expressions in conditions.
- [no-empty](http://eslint.org/docs/rules/no-empty): Disallow Empty Block Statements.
- [no-native-reassign](http://eslint.org/docs/rules/no-native-reassign): Disallow Reassignment of Native Objects.
- [no-process-exit](http://eslint.org/docs/rules/no-process-exit): Disallow process.exit().
- [no-use-before-define](http://eslint.org/docs/rules/no-use-before-define): Disallow Early Use.
- [no-unused-expressions](http://eslint.org/docs/rules/no-unused-expressions): Disallow Unused Expressions.
- [no-regex-spaces](http://eslint.org/docs/rules/no-regex-spaces): Disallow Spaces in Regular Expressions.
- [no-catch-shadow](http://eslint.org/docs/rules/no-catch-shadow): Disallow Shadowing of Variables Inside of catch.
- [strict](http://eslint.org/docs/rules/strict): no strict mode (node env, not necessary).
- [handle-callback-err](http://eslint.org/docs/rules/handle-callback-err): Enforce Callback Error Handling.
- [brace-style](http://eslint.org/docs/rules/brace-style): Use one true brace style.
- [no-shadow](http://eslint.org/docs/rules/no-shadow): Disallow Shadowing.
- [array-bracket-spacing](http://eslint.org/docs/rules/array-bracket-spacing): Disallow spaces inside of brackets.
- [dot-notation](http://eslint.org/docs/rules/dot-notation): Require Dot Notation.
- [eol-last](http://eslint.org/docs/rules/eol-last): Require file to end with single newline.
- [camelcase](http://eslint.org/docs/rules/camelcase): Require Camelcase.
- [no-trailing-spaces](http://eslint.org/docs/rules/no-trailing-spaces): Disallow trailing spaces at the end of lines.
- [no-eq-null](http://eslint.org/docs/rules/no-eq-null): Disallow Null Comparisons (rare exception if you want to check if variable is null and undefined).
- [no-extend-native](http://eslint.org/docs/rules/no-extend-native): Disallow Extending of Native Objects.
- [no-redeclare](http://eslint.org/docs/rules/no-redeclare): Disallow Redeclaring Variables.
- [no-loop-func](http://eslint.org/docs/rules/no-loop-func): Disallow Functions in Loops.
- [yoda](http://eslint.org/docs/rules/yoda): Disallow Yoda Conditions.
- [sort-vars](http://eslint.org/docs/rules/sort-vars): Variable Sorting.
- [quotes](http://eslint.org/docs/rules/quotes): Enforce single quote style.
- [consistent-this](http://eslint.org/docs/rules/consistent-this): Require Consistent This = self.
- [func-style](http://eslint.org/docs/rules/func-style): Enforce function expressions.
- [new-parens](http://eslint.org/docs/rules/new-parens): Require Parens for Constructors.
- [o-array-constructor](http://eslint.org/docs/rules/o-array-constructor): Disallow creation of dense arrays using the Array constructor.
- [no-new-object](http://eslint.org/docs/rules/no-new-object): Disallow the use of the Object constructor.
- [no-spaced-func](http://eslint.org/docs/rules/no-spaced-func): Disallow Spaces in Function Calls.
- [no-mixed-spaces-and-tabs](http://eslint.org/docs/rules/no-mixed-spaces-and-tabs): Disallow mixed spaces and tabs for indentation.
- [space-after-keywords](http://eslint.org/docs/rules/space-after-keywords): Require spaces following keywords.
- [semi](http://eslint.org/docs/rules/semi): Enforce Semicolons.
- [semi-spacing](http://eslint.org/docs/rules/semi-spacing): Disallow spacing before and enforce after semicolons.
- [space-infix-ops](http://eslint.org/docs/rules/space-infix-ops): Require Spaces Around Infix Operators.
- [space-return-throw-case](http://eslint.org/docs/rules/space-return-throw-case): Require spaces following return, throw, and case.
- [space-unary-ops](http://eslint.org/docs/rules/space-unary-ops): Require or disallow spaces before/after unary operators ("words": true, "nonwords": false).
- [eqeqeq](http://eslint.org/docs/rules/eqeqeq): Require === and !==
- [curly](http://eslint.org/docs/rules/curly): Require Following Curly Brace Conventions.
- [no-eval](http://eslint.org/docs/rules/no-eval): Disallow eval().
- [no-else-return](http://eslint.org/docs/rules/no-else-return): Disallow return in else.
- [no-return-assign](http://eslint.org/docs/rules/no-return-assign): Disallow Assignment in return Statement.
- [no-new-wrappers](http://eslint.org/docs/rules/no-new-wrappers): Disallow Primitive Wrapper Instances.
- [comma-dangle](http://eslint.org/docs/rules/comma-dangle): Disallow Dangling Commas.
- [no-sparse-arrays](http://eslint.org/docs/rules/no-sparse-arrays): Disallow Sparse Arrays.
- [no-ex-assign](http://eslint.org/docs/rules/no-ex-assign): Disallow Assignment of the Exception Parameter.
- [indent](http://eslint.org/docs/rules/indent): [2, 4, {"SwitchCase": 1}]
- [space-before-function-paren](http://eslint.org/docs/rules/space-before-function-paren): Require spaces before function parentheses.
- [object-curly-spacing](http://eslint.org/docs/rules/object-curly-spacing): Enforce spaces inside of curly braces in objects.
