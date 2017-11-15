![](https://www.simplicite.io/resources//logos/logo250.png)
* * *

`Reflex` module definition
==========================



`RefDep` business object definition
-----------------------------------



### Fields

| Name                                                         | Type                                     | Req | Upd | Description                                                                      | 
| ------------------------------------------------------------ | ---------------------------------------- | --- | --- | -------------------------------------------------------------------------------- |
| `refNecessaryForTaskId` link to **`RefTask`**                | id                                       | x*  | x   | -                                                                                |
| _Ref. `refNecessaryForTaskId.refTskName`_                    | _char(50)_                               |     |     | -                                                                                |
| `refDependsOnTask` link to **`RefTask`**                     | id                                       | x*  | x   | -                                                                                |
| _Ref. `refDependsOnTask.refTskName`_                         | _char(50)_                               |     |     | -                                                                                |

### Custom actions

No custom action

`RefTask` business object definition
------------------------------------



### Fields

| Name                                                         | Type                                     | Req | Upd | Description                                                                      | 
| ------------------------------------------------------------ | ---------------------------------------- | --- | --- | -------------------------------------------------------------------------------- |
| `refTskName`                                                 | char(50)                                 | x*  | x   | -                                                                                |

### Custom actions

No custom action

