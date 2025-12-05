## Usage

To use `pipex`, run the following command:

```sh
./pipex file1 cmd1 cmd2 file2
```

- `file1` — input file  
- `cmd1` — first command  
- `cmd2` — second command  
- `file2` — output file

Example:

```sh
./pipex infile "grep hello" "wc -l" outfile
```

This runs `grep hello` on `infile`, pipes the result to `wc -l`, and writes the output to `outfile`.
