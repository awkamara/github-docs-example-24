# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. 
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it  allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you to use three backticks (`)
- Not to be confused with single quotations (')

```
# Define a Person class
class Person
  attr_accessor :name, :age, :gender

  def initialize(name, age, gender)
    @name = name
    @age = age
    @gender = gender
  end

  def introduce
    puts "Hello, my name is #{@name}, I am #{@age} years old, and I am #{@gender}."
  end
end
```

- When you can you should attempt to apply syntax highlighting to your codeblocks.

```ruby
class Person
  attr_accessor :name, :age, :gender

  def initialize(name, age, gender)
    @name = name
    @age = age
    @gender = gender
  end

  def introduce
    puts "Hello, my name is #{@name}, I am #{@age} years old, and I am #{@gender}."
  end
end
```

- Make note of where the backtick keyboard key is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.

![backtick](https://github.com/awkamara/github-docs-example-24/assets/145500282/f2f52076-7638-4ce3-85f0-f12b93122861)


Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
        1: from main.rb:2:in `<main>'
main.rb:2:in `<main>': undefined local variable or method `undefined_variable' for main:Object (NameError)# Creating an instance of Person
person1 = Person.new("Alice", 30, "female")
```

> Here is an example of using a codeblock for an error that appears in bash.

When you can always provide a codeblock instead of a screenshot.
If you need to take a screenshot make sure it not a photo from your phone.

> There are certain cases where its okay to take photos with your phone. This is when you are showing something like a keyboard, which does not appear on a computer screen. If it render on your computer screen it should be a screenshot.

## Step 1 - how to take screenshots.

A screenshot is when you capture a part of your screen from your laptop, desktop or phone.

This is not be confused with take a photo with your phone.

**DON'T DO THIS**

![a photo with your phone ](assets/phone-photo.jpg)

This is what a screenshot from your computer should look like

**DO THIS INSTEAD**

![Screenshot example](Screenshot-example.png)

For Mac and Windows, you can take screenshots using built-in hotkeys. Here's how you can do it:

### Mac:

1. **Capture Entire Screen:**
   - Press `Command (⌘) + Shift + 3`.

2. **Capture a Selected Area:**
   - Press `Command (⌘) + Shift + 4`, then click and drag to select the area you want to capture.

3. **Capture a Specific Window:**
   - Press `Command (⌘) + Shift + 4`, then press the `Spacebar`. Your cursor will turn into a camera icon. Click on the window you want to capture.

The screenshots will be saved to your desktop by default.

### Windows:

1. **Capture Entire Screen:**
   - Press `PrtScn` (Print Screen) key. On some keyboards, you might need to use `Fn` key along with `PrtScn`.

2. **Capture the Active Window:**
   - Press `Alt + PrtScn`.

3. **Capture a Selected Area (Windows 10 and later):**
   - Press `Windows key + Shift + S`, then click and drag to select the area you want to capture. This copies the screenshot to clipboard.

These are the basic built-in methods for taking screenshots on Mac and Windows systems. Keep in mind that on Windows, you may also have additional screenshot tools available depending on your version of Windows and any third-party software you have installed.


## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)
- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (optional)

Github Flavored Markdown (GFM) supports emojis shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud with lighting | `:cloud_with_lighting:` | ☁️  |

# Step 5 - How to create a table


You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lighting:` | ☁️  |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external references)


- Make note of where the pipe keyboard key is located.
- It should appear above the return or enter key,
- but it may vary based on your keyboard layout.
  
![Photo of the pipe character on our keyboard](assets/pipe-char.jpeg)

[Secret Window Hidden Garden](secret-window/hidden-garden.md)


## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GFM - Task List](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet).
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
-  
