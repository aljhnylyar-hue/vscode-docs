---
ContentId: 79CD9B45-97FF-48B1-8DD5-2555F56206A6
DateApproved: 6/24/2026
MetaDescription: It is easy to add code snippets to Visual Studio Code both for your own use or to share with others on the public Extension Marketplace. TextMate .tmSnippets files are supported.
---
# Snippets in Visual Studio Code

Code snippets are templates that make it easier to enter repeating code patterns, such as loops or conditional-statements.

In Visual Studio Code, snippets appear in IntelliSense (`kb(editor.action.triggerSuggest)`) mixed with other suggestions, as well as in a dedicated snippet picker (**Insert Snippet** in the Command Palette). There is also support for tab-completion: Enable it with `"editor.tabCompletion": "on"`, type a **snippet prefix** (trigger text), and press `kb(insertSnippet)` to insert a snippet.

The snippet syntax follows the [TextMate snippet syntax](https://manual.macromates.com/en/snippets) with the exceptions of 'interpolated shell code' and the use of `\u`; both are not supported.

![ajax snippet](images/userdefinedsnippets/ajax-snippet.gif)
