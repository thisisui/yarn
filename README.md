`yarn -v` - check version

`yarn -help` - check help

`yarn init` - init

`yarn init -y` - init with default settings

`yarn config set <PROPERTY> <VALUE>` - changes global configuration of property

`yarn config get <PROPERTY>` - get configuration of specific property

`yarn config delete <PROPERTY>` - delete custom configuration properties

`yarn add <PACKAGE_NAME>` - installs package

`yarn remove <PACKAGE_NAME>` - removes package

`yarn add <PACKAGE_NAME>@<PACKAGE_VERSION>` - installs specific version

`yarn outdated` - list outdated packages

`yarn global add <PACKAGE>` - installs package globally

`yarn global remove <PACKAGE>` - removes package globally

`yarn global bin` - path to globals

`yarn list` - list of all packages

`yarn list --depth=0` - list of top level packages only

`yarn list --pattern <PACKAGE>` - list of deps from <PACKAGE>

`yarn add <PACKAGE> -D` - install package as dev dependency

`yarn check` - checks if yarn.lock matches our dependencies

`yarn import` - creates a yarn.lock file

`yarn licences list` - shows all licences of all packages

`yarn pack` - packs all packages

`yarn cache list` - shows the list of cached packages

`yarn cache list --pattern lodash` - shows cached packages mathing the pattern

`yarn cache clean` - cleans yarn cache
