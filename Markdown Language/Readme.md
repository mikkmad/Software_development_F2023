<!-- Introductory section -->
# Introduction to using Markdown language for taking notes in Computer Science
Taking notes in Computer Science can be iffy when using text-editors like Word, OneNote or Google Docs.
There's a filetype named `Markdown` or `.md` for the filetype extension. 

This filetype allows for text-formatting, including: Headings, code-highlighting, lists, bold and italic text.

"_Why should we use it?_", you may ask.

Let me explain shortly what markdown is, followed by how to use it, and hopefully you'll understand _why_.


<!-- Short description of the Markdown language -->
## What is Markdown?
Markdown is a `markup` language, making it possible to format text for webpages, using a text-editor.

There are multiple ways of styling such document, i.e. by using headings, lists (numbered or bullet points), emphasis 
(**bold text** or _italics_) or code highlighting, like this:

```java
public class HelloWorld{
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

<!-- 
Examples of how to use headers in Markdown language
Please note, the <h1></h1> is HTML form-style, and is not required for normal Markdown language: simply use the hashtags :) 
-->
## Examples of using headers:

| Heading Type | Example  |
| :-------------:   | :-----------------: |
| # Heading 1       | <h1>Heading 1 </h1> |
| ## Heading 2      | <h2>Heading 2 </h2> |
| ### Heading 3     | <h3>Heading 3 </h3> |
| #### Heading 4    | <h4>Heading 4 </h4> |
| ##### Heading 5   | <h5>Heading 5 </h5> |
| ###### Heading 6  | <h6>Heading 6 </h6> |

- One `#` equals to `Heading 1` in Word or in Google Docs. 
- Two `##` equals to `Heading 2` in Word or in Google Docs.
- Three `###` equals to `Heading 3` in Word or in Google Docs.
- And so forth...

### Example:
The `What is Markdown?` heading, is a type 2 heading, formatted with two hashtags `##`, whereas the title 
`Introduction to using Markdown language for taking notes in Computer Science` is using a 
heading 1, formatted with a single `#`.


<!-- How to use Bullet Points and Lists-->
## Bullet points and lists
One may need to showcase a numbered list or list of bullet points. This is also possible, simply by prefacing your 
list item with a `*` for bullet-points and a `1` for numbered items (remember to increment the number for each 
list-item).

Bullet-point list example:
* This is item 1
* This is item 2
* This is item 3

Numbered list example:
1. This is item 1
2. This is item 2
3. This is item 3

<!-- Important side-note information -->
**Sidenote**: Some editors (like IntelliJ and Visual Studio Code, etc.) will increment the number automatically, if you press 
the `Enter` key to jump to the next line.


<!-- How to emphasize text, i.e. making it Bold or Italic -->
## Emphasising Text
Sometimes you may need to put certain words in **bold** text or in _italic_ text, to emphasize the said word.

Some text-editors (IntelliJ and Visual Studio Code, etc.) allows for keyboard shortcuts to said functions:
- Windows: `ctrl+b` for **bold text** and `ctrl+i` for
_italic text_. 
- MAC: I assume that would be `Command+b` for **bold** and `Command+i` for _italic_.

Otherwise, to do it manually, you would need to put double asterisk (`*`) before and after the string of 
text: `**text you want to be bold**`, and for italic text, that would be `_some text you want to be italic_`. 

<!-- How to use Syntax highlighting -->
## Code-highlighting (Also called 'Syntax highlighting')
This is probably the most important and most valuable aspect of using Markdown language for taking notes and 
describing your Coding-project in detail.

Code-highlighting is a pain to setup in text-editors like Word or the like, but it is rather simply in Markdown
language.

All one have to do is type triple '`' followed by the code language, you want to use the highlighting from. To see 
exactly how the setup looks, I advice to look in the "Readme.md" file provided in this project. 

<!-- Examples of Syntax Highlighting in Java, Python and C# -->
### **Java example**:
```java
public class HelloWorld{
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
output: 
```console
Hello World!
```

### **Python example**:
```py
print("Hello world!")
```
output: 
```console
Hello World!
```

### **C# example** (Taken from: [GeeksForGeeks](https://www.geeksforgeeks.org/hello-world-in-c-sharp/)):
```csharp
// C# program to print Hello World!
using System;
  
// namespace declaration
namespace HelloWorldApp {
      
    // Class declaration
    class Geeks {
          
        // Main Method
        static void Main(string[] args) {
              
            // statement
            // printing Hello World!
            Console.WriteLine("Hello World!");
              
            // To prevents the screen from 
            // running and closing quickly
            Console.ReadKey();
        }
    }
}
```
output: 
```console
Hello World!
```

<!-- Important side-note information -->
**Sidenote**: 
Please note the **Syntax Highlighting** is only highlighting the Java code if being viewed in IntelliJ, as IntelliJ will only provide syntax-highlighting for the programming language in question, which is Java.

Should you view this Readme.md in your browser, i.e. on GitHub, or in Visual Studio Code it will provide syntax-highlighting for ALL the examples.

And as such, you have now been introduced to the basics of using Markdown language. This should be enough for you to 
start taking notes, using markdown language.

For more information, see [GitHub's QuickStart guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)! :)

This link provides information on how to do the following:
- Make tables
- Inserting quotes
- Adding comments
- Adding collapsable sections
- Inserting images
- And more advanced features