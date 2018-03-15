# flaggy
Flag parsing with subcommands and any-position arguments.  No required code layout like [Cobra](https://github.com/spf13/Cobra), and no third party dependencies.

# Interesting Features

- Very easy to use
- Any flag can be at at any position
- Positional subcommands
- Positional parameters
- Suggested subcommands on typo or bad command
- Nested subcommands
- Both global and subcommand specific flags
- Both global and subcommand specific positional parameters
- Customizable help template, or optional prepended/appended messages
- Flags and subcommands may have both a short and long name
- Flags can use a single dash or double dash (`--flag`, `-flag`, `-f`, `--f`)
- Flags can have `=` assignment operators, or use a space (`--flag=value`, `--flag value`)
- Flags support single quote globs with spaces (`--flag 'this is all one value'`)
- Optional but default version output with `-v` or `--version`
- Optional but default help output with `-h` or `--help`
- Optional but default show help when any invalid parameter is passed


# TODO

- help output with templating
- default flag values at time of flag creation?
- display help when subcommand missing required positionals
- display subcommands on typo
  - only when the flag is of type positional
  - only when no positional value is set
- slick readme with logo
- more UX testing
