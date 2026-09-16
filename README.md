# BimQ Connection

The PythonPart enables the to take over model requiremtes defined in **BimQ** in ALLPLAN. Most of the necessary steps can be executed more or less automatically:
- **define** the required attributes
- **assign** attributes to dedicated objects
- **create** an adapted a **mapping table** for the IFC export

An additional filter allows the adoption of the attributes to the range needed for the current **project phase** or **UseCase**.

As basis for the execusion of the individual steps serves an **Excel** file exported from the **BimQ** platform with Allplan specific settings. It is usually delivered by the client.


## Installation

The PythonPart **BimQ_Connection** can be installed directly from the PluginManager in ALLPLAN. 

Alternatively, the corresponding ***.allep** package can be downloaded from the [release page](https://github.com/AnkeNiedermaier/som-attributes-public/releases). ***.allep** files are ALLPLAN internal setups that can be installed via drag and drop into the program window.

At least the version 2026 is needed to install the PythonPart.

## Installed PythonPart Scripts

If the installation was successfull, the PythonPart **BimQ_Connection.pyp** can be found
in the ALLPLAN Library:
`Office` → `Library` → `ALLPLAN GmbH` → `BimQ_Connection`

Besides the library, the PythonPart can also be found in the ActionBar in a newly created task area **BimQ Connection** inside the task **Plug-ins**.
