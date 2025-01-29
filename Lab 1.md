## Lab 01

- Name: Ethan Spurgeon
- Email: spurgeon.11@wright.edu

## Part 1 - GitHub Profile

1. [Agon-Scuffe Profile](https://github.com/Agon-Scuffe)

## Part 2 - Research

| Windows       | Linux / Mac  | Action                                                 |
| ------------- | ------------ | ------------------------------------------------------ |
| help          | man          | Shows help documentation for commands                  |
| Get-Location  | pwd          | Shows the current file path of where you are at        |
| Get-ChildItem | ls           | Lists all items in a directory                         |
| mkdir         | mkdir        | Makes a directory                                      |
| Set-Location  | cd           | Changes the current directory                          |
| New-Item      | touch        | Creates a new file                                     |
| Move-Item     | mv           | Moves an item from one location to another             |
| Copy-Item     | cp           | Copies an item from one location to another            |
| Remove-Item   | rm           | Deletes an item or directory                           |
| notepad.exe   | vim          | Opens up a text editor                                 |



## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Powershell

### Navigating My OS on the Command Line

1. Create a directory named `DirA`: mkdir DirA
2. Create a directory named `Dir B`: mkdir "Dir B"
3. Go into `DirA`: cd DirA
4. Go into `Dir B` from `DirA`: cd "../Dir B"
5. Return to your user's home directory: cd ~
6. Create a file named `test.txt`: New-Item test.txt
7. Move the file named `test.txt` into `DirA`: Move-Item "C:\Users\takeflight\test.txt" "C:\Users\takeflight\downloads\College Classes\Sophmore\2nd Semester\Operating System Concepts and Usage\Lab 1\Testing part 3\DirA\"


8. Contents of `test.txt`:
```
You'll do great things if you believe in yourself!

```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item test.txt copy.txt
10. View the contents of `DirA`: Get-ChildItem DirA
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item DirA/test.txt "Dir B/fodder.txt"
12. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item "Dir B" -recurse

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.
https://devblogs.microsoft.com/scripting/table-of-basic-powershell-commands/ : Gave me all the commands for powershell.
I used the AI copilot to make the template line up at the end. "Can you make everything line up and let me copy the result?"
