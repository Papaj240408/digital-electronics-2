# digital-electronics-2
laboratore-de2

## Sample work (1st computer practice lesson)
### Sample H3 header

_This line contains_ **formatted text.**

### Lists:

- Unordered item 1
- Unordered item 2
- Unordered item 3
  - Nested item

1. Ordered item 1
2. Ordered item 2
3. Ordered item 3

### Table

|          | Column 1 | Column 2 | 
|----------|----------|----------|
|  Row 1   |Content 11|Content 21|
|  Row 2   |Content 12|Content 22|

## About
This repository contains [Digital Electronics](https://www.vut.cz/en/students/courses/detail/258369) and VHDL course files.

### Code Sample

```vhdl
entity gates is -- Sample comment
    port (
        c_i      : in std_logic;
        b_i      : in std_logic;
        a_i      : in std_logic;
        f_orig_o : out std_logic;
        f_nand_o : out std_logic;
        f_nor_o  : out std_logic
    );
end entity gates;
```
