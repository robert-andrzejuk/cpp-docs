# [Building C/C++ Programs](building-c-cpp-programs.md)
# [Building C/C++ Isolated Applications and Side-by-side Assemblies](building-c-cpp-isolated-applications-and-side-by-side-assemblies.md)
## [Concepts of Isolated Applications and Side-by-side Assemblies](concepts-of-isolated-applications-and-side-by-side-assemblies.md)
## [Building C/C++ Isolated Applications](building-c-cpp-isolated-applications.md)
## [Building C/C++ Side-by-side Assemblies](building-c-cpp-side-by-side-assemblies.md)
## [How to: Build Registration-Free COM Components](how-to-build-registration-free-com-components.md)
## [How to: Build Isolated Applications to Consume COM Components](how-to-build-isolated-applications-to-consume-com-components.md)
## [Understanding Manifest Generation for C/C++ Programs](understanding-manifest-generation-for-c-cpp-programs.md)
### [Manifest Generation in Visual Studio](manifest-generation-in-visual-studio.md)
### [Manifest Generation at the Command Line](manifest-generation-at-the-command-line.md)
### [How to: Embed a Manifest Inside a C/C++ Application](how-to-embed-a-manifest-inside-a-c-cpp-application.md)
## [Troubleshooting C/C++ Isolated Applications and Side-by-side Assemblies](troubleshooting-c-cpp-isolated-applications-and-side-by-side-assemblies.md)
# [Configuring Programs for 64-Bit (Visual C++)](configuring-programs-for-64-bit-visual-cpp.md)
## [How to: Configure Visual C++ Projects to Target 64-Bit Platforms](how-to-configure-visual-cpp-projects-to-target-64-bit-platforms.md)
## [How to: Enable a 64-Bit Visual C++ Toolset on the Command Line](how-to-enable-a-64-bit-visual-cpp-toolset-on-the-command-line.md)
## [Common Visual C++ 64-bit Migration Issues](common-visual-cpp-64-bit-migration-issues.md)
## [x64 Software Conventions](x64-software-conventions.md)
### [Overview of x64 Calling Conventions](overview-of-x64-calling-conventions.md)
### [Types and Storage](types-and-storage.md)
#### [Scalar Types](scalar-types.md)
#### [Aggregates and Unions](aggregates-and-unions.md)
#### [Examples of Structure Alignment](examples-of-structure-alignment.md)
#### [Bitfields](bitfields.md)
#### [Conflicts with the x86 Compiler](conflicts-with-the-x86-compiler.md)
### [Register Usage](register-usage.md)
### [Calling Convention](calling-convention.md)
#### [Parameter Passing](parameter-passing.md)
#### [Varargs](varargs.md)
#### [Unprototyped Functions](unprototyped-functions.md)
#### [Return Values (C++)](return-values-cpp.md)
#### [Caller-Callee Saved Registers](caller-callee-saved-registers.md)
#### [Function Pointers](function-pointers.md)
#### [Floating-Point Support for Older Code (Visual C++)](floating-point-support-for-older-code-visual-cpp.md)
#### [FpCsr](fpcsr.md)
#### [MxCsr](mxcsr.md)
#### [setjmp-longjump](setjmp-longjump.md)
### [Stack Usage](stack-usage.md)
#### [Stack Allocation](stack-allocation.md)
#### [Dynamic Parameter Stack Area Construction](dynamic-parameter-stack-area-construction.md)
#### [Function Types](function-types.md)
#### [malloc Alignment](malloc-alignment.md)
#### [alloca](alloca.md)
### [Prolog and Epilog](prolog-and-epilog.md)
### [Exception Handling (x64)](exception-handling-x64.md)
#### [Unwind Data for Exception Handling, Debugger Support](unwind-data-for-exception-handling-debugger-support.md)
##### [struct RUNTIME_FUNCTION](struct-runtime-function.md)
##### [struct UNWIND_INFO](struct-unwind-info.md)
##### [struct UNWIND_CODE](struct-unwind-code.md)
##### [Chained Unwind Info Structures](chained-unwind-info-structures.md)
#### [Unwind Procedure](unwind-procedure.md)
#### [Language Specific Handler](language-specific-handler.md)
#### [Unwind Helpers for MASM](unwind-helpers-for-masm.md)
##### [Raw Pseudo Operations](raw-pseudo-operations.md)
##### [MASM Macros](masm-macros.md)
#### [Unwind Data Definitions in C](unwind-data-definitions-in-c.md)
### [Intrinsics and Inline Assembly](intrinsics-and-inline-assembly.md)
### [Image Format](image-format.md)
# [Configuring Programs for ARM Processors (Visual C++)](configuring-programs-for-arm-processors-visual-cpp.md)
## [Common Visual C++ ARM Migration Issues](common-visual-cpp-arm-migration-issues.md)
## [Overview of ARM ABI Conventions](overview-of-arm-abi-conventions.md)
## [ARM Exception Handling](arm-exception-handling.md)
# [DLLs in Visual C++](dlls-in-visual-cpp.md)
## [Walkthrough: Creating and Using a Dynamic Link Library (C++)](walkthrough-creating-and-using-a-dynamic-link-library-cpp.md)
## [Differences Between Applications and DLLs](differences-between-applications-and-dlls.md)
## [Advantages of Using DLLs](advantages-of-using-dlls.md)
## [Kinds of DLLs](kinds-of-dlls.md)
### [Non-MFC DLLs: Overview](non-mfc-dlls-overview.md)
### [Regular DLLs Statically Linked to MFC](regular-dlls-statically-linked-to-mfc.md)
### [Regular DLLs Dynamically Linked to MFC](regular-dlls-dynamically-linked-to-mfc.md)
### [Extension DLLs: Overview](extension-dlls-overview.md)
## [MFC DLL Frequently Asked Questions](dll-frequently-asked-questions.md)
## [Linking an Executable to a DLL](linking-an-executable-to-a-dll.md)
### [Determining Which Linking Method to Use](determining-which-linking-method-to-use.md)
### [Linking Implicitly](linking-implicitly.md)
### [Linking Explicitly](linking-explicitly.md)
## [Initializing a DLL](initializing-a-dll.md)
### [Initializing Regular DLLs](initializing-regular-dlls.md)
### [Initializing Extension DLLs](initializing-extension-dlls.md)
### [Initializing Non-MFC DLLs](initializing-non-mfc-dlls.md)
## [Run-Time Library Behavior](run-time-library-behavior.md)
## [LoadLibrary and AfxLoadLibrary](loadlibrary-and-afxloadlibrary.md)
## [GetProcAddress](getprocaddress.md)
## [FreeLibrary and AfxFreeLibrary](freelibrary-and-afxfreelibrary.md)
## [Search Path Used by Windows to Locate a DLL](search-path-used-by-windows-to-locate-a-dll.md)
## [Module States of a Regular DLL Dynamically Linked to MFC](module-states-of-a-regular-dll-dynamically-linked-to-mfc.md)
## [Extension DLLs](extension-dlls.md)
### [Using Database, OLE, and Sockets Extension DLLs in Regular DLLs](using-database-ole-and-sockets-extension-dlls-in-regular-dlls.md)
## [Creating a Resource-Only DLL](creating-a-resource-only-dll.md)
## [Localized Resources in MFC Applications: Satellite DLLs](localized-resources-in-mfc-applications-satellite-dlls.md)
## [Importing and Exporting](importing-and-exporting.md)
### [Importing into an Application](importing-into-an-application.md)
#### [Importing into an Application Using __declspec(dllimport)](importing-into-an-application-using-declspec-dllimport.md)
#### [Importing Function Calls Using __declspec(dllimport)](importing-function-calls-using-declspec-dllimport.md)
#### [Importing Data Using __declspec(dllimport)](importing-data-using-declspec-dllimport.md)
#### [Importing Using DEF Files](importing-using-def-files.md)
### [Exporting from a DLL](exporting-from-a-dll.md)
#### [Exporting from a DLL Using DEF Files](exporting-from-a-dll-using-def-files.md)
#### [Exporting from a DLL Using __declspec(dllexport)](exporting-from-a-dll-using-declspec-dllexport.md)
#### [Exporting and Importing Using AFX_EXT_CLASS](exporting-and-importing-using-afx-ext-class.md)
#### [Exporting C++ Functions for Use in C-Language Executables](exporting-cpp-functions-for-use-in-c-language-executables.md)
#### [Exporting C Functions for Use in C or C++ Language Executables](exporting-c-functions-for-use-in-c-or-cpp-language-executables.md)
#### [Determining Which Exporting Method to Use](determining-which-exporting-method-to-use.md)
#### [Exporting Functions from a DLL by Ordinal Rather Than by Name](exporting-functions-from-a-dll-by-ordinal-rather-than-by-name.md)
### [Mutual Imports](mutual-imports.md)
### [Importing and Exporting Inline Functions](importing-and-exporting-inline-functions.md)
## [Active Technology and DLLs](active-technology-and-dlls.md)
## [Automation in a DLL](automation-in-a-dll.md)
## [Naming Conventions for MFC DLLs](naming-conventions-for-mfc-dlls.md)
## [Calling DLL Functions from Visual Basic Applications](calling-dll-functions-from-visual-basic-applications.md)
# [Compiler Intrinsics and Assembly Language](../intrinsics/TOC.md)
# [Building on the Command Line](building-on-the-command-line.md)
## [Walkthrough: Compiling a Native C++ Program on the Command Line](walkthrough-compiling-a-native-cpp-program-on-the-command-line.md)
## [Walkthrough: Compile a C program on the command line](walkthrough-compile-a-c-program-on-the-command-line.md)
## [Walkthrough: Compiling a C++-CLI Program on the Command Line](walkthrough-compiling-a-cpp-cli-program-on-the-command-line.md)
## [Walkthrough: Compiling a C++-CX Program on the Command Line](walkthrough-compiling-a-cpp-cx-program-on-the-command-line.md)
## [Setting the Path and Environment Variables for Command-Line Builds](setting-the-path-and-environment-variables-for-command-line-builds.md)
## [NMAKE Reference](nmake-reference.md)
### [Running NMAKE](running-nmake.md)
#### [NMAKE Options](nmake-options.md)
#### [Tools.ini and NMAKE](tools-ini-and-nmake.md)
#### [Exit Codes from NMAKE](exit-codes-from-nmake.md)
### [Contents of a Makefile](contents-of-a-makefile.md)
#### [Wildcards and NMAKE](wildcards-and-nmake.md)
#### [Long Filenames in a Makefile](long-filenames-in-a-makefile.md)
#### [Comments in a Makefile](comments-in-a-makefile.md)
#### [Special Characters in a Makefile](special-characters-in-a-makefile.md)
#### [Sample Makefile](sample-makefile.md)
### [Description Blocks](description-blocks.md)
#### [Targets](targets.md)
##### [Pseudotargets](pseudotargets.md)
##### [Multiple Targets](multiple-targets.md)
##### [Cumulative Dependencies](cumulative-dependencies.md)
##### [Targets in Multiple Description Blocks](targets-in-multiple-description-blocks.md)
##### [Dependency Side Effects](dependency-side-effects.md)
#### [Dependents](dependents.md)
##### [Inferred Dependents](inferred-dependents.md)
##### [Search Paths for Dependents](search-paths-for-dependents.md)
### [Commands in a Makefile](commands-in-a-makefile.md)
#### [Command Modifiers](command-modifiers.md)
#### [Filename-Parts Syntax](filename-parts-syntax.md)
#### [Inline Files in a Makefile](inline-files-in-a-makefile.md)
##### [Specifying an Inline File](specifying-an-inline-file.md)
##### [Creating Inline File Text](creating-inline-file-text.md)
##### [Reusing Inline Files](reusing-inline-files.md)
##### [Multiple Inline Files](multiple-inline-files.md)
### [Macros and NMAKE](macros-and-nmake.md)
#### [Defining an NMAKE Macro](defining-an-nmake-macro.md)
##### [Special Characters in Macros](special-characters-in-macros.md)
##### [Null and Undefined Macros](null-and-undefined-macros.md)
##### [Where to Define Macros](where-to-define-macros.md)
##### [Precedence in Macro Definitions](precedence-in-macro-definitions.md)
#### [Using an NMAKE Macro](using-an-nmake-macro.md)
##### [Macro Substitution](macro-substitution.md)
#### [Special NMAKE Macros](special-nmake-macros.md)
##### [Filename Macros](filename-macros.md)
##### [Recursion Macros](recursion-macros.md)
##### [Command Macros and Options Macros](command-macros-and-options-macros.md)
##### [Environment-Variable Macros](environment-variable-macros.md)
### [Inference Rules](inference-rules.md)
#### [Defining a Rule](defining-a-rule.md)
##### [Search Paths in Rules](search-paths-in-rules.md)
#### [Batch-Mode Rules](batch-mode-rules.md)
#### [Predefined Rules](predefined-rules.md)
#### [Inferred Dependents and Rules](inferred-dependents-and-rules.md)
#### [Precedence in Inference Rules](precedence-in-inference-rules.md)
### [Dot Directives](dot-directives.md)
### [Makefile Preprocessing](makefile-preprocessing.md)
#### [Makefile Preprocessing Directives](makefile-preprocessing-directives.md)
#### [Expressions in Makefile Preprocessing](expressions-in-makefile-preprocessing.md)
##### [Makefile Preprocessing Operators](makefile-preprocessing-operators.md)
##### [Executing a Program in Preprocessing](executing-a-program-in-preprocessing.md)
## [MSBuild (Visual C++)](msbuild-visual-cpp.md)
### [MSBuild (Visual C++) Overview](msbuild-visual-cpp-overview.md)
### [Build System Changes](build-system-changes.md)
### [Walkthrough: Using MSBuild to Create a Visual C++ Project](walkthrough-using-msbuild-to-create-a-visual-cpp-project.md)
### [How to: Use Build Events in MSBuild Projects](how-to-use-build-events-in-msbuild-projects.md)
### [How to: Add a Custom Build Step to MSBuild Projects](how-to-add-a-custom-build-step-to-msbuild-projects.md)
### [How to: Add Custom Build Tools to MSBuild Projects](how-to-add-custom-build-tools-to-msbuild-projects.md)
### [How to: Integrate Custom Tools into the Project Properties](how-to-integrate-custom-tools-into-the-project-properties.md)
### [How to: Modify the Target Framework and Platform Toolset](how-to-modify-the-target-framework-and-platform-toolset.md)
# [Configuring Programs for Windows XP](configuring-programs-for-windows-xp.md)
# [C/C++ Building Reference](reference/TOC.md)