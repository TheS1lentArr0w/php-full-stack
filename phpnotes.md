# Encapsulation
- 'public' tag means variables/functions/methods etc. can be accessed wherever in the code
- 'private' and 'protected' tag means it cannot be accessed outside of the class

## Difference between 'private' and 'protected'
If a class is inherited into a subclass, it has access to 'protected' methods and variables. If they're labelled with 'private', the subclasses do not have access to it.

# Inheritance
## 'abstract' key word
If a class is tagged with 'abstract', then the class itself cannot be instantiated. It is only there solely to be inherited from (using the 'extends' key word)

# Composer
Search 'composer comes first' on [laracasts.com][laracasts].

It is an autoloader.

When putting classes in their own file, can use said autoloader to automatically get the dependencies in so that you don't have to have a bunch of import lines at the start of your file.


[laracasts]: https://laracasts.com/