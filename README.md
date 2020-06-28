## 🍴 Fork 

This is a fork of https://github.com/ccampbell/mousetrap.

It adds a `destroy` method to mousetrap which:

- calls the already available `reset` on the mousetrap object (to remove all bindings)
- removes all javascript event listeners from the specified target element or `document`
- removes all references to the target element

This **prevents DOM node memory leaks** and ensures everything is properly garbage collected.

## 📜 Documentation for `mousetrap`

Full documentation can be found at https://craig.is/killing/mice
