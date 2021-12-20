# Hello, world!

A beginner level task for practicing AutoCode task management and running unit tests in Visual Studio.

Translations: [Russian](README-RU.md).

Estimated time to complete the task - 1h.

The task requires .NET 6 SDK.


## Task Description

The task has no coding work, just only Visual Studio work.

1. Open a [Solution Explorer](https://docs.microsoft.com/en-us/visualstudio/ide/solutions-and-projects-in-visual-studio#solution-explorer).
    * Click on the menu item - _View\Solution Explorer_.
    * Or use the default keyboard shortcut - _Ctrl+Alt+L_ (various versions of Visual Studio may have different keyboard shortcuts. See [Keyboard shortcuts in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/ide/default-keyboard-shortcuts-in-visual-studio) article).

![View Solution Explorer](images/view-solution-explorer.png)

2. Find "HelloWorld" and "HelloWorld.Tests" projects in the Solution Explorer view.

![Solution Explorer](images/solution-explorer.png)

3. Open the "HelloWorld" project and find [SimpleHelloWorld.cs](HelloWorld/SimpleHelloWorld.cs) file in the project. Open the file in the editor window.

![SimpleHelloWorld.cs](images/simple-hello-world.png)

4. Open the "HelloWorld.Tests" project and find [SimpleHelloWorldTests.cs](HelloWorld.Tests/SimpleHelloWorldTests.cs) file in the project. Open the file in editor window.

![SimpleHelloWorldTests.cs](images/simple-hello-world-tests.png)

5. [Build the solution](https://docs.microsoft.com/en-us/visualstudio/ide/building-and-cleaning-projects-and-solutions-in-visual-studio).
    * Click on menu item - _Build\Build Solution_.
    * Or use default keyboard shortcut - _Ctrl+Shift+B_.

![Build Solution](images/build-solution.png)

6. Open the [Error List](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-the-error-list) view.
    * Click on menu item - _View\Error List_.
    * Or use default shortcut - _Ctrl+\\, E_.

![View Error List](images/view-error-list.png)

Make sure there are no compiler issues (warnings or errors).

![Error List](images/error-list.png)

7. Open [Test Explorer](https://docs.microsoft.com/ru-ru/visualstudio/test/run-unit-tests-with-test-explorer). 
    * Click on the menu item - _Tests\Test Explorer_.
    * Or use the default keyboard shortcut - _Ctrl+E, T_.

![Test Explorer](images/test-test-explorer.png)

All tests in the test list are have blue icon with white exclamation mark. That tell us the unit tests were not run.

![Test Explorer](images/test-explorer-white.png)

8. Right click on "HelloWorld.Tests" list item and click on "Run" menu item.
    * Or use the default shortcut - _Ctrl+R, T_.

![Run Tests](images/run-tests.png)

All list items should be marked "green".

![Test Explorer](images/test-explorer-green.png)

9. Unfold the list in Test Explorer (if necessary), right click on "ReturnHelloWorld" unit test, and click on "Run" menu item. The selected list item should stay "green".
    * Or use the default shortcut - _Ctrl+R, T_.

![Run Test](images/run-test.png)

10. Run all unit tests.
    * Click on the menu item - _Test\Run All Tests_.
    * Or use the defaul keyboard shortcut - _Ctrl+R, A_.

![Run All Tests](images/run-all-tests.png)

You can go to AutoCode portal, open the task page, and click on the "Check task" button.


## Fix Compiler Issues

Additional style and code checks are enabled for the projects in this solution to help you maintaining consistency of the project source code and avoiding silly mistakes. [Review the Error List](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-the-error-list) in Visual Studio to see all compiler warnings and errors.

If a compiler error or warning message is not clear, [review errors details](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-errors-in-detail) or google the error or warning code to get more information about the issue.


## Task Checklist

1. Rebuild the solution.
2. Fix all compiler warnings and errors.
3. Run all unit tests, make sure all unit tests completed successfully.


## See also

* Visual Studio
  * [Getting Started with Visual Studio 2019](https://www.youtube.com/watch?v=1CgsMtUmVgs)
  * [Default keyboard shortcuts in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/ide/default-keyboard-shortcuts-in-visual-studio)
