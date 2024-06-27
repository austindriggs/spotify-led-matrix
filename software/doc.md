# This file is stored inside the PACKAGE called "library" with other files called MODULES.
# This init file will only run only once the first time the package is imported.

# Documenting Python

This is just to document some of the things I've learned about python, specifically more focused towards project management and best practices.

## General Notes

File Structure
- In python there are PACKAGES such as my "library" and then individual MODULES inside of those packages.
- The init file inside of the package runs only once the first time the package is imported.

Conventions
- File names should be lowercase with underscores_as_spaces.
- Classes shoudld be CamelCase.

Code Structure
- Import statements should be organized at the top in order of 3rd party, built in, and then local files and relative imports.


## Sources
- [5 Tips To Organize Python Code](https://youtu.be/e9yMYdnSlUA?si=itcyDQPMNSYw2KuU) by Tech With Tim