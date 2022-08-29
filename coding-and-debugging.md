# Coding and Debugging

A big chunk of your time as a software developer will go towards extending and refactoring parts of the system you work on. In this section we are going to take a look at some of the fundamental skills you need to practice and improve on.

Probably the most common problem in junior developers is that they tend to get stuck for long periods of time. This is natural and even as a senior you will still get stuck. The goal is to manage to unstuck yourself and ideally to do so rather quickly.

Debugging is the main thing that will help you get unstuck. We are going to have a look at two different styles of debugging.

The first and probably most universal one is print based debugging. Put print messages on different points in your code and you will see what execution path the code has taken. You can also add variables to your program to print the current state.

The great thing about debugging via print messages is that it is really easy to do, universal to any language and fast to implement. The downside is that you are editing the code, therefore you must clean it up and if you need more information in the log, you need to rewrite the log call. Also sometimes you need to rebuild/reload the project to see them.

The next thing we will discuss is debugger driven debugging. The great thing about the debugger is that it will jump frame by frame and most debuggers will also let you see the state of any variable in that frame. This approach is great and may seem like it makes the print driven debugging redundant. This is partially true - the debugger is special software dedicated for that specific task and will have goodies that can't be done easily with a print. The downside is that it is slower to start up, sometimes they get laggy or their integration with your IDE/Text Editor freezes.

There isn't a golden rule about which to use. Using the debugger too often will harm your logging skills. Using prints too often will take more time since you need to clean up. You can say that usually debugging via debugger is faster, but debugging via prints may show places in your systems where you need extra traces.

Make sure you get acquainted with both types of debugging - when you can't progress easily with one of them, switch to the other. They complement each other.
