# Prettier SQL Oracle

A [Prettier](https://prettier.io/) plugin for Oracle PL/SQL.

## Table of Contents

1. [Working Notes](#working-notes)

## Working Notes

1. Install [Antlr4](https://github.com/antlr/antlr4/blob/master/doc/getting-started.md) to build lexer/parser.
1. Copy PlSqlLexer.g4 from <https://github.com/antlr/grammars-v4/blob/master/sql/plsql/PlSqlLexer.g4>.

   ```cmd
   npm run download-lexer
   ```

1. Copy PlSqlParser.g4 from <https://github.com/antlr/grammars-v4/blob/master/sql/plsql/PlSqlParser.g4>.

   ```cmd
   npm run download-parser
   ```

1. Copy JavaScript modules from <https://github.com/antlr/grammars-v4/tree/master/sql/plsql/JavaScript>.

   ```cmd
   npm run download-lexer-base
   npm run download-parser-base
   ```

1. Build lexer and parser

   ```cmd
   npm run build-parser
   npm run build-lexer
   ```
