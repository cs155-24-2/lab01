# CS 155 24.2 Lab 01

## Instructions

1. Lab 01 specs are attached in github classroom.

2. Write your code such that it accepts the input file's filename as a parameter, i.e. your `int main` in your `.y` bison code should look like:

```
int main (int argc, char *argv[])
{
    freopen (argv[1], "r", stdin);
    return yyparse ();
}
```

3. **Important:** Whenever you do a `git add` to incorporate your changes, make sure to use: 

```
git add --chmod=+x .
``` 

This way, the custom github autocorrect has permissions to execute your file.

4. **Also Important:** Lab 01 asks you to write three versions, the third of which is a bonus. Please make sure to upload the **.l**, the **.y** and the **.out** files for each version according to the following filenames:

```
v1.l
v1.y
v1.out
v2.l
v2.y
v2.out
v3.l
v3.y
v3.out
```

5. Once you push your code, github will automatically run an autocorrect routine using some sample input. To check if you passed the sample tests, go to the Actions tab of your github lab 01 site.