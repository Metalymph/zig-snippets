# Zig Snippets

This extension provides a comprehensive and always updated set of snippets for the [Zig programming language](https://ziglang.org).

-----------------------------------------------------------------------------------------------------------
Snippets are separated into the following categories:

* Main language
* Async programming
* Templates

### Notes on v.2.0.0 +

Some snippets are been completly refactored to improve coding speed, others are been removed since ZLS can provides an ergonomic and always updated version of them.
I hope you'll like it and ***Enjoy coding faster!*** :fire: with this.

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

Templates:

| prefix                 | description               |
|:-----------------------|:--------------------------|
| ```arena/alloc/heap``` | std.heap.ArenaAllocator |
| ```main_template```    | Main function             |
| ```adt_template```     | Algebraic Data Type       |
| ```builder_template``` | Default build.zig builder |
