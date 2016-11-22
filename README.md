# angular-spa

[![Build Status][bimage]][bstatus]

Utilities, classes and components for projects generated by yoman generator 
[spring-spa](https://github.com/giovannicandido/generator-spring-spa) in Angular 2.

You can probally use a lot of this on your projects, even if you don't use the generator 
I created.

What you get?

* User account service. This user service loads information about the current login in user. Intentionally
you don't have things for user management like: create, update, password reset, because my projects use
a separate Single Sign On server [Keycloak](https://keycloak.org) that ships with all and way more.
* Directives for security template display. This let you conditionally display user UI elements
based on user roles and authorities.
* UI elements - LoadingBar, Menus, and other little things. This are more specific for the
projects I create. Do not interpret me wrong here, I'm not trying to compete with huge UI frameworks,
but somethings are just too repetitive. We will not put unnecessary dependencies 
to make this project very slim for everyone.

You probally want check [angular-http-interceptor](https://github.com/atende/angular-http-interceptor)
for other usefull project.

# Motivation

I think motivation is important, and in the past few month's I'm pursue a big picture.

The big picture is to standardise a architeture for Web Apps that are related, 
or a family of web apps.

You can find clues about it in this projects:

* [Audit]
* [Spring SPA]
* [Notification Server]

Have fun ;-)

[Audit]: https://github.com/atende/audit-docs
[Spring SPA]: https://github.com/giovannicandido/generator-spring-spa
[Notification Server]: https://github.com/atende/notification-server
[bimage]: https://travis-ci.org/atende/angular-spa.svg?branch=master
[bstatus]: https://travis-ci.org/atende/angular-spa