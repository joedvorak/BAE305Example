# Helpful Hints for creating your GitHub Pages Design File
* Keep all files used in your design file in a single folder called ""/docs"
* Create a file named "README.md" in the "/docs" folder
* Edit the README.md file with GitHub's editor. You can preview the final document by clicking on the tab at the top.
* Make sure to save your online edits by clicking commit at the bottom.
* At the top of the editor is a "?" that you can click for help.
* The formatting buttons can also help.
* Resize images before uploading to the /docs folder. You can use any image editor for that. I set mine a maximum of 3 inches high so that they appear on the screen easily.
* The programming language type for README.md is Markdown.
* You will likely need a space before hitting enter at the end of a line. This helps the interpreter recognize different paragraphs.
* If you see sections that run onto each other. Try a space before the enter. If that doesn't work, try adding an extra blank line (hit enter again). That helps separate sections.
* Markdown elimnates extra blank lines between paragraphs so don't worry about having too many.

# Formatting Code

Markdown has several ways to represent code. The basic code button just puts it in a gray box. It's not too useful. To get the nice syntax highlighting you have to tell the Markdown interpreter the programming language. Arduino is very similar to C or C++ so the following can be used to designate code:

Basic code notation: 

`
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
`
Using C notation:

```C
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
```
Using C++ notation:

```C++
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
```

Using Arduino notation:
```Arduino
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
```

I don't suggest using Arduino notation as it sometimes isn't handled well.

How do you tell it the notation to use?
Write the code section like this:
```Markdown
```C
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
```
```
`Markdown
```C
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
```
`
More about highlighting code is [here](https://help.github.com/articles/creating-and-highlighting-code-blocks/). You might need to look it up if you decide to use something other than Arduino for your project. 
