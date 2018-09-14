## 3.0.0
* Ember runloop snippets
* Add snippets for most of ember-test-helpers #50
* More ember computed snippets
* Remove logger snippets. Closes #40
* Update service snippet. Closes #43 and #48
* Bump atom-package-deps
* Ember data import snippets #47 from @jrock2004
* Handlebars #let #49 from @jrock2004

## 2.1.6
* Update route skeleton #37 @samselikoff
* Update helper skeleton
* Add beforeModel route hook

## 2.1.4
* Fixes imports for controller/service injection #34 @caseywatts

## 2.1.3
* Removes third-party snippets (Mirage)
* Ember skeleton snippets are now RFC176 compliant

## 2.1.2
* Support for typescript files #28 @bartocc

## 2.1.0
* Ember rfc176 compliant import snippets. #26 @jbailey4
* More component lifecycle hooks #25 @jakenewby

## 2.0.4
* Respect configured indent rule when inserting #23

## 2.0.3
* Fix typos in some skeletons #21

## 2.0.2
* Consistently use spaces after parens. Closes #20

## 2.0.0
* Deprecate coffee script snippets
* Introduce mirage snippets
* Introduce ember specific handlebars snippets
* Reorganize snippet files
* Introduce lots of new ember snippets

## 1.4.0
* Add Ember Data v1.13 snippets @locks

## 1.3.0
* Rename Ember Computed prefix from `property` to `computed` @locks
* Add Ember.Service snippet @jasonmit
* Add Ember.Helper snippet as `helper`, while keeping deprecated helper as `bound-helper` @jasonmit

## 1.2.1
* Add keywords to improve package discovery

## 1.2.0
* Add Ember Enumerable functions. @taylon
* Add Test helpers. @blimmer

## 1.1.3
* Fix property

## 1.1.2
* Add event as `.on` to properties
* Rename observes to observer for consistency
* Fix properties and observer syntax
* Make `.coffee` syntax for properties more consistent

## 1.1.1
* Use new computed property and observer syntax
* Replace Ember.ObjectController with Ember.Controller

## 1.1.0
* Add support for CoffeeScript. @jgarth

## 1.0.0
* Add `Ember.computed.alias` snippet
* Split snippets into different files
* Fix package version number

## 0.3.1
* Fix ember-data snippets importing `DS` instead `ember-data`

## 0.3.0
* Add `Ember.Object` snippet
* Fix view snippet

## 0.2.0
* Use shorter names. e.x.`route` instead of `ember-route`
* Add snippet keyword triggers
* Add more module snippets (Components, Views, Mixins, Adapters, Serializers, Transforms)
* Add `Ember.Logger` in functions
* Remove doc-comments from generated snippets

## 0.1.0 - First Release
* Add modules (Route, ArrayController, ObjectController, Model,
Helper, Initializer, Utility)
* Add properties (ComputedProperty, Observer, Actions)
* Add functions (Find model, find by id)
