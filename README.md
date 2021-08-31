# sourcemod-consolecolors
Uses ANSI escape codes to print colored text in server console (LINUX ONLY PROBABLY)

Example usage:

```c
#include <sourcemod>
#include <concolors>

public void OnPluginStart()
{
    PrintToServer(ansi_cyan ... "Hello " ... ansi_bright_magenta ... "there" ... ansi_reset ... "!");
}
```
