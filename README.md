# techInfo
# VSCode Version: 1.47 Debugging Issue
# Description
A problem occurred after update to v1.47. Debugger not functioning properly.
# Advice: 
debug.javascript.usePreview: false; 
This temporary fix was recommended in this commit:
https://github.com/microsoft/vscode/issues/102166

For the new interface: "debug.javascript.usePreview” and uncheck “Use the new in-preview JavaScript debugger for Node.js and Chrome”

I hope that helps !

