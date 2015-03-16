# All Rhino ChangeSets Since 01.01.2007 00:00 #

## Status New (362 ChangeSets, 931 Files and 19628/11993 Lines changed) ##

| **MaxDate** | **Files** | **Added** | **Removed** | **Description** | **Comment** |
|:------------|:----------|:----------|:------------|:----------------|:------------|
| 06.25.2008 19:11 | 1 | 1 | 1 | Changes URI encoding so that the hex letters are capitalized, which is important in oAuth.  According to rfc3986:  2.1.  Percen... |  |
| 06.19.2008 17:46 | 1 | 0 | 3 | Remove obsolete statement in comment. |  |
| 06.19.2008 10:30 | 11 | 68 | 18 | Fix the last of the warnings! |  |
| 06.11.2008 06:02 | 2 | 29 | 21 | Fix [bug 437988](https://code.google.com/p/ecmascript-net/issues/detail?id=37988). Rhino must discover the abstract methods in the interface of a base class in JavaAdapter |  |
| 05.28.2008 05:36 | 1 | 2 | 2 | Fix typos in comments. |  |
| 05.28.2008 05:35 | 1 | 1 | 1 | fix typo in comment. |  |
| 05.28.2008 05:35 | 1 | 7 | 2 | Improve error reporting if sourceName == null. |  |
| 05.22.2008 13:42 | 1 | 6 | 0 | Fix bug where we were getting a strict warning on the following code: function f() { x &amp;&amp; g(); } |  |
| 05.16.2008 14:13 | 4 | 27 | 15 | Fix [bug 433878](https://code.google.com/p/ecmascript-net/issues/detail?id=33878): minor glitch when decompiling 'let' statements  Once I ran this through the regression tests, this ended up bei... |  |
| 05.07.2008 06:02 | 1 | 3 | 3 | Fix spelling error, add more info about -f - |  |
| 05.06.2008 05:43 | 2 | 1 | 3 | Fix warning for use of cx.enter(), move regExpParse.doctest |  |
| 05.04.2008 08:24 | 1 | 0 | 0 | Regression test for Matrix example |  |
| 05.04.2008 08:22 | 12 | 53 | 30 | Fix more warnings, serialVersionUID, generics, clean up examples |  |
| 05.03.2008 18:32 | 1 | 0 | 0 | Regression test (updated to fix warnings). |  |
| 05.02.2008 05:57 | 2 | 1 | 1 | Had already fixed [bug 368019](https://code.google.com/p/ecmascript-net/issues/detail?id=68019) from another source, mark it fixed and rename regression test |  |
| 05.01.2008 19:02 | 1 | 1 | 1 | fix typo in comment |  |
| 05.01.2008 07:08 | 3 | 35 | 6 | Fix [bug 431674](https://code.google.com/p/ecmascript-net/issues/detail?id=31674) Java field private access doesn't work well with Java Bean access |  |
| 05.01.2008 05:36 | 2 | 86 | 33 | Fix [bug 419090](https://code.google.com/p/ecmascript-net/issues/detail?id=19090): Object properties list in different (hash?) order than entered Connect slots in a linked list to keep track of ... |  |
| 04.22.2008 05:13 | 2 | 18 | 1 | fix more warnings |  |
| 04.21.2008 12:54 | 16 | 108 | 19 | Fix a bunch of warnings. |  |
| 04.20.2008 11:14 | 2 | 84 | 59 | Convert to newer collection classes and parameterized types. |  |
| 04.19.2008 18:53 | 1 | 1 | 4 | Fix [Bug 429853](https://code.google.com/p/ecmascript-net/issues/detail?id=29853): msg.inconsistent.return strict-warning incorrect for nested functions |  |
| 04.14.2008 08:21 | 1 | 1 | 1 | More clarification that the Sun code is available only under the Sun license. |  |
| 04.14.2008 08:20 | 1 | 1 | 3 | Clean up wording a bit. |  |
| 04.14.2008 08:18 | 1 | 819 | 35 | Updated to include text of MPL and GPL. |  |
| 04.14.2008 06:04 | 8 | 5 | 30 | Add treetable sources needed by the Rhino debugger. Add LICENSE.txt to show the license terms, and propagate that file to the b... |  |
| 04.14.2008 05:49 | 1 | 2 | 2 | Fix typos in javadoc. |  |
| 04.14.2008 05:48 | 1 | 2 | 2 | Fix syntax in comment. |  |
| 04.14.2008 05:48 | 1 | 1 | 1 | Fix spelling error in error message. |  |
| 04.11.2008 07:45 | 2 | 10 | 0 | fix warnings. |  |
| 04.11.2008 07:41 | 1 | 0 | 0 | Parsing of regexp boundaries was a little too dumb in TokenStream.readRegExp. |  |
| 04.11.2008 07:40 | 1 | 6 | 2 | Parsing of regexp boundaries was a little too dumb. |  |
| 04.11.2008 07:39 | 1 | 2 | 2 | Fix spelling errors |  |
| 04.01.2008 04:57 | 2 | 17 | 1 | Fix javadoc typo @links -&gt; @link |  |
| 04.01.2008 04:38 | 1 | 1 | 1 | Fix spelling error. |  |
| 03.31.2008 06:32 | 1 | 26 | 9 | Fix [bug 421071](https://code.google.com/p/ecmascript-net/issues/detail?id=21071): Performance problems after using importPackage |  |
| 03.25.2008 07:32 | 26 | 92 | 20 | More warnings fixed. |  |
| 03.25.2008 06:38 | 16 | 279 | 129 | Fix more warnings. |  |
| 03.24.2008 19:06 | 1 | 0 | 0 | We no longer support JDKs older than JDK 1.4, so remove this class. |  |
| 03.24.2008 19:05 | 1 | 1 | 1 | Add PRERELEASE to version string. |  |
| 03.23.2008 17:09 | 2 | 49 | 6 | Add code and test for canonicalizing the output of java.lang.Object.toString for the purposes of doctest. |  |
| 03.23.2008 10:32 | 1 | 50 | 24 | Improve JLine completion. |  |
| 03.23.2008 05:47 | 4 | 13 | 14 | fix warnings. |  |
| 03.18.2008 08:10 | 47 | 436 | 451 | Massive fix of warnings, mostly supplying type parameters for generics. Also switched to modern collections classes. |  |
| 03.18.2008 08:08 | 2 | 28 | 10 | Add support for optional JLine editing in interactive shell. Contribution from Matthieu Riou. |  |
| 03.13.2008 17:52 | 1 | 1 | 1 | Fix spelling in comment. |  |
| 03.13.2008 13:00 | 20 | 153 | 31 | Fix many warnings, mostly adding @Override, a few Class&lt;?&gt;. |  |
| 03.12.2008 14:09 | 1 | 0 | 0 | Add test |  |
| 03.12.2008 12:05 | 1 | 7 | 2 | Patch from Dominic Cooney:  Some users are getting bitten by Xerces' DocumentBuilderImpl throwing UnsupportedOperationException... |  |
| 03.12.2008 12:04 | 1 | 2 | 2 | Begin 1.7R2 work |  |
| 03.12.2008 05:47 | 7 | 36 | 9 | Fix warnings, mainly @Override and generics. |  |
| 03.10.2008 10:06 | 2 | 7 | 0 | Add @Override |  |
| 03.07.2008 12:43 | 2 | 18 | 10 | Add reporting of location of doctest failure. |  |
| 03.07.2008 12:17 | 1 | 0 | 0 | Add regression test. |  |
| 03.07.2008 06:51 | 1 | 1 | 4 | Fix [bug 416127](https://code.google.com/p/ecmascript-net/issues/detail?id=16127). |  |
| 03.06.2008 14:00 | 2 | 27 | 1 | Stop building debugger to avoid incorporation of binaries built from non-open source. |  |
| 03.06.2008 13:47 | 1 | 3 | 3 | Changes for new JsTest JUnit test runner. |  |
| 03.06.2008 10:33 | 5 | 66 | 23 | Add new JsTests unit test wrapper |  |
| 03.03.2008 14:20 | 10 | 98 | 1 | First take at a doctest function like the Python doctest, with JUnit driver and a few tests. |  |
| 02.28.2008 16:53 | 1 | 13 | 4 | Fix [bug 420012](https://code.google.com/p/ecmascript-net/issues/detail?id=20012): VerifyError on generated class |  |
| 02.27.2008 19:49 | 2 | 8 | 6 | Fix [bug 419940](https://code.google.com/p/ecmascript-net/issues/detail?id=19940): Incorrect JavaAdapter generation for base class that overrides an abstract method. |  |
| 02.14.2008 05:22 | 1 | 12 | 9 | Fix bug reported in newsgroup: Tail call opimization was interfering with catching exceptions. The following program should pri... |  |
| 02.13.2008 18:41 | 1 | 2 | 2 | Fix spelling errors in comments |  |
| 02.13.2008 10:33 | 1 | 13 | 1 | Fix [bug 413838](https://code.google.com/p/ecmascript-net/issues/detail?id=13838): Incorrect ScriptRuntime.eq(Object, Object) implementation |  |
| 02.13.2008 08:44 | 4 | 35 | 2 | Fix for [Bug 190841](https://code.google.com/p/ecmascript-net/issues/detail?id=90841) Ð Generated classes have too low privileges |  |
| 02.11.2008 10:33 | 1 | 13 | 3 | Update to skip new tests. |  |
| 02.11.2008 10:01 | 1 | 10 | 22 | Remove dead code (thanks to Steve Yegge for pointing it out). |  |
| 02.11.2008 07:53 | 1 | 0 | 1 | Remove unused import. |  |
| 02.08.2008 11:15 | 1 | 3 | 0 | Fix for [Bug 405558](https://code.google.com/p/ecmascript-net/issues/detail?id=05558): use "unnamed script" as name of scripts that are given no name explicitly. |  |
| 02.08.2008 10:07 | 1 | 2 | 1 | fix comment |  |
| 02.08.2008 08:52 | 2 | 87 | 88 | Various NativeArray fixes: - 1.6R7 version didn't guarantee synchronization, so don't introduce for this version - Fix performa... |  |
| 02.08.2008 08:47 | 1 | 0 | 2 | Remove unused imports. |  |
| 02.08.2008 08:44 | 1 | 4 | 3 | Fix for [bug 400031](https://code.google.com/p/ecmascript-net/issues/detail?id=00031) |  |
| 02.06.2008 10:32 | 1 | 1 | 1 | Minor cleanup. |  |
| 02.05.2008 13:58 | 2 | 7 | 5 | Try for better efficiency using the denseOnly flag |  |
| 02.05.2008 13:19 | 1 | 1 | 0 | Add missing @Override. |  |
| 02.05.2008 12:49 | 2 | 15 | 3 | Fix [bug 409702](https://code.google.com/p/ecmascript-net/issues/detail?id=09702) - JavaAdapter causes VerifyError with some abstract classes |  |
| 02.05.2008 10:37 | 3 | 46 | 5 | Fix [bug 414098](https://code.google.com/p/ecmascript-net/issues/detail?id=14098) - Support for define[GS](GS.md)etter on array indexes Patch from Matthieu Riou |  |
| 02.05.2008 09:39 | 1 | 44 | 24 | Get NervousText.js working again: - create Context if need be in JavaMembers constructor - handle exceptions caused by calling ... |  |
| 02.05.2008 09:37 | 1 | 12 | 11 | Get NervousText.js working again by avoiding duplicate generation of "super$method" methods. Also fix a few spelling errors. |  |
| 02.05.2008 09:18 | 1 | 7 | 0 | Skip stress tests. |  |
| 02.04.2008 06:20 | 1 | 5 | 5 | fix [bug 415451](https://code.google.com/p/ecmascript-net/issues/detail?id=15451) - Array.lastIndexOf does not work correctly |  |
| 02.04.2008 05:43 | 1 | 1 | 2 | From newsgroup:  I think I've found a small bug in the Array.function shortcut (instead of Array.prototype.function.call(...)).... |  |
| 02.03.2008 23:52 | 1 | 1 | 0 | Fix for [Bug 415508](https://code.google.com/p/ecmascript-net/issues/detail?id=15508) Ð PolicySecurityController bug: it creates lots of SecureCallerImpl instances! |  |
| 02.01.2008 12:54 | 1 | 50 | 6 | Fix [bug 414984](https://code.google.com/p/ecmascript-net/issues/detail?id=14984): Array.lastIndexOf gives ArrayIndexOutOfBoundsException |  |
| 02.01.2008 07:11 | 1 | 10 | 3 | Fix [bug 414869](https://code.google.com/p/ecmascript-net/issues/detail?id=14869): Rhino debugger fails to launch due to updates in mac os x leopard |  |
| 01.30.2008 11:40 | 1 | 12 | 17 | No point in using WeakHashMap with classes as keys. Back off to plain HashMap until we figure out more about the particular pro... |  |
| 01.29.2008 11:41 | 1 | 9 | 9 | Fix function case for 414553. |  |
| 01.29.2008 10:39 | 3 | 35 | 12 | Fix [Bug 414553](https://code.google.com/p/ecmascript-net/issues/detail?id=14553) - destructuring assignment in let causes bindings to be lost |  |
| 01.29.2008 06:34 | 3 | 41 | 28 | Fix [Bug 414554](https://code.google.com/p/ecmascript-net/issues/detail?id=14554) - ClassCache should use WeakHashMap |  |
| 01.28.2008 06:41 | 3 | 12 | 8 | Complete fix for [bug 412247](https://code.google.com/p/ecmascript-net/issues/detail?id=12247) - Allow to customize toBoolean conversion Fix misspelling in method name (!) and correct support fo... |  |
| 01.23.2008 09:24 | 1 | 5 | 6 | Fix exclusions |  |
| 01.23.2008 08:52 | 1 | 1 | 0 | Make sure it finds JUnit |  |
| 01.23.2008 06:59 | 2 | 25 | 1 | Fix [Bug 412247](https://code.google.com/p/ecmascript-net/issues/detail?id=12247)  Allow to customize toBoolean conversion  Add new ScriptableObject method, avoidObjectDectection:  / **Emulate...**|  |
| 01.23.2008 05:45 | 1 | 1 | 1 | Fix [bug 392593](https://code.google.com/p/ecmascript-net/issues/detail?id=92593) Wrong type for arguments object |  |
| 01.21.2008 17:12 | 1 | 0 | 6 | Remove unused method. |  |
| 01.19.2008 18:20 | 2 | 25 | 7 | Fix [bug 412755](https://code.google.com/p/ecmascript-net/issues/detail?id=12755) - Provide better error message when a function is not found Modification of patch by Marc Guillemot. |  |
| 01.18.2008 11:21 | 2 | 33 | 27 | Refactor prompts to make them more accessible for other uses (i.e. doctest) |  |
| 01.18.2008 10:37 | 1 | 2 | 1 | More skips for flaky tests. |  |
| 01.16.2008 12:58 | 1 | 10 | 0 | Add additional skips for flaky tests: see <a href="http://groups.google.com/group/mozilla.dev.tech.js-engine.rhino/browse_threa... |  |
| 01.15.2008 11:27 | 2 | 18 | 21 | Fix [bug 412467](https://code.google.com/p/ecmascript-net/issues/detail?id=12467) - Iterator value escapes from array comprehension |  |
| 01.15.2008 09:53 | 1 | 2 | 2 | Fix comments: interpreterLoop -&gt; interpretLoop |  |
| 01.15.2008 09:39 | 2 | 12 | 4 | Remove dependency on Arrays.copyOfRange, which is in JDK 1.6 only. |  |
| 01.15.2008 09:38 | 1 | 3 | 0 | Skip new failing tests. |  |
| 01.11.2008 07:02 | 1 | 40 | 8 | Some work to address https://bugzilla.mozilla.org/show_bug.cgi?id=411895.  I noticed that we were creating a DocumentBuilder fr... |  |
| 01.10.2008 14:47 | 2 | 13 | 11 | Fix case that had been getting a ClassCastException (then changed to be a Kit.codeBug) that I now report an error on. |  |
| 01.10.2008 14:45 | 1 | 27 | 1 | Add support for customizable prompt characters for the shell using the "prompts" global variable. |  |
| 01.10.2008 14:44 | 2 | 394 | 224 | Fix missing functionality of Array and String methods available as function properties of the constructor (e.g., Array.every, S... |  |
| 01.09.2008 11:23 | 3 | 26 | 28 | Fix miscellaneous failures in JavaScript 1.7 support as demonstrated by test suite. |  |
| 01.09.2008 11:22 | 1 | 1 | 1 | Fix bug: was printing out name of resource rather than error message. |  |
| 01.09.2008 11:19 | 1 | 3 | 3 | Prepare for release candidate. |  |
| 01.09.2008 07:46 | 1 | 2 | 0 | Fix the use of property or array lvalues in destructuring assignment. Test case:  var obj = { p:3 }; var arr = [3 ](.md); [obj.p] =... |  |
| 01.07.2008 09:51 | 1 | 1 | 0 | Add skip for new test |  |
| 01.07.2008 09:46 | 1 | 3 | 1 | More accurate description of Rhino behavior with generators and gc. |  |
| 01.07.2008 09:45 | 1 | 46 | 45 | Make retro-translated 1.4 jar part of standard distribution. |  |
| 01.05.2008 14:27 | 1 | 7 | 0 | Update for latest test cases. |  |
| 01.05.2008 12:58 | 1 | 1 | 1 | Fix iteration behavior for new Iterator(obj,true). |  |
| 01.04.2008 16:57 | 1 | 66 | 30 | Implement a finalizer for generators that closes the generator. |  |
| 01.03.2008 18:49 | 2 | 29 | 25 | Fix all the variants of behavior of Iterator constructor to match SpiderMonkey. |  |
| 01.03.2008 10:39 | 4 | 73 | 73 | I've made changes to Rhino such that its default behavior is now only to treat Iterables or Iterators specially when they are a... |  |
| 01.03.2008 08:21 | 1 | 1 | 1 | Fix formatting nit |  |
| 12.27.2007 21:58 | 1 | 1 | 1 | Committing Hannes Wallnoefer's patch for 403604 |  |
| 12.20.2007 18:56 | 1 | 5 | 1 | Print script stack traces for uncaught exceptions. |  |
| 12.10.2007 10:00 | 1 | 3 | 3 | Fix [bug 407374](https://code.google.com/p/ecmascript-net/issues/detail?id=07374) - Destructuring assignment isn't threadsafe Patch from Christophe Grand. |  |
| 12.04.2007 12:43 | 1 | 13 | 0 | Skip new tests that fail. |  |
| 12.03.2007 05:50 | 1 | 157 | 126 | Refactor to pull code out of interpretLoop. This fixes a big performance problem where interpretLoop was no longer being JITted... |  |
| 12.01.2007 01:27 | 1 | 8 | 2 | [Bug 405654](https://code.google.com/p/ecmascript-net/issues/detail?id=05654): make sure call() and apply() execute correctly when invoked as a tail call |  |
| 11.29.2007 04:32 | 1 | 8 | 0 | [Bug 404817](https://code.google.com/p/ecmascript-net/issues/detail?id=04817): reinstantiate ContextFactory.exit() |  |
| 11.28.2007 02:15 | 3 | 100 | 27 | Fix for [Bug 405654](https://code.google.com/p/ecmascript-net/issues/detail?id=05654) Ð Execution exits interpreter on Function.apply and Function.call |  |
| 11.27.2007 04:45 | 1 | 1 | 1 | Fix javadoc typo. |  |
| 11.26.2007 22:57 | 9 | 14 | 15 | A bit of a cleanup since we're now compiling primarily for Java 5: clone() returns objects of called type, so no casting is nec... |  |
| 11.26.2007 22:55 | 2 | 119 | 206 | Fix for [Bug 404817](https://code.google.com/p/ecmascript-net/issues/detail?id=04817) Ð ContextFactory.enter results in new contexts that don't have their factory slot set |  |
| 11.26.2007 11:58 | 2 | 93 | 106 | Fix [bug 402331](https://code.google.com/p/ecmascript-net/issues/detail?id=02331): In a compiled iterator "this" points to an instance of RuntimeGeneratorState. Had to save and restore the JavaS... |  |
| 11.26.2007 10:08 | 1 | 5 | 4 | Clean up javadoc. |  |
| 11.24.2007 07:08 | 1 | 4 | 2 | Fix [Bug 404484](https://code.google.com/p/ecmascript-net/issues/detail?id=04484) - destructuring assignment does not work for constants |  |
| 11.23.2007 18:07 | 1 | 2 | 14 | Fix problem reported on newsgroup by Christophe Grand:  I noticed that the java array backing the "arguments" variable is reuse... |  |
| 11.21.2007 08:43 | 2 | 49 | 9 | Add retrotranslator |  |
| 11.20.2007 08:08 | 2 | 15 | 0 | Extension: The E4X XML constructor can now create XML directly from a Java DOM node. Previously the implementation would have c... |  |
| 11.17.2007 08:03 | 1 | 4 | 1 | Fix for [Bug 403604](https://code.google.com/p/ecmascript-net/issues/detail?id=03604) Ð Continuation support missing in Rhino 1.7 (cvs HEAD) |  |
| 11.14.2007 16:58 | 1 | 3 | 1 | The JVM currently doesn't allow changing access on java.lang.Class constructors, so don't try |  |
| 11.14.2007 16:43 | 1 | 1 | 1 | Fix bug: running var x = [.md](.md); x[1](1.md) = 'foo'; x.map(function(e){return e?'yes':'no'}).join(','); should result in ",foo". |  |
| 11.13.2007 13:43 | 1 | 41 | 82 | Fix [bug 368323](https://code.google.com/p/ecmascript-net/issues/detail?id=68323): Global class's runCommand suffers from Bad file descriptor IOExceptions on extra close() calls |  |
| 11.13.2007 13:11 | 2 | 26 | 6 | Optimization for '+' with one string literal operand. Worth about 30% performance improvement. |  |
| 11.12.2007 15:24 | 1 | 0 | 3 | Remove duplicate definition of 'msg.fn.redecl'. |  |
| 11.08.2007 05:12 | 1 | 11 | 5 | Accepting patch for [bug 391439](https://code.google.com/p/ecmascript-net/issues/detail?id=91439): Exception on startup on JDK 1.4. Patch from Jürg Lehni. |  |
| 11.06.2007 14:57 | 4 | 36 | 5 | Truly enable catching all Java exceptions when FEATURE\_ENHANCED\_JAVA\_ACCESS is enabled. |  |
| 11.06.2007 14:52 | 1 | 45 | 32 | When FEATURE\_ENHANCED\_JAVA\_ACCESS gives us access to non-public members, continue to prefer public methods in overloading. |  |
| 11.06.2007 14:50 | 1 | 5 | 2 | Treat Java final the same as JavaScript [[READONLY](READONLY.md)]. Rhino previously just threw a RuntimeException. |  |
| 11.02.2007 06:41 | 5 | 32 | 20 | Store StopIteration in the global scope in a way that cannot be affected by JavaScript. Rhino's behavior now matches SpiderMonk... |  |
| 11.02.2007 06:21 | 7 | 102 | 35 | Break dependencies so that implementations can run without an Interpreter instance. |  |
| 11.01.2007 13:38 | 1 | 30 | 4 | Improve indexOf (and lastIndexOf) performance by 3.5X.  Fix regression:  ~/no\_crawl/src/js/rhino&gt;java -jar build/rhino1\_6R6p... |  |
| 10.31.2007 07:11 | 1 | 3 | 3 | Fix regression caused by fix for [bug 396700](https://code.google.com/p/ecmascript-net/issues/detail?id=96700), as shown by TypeError for Array.prototype.some.call("foobar", function(c) {return ... |  |
| 10.25.2007 06:34 | 1 | 1 | 1 | Restoring "throws IOException" in replaceObject() |  |
| 10.23.2007 14:46 | 1 | 40 | 1 | Dense array optimization for concat. 54X speed improvement. Test case: function f() { var a = [1,2,3,4,5,6,7,8,9,10]; var d = n... |  |
| 10.23.2007 13:28 | 1 | 7 | 1 | Fix for Bugzilla #396117: preserve backwards compatibility with existing jsc-precompiled classes generated with earlier Rhino v... |  |
| 10.23.2007 10:49 | 1 | 7 | 3 | Fix for Bugzilla #396700: primitives passed as thisObj to Array.map etc are converted to object |  |
| 10.23.2007 09:14 | 1 | 5 | 1 | Fix for Bugzilla #397882: forEach and similar methods shouldn't enumerate unassigned or deleted array elements |  |
| 10.23.2007 08:46 | 1 | 1 | 1 | Fix for Bugzilla #400159: Synchronizer should act on the object underlying the Wrapper when applied to one |  |
| 10.23.2007 08:29 | 1 | 1 | 1 | Fix for Bugzilla #399958 |  |
| 10.19.2007 10:06 | 1 | 13 | 1 | Specialized code for dense arrays for concat(). ~24X speedup. |  |
| 10.19.2007 08:58 | 1 | 3 | 1 | Must make IdEnumeration serializable, otherwise a continuation taken in a for loop can't be serialized |  |
| 10.19.2007 06:47 | 3 | 82 | 9 | Add support for iterating over java.lang.Iterable objects using for..in syntax. |  |
| 10.19.2007 03:27 | 1 | 2 | 2 | Fix: opt1.skip was used for interpreted, not for compiled mode... |  |
| 10.18.2007 13:49 | 1 | 1 | 1 | Minor formatting change. |  |
| 10.18.2007 06:26 | 1 | 7 | 0 | Skip recent inapplicable tests. |  |
| 10.12.2007 13:05 | 1 | 54 | 16 | Dense array speedup for sort (9%) and splice (754X!). |  |
| 10.11.2007 12:44 | 3 | 7 | 0 | Adding @version tags with CVS ids |  |
| 10.11.2007 10:24 | 1 | 22 | 7 | Dense implementation for js\_join; about 28% faster. |  |
| 10.11.2007 07:09 | 1 | 5 | 0 | Create HTML reports |  |
| 10.11.2007 06:50 | 1 | 2 | 1 | Must call Thread.stop **before** status.timedOut, as JUnitStatus actually throws an assertion error |  |
| 10.09.2007 08:14 | 2 | 196 | 64 | Implement growable array-based storage for native Array objects with dense allocation patterns. Added specialized implementatio... |  |
| 10.07.2007 10:21 | 1 | 1 | 0 | I just noticed that running tests spins up GUI. Shouldn't happen, and this should take care of it. |  |
| 10.07.2007 10:21 | 1 | 2 | 5 | When cleaning, nuke the full build directory. |  |
| 10.06.2007 10:44 | 1 | 2 | 1 | Adding a bit of additional diagnostics -- printing to stdout the name of file being run, and the threads carry the file name in... |  |
| 10.05.2007 12:39 | 6 | 129 | 3 | Fix [bug 397680](https://code.google.com/p/ecmascript-net/issues/detail?id=97680): Need to support Context.observeInstructionCount for compiled mode. Compile in callbacks to a method that accumu... |  |
| 10.04.2007 06:21 | 1 | 9 | 0 | New skips for new tests. |  |
| 10.03.2007 13:32 | 1 | 6 | 7 | fix [bug 396969](https://code.google.com/p/ecmascript-net/issues/detail?id=96969): bitwise and shift ops evaluate operands in reverse order, contrary to ECMA-262 also avoid generating debugger c... |  |
| 09.28.2007 10:43 | 1 | 1 | 1 | Patch from Bob Jervis (bjervis@google.com):  In reading the LiveConnect spec, it looks like Mark's problem with overloading met... |  |
| 09.28.2007 08:37 | 3 | 57 | 27 | Fix bug in destructuring assignment for let expressions: e.g. "let ([x, y] = [3, 4]) {}" in a functional context, and let expre... |  |
| 09.27.2007 12:02 | 3 | 120 | 101 | Fix [bug 397036](https://code.google.com/p/ecmascript-net/issues/detail?id=97036): NPE with FEATURE\_ENHANCED\_JAVA\_ACCESS  What was going on was a java.lang.SecurityException: "Can not make a jav... |  |
| 09.27.2007 10:59 | 2 | 6 | 2 | Patch from Steve Yegge (stevey@google.com) providing access to shell for easier subclassing. |  |
| 09.21.2007 07:36 | 1 | 3 | 2 | Fix bug: Incorrect behavior for destructuring assignment in Iterator (https://bugzilla.mozilla.org/show_bug.cgi?id=397035) |  |
| 09.21.2007 06:17 | 2 | 27 | 7 | Fixed [bug 396900](https://code.google.com/p/ecmascript-net/issues/detail?id=96900) : can't do destructuring bind in a let |  |
| 09.21.2007 05:52 | 1 | 3 | 0 | Doh! Previous checking removing an unused local variable also removed a call with important side effects. |  |
| 09.18.2007 11:29 | 4 | 0 | 8 | Fix warnings for unused local variables. |  |
| 09.18.2007 09:54 | 1 | 1 | 1 | Correct spelling error in comment |  |
| 09.18.2007 09:54 | 2 | 14 | 2 | Common package names preloaded  Prior to 1.7R1, Java classes in packages starting with "java." could be referenced directly, wh... |  |
| 09.18.2007 09:46 | 1 | 1 | 1 | fix spelling error in comment |  |
| 09.12.2007 09:57 | 5 | 32 | 9 | Enable catching of all Java exceptions through a Rhino FEATURE (disabled by default). |  |
| 09.11.2007 08:30 | 1 | 17 | 2 | Fix warnings in downloaded code. |  |
| 09.11.2007 05:43 | 1 | 2 | 8 | Start running some tests for features we now implement, and skip another bad test. |  |
| 09.11.2007 05:32 | 1 | 1 | 1 | Fix javadoc warning. |  |
| 09.11.2007 05:31 | 1 | 1 | 2 | Drop use of deprecated interface. |  |
| 09.11.2007 05:29 | 1 | 14 | 14 | Fix warnings for unused private fields. |  |
| 09.11.2007 05:28 | 1 | 1 | 1 | Fix javadoc warning. |  |
| 09.07.2007 11:57 | 1 | 59 | 55 | DOM3 E4X implementation preferred  As of Rhino 1.7R1, the E4X implementation based on DOM3 is now preferred over the XMLBeans i... |  |
| 09.07.2007 07:14 | 1 | 0 | 0 | Now tracking changes through Rhino documentation on MDC, so no need to use this file. |  |
| 09.06.2007 13:11 | 2 | 28 | 2 | Fix bug: scope of initializer in for statement should be outside of the scope introduced by the for. |  |
| 09.06.2007 13:08 | 1 | 1 | 1 | small tweak to commented-out debug code |  |
| 08.31.2007 13:49 | 6 | 208 | 129 | We want to suppress strict mode warnings for undefined property o.p for the following constructs: typeof o.p, if (o.p), if (!o.... |  |
| 08.31.2007 13:46 | 1 | 1 | 1 | Fix typo in error message. |  |
| 08.31.2007 06:11 | 1 | 10 | 6 | Wrapped Java objects won't have "toSource" and will report errors for get()s of nonexistent name, so use has() first |  |
| 08.31.2007 05:47 | 10 | 4433 | 4433 | Fix whitespace to match rest of Rhino |  |
| 08.31.2007 05:30 | 4 | 31 | 24 | Fix reported NPE on dereference of lib member variable by moving initialization into the constructors. |  |
| 08.30.2007 06:53 | 2 | 4 | 5 | Remove duplicate line number member variable. |  |
| 08.30.2007 06:48 | 1 | 2 | 1 | **No need to report both an error to the console and throw and exception.** Prettier message for uncaught EvaluatorExceptions |  |
| 08.30.2007 06:45 | 2 | 2 | 2 | fix spelling error in comment |  |
| 08.30.2007 06:43 | 3 | 54 | 12 | Fix bug https://bugzilla.mozilla.org/show_bug.cgi?id=393848: Need better error message for methods that exceed 64K |  |
| 08.24.2007 13:17 | 1 | 1 | 1 | nit: add missing space |  |
| 08.24.2007 08:01 | 1 | 2 | 3 | Fix bug: syntax error on legal construct: var evens = [for (i in range(0, 21)) if (i % 2 == 0)](i.md); |  |
| 08.23.2007 07:46 | 13 | 38 | 41 | Fix a bunch of warnings, mostly javadoc. |  |
| 08.21.2007 06:05 | 2 | 0 | 0 | Tests for fix for [bug 392481](https://code.google.com/p/ecmascript-net/issues/detail?id=92481). Contributed by donnamalayeri@google.com. |  |
| 08.21.2007 05:59 | 3 | 70 | 13 | Fix [bug 392481](https://code.google.com/p/ecmascript-net/issues/detail?id=92481) - Feature request: selectively allowing access to non-public Java methods and fields |  |
| 08.20.2007 13:38 | 2 | 5 | 2 | Fix warning due to member hiding a superclass member. |  |
| 08.20.2007 13:37 | 1 | 3 | 0 | Skip bad test that will occaisionally fail due to changes in system clock |  |
| 08.20.2007 07:16 | 14 | 114 | 140 | Fix miscellaneous Java compilation warnings. |  |
| 08.20.2007 05:57 | 2 | 41 | 20 | Add SAX ErrorHandler that throws Rhino TypeErrors and doesn't print to console for better error handling. |  |
| 08.20.2007 05:53 | 1 | 6 | 0 | Update for latest tests. |  |
| 08.20.2007 05:31 | 2 | 8 | 4 | rerun idswitch tool to remove unused label declarations |  |
| 08.20.2007 05:29 | 1 | 2 | 2 | Fix warning, spelling error in comment |  |
| 08.20.2007 05:29 | 1 | 0 | 1 | Remove unused import |  |
| 08.19.2007 17:32 | 1 | 0 | 3 | Removed unused private member. |  |
| 08.19.2007 17:30 | 2 | 11 | 2 | Fix [bug 392825](https://code.google.com/p/ecmascript-net/issues/detail?id=92825) - ClassShutter doesn't prevent access through Java reflection APIs |  |
| 08.17.2007 06:47 | 1 | 0 | 1 | Remove unused import. |  |
| 08.17.2007 06:45 | 1 | 1 | 1 | Fix spelling error in comment. |  |
| 08.16.2007 06:14 | 1 | 3 | 1 | Make sure all **Tests.class classes are picked up**|  |
| 08.15.2007 05:41 | 1 | 5 | 4 | Fix [bug 392310](https://code.google.com/p/ecmascript-net/issues/detail?id=92310) - send(undefined) on newborn generator shouldn't cause error |  |
| 08.15.2007 05:37 | 1 | 10 | 1 | Fix 392308 - bad StopIteration instanceof behavior |  |
| 08.15.2007 04:56 | 5 | 199 | 158 | Implement correct semantics of storage class (global, var, let) for destructuring assignment. |  |
| 08.10.2007 12:00 | 1 | 1 | 1 | Fix spelling error in comment. |  |
| 08.09.2007 06:23 | 1 | 3 | 0 | Add missing error message resource. |  |
| 08.08.2007 06:01 | 9 | 417 | 162 | Implement JavaScript 1.7 feature destructuring assignment. Currently does not honor the scope implied by "var [a,b] = ..." or "... |  |
| 08.08.2007 05:54 | 1 | 6 | 1 | Fix [bug 391350](https://code.google.com/p/ecmascript-net/issues/detail?id=91350) - Incorrect type inference for array and object literals |  |
| 08.08.2007 05:53 | 1 | 6 | 0 | Fix [bug 391349](https://code.google.com/p/ecmascript-net/issues/detail?id=91349) - Exception on startup on JDK 1.4 |  |
| 08.08.2007 05:48 | 1 | 10 | 12 | Consider methods named "setXxx" to define a setter for "xxx" even if they don't have a void return type. This allows use with s... |  |
| 07.26.2007 18:14 | 1 | 52 | 4 | add more passing tests |  |
| 07.26.2007 17:46 | 2 | 16 | 12 | Fix for last generator codegen bug (nested functions in generators). Patch from Roshan James <a href="[mailto:roshanj@google.com](mailto:roshanj@google.com)... |  |
| 07.26.2007 17:36 | 1 | 1 | 1 | Fix misspelling in comment. |  |
| 07.26.2007 14:48 | 10 | 820 | 159 | Implement JavaScript 1.7 generators for bytecode generation mode. Patch from Roshan James <a href='mailto:roshanj@google.com'>&... <table><thead><th>  </th></thead><tbody>
<tr><td> 07.23.2007 07:10 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Switch to javaObject in the hope that it generalizes to more cases in the future. </td><td>  </td></tr>
<tr><td> 07.21.2007 09:27 </td><td> 1 </td><td> 18 </td><td> 25 </td><td> Download junit and emma jar files from ibiblio maven repo </td><td>  </td></tr>
<tr><td> 07.21.2007 00:36 </td><td> 2 </td><td> 67 </td><td> 5 </td><td> Added JUnit test task that produces code coverage report </td><td>  </td></tr>
<tr><td> 07.21.2007 00:35 </td><td> 1 </td><td> 17 </td><td> 8 </td><td> Use skip files </td><td>  </td></tr>
<tr><td> 07.20.2007 05:37 </td><td> 1 </td><td> 20 </td><td> 5 </td><td> Update to sync with latest tests. </td><td>  </td></tr>
<tr><td> 07.20.2007 05:08 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Add missing language versions. </td><td>  </td></tr>
<tr><td> 07.20.2007 05:06 </td><td> 1 </td><td> 9 </td><td> 15 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=82098'>bug 382098</a> - E4X attribute literals broken. Patch from Adam de Boor <a href='mailto:adeboor@google.com'>&lt;adeboor@google.... </td><td>  </td></tr>
<tr><td> 07.20.2007 05:05 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=82098'>bug 382098</a> - E4X attribute literals broken. Patch from Adam de Boor <a href='mailto:adeboor@google.com'>&lt;adeboor@google.... </td><td>  </td></tr>
<tr><td> 07.20.2007 04:59 </td><td> 1 </td><td> 5 </td><td> 3 </td><td> Always need Object<a href='.md'>.md</a> rather than String<a href='.md'>.md</a> for Context.newArray(). </td><td>  </td></tr>
<tr><td> 07.18.2007 08:13 </td><td> 2 </td><td> 14 </td><td> 22 </td><td> Use "associateValue" approach to save and restore the Generator prototype for each scope rather than the kludgy former approach... </td><td>  </td></tr>
<tr><td> 07.18.2007 08:10 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Minor: Fix spelling error in comment. </td><td>  </td></tr>
<tr><td> 07.18.2007 08:09 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Minor: fix spelling errors in comment. </td><td>  </td></tr>
<tr><td> 07.18.2007 08:08 </td><td> 1 </td><td> 8 </td><td> 1 </td><td> Add special Rhino object exception defined in the catch scope that can be used to retrieve the Java exception associated wi... </td><td>  </td></tr>
<tr><td> 07.18.2007 08:04 </td><td> 1 </td><td> 3 </td><td> 3 </td><td> Minor: fix spelling mistakes in comments. </td><td>  </td></tr>
<tr><td> 07.18.2007 05:42 </td><td> 3 </td><td> 123 </td><td> 114 </td><td> Add testsrc to the distribution, and clean up some build.xml formatting. </td><td>  </td></tr>
<tr><td> 07.16.2007 06:51 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Fix one small warning. </td><td>  </td></tr>
<tr><td> 07.12.2007 08:09 </td><td> 8 </td><td> 46 </td><td> 3 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=86997'>bug 386997</a> - Need to support 'debugger' statement  Adding the 'debugger' keyword will now result in a breakpoint being hit ... </td><td>  </td></tr>
<tr><td> 07.12.2007 07:52 </td><td> 2 </td><td> 19 </td><td> 19 </td><td> Patch from Bob Jervis (bjervis@google.com):  Here is the patch for the (mostly) formatting issues in the code differences. Note... </td><td>  </td></tr>
<tr><td> 07.11.2007 09:53 </td><td> 1 </td><td> 13 </td><td> 0 </td><td> New skips of new tests. </td><td>  </td></tr>
<tr><td> 07.11.2007 09:00 </td><td> 59 </td><td> 780 </td><td> 322 </td><td> Implement block scope (let) and array comprehensions. This required significant changes to symbol table management. </td><td>  </td></tr>
<tr><td> 07.11.2007 06:55 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Switch to 1.4 as the souce and target. </td><td>  </td></tr>
<tr><td> 06.28.2007 05:52 </td><td> 2 </td><td> 7 </td><td> 4 </td><td> See <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=82340'>bug 382340</a>. Additional patch from Hannes Wallnoefer:  The varargs patch does not handle the case where a varargs method is ... </td><td>  </td></tr>
<tr><td> 06.15.2007 08:39 </td><td> 1 </td><td> 22 </td><td> 22 </td><td> Fix boolean value passed to iterator when called by runtime as a result of for..in loop. Also fix formatting. </td><td>  </td></tr>
<tr><td> 06.15.2007 05:40 </td><td> 1 </td><td> 2 </td><td> 5 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=81180'>bug 381180</a> - lookupGetter finds a function even when it should not (similarly for lookupSetter) Patch from Roshan J... </td><td>  </td></tr>
<tr><td> 06.14.2007 11:39 </td><td> 5 </td><td> 69 </td><td> 36 </td><td> There should be no "Generator" constructor. </td><td>  </td></tr>
<tr><td> 06.14.2007 07:01 </td><td> 1 </td><td> 5 </td><td> 16 </td><td> Moving documentation to MDC. Remove from distribution. </td><td>  </td></tr>
<tr><td> 06.13.2007 10:51 </td><td> 1 </td><td> 6 </td><td> 2 </td><td> Fix bug <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=80005'>Bug 380005</a>: Date to String conversion code in NativeDate class is not thread-safe. </td><td>  </td></tr>
<tr><td> 06.13.2007 09:58 </td><td> 1 </td><td> 4 </td><td> 1 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=76632'>bug 376632</a> - Documentation needed for a few of the JSC arguments </td><td>  </td></tr>
<tr><td> 06.13.2007 08:21 </td><td> 1 </td><td> 3 </td><td> 2 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=61067'>bug 361067</a>. Script objects loaded through Packages.... may not have their parent scope set, and need to account for that. </td><td>  </td></tr>
<tr><td> 06.13.2007 08:04 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Remove unneeded extra semicolon. </td><td>  </td></tr>
<tr><td> 06.13.2007 07:16 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Don't perform side effect analysis unless in strict mode. </td><td>  </td></tr>
<tr><td> 06.13.2007 07:14 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Don't report strict error messages for statements without side effects at the top level of a script. Matches SpiderMonkey behav... </td><td>  </td></tr>
<tr><td> 06.12.2007 08:34 </td><td> 6 </td><td> 139 </td><td> 105 </td><td> Add support for JavaScript 1.7 Iterators in Rhino. See <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=79377'>bug 379377</a>. </td><td>  </td></tr>
<tr><td> 06.07.2007 10:51 </td><td> 1 </td><td> 6 </td><td> 1 </td><td> Fix bug in dumpICode that caused a Kit.codeBug(). </td><td>  </td></tr>
<tr><td> 06.07.2007 10:50 </td><td> 1 </td><td> 1 </td><td> 0 </td><td> Fix unfiled bug: we were getting incorrect strict mode warning on const declarations. </td><td>  </td></tr>
<tr><td> 06.07.2007 09:01 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Errors with generators returning values should be TypeErrors. </td><td>  </td></tr>
<tr><td> 06.07.2007 08:56 </td><td> 1 </td><td> 68 </td><td> 87 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=60964'>bug 360964</a> - Native array push is really slow Fixed by implementing chaining instead of linear probing. Patch from Hannes W... </td><td>  </td></tr>
<tr><td> 06.07.2007 08:53 </td><td> 2 </td><td> 15 </td><td> 4 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=83461'>bug 383461</a> - Const redeclaration errors should be TypeErrors, not SyntaxErrors. </td><td>  </td></tr>
<tr><td> 06.07.2007 05:02 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=69342'>bug 369342</a> - LazilyLoadedCtor uses Undefined.instance as default value instead of Scriptable.NOT_FOUND. Patch from Hannes W... </td><td>  </td></tr>
<tr><td> 06.07.2007 05:00 </td><td> 4 </td><td> 89 </td><td> 56 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=73897'>Bug 373897</a> - JavaAdapter classes cannot access protected methods in superclass. Patch from Hannes Wallnoefer. </td><td>  </td></tr>
<tr><td> 06.06.2007 12:47 </td><td> 2 </td><td> 100 </td><td> 0 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=63058'>bug 363058</a> Provide JavaScript-only stack trace from RhinoException. Contribution from Hannes Wallnoefer &lt;hannes <a href='at.md'>at</a> hel... </td><td>  </td></tr>
<tr><td> 06.06.2007 08:06 </td><td> 2 </td><td> 7 </td><td> 2 </td><td> Make FEATURE_STRICT_MODE imply FEATURE_STRICT_EVAL and FEATURE_STRICT_VARS. </td><td>  </td></tr>
<tr><td> 06.06.2007 07:43 </td><td> 1 </td><td> 1 </td><td> 0 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=83356'>bug 383356</a>. Patch from Roshan James. </td><td>  </td></tr>
<tr><td> 06.06.2007 07:32 </td><td> 3 </td><td> 67 </td><td> 23 </td><td> Implement checks for generators returning values. Patch from Roshan James, roshanj@google.com. </td><td>  </td></tr>
<tr><td> 06.05.2007 11:23 </td><td> 20 </td><td> 583 </td><td> 164 </td><td> Initial checkin for Rhino 1.7. Add JavaScript 1.7 version number. Initial implementation of 1.7 generators for interpretive mod... </td><td>  </td></tr>
<tr><td> 06.04.2007 13:33 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Classify another failure </td><td>  </td></tr>
<tr><td> 06.04.2007 11:24 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> Move skip lists to the testsrc directory. </td><td>  </td></tr>
<tr><td> 06.04.2007 08:53 </td><td> 1 </td><td> 9 </td><td> 3 </td><td> Fix failure indicated by test js1_5/extensions/regress-351973.js. </td><td>  </td></tr>
<tr><td> 06.04.2007 06:46 </td><td> 3 </td><td> 46 </td><td> 18 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=74311'>bug 274311</a>: Can you add all of the shell commands to the help() menu? Patch from Roshan James <a href="<a href='mailto:roshanj@googl'>mailto:roshanj@googl</a>... </td><td>  </td></tr>
<tr><td> 06.04.2007 06:18 </td><td> 6 </td><td> 387 </td><td> 20 </td><td> More work on strict mode. <b>Support implemented for checking for inconsistent return usage. Contribution from Roshan James <a h...</b></td><td>  </td></tr>
<tr><td> 05.30.2007 09:41 </td><td> 1 </td><td> 2 </td><td> 1 </td><td> Fix jdk 1.4 compilation. </td><td>  </td></tr>
<tr><td> 05.30.2007 09:07 </td><td> 2 </td><td> 49 </td><td> 30 </td><td> Conditional build for jdk15 package. </td><td>  </td></tr>
<tr><td> 05.30.2007 08:58 </td><td> 7 </td><td> 185 </td><td> 39 </td><td> Java5 varg support:  Java5 varg methods can be called with varg style from JavaScript. The relevant changes are in MemberBox, N... </td><td>  </td></tr>
<tr><td> 05.30.2007 07:07 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Nit: fix comment </td><td>  </td></tr>
<tr><td> 05.29.2007 12:44 </td><td> 1 </td><td> 5 </td><td> 4 </td><td> Fix compile warnings. Submission from umueller@demandware.com. </td><td>  </td></tr>
<tr><td> 05.24.2007 14:10 </td><td> 1 </td><td> 4 </td><td> 11 </td><td> Revert to jsDriver.pl-compatible -l and -L options Ignore unrecognized options (rather than terminating option processing) </td><td>  </td></tr>
<tr><td> 05.24.2007 07:47 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Nit: fix typo in javadoc </td><td>  </td></tr>
<tr><td> 05.24.2007 07:17 </td><td> 1 </td><td> 2 </td><td> 1 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=81819'>bug 381819</a>. Patch from Bob Clary <a href='mailto:bclary@bclary.com'>&lt;bclary@bclary.com&gt;</a>. </td><td>  </td></tr>
<tr><td> 05.24.2007 06:45 </td><td> 1 </td><td> 3 </td><td> 3 </td><td> Add more publicly accessible name for building tests so that we can have better instructions at <a href="<a href='http://developer.mozil'>http://developer.mozil</a>... </td><td>  </td></tr>
<tr><td> 05.16.2007 05:41 </td><td> 1 </td><td> 8 </td><td> 7 </td><td> Correct behavior for enumerability of prototype properties of function objects and Function. See ECMA 15.3.5.2 and 15.3.3.1. </td><td>  </td></tr>
<tr><td> 05.15.2007 13:23 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> The "prototype" property of a function object should be enumerable. </td><td>  </td></tr>
<tr><td> 05.15.2007 10:27 </td><td> 1 </td><td> 6 </td><td> 0 </td><td> Fixing IllegalArgumentException for FEATURE_STRICT_MODE and FEATURE_WARNING_AS_ERROR </td><td>  </td></tr>
<tr><td> 05.11.2007 08:14 </td><td> 1 </td><td> 0 </td><td> 3 </td><td> Fix javadoc </td><td>  </td></tr>
<tr><td> 05.09.2007 11:39 </td><td> 13 </td><td> 33 </td><td> 14 </td><td> Remove a number of warnings by having the switch generator use label L0. </td><td>  </td></tr>
<tr><td> 05.09.2007 11:22 </td><td> 9 </td><td> 6 </td><td> 6 </td><td> Move test classes out of org.mozilla.javascript package. Updates to JsDriver to allow for loading test lists from files using '... </td><td>  </td></tr>
<tr><td> 05.02.2007 13:17 </td><td> 1 </td><td> 21 </td><td> 43 </td><td> Fix for <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=79104'>Bug 379104</a> Ð new Date(2007,5,0) should reflect May 31, 2007, not June 1, 2007 </td><td>  </td></tr>
<tr><td> 05.02.2007 09:42 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Committing fix for #376831: Function.prototype shouldn't be enumerable </td><td>  </td></tr>
<tr><td> 05.02.2007 01:03 </td><td> 1 </td><td> 0 </td><td> 8 </td><td> removed unused imports </td><td>  </td></tr>
<tr><td> 05.01.2007 18:53 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Remove unneeded ';' </td><td>  </td></tr>
<tr><td> 05.01.2007 13:31 </td><td> 1 </td><td> 20 </td><td> 18 </td><td> Fix javadoc. </td><td>  </td></tr>
<tr><td> 05.01.2007 07:11 </td><td> 12 </td><td> 257 </td><td> 28 </td><td> Partial fix for <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=78790'>Bug 378790</a> - Add JS 1.5 strict mode. Patch provided by Bob Jervis (bjervis@google.com). </td><td>  </td></tr>
<tr><td> 04.25.2007 15:32 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=78580'>bug 378580</a> </td><td>  </td></tr>
<tr><td> 04.25.2007 10:31 </td><td> 12 </td><td> 11 </td><td> 79 </td><td> Fix a bunch of warnings. </td><td>  </td></tr>
<tr><td> 04.24.2007 20:23 </td><td> 1 </td><td> 3 </td><td> 1 </td><td> Include stack traces in XML output </td><td>  </td></tr>
<tr><td> 04.24.2007 20:01 </td><td> 1 </td><td> 24 </td><td> 19 </td><td> Identify tests run in XML output format Translate text data into XML-ish (\n) line endings </td><td>  </td></tr>
<tr><td> 04.24.2007 19:50 </td><td> 2 </td><td> 148 </td><td> 53 </td><td> Test driver now also emits results in XML format for possible postprocessing (includes things like performance data, complete o... </td><td>  </td></tr>
<tr><td> 04.24.2007 14:49 </td><td> 1 </td><td> 2 </td><td> 1 </td><td> Correct the dependencies in the XMLBeans download and compilation process (so that download is not done if the xbean.jar and js... </td><td>  </td></tr>
<tr><td> 04.24.2007 14:16 </td><td> 1 </td><td> 26 </td><td> 4 </td><td> Separate compilation of JsDriver from compilation of JUnit-based tests so that JUnit is not required to compile non-JUnit tests </td><td>  </td></tr>
<tr><td> 04.24.2007 05:32 </td><td> 5 </td><td> 7 </td><td> 8 </td><td> Fix javadoc errors. </td><td>  </td></tr>
<tr><td> 04.18.2007 10:08 </td><td> 3 </td><td> 12 </td><td> 1 </td><td> Add -debug flag to shell. Will cause it to generate debug for compiled class files. </td><td>  </td></tr>
<tr><td> 04.18.2007 08:57 </td><td> 1 </td><td> 4 </td><td> 4 </td><td> Minor javadoc changes. </td><td>  </td></tr>
<tr><td> 04.17.2007 08:57 </td><td> 1 </td><td> 6 </td><td> 6 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=77777'>Bug 377777</a> - Don't lose precision on a java.lang.Long passed to a long parameter </td><td>  </td></tr>
<tr><td> 04.13.2007 17:48 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Fix crash on startup in pre 1.5 VMs when XMLBeans not available </td><td>  </td></tr>
<tr><td> 04.13.2007 17:47 </td><td> 1 </td><td> 4 </td><td> 3 </td><td> Rewording docs </td><td>  </td></tr>
<tr><td> 04.12.2007 10:25 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Add missing version option. </td><td>  </td></tr>
<tr><td> 04.12.2007 10:23 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Fix javadoc comment for version 1.6. </td><td>  </td></tr>
<tr><td> 04.10.2007 19:17 </td><td> 1 </td><td> 2 </td><td> 1 </td><td> Fix bug in which elements which looked like HTML documents would get converted to strings incorrectly </td><td>  </td></tr>
<tr><td> 04.06.2007 19:52 </td><td> 1 </td><td> 23 </td><td> 17 </td><td> Add special javaClass property on NativeJavaClass to allow access to the underlying java.lang.Class instance. </td><td>  </td></tr>
<tr><td> 04.06.2007 07:48 </td><td> 1 </td><td> 8 </td><td> 1 </td><td> Insert conditional having to do with <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=69394'>bug 369394</a> while we are reviewing it </td><td>  </td></tr>
<tr><td> 04.05.2007 08:50 </td><td> 1 </td><td> 4 </td><td> 13 </td><td> Fix warnings, clean up javadoc. </td><td>  </td></tr>
<tr><td> 04.05.2007 07:59 </td><td> 2 </td><td> 6 </td><td> 3 </td><td> Fix empty statement warnings. </td><td>  </td></tr>
<tr><td> 04.05.2007 07:56 </td><td> 1 </td><td> 2 </td><td> 9 </td><td> Fix javadoc. </td><td>  </td></tr>
<tr><td> 04.05.2007 07:53 </td><td> 1 </td><td> 0 </td><td> 7 </td><td> Remove IDE-inserted comment. </td><td>  </td></tr>
<tr><td> 04.04.2007 13:52 </td><td> 18 </td><td> 627 </td><td> 61 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=70400'>Bug 370400</a> - Rhino should support const keyword Patch provided by Bob Jervis (bjervis@google.com) </td><td>  </td></tr>
<tr><td> 04.04.2007 12:02 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Fix typo in javadoc (thanks to Bob Jervis). </td><td>  </td></tr>
<tr><td> 04.03.2007 14:15 </td><td> 6 </td><td> 184 </td><td> 16 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=86455'>bug 386455</a> - Implement "get" and "set" getter/setter forms in object initializers in Rhino. <a href='https://bugzilla.mozilla.org/sh'>https://bugzilla.mozilla.org/sh</a>... </td><td>  </td></tr>
<tr><td> 03.30.2007 09:50 </td><td> 2 </td><td> 84 </td><td> 5 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=68453'>Bug 368453</a> - Implement lookupGetter and lookupSetter in Rhino Patch from Bob Jervis (bjervis@google.com). </td><td>  </td></tr>
<tr><td> 03.30.2007 06:30 </td><td> 1 </td><td> 35 </td><td> 1 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=68425'>bug 368425</a>: Implement noSuchMethod in Rhino Patch submitted by Bob Jervis (bjervis@google.com). </td><td>  </td></tr>
<tr><td> 03.29.2007 09:57 </td><td> 2 </td><td> 20 </td><td> 5 </td><td> Partial fix for <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=75682'>bug 375682</a>. This fixes the bug for Rhino's interpretive mode only. </td><td>  </td></tr>
<tr><td> 03.26.2007 12:14 </td><td> 3 </td><td> 33 </td><td> 15 </td><td> Fix bugs 359358 and 359359. Problem was that direct call optimization did not properly handle some cases with ++ and --. </td><td>  </td></tr>
<tr><td> 03.26.2007 10:59 </td><td> 2 </td><td> 335 </td><td> 335 </td><td> change to be conistent with 4 space indent in Rhino codebase. </td><td>  </td></tr>
<tr><td> 03.26.2007 10:56 </td><td> 1 </td><td> 727 </td><td> 727 </td><td> Change tabs to 4 spaces for consistency with rest of Rhino codebase. </td><td>  </td></tr>
<tr><td> 02.24.2007 14:02 </td><td> 3 </td><td> 10 </td><td> 2 </td><td> Assignment out of array range should provide a better error message </td><td>  </td></tr>
<tr><td> 02.08.2007 07:55 </td><td> 1 </td><td> 41 </td><td> 36 </td><td> Improve/fix building optional E4X components, see also <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=67707'>bug 367707</a> </td><td>  </td></tr>
<tr><td> 02.08.2007 03:30 </td><td> 1 </td><td> 7 </td><td> 5 </td><td> Fix up documentation in JsDriver.java source code </td><td>  </td></tr>
<tr><td> 02.07.2007 17:05 </td><td> 1 </td><td> 19 </td><td> 16 </td><td> Fix XMLBeans out-of-the-box build problems </td><td>  </td></tr>
<tr><td> 02.07.2007 14:14 </td><td> 1 </td><td> 6 </td><td> 1 </td><td> Fix for <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=69536'>bug 369536</a> (assignment to index of target property of XMLList overwrites attributes) </td><td>  </td></tr>
<tr><td> 02.07.2007 07:22 </td><td> 2 </td><td> 13 </td><td> 7 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=91930'>bug 291930</a> (XML constructor called with comment followed by element) </td><td>  </td></tr>
<tr><td> 02.06.2007 15:00 </td><td> 1 </td><td> 8 </td><td> 0 </td><td> Fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=88027'>bug 288027</a> (XMLList not instanceof XML) </td><td>  </td></tr>
<tr><td> 02.06.2007 09:48 </td><td> 10 </td><td> 87 </td><td> 6 </td><td> Fix license boilerplate on recent commits </td><td>  </td></tr>
<tr><td> 02.05.2007 15:41 </td><td> 1 </td><td> 13 </td><td> 6 </td><td> Fix bug in EXPECT EXIT Emulate SpiderMonkey exit code for OutOfMemoryError </td><td>  </td></tr>
<tr><td> 02.05.2007 11:08 </td><td> 1 </td><td> 21 </td><td> 3 </td><td> Don't rely on JAXP for ignoring comments (semantics are slightly different than E4X, or JRE parser has a bug, not sure which) </td><td>  </td></tr>
<tr><td> 02.05.2007 09:32 </td><td> 1 </td><td> 1 </td><td> 1 </td><td> Fix infinite-loop condition with &gt;1 generated namespace prefix </td><td>  </td></tr>
<tr><td> 02.01.2007 07:07 </td><td> 1 </td><td> 0 </td><td> 1 </td><td> setAttributes must not be prevented by READONLY attribute -- we must be able to programmatically reset it. </td><td>  </td></tr>
<tr><td> 01.28.2007 11:31 </td><td> 3 </td><td> 13 </td><td> 7 </td><td> Fix spelling errors in code, documentation </td><td>  </td></tr>
<tr><td> 01.28.2007 11:28 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Better documentation on jsdriver target </td><td>  </td></tr>
<tr><td> 01.28.2007 11:23 </td><td> 1 </td><td> 2 </td><td> 2 </td><td> Fix for <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=321967'>bug #321967</a> ("default xml namespace =" statement decompiles incorrectly) </td><td>  </td></tr>
<tr><td> 01.25.2007 07:27 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> Make sure the files in this directory are not accidentally committed to the tree by misbehaving CVS clients (like the one bundl... </td><td>  </td></tr>
<tr><td> 01.24.2007 14:15 </td><td> 6 </td><td> 155 </td><td> 297 </td><td> Fix for #353501: Add Java port of jsDriver.pl; catch some additional failure cases in JUnit test driver </td><td>  </td></tr>
<tr><td> 01.22.2007 18:21 </td><td> 1 </td><td> 3 </td><td> 1 </td><td> Fix for #367385 and #333168 defineClass's inheritance mapping is broken for abstract class subclasses </td><td>  </td></tr>
<tr><td> 01.22.2007 18:14 </td><td> 2 </td><td> 6 </td><td> 2 </td><td> Fix for #366550 Ð increment and decrement operators don't work for global vars with dynamic scopes (patch by Hannes Wallnoefer) </td><td>  </td></tr>
<tr><td> 01.22.2007 18:10 </td><td> 1 </td><td> 14 </td><td> 1 </td><td> Fix for #366550 Ð increment and decrement operators don't work for global vars with dynamic scopes </td><td>  </td></tr>
<tr><td> 01.21.2007 07:28 </td><td> 7 </td><td> 760 </td><td> 519 </td><td> Partial fix for <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=224334'>bug #224334</a>: implements defineGetter and defineSetter. </td><td>  </td></tr></tbody></table>

<h2>Status Merged (0 ChangeSets, 0 Files and 0/0 Lines changed)</h2>

<table><thead><th> <b>MaxDate</b> </th><th> <b>Files</b> </th><th> <b>Added</b> </th><th> <b>Removed</b> </th><th> <b>Description</b> </th><th> <b>Comment</b> </th></thead><tbody></tbody></table>

<h2>Status Ignored (4 ChangeSets, 512 Files and 3828/6621 Lines changed)</h2>

<table><thead><th> <b>MaxDate</b> </th><th> <b>Files</b> </th><th> <b>Added</b> </th><th> <b>Removed</b> </th><th> <b>Description</b> </th><th> <b>Comment</b> </th></thead><tbody>
<tr><td> 02.05.2007 07:24 </td><td> 33 </td><td> 3657 </td><td> 6444 </td><td> Implement E4X without Apache XMLBeans, fix <a href='https://code.google.com/p/ecmascript-net/issues/detail?id=355677'>bug #355677</a> </td><td> E4X Change </td></tr>
<tr><td> 02.05.2007 06:56 </td><td> 5 </td><td> 171 </td><td> 177 </td><td> Remove CVS keywords (at least for now) to make merging easier </td><td> See Description </td></tr>
<tr><td> 02.05.2007 06:04 </td><td> 237 </td><td> 0 </td><td> 0 </td><td> Delete accidental import of entire rhino tree under mozilla/js/rhino/mozilla/js/rhino (oops) </td><td> See Description </td></tr>
<tr><td> 02.05.2007 05:37 </td><td> 237 </td><td> 0 </td><td> 0 </td><td> Import of HEAD before big E4X merge  Status: Vendor Tag:	MOZILLA Release Tags:	RHINO_2007_02_05_08_30  N mozilla/js/rhino/mozil... </td><td> E4X Change </td></tr></tbody></table>
