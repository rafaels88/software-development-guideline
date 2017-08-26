## Summary

This is a guideline based on principles and good practices from trusted sources of software development. As you will
notice, some of these principles and practices may be applied on every programming paradigm despite some specific terms.

Do not hesitate to contribute!

## Content

  > Every piece of knowledge must have a single, unambiguous, and authoritative representation within a system.

  _**Author:** Andy Hunt and Dave Thomas_

  _**Reference:** The Pragmatic Programmer book_

  > Procedural code gets information then makes decisions. Object-oriented code tells objects to do things.

  _**Author:** Alec Sharp_

  _**Reference:** Smalltalk by Example: The Developer's Guide_

  > Each unit should have only limited knowledge about other units: only units "closely" related to the current unit.
  > Each unit should only talk to its friends; don't talk to strangers.
  > Only talk to your immediate friends.

  _**Author:** Ian Holland_

  _**Reference:** [Assuring good style for object-oriented programs](http://ieeexplore.ieee.org/document/35588/)_

  > A class should have only one reason to change.

  _**Author**: Robert C. Martin_

  _**Reference:** [SRP: The Single Responsibility Principle](https://drive.google.com/file/d/0ByOwmqah_nuGNHEtcU5OekdDMkk/view)_

  > Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification.

  _**Author**: Bertrand Meyer_

  _**References:** Object-Oriented Software Construction book, and [The Open-Closed Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1/view)_

  > Functions that use pointers or references to base classes must be able to use objects of derived classes without knowing it.

  _**Author**: Barbara Liskov_

  _**Reference:** [Data Abstraction and Hierarchy](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.12.819&rep=rep1&type=pdf)_, and [The Liskov Substitution Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh/view)

  > Abstract classes should not depend upon concrete classes; concrete classes should depend upon abstract classes.

  _**Author**: Robert C. Martin_

  _**Reference:** [The Dependency Inversion Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz/view)_

  > Clients should not be forced to depend upon interfaces that they do not use.

  _**Author**: Robert C. Martin_

  _**Reference:** [The Interface Segregation Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi/view)_

  > Duplication is far cheaper than the wrong abstraction; prefer duplication over the wrong abstraction.

  _**Author**: Sandi Metz_

  _**Reference:** [RailsConf 2014 - All the Little Things](https://youtu.be/8bZh5LMaSmE?t=892)_

  > Always implement things when you actually need them, never when you just foresee that you need them.

  _**Author**: Ronald E Jeffries_

  _**Reference:** [You're NOT gonna need it!](http://ronjeffries.com/xprog/articles/practices/pracnotneed/)_

  > An object-oriented framework is "a (generative) architecture designed for maximum reuse, represented as a collective set of abstract and concrete classes; encapsulated potential behaviour for subclassed specializations."
  > The major difference between an object-oriented framework and a class library is that the framework calls the application code. Normally the application code calls the class library. This inversion of control is sometimes named the Hollywood principle, "Do not call us, we call You".

  _**Author**: Michael Mattson_

  _**Reference:** [Object Oriented Frameworks: a survey on methodological issues](https://www.researchgate.net/publication/2238535_Object-Oriented_Frameworks) and [On Inversion of Control](https://web.archive.org/web/20040202120126/http://www.betaversion.org/~stefano/linotype/news/38/)_

  > Adding possibly redundant code "just in case"  only contributes to the software's complexity -
  > the single worst obstacle to software quality in general, and to reliability in particular. 
  > The result of such blind checking is simply to introduce more software, hence more sources of things that
  > could go wrong at execution time, hence the need for more checks, and so on ad infinitum.
  > Such blind and often redundant checking causes much of the complexity and unwieldiness that often
  > characterizes software.

  _**Author**: Bertrand Meyer_

  _**Reference:** [Applying "Design by Contract"](http://se.ethz.ch/%7Emeyer/publications/computer/contract.pdf)_


## Contributing

Please, contribute!

Made by Rafael Soares with <3
