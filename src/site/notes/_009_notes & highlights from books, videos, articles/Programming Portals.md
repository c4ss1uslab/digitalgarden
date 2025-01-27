---
{"created in":"2024-10-18T13:46:42-03:00","last tended to":"2024-10-18T14:00:46-03:00","created":"2024-10-18T13:46:42.554-03:00","updated":"2025-01-27T13:06:50.273-03:00","tags":["resource","highlights","lab","patterns"],"dg-publish":true,"permalink":"/009-notes-and-highlights-from-books-videos-articles/programming-portals/","dgPassFrontmatter":true}
---

original article by [[people/references/lab/maggie appleton\|maggie appleton]]: https://maggieappleton.com/programming-portals

#### notes

an introduction to/analysis of a specific type of hackable/malleable software/interface (programming portals), introduced by old-school [[hypercard\|hypercard]] with modern takes by the early versions of [[tbprocessed/base notes/tools;products - general/notion\|notion]], [[fermat.ws\|fermat.ws]] and [[projects & tools/projects/lab/inkbase\|inkbase]].

#### my highlights


> Programming portals are small, scoped areas within a graphical interface that give users access to command lines and text-based programming

> There is very little opportunity to build novel, customised systems. If a regular user in 1980 wanted to write a small programme to automate part of their workflow, the tools to do so were ready at hand. They could chain together small, composable [[UNIX\|UNIX]] commands in the same environment they do everything else in. If someone wants to try that nowadays, they'll need to enter a strange and unfamiliar environment: the terminal. They'll have to learn to navigate it with an unfamiliar language and set of commands. If they want to augment or interact with any third-party software – aka. all the software they have ever known – they're in for a rough awakening. They now need to download an IDE, install homebrew, install node or python, troubleshoot $PATH errors, navigate API documentation, and finally figure out how to execute the programme

> These portals act as entryways into a very different relationship with the computer. One where you learn to think programmatically – in rules and dynamic interactions and conditional statements – rather than just manipulating the static object in front of you. It's closing that crack in the interface world between the restrictive GUI and the open-ended CLI, and ultimately between end-users and programmers.

> The theoretical groundwork for why this kind of dynamic, interactive medium is critical to the future of interfaces has been well-trodden by [[people/references/lab/bret victor\|Bret Victor]]. In pieces like [[concepts/lab/learnable programming\|Learnable Programming]] and [[Drawing Dynamic Visualizations\|Drawing Dynamic Visualizations]].
> 
> Bret outlines a series of principles that make programmatic systems learnable. Such as being able to read the vocabulary of a programme, see the state, and create by reacting to what's on the screen in front of you. Programming portals are one way into these design patterns.

> Could I have changed the stroke through a set of GUI elements like input boxes and colour pickers? Sure! But it wouldn't have been conditional on the circle's size. In this world, if I resize the circle to make it less than 200px, it would lose the gold border. This is the power of programming. We're writing dynamic rules, not the absolute properties of a static image

> Most programming portals don't use fully-fledged programming languages like Python or JavaScript. Instead they offer a simplified language or limited set of commands designed specifically for this context. They might allow users to define and reuse variables, write and call functions, or create chains of if-then logic. Some other common affordances include

> Query for specific properties and data of elements within the interface
> Reference objects within the environment as variables
> Run functions that change how objects are displayed
> Run functions that change how objects behave
> Run calculations with the available data