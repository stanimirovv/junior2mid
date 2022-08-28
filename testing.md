# Testing

All software has bugs.&#x20;

Nevertheless as developers we must try to reduce their count as much as we can.

Doing Test Driven Development or investing otherwise in automated tests is a great way to make sure that your code’s behavior is monitored and working as you expect it to be.

You should treat each bug as a missing test case - that way you can guarantee that the software won’t produce this bug again.

If your company doesn't do automated tests make sure you constantly test your code. Too often developers (regardless of seniority) write code for 30 minutes then spend 1 hour debugging it due to cascading errors. Try to test your code each time you introduce a new function. If the function is private and you can't easily reach it, it is fine to temporarily make it public until you are sure that it has the behavior you want it to have.

When you test your code imagine you will get a prize if you break it.

Too often developers know where their code is fragile and choose to skip some of the testing there. Any bugs you leave will find their way back to you. Best fix them early.

It is much better to delay a release but release with no bugs than release something and spend the next one or two weeks patching it bug after bug. As you can imagine the second scenario is much more stressful too.

If your company does automated tests all from above applies, but instead of testing manually do it with tests.

One very important thing is that coverage doesn't show you the full picture. Coverage shows how much of the code has been passed through, but doesn't take into account the coverage of the combination of the branches.

Writing tests is a notoriously hard thing for developers, even experienced ones. Do not get discouraged. With enough practice you will master it.

Dive deeper into this topic by reading about Test Driven Development and The Testing Pyramid.

You will know that you have improved at testing when you stop doing obvious bugs. Software will always have bugs, but the ones from your code shouldn't be obvious.
