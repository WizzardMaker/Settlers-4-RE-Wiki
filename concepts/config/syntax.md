# Config File Syntax

| Syntax | Definition |
| --- | --- |
| `;` | Comment |
| <center>Section</center> ||
| <pre><code>[SECTIONNAME]<br>{<br><br>}</code></pre> | A section defines the settings category the containing variables belong to.<br>The `{}` brackets have to be on a new line.<br>A file can have more than one section, but sections have to be unique across all config files |
| <center>Variables</center> ||
| `IntegerVar1 = 12345` | IntegerVar1 is set to 12345 |
| `FloatVar = 123.45` | FloatVar is set to 123.45 |
| `StringVar = "Hello world!"` | StringVar is set to "Hello world!" |
| `IntegerVar2 = <BUILDING_SAWMILL>` | IntegerVar2 is set to the value of the BUILDING_SAWMILL define |
| <center>Arrays</center>||
| `ArrayVar1[10] = 1,2,3,4,5,6,7,8,9,10,` | ArrayVar1 is set to an array with 10 entries.<br>**Arrays have to end with a `,`!** |
| `ArrayVar2[5] = <BUILDING_SAWMILL>,<BUILDING_WATCHTOWER>,<BUILDING_WOODCUTTERHUT>,<BUILDING_IRONMINE>,<BUILDING_BIGTEMPLE>,` | ArrayVar2 is set to an array with 5 entries of defines |

