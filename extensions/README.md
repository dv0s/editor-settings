# VS Code Extensions
A list of the extension I currently use in vscode.  
This file (and repo) is made with the sole purpose of keeping track of the extensions used in my editor and to quickly install them on new devices.

The command used on windows
---
Copy and paste te following code into PowerShell or Windows Terminal to export the list of installed extensions.  
```code --list-extensions | % { "code --install-extension $_" }```

The command used on Unix-based systems.
---
Copy and paste te following code into the Terminal to export the list of installed extensions.  
```code --list-extensions | xargs -L 1 echo code --install-extension```

output
---
The output given here is the currently used list of extensions.

```
code --install-extension abusaidm.html-snippets
code --install-extension amiralizadeh9480.laravel-extra-intellisense
code --install-extension austenc.laravel-blade-spacer
code --install-extension bmewburn.vscode-intelephense-client
code --install-extension bradlc.vscode-tailwindcss
code --install-extension cjhowe7.laravel-blade
code --install-extension dbaeumer.vscode-eslint
code --install-extension Equinusocio.vsc-community-material-theme
code --install-extension Equinusocio.vsc-material-theme
code --install-extension equinusocio.vsc-material-theme-icons
code --install-extension felixfbecker.php-debug
code --install-extension felixfbecker.php-intellisense
code --install-extension felixfbecker.php-pack
code --install-extension firefox-devtools.vscode-firefox-debug
code --install-extension hollowtree.vue-snippets
code --install-extension liximomo.sftp
code --install-extension MehediDracula.php-namespace-resolver
code --install-extension ms-dotnettools.csharp
code --install-extension ms-mssql.mssql
code --install-extension ms-python.python
code --install-extension ms-vscode-remote.remote-wsl
code --install-extension ms-vscode.cpptools
code --install-extension ms-vscode.sublime-keybindings
code --install-extension neilbrayfield.php-docblocker
code --install-extension onecentlin.laravel-blade
code --install-extension onecentlin.laravel5-snippets
code --install-extension patbenatar.advanced-new-file
code --install-extension PKief.material-icon-theme
code --install-extension richie5um2.vscode-sort-json
code --install-extension Tyriar.shell-launcher
code --install-extension xabikos.JavaScriptSnippets
code --install-extension xabikos.ReactSnippets
code --install-extension yzhang.markdown-all-in-one
```