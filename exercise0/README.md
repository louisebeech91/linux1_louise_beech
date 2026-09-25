# Exercise0 soulutions documentation

## Task 1 File Management

## Creating files 
Created folder using brace expantion

```bash
mkdir exercise{0..3}
```

and then created file with touch

```bash
touch exercise0/README.md
```

## Moving files
Created a 'files' directory and moved files into it 

```bash
mv file?.md files
```

and then moved file.2.md back out to exercise0.

```bash
mv file2.md ..
```

## Adding content 
Put "Hello file2" into file2.md

```bash 
echo "Hello File2" >> file2.md
```

## Copying files
copied file2.md and called the new copy file2.txt

```bash 
cp file2.md file2.txt
```

then output the content of both files 

```bash 
cat file2.md file2.txt
```

## Clean-up
Removed all files except README.md

```bash
ls file*
^ls^rm 
```

and also removed the directory files

```bash
rm -r files
```

