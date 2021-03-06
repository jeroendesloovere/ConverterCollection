# Converter Collection

--- experimental ----

## Installation

At the moment you best install this Collection in a separate folder with git clone.

After the clone is finished just run `composer install`.

To be sure the Installation went fine, execute the `bin/hercules` console command.
You should be greeted with a set of options.


example command
```php
bin/hercules spoon2twig --all --source '/home/user/Projects/moduleMaker/src'
```

### Spoon2Twig commands

#### Usage

Running the Spoon2Twig Converter.
Run every command starting with `bin/hercules spoon2twig`

>>> Currently only the --all feature is tested and working!

#### Commands

Converts every Spoon .tpl in the project
```php
-- all
```

Converts a Theme based on name
```php
--theme <themeName>
```

Converts a module based on name
```php
--module <moduleName>
```

Converts a single file in the project (relative)
```php
--file src/path/to/filename.tpl
```

#### Additional flag commands

With this command you specify the root folder
```php
--source /path/to/project/source/src
```

Force the command with overwrite options
```php
-f
```
