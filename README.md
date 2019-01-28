# SERIALIZE

Serialize provides the function serialize. It is meant to be sourced into bash or zsh (**source .../serialize** or **. .../serialize** where ... is the parent directory of serialize) and then utilized.

## USAGE

Serialize function takes only one argument and that argument specifies the variable you want to serialize (save for latter). It outputs a string that is suitable for being sourced from a file. It is intended that this string then be redirected to a file from the script that calls it.
**Example:**
> Sourced and then called (**serialize name**) from a script **where name=John** then it outputs a string name=John