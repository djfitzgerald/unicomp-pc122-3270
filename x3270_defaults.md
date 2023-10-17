# x3270 Default Key Bindings
These are the default key bindings used by the x3270 emulator

| **Event**                    | **Keymap:Line** | **Actions**                                                         |
| ---------------------------- | --------------- | ------------------------------------------------------------------- |
| :<KeyPress>Multi_key         | base:1          | Compose()                                                           |
| Ctrl<ButtonPress>1           | base:2          | HandleMenu("fileMenu")                                              |
| Ctrl<ButtonPress>2           | base:3          | HandleMenu("optionsMenu")                                           |
| Ctrl<ButtonPress>3           | base:4          | HandleMenu("hostMenu", "macrosMenu")                                |
| <ButtonPress>1               | base:5          | SelectDown()                                                        |
| ~Shift Button1<MotionNotify> | base:6          | SelectMotion()                                                      |
| <ButtonPress>2               | base:7          | ignore()                                                            |
| Button2<MotionNotify>        | base:8          | ignore()                                                            |
| <ButtonRelease>2             | base:9          | insert-selection("PRIMARY")                                         |
| <ButtonPress>3               | base:10         | start-extend()                                                      |
| Button3<MotionNotify>        | base:11         | select-extend()                                                     |
| ~Shift<ButtonRelease>1       | base:12         | SelectUp("PRIMARY")                                                 |
| ~Shift<ButtonRelease>3       | base:13         | SelectUp("PRIMARY")                                                 |
| Shift<KeyPress>Insert        | base:14         | insert-selection("PRIMARY")                                         |
| :<KeyPress>Insert            | base:15         | Toggle("insertMode")                                                |
| Shift<KeyPress>Up            | base:16         | KybdSelect("Up", "PRIMARY")                                         |
| Shift<KeyPress>Down          | base:17         | KybdSelect("Down", "PRIMARY")                                       |
| Shift<KeyPress>Left          | base:18         | KybdSelect("Left", "PRIMARY")                                       |
| Shift<KeyPress>Right         | base:19         | KybdSelect("Right", "PRIMARY")                                      |
| Shift<KeyPress>F1            | base:20         | PF("13")                                                            |
| Shift<KeyPress>F2            | base:21         | PF("14")                                                            |
| Shift<KeyPress>F3            | base:22         | PF("15")                                                            |
| Shift<KeyPress>F4            | base:23         | PF("16")                                                            |
| Shift<KeyPress>F5            | base:24         | PF("17")                                                            |
| Shift<KeyPress>F6            | base:25         | PF("18")                                                            |
| Shift<KeyPress>F7            | base:26         | PF("19")                                                            |
| Shift<KeyPress>F8            | base:27         | PF("20")                                                            |
| Shift<KeyPress>F9            | base:28         | PF("21")                                                            |
| Shift<KeyPress>F10           | base:29         | PF("22")                                                            |
| Shift<KeyPress>F11           | base:30         | PF("23")                                                            |
| Shift<KeyPress>F12           | base:31         | PF("24")                                                            |
| Meta<KeyPress>F1             | base:32         | PF("13")                                                            |
| Alt<KeyPress>F1              | base:33         | PF("13")                                                            |
| Meta<KeyPress>F2             | base:34         | PF("14")                                                            |
| Alt<KeyPress>F2              | base:35         | PF("14")                                                            |
| Meta<KeyPress>F3             | base:36         | PF("15")                                                            |
| Alt<KeyPress>F3              | base:37         | PF("15")                                                            |
| Meta<KeyPress>F4             | base:38         | PF("16")                                                            |
| Alt<KeyPress>F4              | base:39         | PF("16")                                                            |
| Meta<KeyPress>F5             | base:40         | PF("17")                                                            |
| Alt<KeyPress>F5              | base:41         | PF("17")                                                            |
| Meta<KeyPress>F6             | base:42         | PF("18")                                                            |
| Alt<KeyPress>F6              | base:43         | PF("18")                                                            |
| Meta<KeyPress>F7             | base:44         | PF("19")                                                            |
| Alt<KeyPress>F7              | base:45         | PF("19")                                                            |
| Meta<KeyPress>F8             | base:46         | PF("20")                                                            |
| Alt<KeyPress>F8              | base:47         | PF("20")                                                            |
| Meta<KeyPress>F9             | base:48         | PF("21")                                                            |
| Alt<KeyPress>F9              | base:49         | PF("21")                                                            |
| Meta<KeyPress>F10            | base:50         | PF("22")                                                            |
| Alt<KeyPress>F10             | base:51         | PF("22")                                                            |
| Meta<KeyPress>F11            | base:52         | PF("23")                                                            |
| Alt<KeyPress>F11             | base:53         | PF("23")                                                            |
| Meta<KeyPress>F12            | base:54         | PF("24")                                                            |
| Alt<KeyPress>F12             | base:55         | PF("24")                                                            |
| :<KeyPress>F1                | base:56         | PF("1")                                                             |
| :<KeyPress>F2                | base:57         | PF("2")                                                             |
| :<KeyPress>F3                | base:58         | PF("3")                                                             |
| :<KeyPress>F4                | base:59         | PF("4")                                                             |
| :<KeyPress>F5                | base:60         | PF("5")                                                             |
| :<KeyPress>F6                | base:61         | PF("6")                                                             |
| :<KeyPress>F7                | base:62         | PF("7")                                                             |
| :<KeyPress>F8                | base:63         | PF("8")                                                             |
| :<KeyPress>F9                | base:64         | PF("9")                                                             |
| :<KeyPress>F10               | base:65         | PF("10")                                                            |
| :<KeyPress>F11               | base:66         | PF("11")                                                            |
| :<KeyPress>F12               | base:67         | PF("12")                                                            |
| :<KeyPress>Print             | base:68         | PrintText()                                                         |
| Alt<KeyPress>q               | base:69         | Quit()                                                              |
| :<KeyPress>dead_acute        | base:70         | Compose() Key("apostrophe")                                         |
| :<KeyPress>dead_grave        | base:71         | Compose() Key("grave")                                              |
| :<KeyPress>dead_circumflex   | base:72         | Compose() Key("asciicircum")                                        |
| :<KeyPress>dead_tilde        | base:73         | Compose() Key("asciitilde")                                         |
| :<KeyPress>dead_diaeresis    | base:74         | Compose() Key("quotedbl")                                           |
| :<KeyPress>Prior             | base:75         | Scroll("backward")                                                  |
| :<KeyPress>Next              | base:76         | Scroll("forward")                                                   |
| Shift<KeyPress>Escape        | base:77         | TemporaryKeymap("apl") TemporaryComposeMap("apl") Toggle("AplMode") |
| :Shift Ctrl<ButtonPress>1    | base.3270:1     | MouseSelect()                                                       |
| Shift<ButtonPress>1          | base.3270:2     | MoveCursor()                                                        |
| Shift<KeyPress>Return        | base.3270:3     | Newline()                                                           |
| :<KeyPress>Return            | base.3270:4     | Enter()                                                             |
| :<KeyPress>Linefeed          | base.3270:5     | Newline()                                                           |
| :<KeyPress>BackSpace         | base.3270:6     | Erase()                                                             |
| Shift<KeyPress>Tab           | base.3270:7     | BackTab()                                                           |
| : Meta<KeyPress>Left         | base.3270:8     | PreviousWord()                                                      |
| : Alt<KeyPress>Left          | base.3270:9     | PreviousWord()                                                      |
| : Meta<KeyPress>Right        | base.3270:10    | NextWord()                                                          |
| : Alt<KeyPress>Right         | base.3270:11    | NextWord()                                                          |
| : Meta<KeyPress>1            | base.3270:12    | PA("1")                                                             |
| : Alt<KeyPress>1             | base.3270:13    | PA("1")                                                             |
| : Meta<KeyPress>2            | base.3270:14    | PA("2")                                                             |
| : Alt<KeyPress>2             | base.3270:15    | PA("2")                                                             |
| : Meta<KeyPress>3            | base.3270:16    | PA("3")                                                             |
| : Alt<KeyPress>3             | base.3270:17    | PA("3")                                                             |
| Meta<KeyPress>a              | base.3270:18    | Attn()                                                              |
| Alt<KeyPress>a               | base.3270:19    | Attn()                                                              |
| Meta<KeyPress>b              | base.3270:20    | PrintWindow()                                                       |
| Alt<KeyPress>b               | base.3270:21    | PrintWindow()                                                       |
| Meta<KeyPress>c              | base.3270:22    | Clear()                                                             |
| Alt<KeyPress>c               | base.3270:23    | Clear()                                                             |
| Meta<KeyPress>d              | base.3270:24    | Delete()                                                            |
| Alt<KeyPress>d               | base.3270:25    | Delete()                                                            |
| Meta<KeyPress>e              | base.3270:26    | EraseEOF()                                                          |
| Alt<KeyPress>e               | base.3270:27    | EraseEOF()                                                          |
| Meta<KeyPress>h              | base.3270:28    | Home()                                                              |
| Alt<KeyPress>h               | base.3270:29    | Home()                                                              |
| Meta<KeyPress>i              | base.3270:30    | Set("insertMode", "true")                                           |
| Alt<KeyPress>i               | base.3270:31    | Set("insertMode", "true")                                           |
| Meta<KeyPress>l              | base.3270:32    | Redraw()                                                            |
| Alt<KeyPress>l               | base.3270:33    | Redraw()                                                            |
| Meta<KeyPress>p              | base.3270:34    | PrintText()                                                         |
| Alt<KeyPress>p               | base.3270:35    | PrintText()                                                         |
| Meta<KeyPress>r              | base.3270:36    | Reset()                                                             |
| Alt<KeyPress>r               | base.3270:37    | Reset()                                                             |
| Meta<KeyPress>u              | base.3270:38    | Unselect()                                                          |
| Alt<KeyPress>u               | base.3270:39    | Unselect()                                                          |
| Ctrl<KeyPress>a              | base.3270:40    | SelectAll("PRIMARY")                                                |
| Ctrl<KeyPress>c              | base.3270:41    | set-select("CLIPBOARD")                                             |
| Ctrl<KeyPress>u              | base.3270:42    | DeleteField()                                                       |
| Ctrl<KeyPress>v              | base.3270:43    | insert-selection("CLIPBOARD")                                       |
| Ctrl<KeyPress>w              | base.3270:44    | DeleteWord()                                                        |
| Ctrl<KeyPress>x              | base.3270:45    | Cut("CLIPBOARD")                                                    |
