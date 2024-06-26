command: `help`
```
GNU bash, version 5.1.16(1)-release (x86_64-pc-linux-gnu) 
These shell commands are defined internally.  Type `help' to see this list.
Type `help name' to find out more about the function `name'.
Use `info bash' to find out more about the shell in general.
Use `man -k' or `info' to find out more about commands not in this list.

A star (*) next to a name means that the command is disabled.

 job_spec [&]                                           history [-c] [-d offset] [n] or history -anrw [file>
 (( expression ))                                       if COMMANDS; then COMMANDS; [ elif COMMANDS; then C>
 . filename [arguments]                                 jobs [-lnprs] [jobspec ...] or jobs -x command [arg>
 :                                                      kill [-s sigspec | -n signum | -sigspec] pid | jobs>
 [ arg... ]                                             let arg [arg ...]
 [[ expression ]]                                       local [option] name[=value] ...
 alias [-p] [name[=value] ... ]                         logout [n]
 bg [job_spec ...]                                      mapfile [-d delim] [-n count] [-O origin] [-s count>
 bind [-lpsvPSVX] [-m keymap] [-f filename] [-q name]>  popd [-n] [+N | -N]
 break [n]                                              printf [-v var] format [arguments]
 builtin [shell-builtin [arg ...]]                      pushd [-n] [+N | -N | dir]
 caller [expr]                                          pwd [-LP]
 case WORD in [PATTERN [| PATTERN]...) COMMANDS ;;]..>  read [-ers] [-a array] [-d delim] [-i text] [-n nch>
 cd [-L|[-P [-e]] [-@]] [dir]                           readarray [-d delim] [-n count] [-O origin] [-s cou>
 command [-pVv] command [arg ...]                       readonly [-aAf] [name[=value] ...] or readonly -p
 compgen [-abcdefgjksuv] [-o option] [-A action] [-G >  return [n]
 complete [-abcdefgjksuv] [-pr] [-DEI] [-o option] [->  select NAME [in WORDS ... ;] do COMMANDS; done
 compopt [-o|+o option] [-DEI] [name ...]               set [-abefhkmnptuvxBCHP] [-o option-name] [--] [arg>
 continue [n]                                           shift [n]
 coproc [NAME] command [redirections]                   shopt [-pqsu] [-o] [optname ...]
 declare [-aAfFgiIlnrtux] [-p] [name[=value] ...]       source filename [arguments]
 dirs [-clpv] [+N] [-N]                                 suspend [-f]
 disown [-h] [-ar] [jobspec ... | pid ...]              test [expr]
 echo [-neE] [arg ...]                                  time [-p] pipeline
 enable [-a] [-dnps] [-f filename] [name ...]           times
 eval [arg ...]                                         trap [-lp] [[arg] signal_spec ...]
 exec [-cl] [-a name] [command [argument ...]] [redir>  true
 exit [n]                                               type [-afptP] name [name ...]
 export [-fn] [name[=value] ...] or export -p           typeset [-aAfFgiIlnrtux] [-p] name[=value] ...
 false                                                  ulimit [-SHabcdefiklmnpqrstuvxPT] [limit]
 fc [-e ename] [-lnr] [first] [last] or fc -s [pat=re>  umask [-p] [-S] [mode]
 fg [job_spec]                                          unalias [-a] name [name ...]
 for NAME [in WORDS ... ] ; do COMMANDS; done           unset [-f] [-v] [-n] [name ...]
 for (( exp1; exp2; exp3 )); do COMMANDS; done          until COMMANDS; do COMMANDS; done
 function name { COMMANDS ; } or name () { COMMANDS ;>  variables - Names and meanings of some shell variab>
 getopts optstring name [arg ...]                       wait [-fn] [-p var] [id ...]
 hash [-lr] [-p pathname] [-dt] [name ...]              while COMMANDS; do COMMANDS; done
 help [-dms] [pattern ...]                              { COMMANDS ; }
```
