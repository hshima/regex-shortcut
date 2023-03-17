# Consultas regex

## Busca de conteúdo dentro de uma tag

```text
(?<=<expression>).*?(?=</)
```

### Busca melhorada

fonte: [Regex select all text between tags](https://stackoverflow.com/questions/7167279/regex-select-all-text-between-tags/40908001#40908001)

```text
(?<=(<pre>))(\w|\d|\n|[().,\-:;@#$%^&*\[\]"'+–/\/®°⁰!?{}|`~]| )+?(?=(</pre>))
```

## Seleção de múltiplos resultados no vs code

[Select all occurrences of selected word in VSCode](https://stackoverflow.com/questions/46539714/select-all-occurrences-of-selected-word-in-vscode)


Select All Occurrences of Find Match `editor.action.selectHighlights`.

```text
Ctrl+Shift+L

Cmd+Shift+L or Cmd+Ctrl+G on Mac
```