TODO: 
- Add option to not follow if symlink is broken?

- Allow multiple follows in one line

- Figure out better way to handle bash/zsh issues
  - Args diff in zsh: `$func`, `$current_command`, `$args` (in the else), `$arg_array`, `$dest`
  - Can `make configure install` handle that?
  - Do I just need to check in the function and use a `iszsh` var to change commands as necessary?
