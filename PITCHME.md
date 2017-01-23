#HSLIDE

## <span style="color:white">A PIECE OF CAKE</span>
![Image-Absolute](cake.jpeg)
#HSLIDE

## who i am ?
- dev @csw
- mainly c# and js        <!-- .element: class="fragment" -->
- lazy. i like automation <!-- .element: class="fragment" -->
- love cake               <!-- .element: class="fragment" -->

#HSLIDE

## what is cake ?

Cake (C# Make) is a cross platform build automation system with a C# DSL to do things like compiling code, copy files/folders, running unit tests, compress files and build NuGet packages.

- build automation system              <!-- .element: class="fragment" -->
- OSS project since 2014               <!-- .element: class="fragment" -->
- now part of the .net foundation      <!-- .element: class="fragment" -->
- Uses roslyn to run a c# dsl          <!-- .element: class="fragment" -->

#HSLIDE
## What is a build ?

Steps that need to be executed to get useful artifacts from source code

- restore              <!-- .element: class="fragment" -->
- clean               <!-- .element: class="fragment" -->
- build      <!-- .element: class="fragment" -->
- test          <!-- .element: class="fragment" -->
- package          <!-- .element: class="fragment" -->

#HSLIDE
## How to bake with cake ?

- take a cake file  <!-- .element: class="fragment" -->
- add args env vars at taste  <!-- .element: class="fragment" -->
- if needed enhance with preprocessor directives  <!-- .element: class="fragment" -->
- throw everything at cake.exe  <!-- .element: class="fragment" -->
- wait for roslyn or mono to compile  <!-- .element: class="fragment" -->
- see your cake executing!  <!-- .element: class="fragment" -->

#HSLIDE

## What tools are available ?

A LOT!
- Builtin
  - <span style="font-size:small">Arguments-Assembly Info-Build System-Cake-Chocolatey-Compression-Directory Operations-DNU-DotCover-DotNetBuild-DotNetCore-Environment-File Operations-Fixie-GitReleaseManager-GitReleaseNotes-GitTools-GitVersion-Globbing-HTTP Operations-ILMerge-ILRepack-Inno Setup-Logging-MSBuild-MSBuild Resource-MSTest-NSIS-NuGet-NUnit-NUnit v3-Octopus Deploy-OpenCover-Process-Release Notes-ReportGenerator-ReportUnit-ReSharper-Roundhouse-Security-Signing-SpecFlow-Text-VSTest-WiX-XBuild-XML-xUnit-xUnit v2</span>
- Addins
  - <span style="font-size:small">AndroidAppManifest-AppleSimulator-AppPacakager-AppVeyor-AutoRest-AzureStorage-CakeMail-CMake-CocoaPods-Communication-Compression-Configuration-Coveralls-Curl-Database-Deployment-DocFx-Docker-DoInDirectory-Email-Figlet-File Helpers-File Operations-FluentMigrator-FTP-Gem-Genymotion-Git-Gitter-HipChat-HockeyApp-Http-Json-Kudu-MsDeploy-Node-Npm-NuGet-Orchard-Paket-plist-Postman-Raygun-ReSharperReports-Semantic Versioning-SemVer-SendGrid-Sonar-SqlServer-Squirrel-Strong Naming-Swagger-Tfx-Twitter-Vagrant-Version Reader-VS .proj file helpers-Vsce-Watch-Webpack-Wyam-Xamarin-XCode-XDT-Yaml-Yarn</span>
  
#HSLIDE

## Why use cake ?
- familiariarity with c#
- maintainable and consistent across environments build systems
- if just 1 dev -> ctrl+shift+B
  - does not build on my machine 
  - missing tool
  - missing test runner
- Documented automated part of the process (in repo)
  - computer does not forget to run a step
  
#VSLIDE

## Why use cake ?

Cant i just use FAKE, MAKE, PSAKE, CMAKE, BAU, MSBUILD?
- another lang (good oportunity to learn)
  - but when the build fails, YOU are the one that knows how the build works
- if the same lang no mental switch is needed

#HSLIDE

## Why do i like cake ?
- non intrusive
  - Dont tell the project manager about cake
  - just show him afterwards
- just works
  - lots of builtins
- Easy to implement addins
- consistent regardless of OS

#HSLIDE

## Demo time

#HSLIDE

## Questions ?


