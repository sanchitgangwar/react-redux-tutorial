# React Redux Tutorial

The code present in this repo is entirely derived from Dan Abramov's tutorial
on [egghead](http://egghead.io/lessons/javascript-redux-the-single-immutable-state-tree).

## Principle 1

All the state of an application - simple or complex - is going to be stored in 
a single object.

## Principle 2

The state tree read-only. One can not write or modify it. To change it, one 
needs to dispatch an action.

An action is a minimal representation of the change to your data. An user can 
freely define the structure of the action object, the only requirement being
that there be a field called `type` which is not `undefined`.
