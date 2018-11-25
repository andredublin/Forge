### 2.2.0 - 2018-01-11
* Add FAKE into build group instead Main group
* Add list projects by folder command
* Add checking validity of renamed files

### 2.1.0 - 2017-10-26
* Handle call without and command
* Fix add above/below
* Resolve BadImageFormatException on Mono
* Numbered templates
* Added argument for CopyToOutputDirectory setting

### 2.0.0 - 2017-09-13
* **This is not backward compatible change**
* Update ProjectSystem to support SDK based project files
* Update templates to use SDK based project files
* Move templates to https://github.com/fsharp-editing/forge-templates
* Update generated FAKE script
* Infrastructure changes
* Include `.vscode` folder
* Remove interactive mode
* Add support for solution level content in templates (`_content`)
* Multiple small fixes

### 1.4.2 - 2017-06-03
* Add support for `FORGE_TEMPLATE_DIR` environment variable
* Fix error when adding a file to a project with no files

### 1.4.1 - 2017-03-16
* Fix where path has spaces
* Check validity of new project name and project directory
* Paket.Init function replace Copy

### 1.4.0 - 2017-01-21
* Change `update` into `update-version`

### 1.3.3 - 2017-01-05
* Make build.sh executable and fix line endings

### 1.3.2 - 2016-12-28
* Fix file rename command

### 1.3.1 - 2016-12-19
* Fix bug with paths containing whitespaces and `new scaffold` command

### 1.3.0 - 2016-12-17
* Add integration with ProjectScaffold

### 1.2.1 - 2016-11-28
* Fix release

### 1.2.0 - 2016-11-26
* Add aliases
* Fix `new file` when wrong project name given.

### 1.1.3 - 2016-11-11
* Add `FSharpTargetsPath` to Project System

### 1.1.2 - 2016-11-07
* Add `new solution` command

### 1.0.1 - 2016-09-15
* Update help

### 1.0.0 - 2016-09-11
* Change command format
* Lot of fixes
* Can break stuff (or might not work)
* Add new templates system

### 0.7.0 - 2016-02-22
* Split into core and CLI
* Multiple small fixes

### 0.6.0 - 2016-02-14
* Rename to Forge

### 0.5.0 - 2016-02-10
* Run local Paket or FAKE if they are present

### 0.4.0 - 2016-02-10
* Change applications structure

### 0.3.4 - 2016-02-10
* Handle wrong template name

### 0.3.3 - 2016-01-27
* Ensure UTF-8 encoding on fsproj files

### 0.3.2 - 2016-01-22
* FAKE installed by Paket unless --no-fake flag is sepcified

### 0.3.1 - 2016-01-21
* Fix NullReferenceException when Ctr-d is entered in interactive mode

### 0.3.0 - 2016-01-19
* Add file ordering command
* Change syntax of new command
* Initialize FAKE on new project creation

### 0.2.0 - 2016-01-17
* Add file list command
* Add reference commands

### 0.1.0 - 2016-01-17
* Basic templating using F# generator templates
* Paket integration
* FAKE integration
