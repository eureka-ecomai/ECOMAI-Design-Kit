# New-EdkRepos


## Synopsis

Creates an empty EA repository.


## Description

Creates a new EA repository, based on the repository template located in the EDK installation folder. All MDGs needed by ECOMAI are included.


## Syntax

```
New-EdkRepos
    [-ReposName] <String>
    [-Path] <String>
```


## Examples
 
### Example 1:
```
PS C:\> New-EdkRepos reposname
```
Creates a new EA repository with name '`reposname.qea`' located in the current directory.

### Example 2:
```
PS C:\> New-EdkRepos reposname -Path C:\Path\To
```
Creates a new EA repository with name '`reposname.qea`' located in directory path '`C:\Path\To`'.


### Required Parameters

#### `-ReposName`
The name of the EA repository file to be created. Must be a valid filename; may not exist and may not include any relative or absolute directory information.

|  |  |
|:-----|:---------|
| Position | 1 |
| Alias | - |
| Required | True |
| Type | String |
| Default Value | None |
| Accept Pipeline Input | True (ByValue) |

### Optional Parameters

#### `-Path`
The directory information where the EA repository file is stored. Must be a valid and existing path to a directory.

|  |  |
|:-----|:---------|
| Position | Named |
| Alias | - |
| Required | False |
| Type | String |
| Default Value | The current working directory. |
| Accept Pipeline Input | False |

