#Requirements to Install Custom Icon
Install VSCode Extension "vscode-icons" via Marketplace - repo https://github.com/vscode-icons

#Extending VSCodeIcon with MQ2Macro Icon
1. Created Folder - based on instructions here - https://github.com/vscode-icons/vscode-icons/wiki/Custom
2. Copy included "file_type_mq2macro-icon.svg" to this folder
3. Open "vscode-icons" Settings - Command Palette -> Preferences: Open Settings(UI) -> Extensions -> vscode-icons configuration -> vscodeicons > Associations: Files -> Edit in settings.json
4. Add contents of mq2macro-icon-theme.json to the settings.json according to instructions at https://github.com/vscode-icons/vscode-icons/wiki/FineTuning
5. Ensure you have chosen the vscode-icons icon theme, and reload if neccessary.

