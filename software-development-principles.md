# Software Development Principles

Software development principles are something you will continuously improve on for your entire career as an engineer.



**Why it's important**

Everything we are doing with respect to code quality is to make the system easy to change. There are typically 3 types of changes in a system: you add something (a feature), you remove something (dead code) or you replace something (refactor, update).

The idea of clean code is that it will keep the system easy and quick to change by making sure that the code is written in a way that is easy to understand, isolated so the developer doesn't break multiple components if a bug is introduced and split into intuitive parts. For most projects execution performance isn't the main goal.



**How do we achieve it**

Reading books and practicing. In this chapter we will focus on the first part.

Keep in mind that most of the books mentioned here aren't a one time read. You want to reread them periodically, say every couple of years and you will see that each time you come to different conclusions and even though the words are the same the meaning behind them has changed.

If you are in the beginning of your career, let's say under 1.5 years of experience consider reading Code Complete. It is, frankly, too long of a book if you have been in the game for longer, but it has really clear explanations and covers a very wide variety of source code level topics.

The Pragmatic Programmer is a great book with lots of practical advice. It's also great for starting to build your mindset.

Clean Code is another classic that builds both mindset and practical tips. The author, Robert C. Martin has a whole series of books. I recommend all of them.

Design Patterns are ways to achieve the SOLID principles, so any good book on either subject will cover both of them. They aren't a silver bullet, in IT nothing is, but they are something that will give you a much needed structure. A lot of people fall into the trap of elaborately trying to reinvent the wheel. Don't be one of them - learn and use the verified solutions and once you gain enough experience you will be able to innovate where it makes sense.



**Git**

Git is the de facto standard for version control systems. You will meet it and you, just like every developer who ever lived will struggle with it.

The most common mistake we’'ve observed is that people stop learning about git after learning how to create a branch, commit, push and merge. There is a lot more to git. Most time is lost when you encounter merge or rebase conflicts.

Most people freeze and stop learning. Don't do that. Create an example project and setup. Break things. Figure out how to fix them and learn. Iterate over this until you feel comfortable with merge conflicts. The few hours you will spend playing around and breaking things will pay their weight in gold. Also find some great tools to help you better visualize merge - JetBrains tools like WebStorm make merges very easy.

This is a great resource than can get you started with git branching: https://learngitbranching.js.org/&#x20;

And this resource will get you started with resolving merge conflicts: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line



**Bash Basics**

Bash is the de facto standard for shells. On Mac you are equipped with zsh which is a superset of bash. You don't need to be an expert, but you need to learn it.

Why is it useful ?

* A lot of times this is the only interface you will get when you are working with remote systems
* You can automate good chunks of your repeatable tasks
* You can manage processes and environments faster
* New features come first to the command line interface

You will know that you are good enough (for now :)) with bash when you have automated via aliases, cronjobs or a script at least one common task you are currently doing.



**CI/CD Basics**&#x20;

Continuous Integration and Continuous Delivery are super important. They automate the building and releasing the software. Automation is great because it saves developer time and it reduces human error.

Tests, code quality gates, vulnerability checks and a lot of other things are done for free by the machine executing these scripts.

There are often release teams who manage a lot of the pipelines that run the CI/CD, but despite that when you are a senior developer you must be able to build them.

Right now, as an aspiring mid level developer you don't need to be able to build them, but you should understand what they do, why they are useful and ideally what steps should be executed in them.

Build your understanding and then test yourself by making a few mock bash scripts that will act as what the agents should execute on trigger for CI or CD.

Become a power user of your editor Your editor is something you spend a lot of time working with. It is the same as hammer to blacksmith and katana to samurai. It's important you are productive with it, since that will save you a lot of time, therefore making you more productive.

My first advice is - don't get lost spending weeks tweaking with your editor. I've done it and it's fun, but you can cheaply become a power user by using widely adopted plugins.

The bare minimum you should have is:

* Code Formatter (when to put space, what type of brackets)
* Autocomplete
* Code Critic (prefer constants over variables where possible)
* build in documentation for the standard library (though most editors support it out of the box)

The idea is to make your editor work for you - concretely to help you save time by doing parts of the mundane tasks that gives you more bandwidth to focus on the business problem.



**Basics of architectures**&#x20;

Architecture takes a long time to learn so best start early. It is a combination of how modules are formed, how they communicate, how they don't communicate, how the responsibilities in the system(s) are split, etc. This is the code architecture.

There are other types of architecture, like deployment architecture - even though you may have a single app it can be deployed to several nodes behind a load balancer for example. You don't need to concern yourself with them until you have grasped the basics of code level architecture. As a junior chances are architecture is out of your scope for now.

There is a lot of good literature on the matter and when you are beginning any decent resource will get you started. If you are looking for a concrete recommendation a safe bet is Clean Architecture.

Architecture is one of the things that unfortunately greatly depends on your domain and scale of your app.

With that in mind when you do your research



