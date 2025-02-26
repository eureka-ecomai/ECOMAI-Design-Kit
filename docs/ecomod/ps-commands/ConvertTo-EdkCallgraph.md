# ConvertTo-EdkCallgraph


## Synopsis

Converts a flowgraph description into a callgraph model.


## Description

Converts the data from the standard input, that is expected as a flowgraph description in a specific data format, into a JSON structure, which describes a model representation of the input (the so-called callgraph).

After checking for prerequisites, the command runs these steps for the flowgraph given:

* Read the standard input (STDIN) containing a flowgraph in specified format (default is GNU).
* Create a proper JSON structure describing the construction of a model that represents the flowgraph.
* Write the JSON structure into an output file representing the so-called callgraph.


## Syntax

```
ConvertTo-EdkCallgraph
    [-Name] <String>
    [-Format] <String>
    [-Name] <String>
    [-Path] <String>
```


## Examples
 
### Example 1:
```
PS C:\> {TheStaticCodeAnalysisTool} | ConvertTo-EdkCallGraph filename
```
Converts a GNU formatted flowgraph into a proper JSON structure and saves it as file named '`filename.json`' in the current working directory (here: '`C:\`').

### Example 2:
```
PS C:\> {TheStaticCodeAnalysisTool} | ConvertTo-EdkCallGraph -Name filename
```
Converts a GNU formatted flowgraph into a proper JSON structure and saves it as file named '`filename.json`' in the current working directory (here: '`C:\`').

### Example 3:
```
PS C:\> {TheStaticCodeAnalysisTool} | ConvertTo-EdkCallGraph filename -Format GNU
```
Converts a flowgraph that uses the GNU format.

### Example 4:
```
PS C:\> {TheStaticCodeAnalysisTool} | ConvertTo-EdkCallGraph filename -Format POSIX
```
Converts a flowgraph that uses the POSIX format.

### Example 5:
```
PS C:\> {TheStaticCodeAnalysisTool} | ConvertTo-EdkCallGraph filename -Format DOT
```
Converts a flowgraph that uses the DOT format.

### Example 6:
```
PS C:\> {TheStaticCodeAnalysisTool} | ConvertTo-EdkCallGraph filename -Path C:\Absolute\Path\To
```
Converts a flowgraph and save the output file in directory '`C:\Absolute\Path\To`'.

### Example 7:
```
PS C:\> {TheStaticCodeAnalysisTool} | ConvertTo-EdkCallGraph filename -Path Relative\Path\To
```
Converts a flowgraph and save the output file in directory '`Relative\Path\To`' below the current working directory (here: '`C:\Relative\Path\To`').


### Required Parameters

#### `-Name`
The name of output file to be generated. May *not* any kind of directory information, the default location is the current directory. The default extension '`.json`' is always appended.

|  |  |
|:-----|:---------|
| Position | 1 |
| Alias | - |
| Required | True |
| Type | String |
| Default Value | None |
| Accept Pipeline Input | False |

### Optional Parameters

#### `-Format`
The format of the flowgraph to be processed. Must be one of the supported flowgraph formats (GNU, POSIX, DOT); if not specified, the GNU format is assumed as default.

|  |  |
|:-----|:---------|
| Position | Named |
| Alias | - |
| Required | False |
| Type | String |
| Default Value | None |
| Accept Pipeline Input | False |

#### `-Path`
The directory information where the output file is be stored. Must be a valid and existing path, a relative path must exist below the current directory.

|  |  |
|:-----|:---------|
| Position | Named |
| Alias | - |
| Required | False |
| Type | String |
| Default Value | The current working directory. |
| Accept Pipeline Input | False |
