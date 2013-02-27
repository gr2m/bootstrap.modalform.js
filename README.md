bootstrap modal forms
=======================

Example usage:

```javascript
$.modalForm({
  fields: [ 'username', 'password' ],
  submit: 'Sign In'
}).on('submit', function(event, inputs) {
  // event.targt => <div class="modal">
  // inputs      => { username, password }
})
```

License
---------

MIT license.  
© Gregor Martynus