# Latex multicompiler
This action compiles multiple latex files in your project

## Inputs
**required** .fileToCompile in the root of your project

## Options
**-r** to create a release package in github/workspace/Documents.tar.gz

## Outputs
Result of the command latexmk -pdf -interaction=nonstopmode -f "your file"
