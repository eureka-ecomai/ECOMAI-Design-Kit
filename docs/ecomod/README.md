# ECOMAI Modeling Toolbox (ECOMOD)

The **ECOMAI Modeling Toolbox (ECOMOD ![Logo](images/ECOMOD_MDG.bmp) )** supports the modeling in ECOMAI system development.

**ECOMOD** is neither a completely new system development process nor a new modeling language or simply a language extension. It's an approach trying to solve the problems on focusing in system development projects. **ECOMOD** as a toolbox defines a methodology consisting of activities, methods and products, and provides appropriate model objects in the form of a language extension and model templates.


## Documentation

_Quick Navigation:_ | [Introduction](docs/index.md) | [Processes](docs/processes.md) | [Methods](docs/methods.md) | [Products](docs/products.md) | [Examples](docs/examples.md) | [Reference](docs/quick-reference.md) | [Glossary](docs/glossary.md) |


## Installation

The __edktools__ works on Windows, Linux and macOS (M1 and Intel).
All platforms require at least [PowerShell 7.4 (or above)](https://learn.microsoft.com/de-de/powershell/) running.

Note: Particular attention must be paid to this under Windows, because the PowerShell edition that comes with Windows (the _Windows PowerShell_, up to version 5.1) is not sufficient.


### Minimum Requirements

On all supported systems (_Windows 8/10/11_, _Linux_, _macOS_) the prerequistes are

+ .NET Runtime 8.x ([available downloads](https://dotnet.microsoft.com/en-us/download/dotnet/8.0))
+ PowerShell 7.4 or higher ([available downloads](https://github.com/PowerShell/PowerShell/releases/latest))


### Installation on Windows systems using the setup application

For the installation of the EDK on Windows systems there is a setup application available.
Simply download the [latest release of the EDK setup application](https://github.com/eureka-ecomai/edktools/releases/download/v1.0.0.0/edk-installer-edktools.exe) from ECOMAI's GitHub space and run it to install all parts of the EDK (_please note that you need administrative privileges for a successful installation_).

__Important: Make sure that whether any Windows PowerShell nor any Microsoft PowerShell instance is running on your system before you start the setup!__

__Please note that whether the *.NET Runtime 8.x* nor the *PowerShell* is *not* part of the setup application, you have to download and install them *before* you run the EDK setup application!__

The EDK setup applications installs

+  the EDK-specific PowerShell commandlets in the subdirectory `edktools` below the PowerShell's module directory that is available for all user accounts on the computer (`C:\Program Files\PowerShell\Modules`)

+ all the resources needed by the EDK to the EDK's home folder (`C:\ProgramData\EDK`):

  + the EA template repository including all MDGs needed by ECOMAI model-based projects

  + the EA model patterns needed by the ECOMOD MDG (subdir `ModelPatterns`)

  + a ported variant of the GNU Cflow tool to be run under a 64-bit Windows OS (subdir `bin`)

  + the sample data for the Callgraph feature (subdir `Examples\callgraph-sample-data`); note: do **not** use this data directly! It's recommended copy these data to your preferred workspace.


## Commands

+ [New-EdkCallgraph](ps-commands/New-EdkCallgraph.md)
+ [ConvertTo-EdkCallgraph](ps-commands/ConvertTo-EdkCallgraph.md)

+ [New-EdkRepos](ps-commands/New-EdkRepos.md)


## Usage Scenarios

### Setup a new ECOMAI project repository

To start a new ECOMAI project you need a proper EA repository. This can be done by using the PowerShell commandlet `New-EdkRepos`.

#### Usage Examples

```
PS C:\> cd  C:\Path\To\MyWorkspace

PS C:\Path\To\MyWorkspace\> New-EdkRepos  MyFirstProject
```
Creates a new EA repository file named '`MyFirstProject.qea`' in current working directory '`C:\Path\To\MyWorkspace`'.


### Generate a Callgraph

In addition to the things you do in the development process activity _Perform AI Model Deployment_ the Callgraph can help to

* perform tuning of the _Inference Code_, or
* perform tuning the _Training Code_.


#### Usage Examples

```
PS C:\> cd  C:\Path\To\MyWorkspace

PS C:\Path\To\MyWorkspace\> New-EdkCallGraph  C:\Input\Path\flowgraph.ext  -Name callgraph
```
Converts the GNU formatted flowgraph in '`flowgraph.ext`', which is located in current working directory '`C:\Input\Path`', into a proper JSON structure and saves it as file named '`callgraph.json`' in the current working directory (here: '`C:\Path\To\MyWorkspace`').


## Example Data

Some example data files can be found in the installation directory of the edkdata package, below `ECOMAI\edkdata\examples`:

+ C source files: `sources`
+ Flowgraph files as result of a static code analysis: `flowgraphs` (_please use only the GNU variants_)
+ Callgraph JSON files ready to use with EA: `callgraphs` (_please use only the UTF8 variants_)

A simple EA repository (`Example_CallGraph-DataMining.qeax`) containing a working Data Miner model is also available in the installation directory of the edkdata package, below `ECOMAI\edkdata\examples`.


## Important Note

_None._

## Support

If you need help, feel free to contact the Sparx team by e-mail.
