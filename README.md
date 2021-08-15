# lisp-playground
A personal playground for learning common lisp

## Setup

### Roswell

Install roswell.

[roswell/roswell: intended to be a launcher for a major lisp environment that just works.](https://github.com/roswell/roswell)

```sh
# For macOS
$ brew install roswell
```

Install a lisp implementation and select default implementation.

```sh
$ ros install sbcl
$ ros use sbcl
```

Create new file and run repl

```sh
$ ros init example
$ ros example.ros

# Start REPL
$ ros run
```

Quit REPL

```sh
$ (cl-user::quit) # Or simply (quit)
```

## List of contents

- Hello World
- Atom
- List
- Function (`defun`)
- `eval`
- `quote`
- List operator
  - `first`
  - `rest`
  - `cons`
  - `append`
  - `list`
- Condition
  - `cond`
  - `if`
  - `when`
  - `unless`
  - `case`
