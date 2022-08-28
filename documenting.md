# Documenting

Documentation is not as fun as writing code, that's true. It is, however, when done adequately one of the better investments you can do.

Documentation will first and foremost help you. You won’t update the entire system constantly. Some parts of code will not have any checks or updates for months. When v2 is requested you will have forgotten a lot of the shortcuts and why specific decisions have been made. You will have to rediscover them which will cost you time.

Documentation in source code is generally not recommended. High quality code is readable, contextual, and intuitive. If you write documentation inside your code you will need to update it when changing functionality. Most developers fail to update their documentation and you may read one thing in the comment, but the code will do something else.

There are a few types of comments in the source code that are useful in certain scenarios:

* TODOs that explain something that should be improved. Ideally they will have a link to a ticket inside your system
* Explanation comments as to why something is done in a specific way, for example unintuitive logic
* Birds eye overview of a module or set of modules

The documentation outside of the codebase is generally two types:

1. One off journal style documents that explain why a decision was made or the outcome of a discussion
2. Living documents that are constantly updated.

My recommendation is to heavily favor the journals. Having too many living documents will force you into spending more time documenting and not coding.

Oftentimes the living documents for a project are a set of architecture diagrams + consumer documentation.

If you are wondering if you should document something or not - put it in a journal and leave it. If you need it you will have it. If you don't need it at least you don't have to update it.
