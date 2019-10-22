# CSharpMVC
A repo for testing and learning about the MVC architecture. I'd skip this if I was you.


## Steps taken

### Generate new MVC Project
 * `dotnet new mvc -o MvcMovie`
    - ```
        System.TypeLoadException: Could not load type of field 'McMaster.Extensions.CommandLineUtils.CommandLineApplication:_validationErrorHandler' (36) due to: Could not load  file or assembly 'System.ComponentModel.DataAnnotations, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35' or one of its dependencies.
            at OmniSharp.Stdio.StdioCommandLineApplication..ctor () [0x00000] in <7d8ca5f6aaa744258ab636eec0650bfa>:0 
            at OmniSharp.Stdio.Driver.Program+<>c__DisplayClass0_0.<Main>b__0 () [0x00006] in <a4dc2092d26e4f46a119974e65474780>:0 
            at OmniSharp.HostHelpers.Start (System.Func`1[TResult] action) [0x0001c] in <f81c459126564deb9e4a11d6c3274dfc>:0
        ```
        
 * `code -r MvcMovie`