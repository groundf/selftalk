# SelfTalk

__The small programming language SelfTalk.__

## Overview

Design notes on syntax and grammar and graphics.

    module <name> {
        module <name>
            ...
    }

    module <name> = ... .

    import <name>
    import <name> use <name>, <name>
    import <name>.<name>

    export

    <name> = { }  # class
    <name> = [ ]  # array
    <name> = ( )  # tuple

    type <name> = a | b | c
    type <name> = a . b . c

    f = [x : A y : B] : T -> { ... }

    type { }
    slot (<name>:<value>, <name>:<value>)
    port
    send |>