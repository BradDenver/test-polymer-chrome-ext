# Polymer Chrome Extension Test

This is a test case for using https://github.com/Polymer/polymer-chrome-app inside a Chrome Extension.

As shown in the master branch of this repo `Polymer.register(this, ` used with `<element name="my-element"></element>` works fine.

As shown in the polymer-element branch of this repo `Polymer('my-element',  ` used with `<polymer-element name="my-element"></<polymer-element>` fails with the error `Uncaught TypeError: Property 'Polymer' of object [object Object] is not a function`.

Why?