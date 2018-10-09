# Learning SASS & SCSS

## About

This project was created by completing [The Complete Sass & SCSS Course: From Beginner to Advanced](https://www.udemy.com/sasscourse/) by Joe Parys & Peter Sommerhoff.  This repository is intended to serve as a personal quick reference guide and not a full-fledged tutorial.  I recommend purchasing and completing [The Complete Sass & SCSS Course: From Beginner to Advanced](https://www.udemy.com/sasscourse/) to learn more.

## Notes on SASS Arithmetic

After installing SASS, you can run `sass --interactive` or `sass -i` in your terminal to see how SASS performs calculations.

### Basic Arithmetic

```
## ADDITION / SUBTRACTION:

>> 3px + 4px
7px

>> 7px - 3px
4px


======


## MULTIPLICATION:

>> 3px * 4px
12px*px

>> (3px * 4px) / 1px
12px


======


## DIVISION:

>> 8px / 4px
8px/4px

>> (8px / 4px)
2

>> (8px / 4px) * 1px
2px

---

>> $value: 6px
6px

>> $value / 2px
3

>> ($value / 2px) * 1px
3px


======


## UNIT COMPATABILITY:

>> 1in - 6px
0.9375in

---

>> 2em - 8px
SyntaxError: Incompatible units: 'px' and 'em'.
```

### Color Arithmetic

```
>> #333 + #777
#aaaaaa

>> 090807 - #030201
#060606

>> #123456 * 2
#2468ac

>> #222 * #040404
#888888

>> #888 / #080402
#112244
```
