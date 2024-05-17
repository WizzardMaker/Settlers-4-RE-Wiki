# Config Defaults
The config system uses a list of functions and static initializers to set default values.
Config files then overwrite these values, when needed.

## Static Config Values
These values are based on the [CStaticConfigVar]() class. Their values are set during static variable initialization in the start of the program.
The main static initializer list is located in `0x0B15948` with `0x0B15C24` being the rough start of the config variables, but in no particular order.
