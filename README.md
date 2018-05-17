# Atom Note Syntax Highlighting

Atom syntax highlighting for personal note files, denoted with the .note extension.

Syntax highlighting scheme applies to section headings, not the text of the notes directly.  Each section heading uses a colon delimited key value pair format, with all keys colored in green (#859900).  Section headings should be at the start of a new line, and the key should be written in all caps Section heading.

Examples:
>
> DATE: 01-01-2018 <br />
> TASK: Create documentation for new API endpoints


## Section keys and highlighting Scheme
The follow list denotes each key that can be used.

 | KEY      | Key Color | Value Color |
 | -------- | --------- | ----------- |
 | DATE     | <span style="color: #859900">#859900</span>   | <span style="color: #D33682">#D33682</span>     |
 | HOURS    | <span style="color: #859900">#859900</span>   | <span style="color: #268BD2">#268BD2</span>     |
 | INCIDENT | <span style="color: #859900">#859900</span>   | <span style="color: #DC322F">#DC322F</span>     |
 | INFO     | <span style="color: #859900">#859900</span>   | <span style="color: #6C71C4">#6C71C4</span>     |
 | MEETING  | <span style="color: #859900">#859900</span>   | <span style="color: #B58900">#B58900</span>     |
 | TAGS     | <span style="color: #859900">#859900</span>   | <span style="color: #268BD2">#268BD2</span>     |
 | TASK     | <span style="color: #859900">#859900</span>   | <span style="color: #CB4B16">#CB4B16</span>     |
 | TODO     | <span style="color: #859900">#859900</span>   | <span style="color: #DC322F">#DC322F</span>     |

## Install

Install the package `language-note` in Atom (Preferences->Packages) or Atom's package manager from a shell:

```bash
$ apm install language-note
```
