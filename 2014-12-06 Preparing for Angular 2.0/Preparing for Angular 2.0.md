---

title: Ease the Transition to Angular 2.0
tags:
- Angular
- Angular 2.0
- Migration
- ES6
- Controller As
- Lazy Loading
- SoC
- Separation of Concerns
- ng-router
- Rob Eisenberg
- Durandal
- Adventures in Angular
- ocLazyLoad
- ng-europe
- ngeurope

---

###http://robertdunaway.github.io

#Ease the Transition to Angular 2.0
Significant changes are coming to Angular 2.0. Since the http://ngeurope.org/, I’ve considered how to position my angular applications for Angular 2.0.

The changes coming are being driven in large part by ES6. Eventually, all frameworks will need to make this transition. Angular is stepping up and getting it done now. So let’s just suck it up and get-er-done.

Go ahead and bookmark this blog post. Whenever I learn of a change that positions our applications for Angular 2.0, I’ll update this post. This will be a single go-to place for all changes, making the transition as easy as possible.

Let’s jump right in…


##Learn ES6

I’ll soon post links here to many tutorials, utilities, and advice on making this transition.

##Use the “controller as” syntax

With the release of Angular 1.3 the “controller as” syntax was introduced.

This helps reduce dependence on $scope and positions our controllers to more easily become ES6 classes when we transition to Angular 2.0.


##Use the new ng-router

>Update: Rob Eisenberg left the AngularJS team and is back to working on Durandal.

Rob Eisenberg, the author of Durandal, is championing a new more advanced router for Angular. His experience with Durandal, and a general survey of the features available in all of today’s popular routers, has driven the requirements for the new router.

The ng-router is an Angular 2.0 feature but is being back ported to 1.3. Early adoption of this new router means you’ll have one less thing to deal with when Angular 2.0 comes out.

Besides, it’s got a few freaking cool features in it. Check out the video below. It’s two months old which, in our new world, means it’s ancient and outdated but still a great starting point. I’ll post more tutorials as I learn how to use it.

https://www.youtube.com/watch?v=h1P_Vh4gSQY

https://www.npmjs.org/package/angular-new-router


##Use services wherever possible

The more code we can move out of controllers and into services, the easier the transition to Angular 2.0 will be.

Full disclosure – I came across this advice on “Adventures in Angular” podcast and while I get “separation of concerns,” I don’t know how it helps with Angular 2.0. I’ll figure this out and update my notes here.


##Lazy loading
Lazy (eager) loading of modules is planned for Angular 2.0.

For now, I’ve prepared for this by implementing lazy loading with ocLazyLoad.

I mention it in this router post but I’ll provide a specific post about lazy loading later.

http://robertdunawaypro.blogspot.com/2014/10/routeconfig.html


##Drop-in application design

I have no idea what to call this, so I completely made up that name. The idea is this. With the new angular router you’ll have the ability to modularize your application such that you can drop modules into an application from another application and this is supposed to work.

http://Mashupjs.githut.io has an implementation like this. I’ll upgrade it to use the features of the new Angular router as soon as I can.


##In closing

I’m just like everyone else.  I’m figuring this stuff out as I go.  If you come across something you think might be helpful then post a comment and I’ll add it to this list.

Thanks…
























