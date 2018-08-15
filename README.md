# My pseudo SQL

A python implementation of structure query language

## Usage

***MypseudoSQL*.*Table*(*columns*)**

```
from MypseudoSQL import Table

table = Table(["col_0", "col_1", ...])

table.insert([val_0, val_1, ...])
```
## Parameters

columns: specifying the names of the table's columns 
> list

## Attributes

rows: a dataset as a row which values corresponding to table's columns
> list


## Methods
<table>
  <tr>
    <td>insert(row_values)</td>
    <td></td>
  </tr>
  <tr>
    <td>update(updates, predicate)</td>
    <td></td>
  </tr>
  <tr>
    <td>delete(predicate=lambda row: True)</td>
    <td></td>
  </tr>
  <tr>
    <td>select(keep_columns=None, additional_columns=None)</td>
    <td></td>
  </tr>
  <tr>
    <td>limit(lim)</td>
    <td></td>
  </tr>
  <tr>
    <td>where(predicate=lambda row: True)</td>
    <td></td>
  </tr>
  <tr>
    <td>group_by(group_by_columns, aggregates, having=None)</td>
    <td></td>
  </tr>
  <tr>
    <td>order_by(order)</td>
    <td></td>
  </tr>
  <tr>
    <td>join(other_table, left_join=False)</td>
    <td></td>
  </tr>
</table>


**insert**

**update**

**delete**

**select**

**limit**

**where**

**group_by**

**order_by**

**join**