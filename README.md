# oksoftware-interview

What is the difference between AOT and JIT? What is the advantage of AOT.

https://stackoverflow.com/questions/41450226/angular-2-just-in-time-jit-vs-ahead-of-time-aot-compilation
https://levelup.gitconnected.com/just-in-time-jit-and-ahead-of-time-aot-compilation-in-angular-8529f1d6fa9d

What is the difference between AOT and JIT? What is the advantage of AOT.
https://stackoverflow.com/questions/41450226/angular-2-just-in-time-jit-vs-ahead-of-time-aot-compilation
Data sharing among non-related components. If RxJS getter setter then what will happen if refresh the apps.
https://stackoverflow.com/questions/44414226/angular-4-pass-data-between-2-not-related-components
How to bootstrap angular application
https://medium.com/learnwithrahul/ways-of-bootstrapping-angular-applications-d379f594f604
What are angular different versions and features
https://medium.com/@lifenshades/difference-among-angular-8-7-6-5-4-3-2-breakdown-new-features-and-changes-811fb5f8e6f0
How to set ngfor and ngif in the same div or tag?
By using ng-container or ng-template
https://stackoverflow.com/questions/34657821/ngif-and-ngfor-on-same-element-causing-error
Difference between structural Directive, Attribute directive and components.
https://stackoverflow.com/questions/34613065/what-is-the-difference-between-component-and-directive
Difference between the template and reactive forms
https://stackoverflow.com/questions/45277137/what-are-the-differences-between-template-driven-forms-and-reactive-forms-in-ang
How you write unit test cases?
Mocking stubbing and importing
What are all life cycle hook in Angular => Total 18 life cycle hooks
https://stackoverflow.com/questions/44648066/angular-life-cycle-hooks
Authentication guards, based on token expiration and role-based
https://medium.com/@ryanchenkie_40935/angular-authentication-using-route-guards-bf7a4ca13ae3
https://ryanchenkie.com/angular-authentication-using-route-guards
Angular pipes
https://angular.io/guide/pipes
Lazy loading vs eager loading in Angular
By default angular modules loads eager loading whether they need it or not.
https://stackoverflow.com/questions/53332996/angular-6-7-by-default-uses-eager-lazy-loading
https://angular.io/guide/lazy-loading-ngmodules
What are the common modules and ngmodules automatically added in angular apps? What error it will give if we do not add it.
https://medium.com/@cyrilletuzi/understanding-angular-modules-ngmodule-and-their-scopes-81e4ed6f7407
General questions for Angular
https://github.com/Yonet/Angular-Interview-Questions/blob/master/README.md
How to minify Angular applications
Putting this keyword in npm build — — env=prod
“build_prod”: “npm run build && browserify -s main dist/main.js > dist/bundle.js && npm run minify”
How to register reusable angular component to npm
https://angular.io/guide/creating-libraries
How to implement session idle and session timeout in angular application
https://stackoverflow.com/questions/53988543/angular-6-ng-idle
What is a static class and what are the benefits of it.
Static class only creates one instance when module is initialized. Data sharing is very easy along with instances.
what is :host property in css in Angular application
if overriding any root component styling then use it. Also, you can use it when using any third party design i.e. Angular Material
https://blog.angular-university.io/angular-host-context/
what are media queries and how to use proper media queries in Angular
https://stackoverflow.com/questions/48628220/using-proper-css-media-queries-in-angular
Globalization in Angular and how you handle it.
https://medium.com/frontend-fun/angular-introduction-to-internationalization-i18n-28226a85e04e
View encapsulation in Angular
https://blog.thoughtram.io/angular/2015/06/29/shadow-dom-strategies-in-angular2.html
How server-side rendering works in Angular
https://angular.io/guide/universal
- Facilitate web crawlers through search engine optimization (SEO)
- Improve performance on mobile and low-powered devices
- Show the first page quickly with a first-contentful paint (FCP)
How webpack loader works, What is the difference between Webpack and Grunt
https://webpack.js.org/concepts/loaders/
RXJS and NGRX interview questions
What is the difference between Subject, BehaviourSubject, and ReplaySubject

https://medium.com/@codingindepth/rxjs-a-deep-dive-with-angular-8-7fe9fd675aaa
What will happen if error happens in forkJoin

https://stackoverflow.com/questions/51103799/how-to-catch-error-in-observable-forkjoin
https://stackoverflow.com/questions/49789844/error-handling-observable-forkjoin-with-couple-of-observable-objects-in-angula
Difference between mergemap and concatmap vs flatmap
https://medium.com/@codingindepth/rxjs-a-deep-dive-with-angular-8-7fe9fd675aaa
flatMap, mergeMap, switchMap and concatMap in rxjs?
https://medium.com/@codingindepth/rxjs-a-deep-dive-with-angular-8-7fe9fd675aaa
Promise vs Observables

https://medium.com/@codingindepth/rxjs-a-deep-dive-with-angular-8-7fe9fd675aaa
What is Promise.all()
https://stackoverflow.com/questions/33073509/promise-all-then-resolve
Difference between Observable and Subjects
https://medium.com/@codingindepth/rxjs-a-deep-dive-with-angular-8-7fe9fd675aaa
Difference between scan and reduce
Scan run sequentially and emits value at each stage, reduce run seq but emit the final value
https://stackoverflow.com/questions/45350806/whats-difference-between-reduce-and-scan
How to cache data on the client-side
example time based —
https://stackoverflow.com/questions/39490545/time-based-cache-for-rest-client-using-rxjs-5-in-angular2
Key based caching
callback based caching
In which scenario use combineLatest and when to use forkJoin
https://medium.com/@codingindepth/rxjs-a-deep-dive-with-angular-8-7fe9fd675aaa
JavaScript Interview Questions
Scope in javascript
https://medium.com/backticks-tildes/understanding-hoisting-and-scoping-in-javascript-39ea7b41e31
Prototype in javascript
https://medium.com/better-programming/prototypes-in-javascript-5bba2990e04b
Closures in Javascript
https://stackoverflow.com/questions/111102/how-do-javascript-closures-work
Difference between const and let and diff between var vs let
Const value will not change in the scope provided. But array or object property can be added later also.
Let value depends on the scope.
Var value will be same in function
Example:
let name2 =”Muffin”
function NameChange(){
let name2 =”Muffin2”;
console.log(“Name is %s”, name2);
}
NameChange();
console.log(“Name outside here %s”,name2);
https://medium.com/@gianpaul.r/whats-the-difference-between-let-const-and-var-in-javascript-1535e0ffcdc
https://stackoverflow.com/questions/762011/whats-the-difference-between-using-let-and-var
Create modularization in vanilla Javascript
https://medium.com/@crohacz_86666/basics-of-modular-javascript-2395c82dd93a
what is curry in javascript? How you will pass multiple arguments to the function
https://stackoverflow.com/questions/36314/what-is-currying
sum(2)(3) and sum(2,3)
https://stackoverflow.com/questions/35320448/javascriptwhat-is-meaning-of-sum23-returns-5
What is the use of strict in javascript, Why it is used and what is the benefits of using strict give one example
https://www.geeksforgeeks.org/strict-mode-javascript/
How to create prototype property for array in javascript
https://stackoverflow.com/questions/948358/adding-custom-functions-into-array-prototype
https://www.geeksforgeeks.org/javascript-array-prototype-constructor/
Difference between ES5 and ES6
https://medium.com/recraftrelic/es5-vs-es6-with-example-code-9901fa0136fc
Callback vs Promise
Arrow functions
Exporting and importing modules
Type in which we assign objects
What will be the output of the following questions?
https://stackblitz.com/edit/fun-question-javascript-3
How many ways you can create objects in javascript?
https://medium.com/@codingindepth/5-ways-to-create-objects-in-javascript-2ecd8a8af647

source: https://medium.com/coding-in-depth/advanced-angular-interview-questions-with-answers-in-2020-5d49d01cdd01
