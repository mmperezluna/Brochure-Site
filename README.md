# Brochure Site

This is a brochure website
// create a function that will greet a person,
// and assign the function to the `greet` variable
var greet = function( person, message ) {
  var greeting = 'Hello, ' + person + '!';
  log( greeting + ' ' + message );
};

// use the function to greet Jory, passing in her
// name and the message we want to use
greet( 'Jory', 'Welcome to JavaScript' );

// use the function to greet Rebecca, passing in her
// name and a different message
greet( 'Rebecca', 'Thanks for joining us' );
