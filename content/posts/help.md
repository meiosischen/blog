---
title: "Emacs常用快捷键"
lastmod: 2024-09-14T13:43:00+08:00
tags: ["$2"]
categories: ["$3"]
draft: false
toc: true
---

| Functions                      | Keys                                      | Section | ID    | Comments                       |
|-------------------------------:|:------------------------------------------|:-------:|:-----:|--------------------------------|
| 宏展开                         | (macroexpand '(defun xxx ..))             |         |       |                                |
| view echo-area messages        | C-h e / F1 e                              | Emacs   | E001  | 切换至Message缓冲区            |
| eval in minibuf                | M-:                                       | Emacs   | E002  |                                |
| run shell                      | M-!                                       | Emacs   | E003  |                                |
| jump to begin/end of paragraph | M-{ / M-}                                 | Emacs   | E004  | helpful to eval func           |
| jump to begin/end of func      | C-M-a / C-M-e                             | Emacs   | E005  | helpful to eval func           |
| switch back/forward buf        | C-x &lt;left&gt;/&lt;right&gt;            | Emacs   | E006  |                                |
| bookmark set/list              | C-x r m / C-x r l                         | Emacs   | E007  | bookmark                       |
| eval current sexpr             | C-M-x                                     | Elisp   | EL001 |                                |
| save layout                    | C-x r w [a]                               | Layout  | L001  |                                |
| load layout                    | C-x r j [a]                               | Layout  | L002  |                                |
| rename                         | C-x C-q                                   | Dir     | D001  | C-c C-c confirm                |
| org-mode                       |                                           | Org     |       |                                |
| toggle checkbox                | C-c C-x C-b                               |         | R003  | - [ ]                          |
| edit in literate               | C-c '                                     |         | R004  |                                |
| result fmt literate            | table/list/verbatim/file/html/code/silent |         | R005  | #+BEGIN_SRC ruby :results list |
| add log to headline/logbook    | C-c C-z                                   |         | R006  |                                |
| rectangle-mark-mode            |                                           | Rect    | RE006 | 矩形操作                       |
| kill                           | C-x r k                                   |         |       | 删除一个矩形并把它保存起来     |
| insert at begin                | C-x r t                                   |         |       | 在前面插入字符                 |
| delete                         | C-x r d                                   |         |       | 删除一个矩形但不把它保存起来   |
| yank                           | C-x r y                                   |         |       | 在光标位置插入最后一次删除的矩形 |
| clear                          | C-x r c                                   |         |       | 清除矩形区域的内容,并且不保存它 |
| open                           | C-x r o                                   |         |       | 在矩形区域里插入一个空白矩形   |
