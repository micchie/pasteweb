## Overview

PASTE provides scalability to concurrent TCP
connections by system call and I/O batching, multi-core scalability by
parallel, zero-copy data paths on a multi-queue NIC, and abstractions to build
storage stacks directly with packet buffers on regular or non-volatile main
memory.  It utilizes the kernel TCP/IP implementation that supports various
modern extensions.
PASTE provides both blocking and busy-polling, as well as protects the system
from application crash.

You can use the [editor on GitHub](https://github.com/micchie/paste/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/micchie/paste/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
