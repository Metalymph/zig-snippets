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
| ```fn_T```         | generic fn decl                     |
| ```pub_fn```       | pub fn decl                         |
| ```ext_fn```       | extern fn                           |
| ```exp_fn```       | export fn                           |
| ```inline```       | inline fn                           |
| ```naked```        | nakedcc fn                          |
| ```block```        | block expr                          |
| ```stru_val```     | struct val                          |
| ```stru_decl```    | struct decl                         |
| ```enum```         | enum decl                           |
| ```union```        | tagged/untagged union decl          |
| ```for_v```        | for value loop                      |
| ```for_v_i```      | for value,index loop                |
| ```for_inline```   | inline for loop                     |
| ```for_l```        | labeled for loop                    |
| ```for_e```        | for else loop expr                  |
| ```while```        | while loop                          |
| ```while_inline``` | inline while loop                   |
| ```while_l```      | labeled while loop                  |
| ```while_e```      | while else loop expr                |
| ```while?```       | while optional loop                 |
| ```if```           | if expr                             |
| ```if_e```         | if else expr                        |
| ```if?```          | if optional                         |
| ```if_e?```        | if else optional                    |
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
| ```free```                           | allocator free                                |
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

Std library utils:

| prefix                 | description             |
|:-----------------------|:------------------------|
| ```warn```             | std.debug.warn          |
| ```mem.eql```          | std.mem.eql             |
| ```std in/out/err```   | std.io in/out/err       |
| ```assert```           | std.debug.assert        |
| ```expect```           | std.testing.expect      |
| ```arena/alloc/heap``` | std.heap.ArenaAllocator |

Program templates:

| prefix                 | description               |
|:-----------------------|:--------------------------|
| ```main_template```    | Main function             |
| ```adt_template```     | Algebraic Data Type       |
| ```builder_template``` | Default build.zig builder |


***Enjoy coding faster!*** :fire:
