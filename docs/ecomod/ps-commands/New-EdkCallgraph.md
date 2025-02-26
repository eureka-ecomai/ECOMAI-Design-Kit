# New-EdkCallgraph


## Synopsis

Create a callgraph model from a flowgraph description.


## Description

Converts the data from the standard input, that is expected as a flowgraph description in a specific data format, into a JSON structure, which describes a model representation of the input (the so-called callgraph).

After checking for prerequisites, the command runs these steps for the flowgraph given:

* Read the input file containing a flowgraph in specified format (default is GNU).
* Create a JSON structure which describes a proper model representation of that flowgraph.
* Write the JSON structure into an output file.


## Syntax

```
New-EdkCallgraph
    [-InputFilePath] <String>
    [-Format] <String>
    [-Name] <String>
    [-Path] <String>
```


## Examples
 
### Example 1:
```
PS C:\> New-EdkCallGraph name.ext
```
Converts the GNU formatted flowgraph in '`name.ext`', which is located in the current working directory (here: '`C:\`'), into a proper JSON structure and saves it as file named '`name.json`' in the current working directory (here: '`C:\`').

### Example 2:
```
PS C:\> New-EdkCallGraph C:\Path\To\name.ext
```
Converts the GNU formatted flowgraph in '`name.ext`', which is located in directory path '`C:\Path\To`', into a proper JSON structure and saves it as file named '`name.json`' in the current working directory (here: '`C:\`').

### Example 3:
```
PS C:\> New-EdkCallGraph filename -Format GNU
```
Converts a flowgraph that uses the GNU format.

### Example 4:
```
PS C:\> New-EdkCallGraph filename -Format POSIX
```
Converts a flowgraph that uses the POSIX format.

### Example 5:
```
PS C:\> New-EdkCallGraph filename -Format DOT
```
Converts a flowgraph that uses the DOT format.

### Example 6:
```
PS C:\> New-EdkCallGraph filename -Path C:\Path\To
```
Converts a flowgraph and save the output into directory path '`C:\Path\To`'.

### Example 7:
```
PS C:\> New-EdkCallGraph filename -Name myfilename
```
Converts a flowgraph and save the output as '`myfilename.json`'.

### Example 8:
```
PS C:\> filename | New-EdkCallGraph
```
Gets the filename of the flowgraph to be converted from the pipeline.

### Example 9:
```
PS C:\> filename1,filename2 | New-EdkCallGraph
```
Gets the filename(s) of the flowgraph(s) to be converted from the pipeline.


### Required Parameters

#### `-InputFilePath`
The name of input file to be processed. Must be an existing file, can including a relative or absolute path; if no path or a relative path is specified, the base location is the current directory.

|  |  |
|:-----|:---------|
| Position | 1 |
| Alias | - |
| Required | True |
| Type | String |
| Default Value | None |
| Accept Pipeline Input | True (ByValue) |

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

#### `-Name`
The name of output file to be generated. May *not* any kind of directory information, the default location is the current directory; if not specified, the name of the input file (without its extension) is used. The default extension '`.json`' is always appended.

|  |  |
|:-----|:---------|
| Position | Named |
| Alias | - |
| Required | False |
| Type | String |
| Default Value | The input filename excluding its extension, appended by '`.json`'. |
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

