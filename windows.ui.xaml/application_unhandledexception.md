---
-api-type: winrt event
---
 Typically the [UnhandledException](application_unhandledexception.md) event handler doesn’t have enough information to know whether continuing on after an exception is safe. Parts of the application code or the Windows Runtime may be in an inconsistent state, which could result in subsequent failures if the app continues running its code.
 The Windows Runtime considers exceptions encountered during certain operations as nonrecoverable, because the Windows Runtime itself will be in an inconsistent state following these exceptions. For such exceptions, even if the [UnhandledException](application_unhandledexception.md) event handler sets [Handled](unhandledexceptioneventargs_handled.md) to **true**, the app will still be terminated.
 Errors that happen during navigation could cause a state where there's nothing loaded as content and nothing to indicate to the user that the app is still running.
 For more info on these points see [Exception handling for    in C# or Visual Basic](http://msdn.microsoft.com/library/825c5d4f-5ce0-ee93-fd1e-aca1372b1670).