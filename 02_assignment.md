# Assignments for most used commands

## Few basics before doing the assignment

Linux/Unix has three standard Input/Output(I/O) files identified by: 

- `0` : Standard Input (stdin)
- `1` : Standard Output (strout)
- `2` : Standard Error (stderr)

When you type `ls` and hit enter on terminal, what happens is that `ls` command
does its job and return the output to Standard Output (1), and it can just be
seen on the terminal. Terminal also act as Standard Error (2). 

There is a very important file known as `pipe` (|) and literally it means
output of a command becomes input of the second if you have a pipe between them

NOTE: If you want to use standard input as a file you can use `-` as the file name 


## cat and paste

Alice made a mistake and put the name of famous **Die Hard** movie actor full name
in three different files having first middle and last names respectively (see
`data/first_name.txt`, `data/middle_name.txt`, and `data/last_name.txt`). You
are given only two commands `cat` and `paste` to use and print his complete
name with following constraints. 

- Use only `paste` to complete the name
- Use cat to print middle name fist and place it between first and last using
  both `cat` and `paste` command.

## Generate non-overlapping intervals

Generate non-overlapping interval between `1` and `100` with a period of 10.

You output should look like the following:
```
1 10
11 20
21 30 
...
91 100
```

## Get selected columns from file by column names

Susan was creating a tabular data with patient names as columns and observation
under different conditions and she ended up with this tab separated (`tsv`)
file ([patient_data.tsv](./data/patient_data.tsv)). Your job is to get extract columns for:

- Patient1 
- Patient3
- Patient4
- Patient5

without visually determining the column numbers from the file. You can slack me if the question is not clear.
