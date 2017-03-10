# iterm2-smart-selection-rules

|Notes|Regular Expression|Precision|
|---|---|---
|\`match text inside backticks\`|(?<=\`)[^\`]+(?=\`)|Very High
|[match text inside brackets]|(?<=\[)[^]]+(?=\])|Very High
|"match text inside double quotes"|(?<=")[^"]+(?=")|Very High
