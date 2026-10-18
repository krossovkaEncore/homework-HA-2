[Настройка горячих клавиш и изучение программ для переназначения клавиш и автоматизации действий пользователя..docx](https://github.com/user-attachments/files/33641150/default.docx)

---

#Requires AutoHotkey v2.0
#SingleInstance Force

; Ctrl + Alt + N — Open Notepad
^!n::Run("notepad.exe")

; Ctrl + Alt + C — Open Calculator
^!c::Run("calc.exe")

; Ctrl + Alt + E — Open File Explorer
^!e::Run("explorer.exe")

; Ctrl + Alt + P — Open Paint
^!p::Run("mspaint.exe")

; Ctrl + Alt + T — Open Windows Terminal
^!t::Run("cmd.exe")

; Ctrl + Alt + Esc — Exit the script
^!Esc::ExitApp()
