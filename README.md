# rls-vscode-server
VS Code language server wrapper for RLS.

# Overview
Visual Studio Code has two elements to most language validation/build plugins: the client that reports language events to the user, and the server that actually evaluates documents to build the code and generate errors and warnings if the code is invalid. It is possible to put the server code in the client plugin, but it doesn't seem to line up with VSC's design expectations.