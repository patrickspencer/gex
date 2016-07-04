# Coding guidelines

## General

No line is more than 78 characters.
Indents are 4 spaces. No tabs used.

## Variables

One Variable Per Line:

Not:
char **a, *x;

Do:
char **a = 0;  /* add doc */
char  *x = 0;  /* add doc */


## Braces

if (1 == somevalue) {
    somevalue = 2;
}

if (condition) {
    somevalue = 2;
} else if (condition) {
    anothervalue = 3;
} else {
    finalvalue = 4;
}
