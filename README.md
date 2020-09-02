# oksoftware-interview

https://github.com/Yonet/Angular-Interview-Questions/blob/main/README.md#animations-questions
https://medium.com/coding-in-depth/advanced-angular-interview-questions-with-answers-in-2020-5d49d01cdd01
https://www.fullstack.cafe/angular

**What are some of the reasons you would choose to use Angular in your project?**
-Detailed documentation.
-Support by Google.
-Great ecosystem of third-party components.
-Component-based architecture.

**How do you keep your Angular code more readable and maintainable?**

-It is very important not to create more than one component, service, directive… inside a single file. Every file should be responsible for a single functionality. By doing this, we are keeping our files clean, readable and maintainable.

-Using Interfaces and types and tslint

-a lot of modules core fodler and shared

-added prettier autoformater 


**How do you define transition between two states in Angular?
How do you define a wildcard state?**

animations: [
  trigger('openClose', [
    // ...
    state('open', style({
      height: '200px',
      opacity: 1,
      backgroundColor: 'yellow'
    })),
    state('closed', style({
      height: '100px',
      opacity: 0.5,
      backgroundColor: 'green'
    })),
    transition('open => closed', [
      animate('1s')
    ]),
    transition('closed => open', [
      animate('0.5s')
    ]),
    transition('* => closed', [
      animate('1s')
    ]),
    transition('* => open', [
      animate('0.5s')
    ]),
    transition('open <=> closed', [
      animate('0.5s')
    ]),
    transition ('* => open', [
      animate ('1s',
        style ({ opacity: '*' }),
      ),
    ]),
    transition('* => *', [
      animate('1s')
    ]),

**Why would you use renderer methods instead of using native element methods?**

The Renderer is a class that is a partial abstraction over the DOM. Using the Renderer for manipulating the DOM doesn't break server-side rendering or Web Workers (where direct access to the DOM would break).

ElementRef is a class that can hold a reference to a DOM element. This is again an abstraction to not break in environments where the browsers DOM isn't actually available.

**How would you control size of an element on resize of the window in a component?**
<div (window:resize)="onResize($event)"
onResize(event) {
  event.target.innerWidth;
}

@HostListener('window:resize', ['$event'])
onResize(event) {
  event.target.innerWidth;
}
this.resizeObservable$ = fromEvent(window, 'resize')
this.resizeSubscription$ = this.resizeObservable$.subscribe( evt => {
  console.log('event: ', evt)
})
