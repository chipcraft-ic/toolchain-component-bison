# AT_BISON_OPTION_PUSHDEFS/AT_BISON_OPTION_POPDEFS

These two macros must be given the (main) directives so that they
define a number of other macros to:
- what the language is (so what compiler tool chain to use, what
  definition of yylex/yyerror, etc.)
- what skeleton is used

# Keywords
The following keywords are used to label tests.  Please follow them
and avoid creating synonyms.
- action
- api.value.type
- c++
- cex: counterexamples.
- d: d language
- deprec: deprecated features.
- diagnostics
- glr
- graph
- java
- lac
- %merge
- multistart
- push
- report
- %union
- variant

# Calculator
The grammar features several special directives:
- `!!` YYERROR
- `!+` YYACCEPT
- `!-` YYABORT
- `!*` YYNOMEM