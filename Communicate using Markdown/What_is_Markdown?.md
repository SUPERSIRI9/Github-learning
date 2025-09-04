# Markdown

_This is **italic and bold** text_ using a single underscore for italic and double asterisks for bold.
__This is bold and *italic* text__ using double underscores for bold and single asterisks for italic.

###### This is H6 text

### link
#### image 
![Link an image.](/learn/azure-devops/shared/media/mara.png)
#### site
[Link to Microsoft Training](/training)
### ordered list

1. first 
1. second
1. third

### unordered list
- first
- second
- third
  - nested

### table
first | second
-|-
1|2
3|4
5|6

### quote text
>this is quoted text

### line break
this is a<br />line break

### code 
` this is code `

```markdown
var first = 1;
var second = 2;
var sum = first + second;
```

``` javascript
var first = 1;
var second = 2;
```

### Cross-link issues and pull requests

Reference type	| Raw reference	| Short link
-----------------------------------------------------|----------------------------------|-----------------------------------
Issue or pull request URL	| `https://github.com/desktop/desktop/pull/3602` | #3602
`#` and issue or pull request number | #3602 |	#3602
`GH-` and issue or pull request number | GH-3602 | GH-3602
Username/Repository# and issue or pull request number	| desktop/desktop#3602 | desktop/desktop#3602


Reference type | Raw reference | Short link
--------------------|----------------------------------------|--------------------------
Commit URL | https://github.com/desktop/desktop/commit/	
`8304e9c271a5e5ab4fda797304cd7bcca7158c87` | 8304e9c	
SHA | `8304e9c271a5e5ab4fda797304cd7bcca7158c87` | 8304e9c
User@SHA | desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | desktop@8304e9c
Username/Repository@SHA | desktop/desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | desktop/desktop@8304e9c


### Track task lists

- [ ] task1
- [ ] task2
- [x] task 3

### `/` commands
Command | Description
-----------------------|----------------
`/code`|Inserts a Markdown code block. You choose the language.
`/details`|Inserts a collapsible detail area. You choose the title and content.
`/saved-replies`|Inserts a saved reply. You choose from the saved replies for your user account. If you add %cursor% to your saved reply, the slash command places the cursor in that location.
`/table`|Inserts a Markdown table. You choose the number of columns and rows.
`/tasklist`|Inserts a tasklist. This slash command only works in an issue description.
`/template`|Shows all of the templates in the repository. You choose the template to insert. This slash command works for issue templates and a pull request template.

