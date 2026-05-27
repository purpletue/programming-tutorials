;;; learn.el --- Emacs Lisp learning guide
;;; Commentary:
;;; This file contains comments only. It is a study guide for Emacs Lisp
;;; syntax and concepts, not actual code to load. Read the notes, then
;;; write your own Emacs Lisp files separately.
;;; ------------------------------------------------------------------
;;; 1) What is Emacs Lisp?
;;; ------------------------------------------------------------------
;;; Emacs Lisp is the extension language for GNU Emacs. It is a dialect of
;;; Lisp used to configure Emacs, define commands, and extend editor
;;; behavior.
;;;
;;; Learn that Emacs Lisp programs are composed of S-expressions and that
;;; editing modes, key bindings, and packages are often written in ELisp.
;;; ------------------------------------------------------------------
;;; 2) Basic syntax
;;; ------------------------------------------------------------------
;;; ELisp uses prefix notation and parentheses.
;;;   (+ 1 2)
;;;   (setq x 5)
;;;
;;; Learn how symbols, lists, numbers, strings, and booleans appear in
;;; Lisp code.
;;; ------------------------------------------------------------------
;;; 3) Variables and assignment
;;; ------------------------------------------------------------------
;;; Use `setq` and `defvar` to assign variables.
;;;   (setq my-var 10)
;;;   (defvar my-var 10 "A documentation string.")
;;;
;;; Learn the difference between buffer-local variables and global
;;; variables, and how to use `let` for local bindings.
;;; ------------------------------------------------------------------
;;; 4) Functions and lambdas
;;; ------------------------------------------------------------------
;;; Define functions with `defun`.
;;;   (defun add (a b)
;;;     (+ a b))
;;;
;;; Learn how to write anonymous functions with `lambda` and how to
;;; pass functions as arguments.
;;; ------------------------------------------------------------------
;;; 5) Conditionals and control flow
;;; ------------------------------------------------------------------
;;; Use `if`, `when`, `unless`, and `cond` for branching.
;;;   (if (> x 0) (message "positive") (message "non-positive"))
;;;
;;; Learn how `while` loops and `cl-loop` work for repetition.
;;; ------------------------------------------------------------------
;;; 6) Lists and cons cells
;;; ------------------------------------------------------------------
;;; Lists are central in ELisp. Use `car`, `cdr`, `cons`, `append`, and
;;; `list` to construct and manipulate lists.
;;;
;;; Learn how dotted pairs and improper lists differ from regular lists.
;;; ------------------------------------------------------------------
;;; 7) Emacs-specific features
;;; ------------------------------------------------------------------
;;; Emacs Lisp interacts with the editor via buffers, windows, and faces.
;;; Common functions include `find-file`, `switch-to-buffer`, and
;;; `insert`.
;;;
;;; Learn how to use hooks, advices, commands, and key bindings.
;;; ------------------------------------------------------------------
;;; 8) Packages and libraries
;;; ------------------------------------------------------------------
;;; Use `require` and `provide` to load and define libraries.
;;; Example:
;;;   (require 'cl-lib)
;;;   (provide 'my-feature)
;;;
;;; Learn how package.el installs packages and how to organize code into
;;; modules.
;;; ------------------------------------------------------------------
;;; 9) Debugging and evaluation
;;; ------------------------------------------------------------------
;;; Evaluate expressions with `M-:` or the `*scratch*` buffer.
;;; Use `edebug`, `debug-on-error`, and `message` for debugging.
;;;
;;; Learn how to inspect variables and step through code execution.
;;; ------------------------------------------------------------------
;;; 10) Exercises to practice Emacs Lisp
;;; ------------------------------------------------------------------
;;; Write these exercises in separate .el files. Use this guide only as
;;; reference, and write the solutions yourself.
;;;
;;; Exercise 1: Hello world
;;; - Write a function that prints a message with `message`.
;;; - Call it interactively or from `eval-buffer`.
;;;
;;; Exercise 2: Variables
;;; - Define a global variable with `defvar`.
;;; - Use `setq` to change a local variable inside `let`.
;;;
;;; Exercise 3: Functions
;;; - Define a function that takes arguments and returns a value.
;;; - Write an anonymous `lambda` and call it.
;;;
;;; Exercise 4: Conditionals
;;; - Write an `if` expression that checks a variable.
;;; - Use `cond` for multiple branches.
;;;
;;; Exercise 5: List manipulation
;;; - Create a list and access its elements.
;;; - Use `cons`, `car`, and `cdr`.
;;;
;;; Exercise 6: Editor interaction
;;; - Write a function that inserts text into the current buffer.
;;; - Bind it to a key with `global-set-key`.
;;;
;;; Exercise 7: Hooks and modes
;;; - Add a function to a hook like `text-mode-hook`.
;;; - Define a simple minor mode or command.
;;;
;;; Exercise 8: Package structure
;;; - Create a small library with `provide`.
;;; - Use `require` to load it from another file.
;;; ------------------------------------------------------------------
;;; 11) Learning tips
;;; ------------------------------------------------------------------
;;; Start small and test expressions incrementally.
;;; Use Emacs help with `C-h f`, `C-h v`, and `C-h k`.
;;; Keep your ELisp readable and avoid global side effects when possible.
;;; End of Emacs Lisp learning guide.
