# SQL

## Entry requirements

TODO, summarise what a learner should already have learnt / demonstrated
before they start this unit.

- know about fruit
- have completed [the cooking course](cooking.md)

## Exit goals

TODO, summarise what a learner would have achieved by the end of this unit.
i.e. what might fulfil the entry requirements of another unit, or what another unit
can understand if _this_ unit is listed as an entry requirement.

## Out of scope

TODO, Anything that we wish explicitly to state is _not_ within the scope of this unit.

## Detail

- DDL
  - CREATE / DROP DATABASE
  - CREATE / DROP TABLE
    - data types
      - text
      - numbers
        - in particular, integers
      - dates & times
      - boolean
      - null / not null
  - primary key
    - why?
    - how?
  - foreign key
    - why?
    - how?
  - other indexes
- DML
  - [SELECT](./select.md)
  - BEGIN / COMMIT / ROLLBACK
  - INSERT
    - single row
    - N rows
    - from a select
  - UPDATE
    - WHERE
    - SET
    - joins are possible
  - DELETE
    - DELETE FROM table WHERE ...
      - often, `WHERE id = ?`
