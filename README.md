AngularJS Tablesortesize
===================

It is a fork of [angular-tablesort](http://mattiash.github.io/angular-tablesort) package that is able to work with [angular-table-resize](https://www.npmjs.com/package/angular-table-resize).

The original library defines the `scope: true` directive's option so there's a conflict between two libraries resulting in the following error:

> Error: [$compile:multidir] Multiple directives [resizeable, tsWrapper] asking for new/isolated scope on: ...

I've just deleted this option from the corresponding directive and that's it.
