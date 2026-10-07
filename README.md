# Black Ops II: Sublime Syntax
A fresh coat of color for your code! Give every keyword, function, string, and operator its own little spotlight, turning messy lines of script into something clean, colorful, and much easier on the eyes. Because even your code deserves to look pretty while it works.

| Feature | Example |
| --- | --- |
| comment block | `/* comment block */`, `/@ comment documentation @/`, and `/# developer block #/`|
| comment line | `// comment line` |
| directive | `#include path\file;`, `#using_animtree( "anim" )`, and `#animtree` |
| statement | `break;`, `case 1:`, `continue;`, `default:`, `else`, `endon( ... )`, `for( ... )`, `foreach( ... )`, `if( ... )`, `in`, `notify( ... )`, `return 1;`, `switch( ... )`, `thread foo();`, `wait 1;`, `waittill( ... )`, `waittillframeend;`, `waittillmatch( ... )`, and finally `while( ... )` |
| specifier | `private foo()` or `autoexec foo()` retail |
| qualified function | `var = path\file::foo;` and `var = path\file::foo();` |
| function | `var = foo();` and yes this also handles the declaring function |
| pointer | `var = ::foo;` |
| const | `const var = 20;` retail |
| object | `self.var = 5;`, `level.var = 10;`, `game.var = 15;`, and `anim.var = 20;` is valid |
| string | `var = "string";` |
| float | `var = 1.0;` negation support: `var = -1.0;` |
| integer | `var = 20;` negation support: `var = -20;` |
| boolean | `var = true;` or `var = false;` |
| undefined | `var = undefined;` |
| operator | `+ - * / % ++ --`, `= += -= /= %= &= \|= ^= <<= >>=`, `== != < > <= >=`, `&& \|\| !`, and `& \| ^ ~ << >>` |

> [!WARNING]
> operator uses a very loose match `[+\-*\/%=<>!&|^~]`, so everything is valid.
> feel free to fork this project and add full gsc-tool support. personally never use most of those features, so they were not a priority. this includes things like do-while loops and preprocessor directives. since hardly anyone uses headers or similar functionality, i've only implemented the bare essentials needed for gsc/csc development. the primary goal was retail compatibility, so the ternary operator is also unsupported because the retail compiler does not support it.

> [!IMPORTANT]
> cooljay really likes hella men!
