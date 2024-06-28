This is meant to be a universal representation of the type. A list of this organized by dependencies will be the output of the main workflow of this program. This output will be the input of language specific generators. 

This type will hold:

- Name of type
- Size
- List of dependencies (list of String paths to the sub type (this is expecting the folder names to represent namespaces or modules))
- Description
- List of fields
	- Name
	- Type
	- Collection type