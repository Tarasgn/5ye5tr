Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\Acer> leo --help
leo : The term 'leo' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the s
pelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ leo --help
+ ~~~
    + CategoryInfo          : ObjectNotFound: (leo:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Acer> C:\Users\Acer\usr\local\bin leo --help
C:\Users\Acer\usr\local\bin : The term 'C:\Users\Acer\usr\local\bin' is not recognized as the name of a cmdlet, functio
n, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is
 correct and try again.
At line:1 char:1
+ C:\Users\Acer\usr\local\bin leo --help
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\Acer\usr\local\bin:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Acer> C:\Users\Acer\usr\local\bin\leo --help
CLI Arguments entry point - includes global parameters and subcommands

Usage: leo.exe [OPTIONS] <COMMAND>

Commands:
  account  Create a new Aleo account
  new      Create a new Leo package in a new directory
  example  Create a new Leo example package in a new directory
  build    Compile the current package as a program
  clean    Clean the output directory
  run      Run a program with input variables
  execute  Execute a program with input variables
  update   Update the Leo CLI
  help     Print this message or the help of the given subcommand(s)

Options:
  -d                 Print additional information for debugging
  -q                 Suppress CLI output
      --path <PATH>  Optional path to Leo program root folder
  -h, --help         Print help
  -V, --version      Print version
PS C:\Users\Acer> C:\Users\Acer\usr\local\bin\leo account new

  Private Key  APrivateKey1zkpEzhdiMiKfAfTHccWi5RLvJTzbVT87vHU26aEwtgL1i9h
     View Key  AViewKey1h8xmo4C7EtT6wYyvQM1wncw1H9GaKRffJsE5rgmBt8jm
      Address  aleo1rl4mwrfe6j42v685mqzsy0hyy7ft35czat6d7x335lrvfqmp6qxs8kppu9

PS C:\Users\Acer> C:\Users\Acer\usr\local\bin\leo example
Create a new Leo example package in a new directory

Usage: leo.exe example [OPTIONS] <COMMAND>

Commands:
  lottery    A public lottery program
  tictactoe  A standard tic-tac-toe game program
  token      A transparent & shielded custom token program
  help       Print this message or the help of the given subcommand(s)

Options:
  -d                 Print additional information for debugging
  -q                 Suppress CLI output
      --path <PATH>  Optional path to Leo program root folder
  -h, --help         Print help
PS C:\Users\Acer> C:\Users\Acer\usr\local\bin\leo example tictactoe
       Leo ✅ Created an Aleo program 'tictactoe' (in "C:\Users\Acer\tictactoe")
       Leo 🚀 To run the 'tictactoe' program follow the instructions at C:\Users\Acer\tictactoe\README.md
PS C:\Users\Acer> C:\Users\Acer\usr\local\bin\leo cd tictactoe
error: unrecognized subcommand 'cd'

Usage: leo.exe [OPTIONS] <COMMAND>

For more information, try '--help'.
PS C:\Users\Acer> C:\Users\Acer\usr\local\bin\leo leo run new
error: unrecognized subcommand 'leo'

Usage: leo.exe [OPTIONS] <COMMAND>

For more information, try '--help'.
PS C:\Users\Acer> C:\Users\Acer\usr\local\bin\leo\README.md leo run new
C:\Users\Acer\usr\local\bin\leo\README.md : The term 'C:\Users\Acer\usr\local\bin\leo\README.md' is not recognized as the name of a cmdlet, function, scrip
t file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ C:\Users\Acer\usr\local\bin\leo\README.md leo run new
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\Acer\u...n\leo\README.md:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md tictactoe
PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
PS C:\Users\Acer> pwd

Path
----
C:\Users\Acer


PS C:\Users\Acer>  C:\Users\Acer\usr\local\bin\leo pwd
error: unrecognized subcommand 'pwd'

Usage: leo.exe [OPTIONS] <COMMAND>

For more information, try '--help'.
PS C:\Users\Acer>  C:\Users\Acer\usr\local\bin\leo --pwd
error: unexpected argument '--pwd' found

Usage: leo.exe [OPTIONS] <COMMAND>

For more information, try '--help'.
PS C:\Users\Acer>  C:\Users\Acer\usr\local\bin\leo cd tictactoe
error: unrecognized subcommand 'cd'

Usage: leo.exe [OPTIONS] <COMMAND>

For more information, try '--help'.
PS C:\Users\Acer> cd tictactoe
PS C:\Users\Acer\tictactoe> cd leo
cd : Cannot find path 'C:\Users\Acer\tictactoe\leo' because it does not exist.
At line:1 char:1
+ cd leo
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\Acer\tictactoe\leo:String) [Set-Location], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\Acer\tictactoe> clean
clean : The term 'clean' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a pat
h was included, verify that the path is correct and try again.
At line:1 char:1
+ clean
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (clean:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Acer\tictactoe> C:\Users\Acer\usr\local\bin\leo cd
error: unrecognized subcommand 'cd'

Usage: leo.exe [OPTIONS] <COMMAND>

For more information, try '--help'.
PS C:\Users\Acer\tictactoe> C:\Users\Acer\usr\local\bin\ cd leo
C:\Users\Acer\usr\local\bin\ : The term 'C:\Users\Acer\usr\local\bin\' is not recognized as the name of a cmdlet, function, script file, or operable progra
m. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ C:\Users\Acer\usr\local\bin\ cd leo
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\Acer\usr\local\bin\:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Acer\tictactoe> git init -b main
Initialized empty Git repository in C:/Users/Acer/tictactoe/.git/
PS C:\Users\Acer\tictactoe> git add .
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'build/main.aleo', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'build/program.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'inputs/tictactoe.in', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'program.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main.leo', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\Acer\tictactoe> git commit -m "First commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Acer@DESKTOP-KRV38CE.(none)')
PS C:\Users\Acer\tictactoe> git remote add origin <REMOTE_URL>
At line:1 char:23
+ git remote add origin <REMOTE_URL>
+                       ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Acer\tictactoe> git remote -v
PS C:\Users\Acer\tictactoe> git remote add origin <REMOTE_URL>
At line:1 char:23
+ git remote add origin <REMOTE_URL>
+                       ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Acer\tictactoe> git remote -v
PS C:\Users\Acer\tictactoe> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'
PS C:\Users\Acer\tictactoe> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'
PS C:\Users\Acer\tictactoe> https://github.com/Tarasgn/5ye5tr.git
https://github.com/Tarasgn/5ye5tr.git : The term 'https://github.com/Tarasgn/5ye5tr.git' is not recognized as the name of a cmdlet, function, script file,
or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ https://github.com/Tarasgn/5ye5tr.git
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (https://github.com/Tarasgn/5ye5tr.git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Acer\tictactoe> git remote add origin <REMOTE_URL>
At line:1 char:23
+ git remote add origin <REMOTE_URL>
+                       ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Acer\tictactoe> git remote -v
PS C:\Users\Acer\tictactoe> https://github.com/Tarasgn/5ye5tr.git
https://github.com/Tarasgn/5ye5tr.git : The term 'https://github.com/Tarasgn/5ye5tr.git' is not recognized as the name of a cmdlet, function, script file,
or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ https://github.com/Tarasgn/5ye5tr.git
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (https://github.com/Tarasgn/5ye5tr.git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\Acer\tictactoe> git remote add origin <REMOTE_URL>
At line:1 char:23
+ git remote add origin <REMOTE_URL>
+                       ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Acer\tictactoe> git remote -vhttps://github.com/Tarasgn/5ye5tr.git
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

PS C:\Users\Acer\tictactoe> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'
PS C:\Users\Acer\tictactoe> PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
Get-Process : A positional parameter cannot be found that accepts argument 'C:\Users\Acer\tictactoe\README.md'.
At line:1 char:1
+ PS C:\Users\Acer> C:\Users\Acer\tictactoe\README.md leo run new
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Process], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetProcessCommand

PS C:\Users\Acer\tictactoe> C:\Users\Acer\tictactoe\README.md tictactoe
PS C:\Users\Acer\tictactoe>
