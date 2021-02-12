# Zig Snippets

This extension provides a comprehensive and always updated set of snippets for the [Zig programming language](https://ziglang.org).

-----------------------------------------------------------------------------------------------------------
Snippets are separated into the following categories:

* Main language
* Async programming
* Zig default functions
* Std library utils
* Program templates


Main language:

| prefix             | description                         |
|:-------------------|:------------------------------------|
| ```var```          | variable declaration and definition |
| ```const```        | Constant decl                       |
| ```arr_init```     | array/sentinel init                 |
| ```list```         | anonymous list                      |
| ```fn```           | fn decl                             |
| ```fn_gen```         | generic fn decl                     |
| ```pub_fn```       | pub fn decl                         |
| ```ext_fn```       | extern fn                           |
| ```exp_fn```       | export fn                           |
| ```inl_fn```       | inline fn                           |
| ```naked_fn```        | nakedcc fn                          |
| ```block```        | block expr                          |
| ```stru_val```     | struct val                          |
| ```stru_decl```    | struct decl                         |
| ```enum```         | enum decl                           |
| ```union```        | tagged/untagged union decl          |
| ```for_v```        | for value loop                      |
| ```for_v_i```      | for value,index loop                |
| ```inl_for```   | inline for loop                     |
| ```label_for```        | labeled for loop                    |
| ```for_else```        | for else loop expr                  |
| ```while```        | while loop                          |
| ```inl_while``` | inline while loop                   |
| ```label_while```      | labeled while loop                  |
| ```while_else```      | while else loop expr                |
| ```while?```       | while optional loop                 |
| ```if```           | if expr                             |
| ```if_else```         | if else expr                        |
| ```if?```          | if optional                         |
| ```if_else?```        | if else optional                    |
| ```orelse```       | orelse expr                         |
| ```switch```       | switch expr                         |
| ```defer```        | defer block                         |
| ```errdefer```     | errdefer block                      |
| ```error```        | error decl                          |
| ```catch```        | catch error block                   |
| ```comptime```     | comptime block                      |
| ```asm```          | asm block                           |
| ```test```         | test block                          |

Async programming:

| prefix        | description   |
|:--------------|:--------------|
| ```async```   | async fn call |
| ```await```   | await frame   |
| ```suspend``` | suspend block |
| ```resume```  | resume frame  |

Zig default functions:

| prefix                               | description                                   |
|:-------------------------------------|:----------------------------------------------|
| ```overflow/{add|sub|mul|shl}With``` | Algebraic/Shift operation with overflow check |
| ```alignOf```                        | align on specific type                        |
| ```as```                             | cast value                                    |
| ```frame```                          | switching frame                               |
| ```imp```                            | import dependency                             |
| ```imp_std```                        | import standard namespace                     |
| ```typeOf```                         | type of value                                 |
| ```typeName```                       | type name of value                            |
| ```panic```                          | import dependency                             |
| ```sizeOf```                         | size of type                                  |
| ```setC```                           | set rarely call info to compiler              |
| ```compileErr```                     | compile error                                 |
| ```compileLog```                     | compile log                                   |
| ```cast```                           | fnCast function                               |
| ```bitCast```                        | value to bit cast                             |
| ```bitOff```                         | bit offset                                    |
| ```byteOff```                        | byte offset                                   |
| ```byteToSlice```                    | bytes to slice                                |
| ```memberC```                        | enum member count                             |
| ```tagName```                        | enum tag name                                 |
| ```tagType```                        | enum tag's count type                         |
| ```reflect.type_prop```              | type property (Property,ErrorSet,...)         |
| ```atomicLoad```                     | atomics: load ptr dereferenced value          |
| ```atomicRmw```                      | atomics: modify memory and return prev value  |
| ```math.fn```                        | math functions                                |

Templates:

| prefix                 | description               |
|:-----------------------|:--------------------------|
| ```arena/alloc/heap``` | std.heap.ArenaAllocator |
| ```main_template```    | Main function             |
| ```adt_template```     | Algebraic Data Type       |
| ```builder_template``` | Default build.zig builder |


***Enjoy coding faster!*** :fire:
