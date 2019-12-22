# LYMN Programming Language

### Purpose
LYMN aims to democratize the process by which someone develops a program through natural language

```javascript
x is a Variable, with a datatype of String. x is initialized as "example".
```

--------

Lymn <source_file>

./hello_world.paragraph ""

Lymn hello_world.paragraph "{"HelloWorld": {
    "P":
  }
}"

Lymn hello_world.paragraph P=""
-----------

----------------
HelloWorld has a paragraph called P. P is initialized to "hello world".
----------------

## Grammar
The LYMN compiler reads in the grammar defining the language, and that grammar informs how the compiler works. This is opposed to hard coding a compiler based on hard coded rules

```
<statement> := <paragraph>;
<paragraph> := <sentence> {<sentence>};
<sentence> := <words> <punctuation> [<paragraph>];
<word> := {<word>} | {<word>};
<punctuation> := <comma> | <period>;
<word> := <variable> | <a> | <with> | <datatype> | <of> | <string> <is>;
```

## Automatic BNF Conversion
From the BNF defined grammar, we generate a derivation

## Derivations
The derivation generated from the BNF format, is then used to construct a parse tree directly

## Automatic Parse Tree Generation from BNF

## Walking the parse tree

# Language Concepts

# NLP
