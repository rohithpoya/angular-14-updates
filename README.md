# Angular 14 release summary
 Major updates in Angular 14

The new features of the new angular 14 release include cli auto completion, typed reactive forms, standalone components, directives and pipes and an enhanced template diagnostics.


**Strictly typed forms**

Strictly typed forms are Angular's most popular feature request on GitHub which, once implemented, will enhance Angular's model-driven approach to working with forms.

For the first time, `FormControl` accepts a generic type that describes the kind of value it carries. An automatic migration was added by the Angular team in v14 to guarantee that existing applications will not be broken during the upgrade. As long as API complexity is kept in check, changes must be handed out smoothly, and the ecosystem must not be split apart.

The new updates will not affect template-based forms.

**Angular CLI auto completion**

If you have previously worked with Angular CLI, you can agree how it boots productivity by providing the necessary commands to generate artifacts such as modules, components and directives for your project.

There are several commands at your disposal but most of times you will need to go to the official guide to look for commands and specially commands' options.

With the release of Angular 14, this is no longer necessary.

Angular 14 provides a new feature in the cli that enables real-time type ahead auto completion in the terminal.

The first time you must execute the ng completion command in your terminal.

You can just type ng command then press Tab to view all of the possible choices and Enter to choose one of them, moreover if we are working on an angular 14 project more auto completion options, such as the `ng generate` command options, are available.

**Enhanced template diagnostics**

Angular 14 has brought enhanced template diagnostics so developers can be protected from typical mistakes by the compiler similar to typescript code. Currently, in Angular 13 and previous versions, the compiler does not generate warnings and only fails to build if there is an issue that would otherwise prohibit it from doing so.

Warnings may be readily generated for minor issues, such as incorrect two-way binding syntax or the use of unnecessary operators, such as ?? when the variable is not nullable.

The addition of a new private compiler option would allow diagnostic tests that would provide warnings or information diagnostics for user templates that aren't strictly lethal.

**Angular 14 standalone components**

Angular modules will be optional in Angular 14 and standalone components will be finally possible. Angular aims to move away from the current state of affairs by making artifacts such as components, directives and pipes the primary focus of the framework.

Angular issued an RFC (Request for Comments) on standalone components which is an attempt to make `NgModules` optional.

In order to maintain compatibility with the current ecosystem of Angular-based libraries and apps, modules will not be retired completely; instead, they will become optional.

