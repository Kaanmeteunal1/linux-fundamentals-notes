# 🎨 Customizing the Shell Prompt (PS1)

The **PS1 (Prompt String 1)** variable defines how the command prompt looks in the terminal. We can customize it by editing the `.bashrc` file in the home directory.

Here is a list of special characters (escape sequences) used to display information in the prompt:

| Character | Description |
| :--- | :--- |
| **`\u`** | **Current username** of the user. |
| **`\h`** | **Hostname** (computer name), up to the first dot. |
| **`\H`** | **Full hostname** (domain name included). |
| **`\w`** | **Full path** of the current working directory. |
| **`\W`** | **Base name** of the current working directory (only the current folder). |
| **`\d`** | **Date** in "Weekday Month Day" format (e.g., Mon Feb 6). |
| **`\D{format}`** | **Custom Date** format (e.g., `\D{%Y-%m-%d}` for 2024-01-20). |
| **`\t`** | Current time in **24-hour** format (HH:MM:SS). |
| **`\T`** | Current time in **12-hour** format (HH:MM:SS). |
| **`\@`** | Current time in **12-hour** format (am/pm). |
| **`\n`** | **Newline.** Moves the prompt to the next line. |
| **`\s`** | **Name of the shell** (e.g., bash). |
| **`\j`** | Number of **jobs** currently managed by the shell. |
| **`\$`** | Shows `#` if the user is root, otherwise shows `$`. |

### 💡 Example Configuration
To change your prompt, you can add a line like this to your `.bashrc` file:

```bash
# This will display: [username@hostname current-folder]$ 
export PS1="[\u@\h \W]$ "
