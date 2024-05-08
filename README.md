
![225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9](https://github.com/michredteam/ShellExecute/assets/168865716/f2fc629c-8d7f-4bf2-9acc-56a22d095092)

# ShellExecute
The purpose of this program is to interact with running processes on a Windows system.

# Limitations
The program is currently designed to interact with processes within the same user context. It does not have the capability to interact with processes in other user contexts.
The current functionality is limited to loading the shell32.dll module into the remote process and executing the ShellExecuteExW function. Modifications to the code are required to perform other operations.

# Usage

This tool allows you to launch a program from within another program. It's particularly useful in situations where you're operating in a restricted environment.

In most cases, you'll want to use 'explorer.exe' as the target program because it has the necessary functionality ('ShellExecuteExW' import) required for this tool to work.

ShellExecute.exe explorer.exe C:\Users\silen\Desktop\Malware.exe
