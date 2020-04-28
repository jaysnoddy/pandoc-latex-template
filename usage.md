Please note: complicated cmds may be constructed and logged for reference/further use in **journal.md**
 by invoking

    `Journal: CreateOrOpen and Journal: Create Entry`
      `ctrl-alt-J and ctrl-alt-e, respectively`

# Common examples of command line
## Simple example:

    `  pandoc example.md -o example.pdf --from markdown --template eisvogel  `
    ```

    where `example.md` is the markdown file you want to convert to PDF.

## To standalone latex code
      `  pandoc example.md -o example.tex --template eisvogel  `
