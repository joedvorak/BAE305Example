# Helpful Hints for creating your GitHub Pages Design File
* Keep all files used in your design file in a single folder called ""/docs"
* Create a file named "README.md" in the "/docs" folder
* Edit the README.md file with GitHub's editor. You can preview the final document by clicking on the tab at the top.
* Make sure to save your online edits by clicking commit at the bottom.
* At the top of the editor is a "?" that you can click for help.
* The formatting buttons can also help.
* Resize images before uploading to the /docs folder. You can use any image editor for that. I set mine a maximum of 3 inches high so that they appear on the screen easily.
* The programming language type for README.md is Markdown.

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
How do you tell it the notation to use?
Write the code section like this:
```md
```C
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
```
```
`md
```C
void setup(){
int myNumber = 3;
Serial.begin(9600);
myNumber++;
}
```
`
