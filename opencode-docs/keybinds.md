---
title: keybinds
slug: keybinds
url: https://opencode.ai/docs/zh-cn/keybinds/
source: opencode.ai
lang: zh-CN
---

# 快捷键

自定义您的快捷键。
       
OpenCode 提供了一系列快捷键，您可以通过 `tui.json` 进行自定义。

tui.json
```
{ "$schema": "https://opencode.ai/tui.json", "keybinds": { "leader": "ctrl+x", "app_exit": "ctrl+c,ctrl+d,&#x3C;leader>q", "editor_open": "&#x3C;leader>e", "theme_list": "&#x3C;leader>t", "sidebar_toggle": "&#x3C;leader>b", "scrollbar_toggle": "none", "username_toggle": "none", "status_view": "&#x3C;leader>s", "tool_details": "none", "session_export": "&#x3C;leader>x", "session_new": "&#x3C;leader>n", "session_list": "&#x3C;leader>l", "session_timeline": "&#x3C;leader>g", "session_fork": "none", "session_rename": "none", "session_share": "none", "session_unshare": "none", "session_interrupt": "escape", "session_compact": "&#x3C;leader>c", "session_child_first": "&#x3C;leader>down", "session_child_cycle": "&#x3C;leader>right", "session_child_cycle_reverse": "&#x3C;leader>left", "session_parent": "&#x3C;leader>up", "messages_page_up": "pageup,ctrl+alt+b", "messages_page_down": "pagedown,ctrl+alt+f", "messages_line_up": "ctrl+alt+y", "messages_line_down": "ctrl+alt+e", "messages_half_page_up": "ctrl+alt+u", "messages_half_page_down": "ctrl+alt+d", "messages_first": "ctrl+g,home", "messages_last": "ctrl+alt+g,end", "messages_next": "none", "messages_previous": "none", "messages_copy": "&#x3C;leader>y", "messages_undo": "&#x3C;leader>u", "messages_redo": "&#x3C;leader>r", "messages_last_user": "none", "messages_toggle_conceal": "&#x3C;leader>h", "model_list": "&#x3C;leader>m", "model_cycle_recent": "f2", "model_cycle_recent_reverse": "shift+f2", "model_cycle_favorite": "none", "model_cycle_favorite_reverse": "none", "variant_cycle": "ctrl+t", "variant_list": "none", "command_list": "ctrl+p", "agent_list": "&#x3C;leader>a", "agent_cycle": "tab", "agent_cycle_reverse": "shift+tab", "input_clear": "ctrl+c", "input_paste": "ctrl+v", "input_submit": "return", "input_newline": "shift+return,ctrl+return,alt+return,ctrl+j", "input_move_left": "left,ctrl+b", "input_move_right": "right,ctrl+f", "input_move_up": "up", "input_move_down": "down", "input_select_left": "shift+left", "input_select_right": "shift+right", "input_select_up": "shift+up", "input_select_down": "shift+down", "input_line_home": "ctrl+a", "input_line_end": "ctrl+e", "input_select_line_home": "ctrl+shift+a", "input_select_line_end": "ctrl+shift+e", "input_visual_line_home": "alt+a", "input_visual_line_end": "alt+e", "input_select_visual_line_home": "alt+shift+a", "input_select_visual_line_end": "alt+shift+e", "input_buffer_home": "home", "input_buffer_end": "end", "input_select_buffer_home": "shift+home", "input_select_buffer_end": "shift+end", "input_delete_line": "ctrl+shift+d", "input_delete_to_line_end": "ctrl+k", "input_delete_to_line_start": "ctrl+u", "input_backspace": "backspace,shift+backspace", "input_delete": "ctrl+d,delete,shift+delete", "input_undo": "ctrl+-,super+z", "input_redo": "ctrl+.,super+shift+z", "input_word_forward": "alt+f,alt+right,ctrl+right", "input_word_backward": "alt+b,alt+left,ctrl+left", "input_select_word_forward": "alt+shift+f,alt+shift+right", "input_select_word_backward": "alt+shift+b,alt+shift+left", "input_delete_word_forward": "alt+d,alt+delete,ctrl+delete", "input_delete_word_backward": "ctrl+w,ctrl+backspace,alt+backspace", "history_previous": "up", "history_next": "down", "terminal_suspend": "ctrl+z", "terminal_title_toggle": "none", "tips_toggle": "&#x3C;leader>h", "display_thinking": "none" }}
```
q&#x22;,    &#x22;editor_open&#x22;: &#x22;e&#x22;,    &#x22;theme_list&#x22;: &#x22;t&#x22;,    &#x22;sidebar_toggle&#x22;: &#x22;b&#x22;,    &#x22;scrollbar_toggle&#x22;: &#x22;none&#x22;,    &#x22;username_toggle&#x22;: &#x22;none&#x22;,    &#x22;status_view&#x22;: &#x22;s&#x22;,    &#x22;tool_details&#x22;: &#x22;none&#x22;,    &#x22;session_export&#x22;: &#x22;x&#x22;,    &#x22;session_new&#x22;: &#x22;n&#x22;,    &#x22;session_list&#x22;: &#x22;l&#x22;,    &#x22;session_timeline&#x22;: &#x22;g&#x22;,    &#x22;session_fork&#x22;: &#x22;none&#x22;,    &#x22;session_rename&#x22;: &#x22;none&#x22;,    &#x22;session_share&#x22;: &#x22;none&#x22;,    &#x22;session_unshare&#x22;: &#x22;none&#x22;,    &#x22;session_interrupt&#x22;: &#x22;escape&#x22;,    &#x22;session_compact&#x22;: &#x22;c&#x22;,    &#x22;session_child_first&#x22;: &#x22;down&#x22;,    &#x22;session_child_cycle&#x22;: &#x22;right&#x22;,    &#x22;session_child_cycle_reverse&#x22;: &#x22;left&#x22;,    &#x22;session_parent&#x22;: &#x22;up&#x22;,    &#x22;messages_page_up&#x22;: &#x22;pageup,ctrl+alt+b&#x22;,    &#x22;messages_page_down&#x22;: &#x22;pagedown,ctrl+alt+f&#x22;,    &#x22;messages_line_up&#x22;: &#x22;ctrl+alt+y&#x22;,    &#x22;messages_line_down&#x22;: &#x22;ctrl+alt+e&#x22;,    &#x22;messages_half_page_up&#x22;: &#x22;ctrl+alt+u&#x22;,    &#x22;messages_half_page_down&#x22;: &#x22;ctrl+alt+d&#x22;,    &#x22;messages_first&#x22;: &#x22;ctrl+g,home&#x22;,    &#x22;messages_last&#x22;: &#x22;ctrl+alt+g,end&#x22;,    &#x22;messages_next&#x22;: &#x22;none&#x22;,    &#x22;messages_previous&#x22;: &#x22;none&#x22;,    &#x22;messages_copy&#x22;: &#x22;y&#x22;,    &#x22;messages_undo&#x22;: &#x22;u&#x22;,    &#x22;messages_redo&#x22;: &#x22;r&#x22;,    &#x22;messages_last_user&#x22;: &#x22;none&#x22;,    &#x22;messages_toggle_conceal&#x22;: &#x22;h&#x22;,    &#x22;model_list&#x22;: &#x22;m&#x22;,    &#x22;model_cycle_recent&#x22;: &#x22;f2&#x22;,    &#x22;model_cycle_recent_reverse&#x22;: &#x22;shift+f2&#x22;,    &#x22;model_cycle_favorite&#x22;: &#x22;none&#x22;,    &#x22;model_cycle_favorite_reverse&#x22;: &#x22;none&#x22;,    &#x22;variant_cycle&#x22;: &#x22;ctrl+t&#x22;,    &#x22;variant_list&#x22;: &#x22;none&#x22;,    &#x22;command_list&#x22;: &#x22;ctrl+p&#x22;,    &#x22;agent_list&#x22;: &#x22;a&#x22;,    &#x22;agent_cycle&#x22;: &#x22;tab&#x22;,    &#x22;agent_cycle_reverse&#x22;: &#x22;shift+tab&#x22;,    &#x22;input_clear&#x22;: &#x22;ctrl+c&#x22;,    &#x22;input_paste&#x22;: &#x22;ctrl+v&#x22;,    &#x22;input_submit&#x22;: &#x22;return&#x22;,    &#x22;input_newline&#x22;: &#x22;shift+return,ctrl+return,alt+return,ctrl+j&#x22;,    &#x22;input_move_left&#x22;: &#x22;left,ctrl+b&#x22;,    &#x22;input_move_right&#x22;: &#x22;right,ctrl+f&#x22;,    &#x22;input_move_up&#x22;: &#x22;up&#x22;,    &#x22;input_move_down&#x22;: &#x22;down&#x22;,    &#x22;input_select_left&#x22;: &#x22;shift+left&#x22;,    &#x22;input_select_right&#x22;: &#x22;shift+right&#x22;,    &#x22;input_select_up&#x22;: &#x22;shift+up&#x22;,    &#x22;input_select_down&#x22;: &#x22;shift+down&#x22;,    &#x22;input_line_home&#x22;: &#x22;ctrl+a&#x22;,    &#x22;input_line_end&#x22;: &#x22;ctrl+e&#x22;,    &#x22;input_select_line_home&#x22;: &#x22;ctrl+shift+a&#x22;,    &#x22;input_select_line_end&#x22;: &#x22;ctrl+shift+e&#x22;,    &#x22;input_visual_line_home&#x22;: &#x22;alt+a&#x22;,    &#x22;input_visual_line_end&#x22;: &#x22;alt+e&#x22;,    &#x22;input_select_visual_line_home&#x22;: &#x22;alt+shift+a&#x22;,    &#x22;input_select_visual_line_end&#x22;: &#x22;alt+shift+e&#x22;,    &#x22;input_buffer_home&#x22;: &#x22;home&#x22;,    &#x22;input_buffer_end&#x22;: &#x22;end&#x22;,    &#x22;input_select_buffer_home&#x22;: &#x22;shift+home&#x22;,    &#x22;input_select_buffer_end&#x22;: &#x22;shift+end&#x22;,    &#x22;input_delete_line&#x22;: &#x22;ctrl+shift+d&#x22;,    &#x22;input_delete_to_line_end&#x22;: &#x22;ctrl+k&#x22;,    &#x22;input_delete_to_line_start&#x22;: &#x22;ctrl+u&#x22;,    &#x22;input_backspace&#x22;: &#x22;backspace,shift+backspace&#x22;,    &#x22;input_delete&#x22;: &#x22;ctrl+d,delete,shift+delete&#x22;,    &#x22;input_undo&#x22;: &#x22;ctrl+-,super+z&#x22;,    &#x22;input_redo&#x22;: &#x22;ctrl+.,super+shift+z&#x22;,    &#x22;input_word_forward&#x22;: &#x22;alt+f,alt+right,ctrl+right&#x22;,    &#x22;input_word_backward&#x22;: &#x22;alt+b,alt+left,ctrl+left&#x22;,    &#x22;input_select_word_forward&#x22;: &#x22;alt+shift+f,alt+shift+right&#x22;,    &#x22;input_select_word_backward&#x22;: &#x22;alt+shift+b,alt+shift+left&#x22;,    &#x22;input_delete_word_forward&#x22;: &#x22;alt+d,alt+delete,ctrl+delete&#x22;,    &#x22;input_delete_word_backward&#x22;: &#x22;ctrl+w,ctrl+backspace,alt+backspace&#x22;,    &#x22;history_previous&#x22;: &#x22;up&#x22;,    &#x22;history_next&#x22;: &#x22;down&#x22;,    &#x22;terminal_suspend&#x22;: &#x22;ctrl+z&#x22;,    &#x22;terminal_title_toggle&#x22;: &#x22;none&#x22;,    &#x22;tips_toggle&#x22;: &#x22;h&#x22;,    &#x22;display_thinking&#x22;: &#x22;none&#x22;  }}">

## 前导键

OpenCode 的大多数快捷键使用 `leader`（前导键）。这可以避免与终端中的其他快捷键冲突。

默认情况下，`ctrl+x` 是前导键，大多数操作需要您先按下前导键，然后再按对应的快捷键。例如，要新建一个会话，请先按 `ctrl+x`，然后按 `n`。

您不一定需要使用前导键来设置快捷键，但我们建议您这样做。

## 禁用快捷键

您可以通过将键值添加到 `tui.json` 并设置为 “none” 来禁用某个快捷键。

tui.json
```
{ "$schema": "https://opencode.ai/tui.json", "keybinds": { "session_compact": "none" }}
```

## 桌面版提示词输入快捷键

OpenCode 桌面应用的提示词输入框支持常见的 Readline/Emacs 风格文本编辑快捷键。这些快捷键为内置功能，目前无法通过 `opencode.json` 进行配置。

| 快捷键 | 操作 |
| --- | --- |
| `ctrl+a` | 移动到当前行的开头 |
| `ctrl+e` | 移动到当前行的末尾 |
| `ctrl+b` | 光标向后移动一个字符 |
| `ctrl+f` | 光标向前移动一个字符 |
| `alt+b` | 光标向后移动一个单词 |
| `alt+f` | 光标向前移动一个单词 |
| `ctrl+d` | 删除光标所在位置的字符 |
| `ctrl+k` | 删除从光标到行尾的内容 |
| `ctrl+u` | 删除从光标到行首的内容 |
| `ctrl+w` | 删除前一个单词 |
| `alt+d` | 删除后一个单词 |
| `ctrl+t` | 交换光标前后的字符 |
| `ctrl+g` | 取消弹出窗口 / 中止正在运行的响应 |

## Shift+Enter

某些终端默认不会发送带修饰键的 Enter 键。您可能需要配置终端将 `Shift+Enter` 作为转义序列发送。

### Windows Terminal

打开您的 `settings.json` 文件，路径为：

```
%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json
```

将以下内容添加到根级 `actions` 数组中：

```
"actions": [ { "command": { "action": "sendInput", "input": "\u001b[13;2u" }, "id": "User.sendInput.ShiftEnterCustom" }]
```

将以下内容添加到根级 `keybindings` 数组中：

```
"keybindings": [ { "keys": "shift+enter", "id": "User.sendInput.ShiftEnterCustom" }]
```

保存文件并重启 Windows Terminal，或打开一个新标签页。
