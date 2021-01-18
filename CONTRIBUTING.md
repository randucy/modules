# Contributing Guidelines and Tips
The best way to contribute to RanDucy is contributing to RanDucy modules. That is because Modules is just like Node packages, pieces of you can install, but you don't have to!

## How to start contributing
Making modules and fixing bugs/improving existing modules is the best way to contribute to RanDucy Modules

### Making modules
To keep everything organized, we have constructed a list of steps to follow.

1. Fork the repository
2. Make a new folder with the module name (nothing else)
3. Write your code and do your thing
4. Make documentation (please do this even if it is a really simple module)
5. Make a pull request to this repository and put everything your modules does in it, use the provided template!
6. If necessary make requested adjustments

#### Important things to know
* When your pull request gets merged, you'll get credit. However, it'll still be under AGPL-3.0 license. You do not own that code!
* One module per pull request. If there are any changes outside of the folder *you* made, it'll be rejected.

### Fixing bugs in / improving modules
The other way to improve RanDucy via modules is fixing bugs or improve existing modules! We also made a list of steps to follow if this is what you want to do.

1. Fork the repository
2. Make desired changes
3. Update the documentation (if needed)
4. Make a pull request (make it very clear what you did, use the template)
5. If necessary make requested adjustments

#### Important things to know
* When your pull request gets merged, you'll get credit. However, it'll still be under AGPL-3.0 license. You do not own that code!
* One issue per pull request. If there are any changes outside of the folder *you* made, it'll be rejected.

### General RanDucy Module Coding Guidelines
Because we don't want interference with variables and function, we have a few guidelines:

1. Try to limit the amount of global variables as much as possible
2. When creating global variables, make the first part the name of the module
3. When creating functions, make the first part of the function name the name of the module
4. For triggering the modules functionality, make a module specific function that reads the input and triggers the functionalities. This makes it easier to work with.

### RanDucy Module Development Tips
We also have a few tips and tricks:

1. Use the RanDucy DevEnv, more information [here][1]
2. If you have to update your code very often or it is part of something else, you can enter an external files in the Pull Request for your module!

### Making issues
Making issues is another way to contribute! When making issues please do keep in mind these things:

* Use the templates
* Be very clear in your issue


[1]: https://github.com/randucy/devenv
