# Craft Handbook

Here's a **::'how to'::** of Craft’s features.

Want to get started fast? Check out our **::Quick Start Guide document::**.

---

## Adding Content

#### Adding Text

Adding content is very simple - just tap on an empty area and start typing. You can also drag and drop the input field on both Mac (from the sidebar) and iOS (from the bottom bar) in order to drop content at a specific location.

If you are using a keyboard, you can also just press `space` when a block is focused to insert a new block below.

# Shortcuts

We’ve added a number of shortcuts for common types of text - just start your text blocks with these, and it will auto apply formatting. These include:

`-`  or `*` for ::bullet list::

`1.` or any other number for ::numbered list::

`+` for ::toggle list::

`x` or `[]` for ::tasks:: (`x` *for todos is our personal favorite. So easy!*)

`#` `##` `###` `####` For **Title**, **Subtitle**, **Heading**, or **Strong**

`>` or `|` for ::block quote::

On a keyboard, you can also just press `CMD +` or `CMD -` to increase or decrease text sizes.

And of course, you can also invoke the /quick menu by typing `/` .

Adding Emojis is really easy - just type `:` and start typing the name of an emoji.

And you can mention any other document or block by typing `@` and then filtering for the name of the page.

#### Adding Images, Videos and Files

Craft lets you insert photos, videos, and any files from your **Camera**, **Photo Library**, **Files**, or from [**Unsplash**](https://unsplash.com).

> #### On iOS :

- > You can either type a  `/`  character while editing and selecting the desired option from the menu.
- > You can also tap on the `+` button in the bottom left corner to see the list of options - and pick the one you'd like from there.

> #### On Mac :

- > Just as on iOS, you can also just type `/` and select the desired action. You can also drag and drop images into the mac app from your folders, or any website.

---

Photos, videos, and files will look absolutely stunning in your documents. Craft will automatically arrange them in the best possible layout. See some examples below:

![](Craft%20Handbook.assets/242bc03e-c9ec-91fc-6793-b3c63ae707f8_png_preview.png)

![](Craft%20Handbook.assets/a1f2aa92-f2ca-8f91-b739-325aef5f16c0_png_preview.png)

![](Craft%20Handbook.assets/3b62f42e-dae9-88b4-ae30-e3201bb72513_png_preview.png)

![](Craft%20Handbook.assets/12bc4866-b305-d513-10c3-9c0fbf99dd7e_png_preview.png)

#### Adding Code, Math Formula (TeX), and Inline Equation

You can also add Code, Math Formula (TeX), plaintext snippets, inline code, and inline equation.

To do so, you can use the same methods as you would do when adding images.

Just type `/` and filter for either `Formula` or `Code`.

You can also choose different syntax highlight options for code - See some examples below:

---

## Code Examples

```css
body {
  background-image: url("barn.jpg");
  background-repeat: repeat-y;
  background-position: right top;
  background-attachment: fixed;
}
```

*CSS Code*

```swift
func isCountEnough(_ number: Int) -> Bool {
	return number > 15
}
```

*Swift Code*

## Text Snippet

```plaintext
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```

*Text Snippet*

## TeX Formula

$$
f(x) &= x^2\\
 g(x) &= \frac{1}{x}\\
 F(x) &= \int^a_b \frac{1}{3}x^3
$$

*TeX Formula*

## Inline code

`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`

*Inline code*

## Inline Equation

You can use inline equation too: $$(a+b)^2$$, just wrap your text around `$$` and `$$`, or transform your existing text to equation.

![Screenshot 2021-07-05 at 12.53.29.png](Craft%20Handbook.assets/Screenshot%202021-07-05%20at%2012.53.29.png)

*Inline Equation*





## Styling Content

#### Styling Basics

### Styling Blocks

Craft allows you to style your content in a beautiful and simple way. We've created a set of styles that won’t overwhelm, but by combining these, you can still perfectly express yourself - and all of these work great both in dark or in light mode.

> #### I.e., combining our text type “strong” with a “focus” decoration will create the effect of a quote.

---

- > If blocks have the same styles, they also merge visually.
- > I.e., these two blocks look as if they were one.

---

Apart from block-level styles, you can also apply inline styles: ::highlight::, **bold**, *italic,* ~~strikethrough~~, `code`, or add [links](https://www.craft.do/).

---

> > To start styling, just swipe → or ← on a block on iOS (or select the Aa menu on the right side on Mac) and start exploring different options!

### Styling Entire Pages

You can also change page-wide styles, including:

- Font Style
- Header Settings - Cover Image, Title, and Author visibility
- Page Width
- and Paragraph Spacings

To do so :

- on iOS, tap on the … button on the top right corner and select “Page Style”
- on Mac, from the right sidebar, select the “Page Details” tab.

#### Quick Styling

Apart from using visual controls and buttons, Craft allows you to style your content right from the keyboard as well. There are a number of options you can use:

## The `/Command` Menu

If you love using your keyboard, you'll love this option. To activate it, just press `/` on your keyboard while either in editing mode (with text cursor) or when any blocks are selected. After that, you can start typing and filtering for the desired Style

## Markdown Formatting Options

Craft supports the full suite **markdown** formatting, i.e., ****bold content**** for bold. You can see a [full list of markdown shortcuts here.](https://support.craft.do/hc/en-us/articles/360019555597-Markdown-Style-Shortcuts)

## Keyboard Shortcuts for iPad And Mac

Craft supports over **75 keyboard shortcuts**. That’s a lot - thankfully, if you hover on buttons, you’ll see the keyboard shortcut, so you don’t have to memorize all of them. Some of our favorite ones are :

- `CMD`  `+`  for increasing text size
- `CMD`  `-`  for increasing decreasing text size
- `CMD`  `B`  for **bold**
- `CMD`  `I`  for *italic*
- `TAB` to increase indent, `SHIFT` `TAB` to decrease indent

See the [full list of supported keyboard shortcuts by clicking here](https://support.craft.do/hc/en-us/articles/360019555557-Keyboard-Shortcuts) (or tapping on the keyboard button on Mac in the bottom right corner of the screen)

#### Markdown

Craft supports a number of markdown style shortcuts to make editing and writing faster for those of you who prefer these. Supported elements are:

## Full Block Commands

- `#` followed by a `space` to create a **title**
- `##` followed by a `space` to create a **subtitle**
- `###` followed by a `space` to create a **heading**
- `####` followed by a `space` to create a **strong block**
- `x`  or `[]`  followed by a `space` to create an **uncompleted todo**
- `[x]`  followed by a `space` to create a **completed todo**
- `-` or `*`  followed by a `space` to create a **bullet list**
- `1.`, `2.`, `3.`, `4.` etc. followed by a `space` to create a **numbered list**
- `+` followed by a `space` to create a **toggle list**
- `>`  or `|` followed by a `space` to create a **block quote**
- ````` or `'''` followed by a `space` to create a **code block**

## Inline Commands

- Wrap words between `*` and `*` or  `_` and `_` for *italic*
- Wrap words between `**` and `**` or `__` and `__` for **bold**
- Wrap words between `***` and `***` or `___` and `___`  for ***bold&italic***
- Wrap words between `~~` and `~~` for ~~strikethrough~~
- Wrap words between `::` and `::` or `==` and `==` for ::highlight::
- Use the notation `[link name](url)`  to insert a [link](https://craft.do)
- Wrap words between ``` and ``` for `inline code`
- Wrap word between `$$` and `$$` for $$inline-equation$$
- Type `..-` to insert extra light rule
- Type `.--` to insert light rule
- Type `---` to insert regular rule
- Type `=--` to insert strong rule
- Type  `@` or `[[` to insert a page or block link

## Organizing Content

#### Documents, Pages, and Blocks

Types of Craft content:

- Every paragraph in Craft is a `Block`.  And every block can have its own content. So a paragraph is both a piece of text on a page, and can also act as the title of a deeper page - allowing you to create a simple structure.
- Blocks, which have content, are called `Pages`. They can be styled the same way as any regular block. But if you tap or click on a page, you navigate inside it. There's also a “Page“ text style option for blocks, which - along with the Card style - is a great fit for Pages.
- `Documents` are documents. These behave very similarly as they do in your filesystem. You can star them, move them into folders, sort them, and so on.

---

The best way to learn Craft is to play.

**Start writing in Craft as you would normally** - and when you feel you need more structure or your document is getting too long - you’ll naturally explore how Pages work.

#### Creating Pages

One of the amazing features of Craft is that every block (paragraph) of text also acts as a note (Page) itself. I.e., you can easily nest subtasks within a task - just like this:

---

- [ ] #### Finish Project Assignment

- [ ] Finalize Structure
- [ ] Send for review
- [ ] Submit final version

This can come very handy both when you want to add more context for a specific piece of information or when you want to create documents which are easier to read and navigate. (i.e., instead of sending a 15 page long PDF).

---

## There are two ways of creating pages in Craft:

1. **Grouping Existing Blocks** into a new Page

   To do this, select the blocks you want to group and tap "group" on the bottom menu on iOS, or press `CMD + G` on Mac.

1. **Adding Content** to an existing block
   - On iOS, you can find the `→` icon above the keyboard when editing or in the bottom menu after you swiped → or ← on a block.
   - On Mac, you can find it on the right side of the block you are editing.
   - If you have a keyboard, you can also just press `CMD →`  or `CMD ]`

That’s it! There’s no right or wrong way of doing this - in fact, as your document grows you’ll re-organize it a couple of times - and it’s **::fun::** to do so!

#### Linking Content

Documents and Pages allow you to create structures akin to chapters and sections in books. They allow you to add a simple yet powerful structure - but what happens if you want to reference / link to the content in a different document?

That’s where our **page** and **block** **links** come in.

> #### You can easily add a link to any page or block you have in Craft. To do so, just type `@` and start searching for the block or page you would like to link to.

Craft’s links are smarter though than regular links - as they also behave as **backlinks**. Don’t worry if that sounds too complex - just play with it if you want to, and you’ll get into it. Or not, and then you can ignore it 😅

---

> With the help of this advanced linking system, you can go as far as creating a whole personal or professional Wiki or Website within Craft - it’s very simple - yet extremely powerful.

#### Daily Notes and Calendar

**Daily Notes allows you to frictionlessly take quick notes, plan your day, add tasks or start a daily journal!** With the tasklist behaviour in the Daily Notes you can track all your to do / completed / overdue tasks for a given day too.

Once you connect **your Calendar to Craft**, you will **see all your calendar events** and interact with them — from taking meeting notes, quickly joining video calls, or messaging the attendees.



#### Calendar tab

On the new tab you can **connect your Calendar app with Craft** (with the Customize button on Mac and iPad, and the exclamation mark button on top right corner on iOS).

After successfully connecting them, you will see all your events. For every day you can add your Daily Note too. Tasks added to Daily Notes will be tracked so you will see how many To Do / Completed / Overdue tasks you have for each day.

![daily_note.png](Craft%20Handbook.assets/daily_note.png)

You can find all your events and Daily Notes on the Calendar tab

---

**Calendar event details**

Selecting any of your event will display the most important details about the event (time, place, attendees), and also you will have multiple options to interact with the event:

- Open the link for the event, e.g. if it’s an online call
- Quickly start a new email for the attendees in your Email app
- Open your Calendar app
- Create a new Meeting Note in Craft

![event_details.png](Craft%20Handbook.assets/event_details.png)

You can see the most important details about every calendar event after clicking on them, and also you will have some additional actions to interact with the event

---

#### Meeting notes

When you create a meeting note, it will auto-populate the document with some initial content based on the event. You can than quickly and easily start taking notes before, or during the meeting.

As with every other document in Craft, you can easily share these meeting notes either via the secret link or a variety of export options.

![meeting_note.png](Craft%20Handbook.assets/meeting_note.png)

You can create a meeting note for any calendar events, and it will be auto-populated based on the event.

---

> **Quick Tip**

> Set up a daily note widget to be able to note your thoughts on the fly.

![IMG_FC63450B3322-1.jpeg](Craft%20Handbook.assets/IMG_FC63450B3322-1.jpeg)

#### Tables

![tables_mac_small.png](Craft%20Handbook.assets/tables_mac_small.png)

We created tables in Craft to **make sure you can quickly and easily start using them in your documents**. In the future, we are planning to keep iterating on them, adding more capabilities and allowing larger tables.

Your feedback is essential, so **please let us know, how you are using tables and what you would like to see next**!



#### Adding Tables

You can always use the `/` slash command to add a new table quickly. Just type `/table` or the size of the needed table (up to 9), e.g., `/4x4`.



**Mac**

On Mac, we redesigned the **first tab of the right sidebar.** From here, you can add a table to the current page.

![mac_add_tables.png](Craft%20Handbook.assets/mac_add_tables.png)

---

**iOS**

On iOS, you need to **tap first to the `+` sign on the bottom left and then pick Table** from the horizontal list.

![ios_add_table.jpeg](Craft%20Handbook.assets/ios_add_table.jpeg)

#### Import documents into Craft

### Import your notes into Craft

The fundamental goal of Craft is to help you think, write & communicate better. All of these activities involve processing and managing your data, so it’s crucial that you can bring your content into Craft.



Craft Mac and iOS apps let you import the following file types:

- Markdown (.md or .markdown)
- TextBundle (.textbundle)

### Import your content into Craft with a few clicks

To get started go to three dot menu in the upper right corner in All Documents (both on Mac and iOS) and select Import from the Import / Export section.

![Image.png](Craft%20Handbook.assets/Image.png)



You can import a single file or on Mac you can import a folder full of with the same type of files.

If you don’t select a folder the newly imported documents will end up in the ‘Imported Notes’ folder, but if you select a folder before the import, all the documents will be placed in this specific folder.



## Import how-to by app

### Evernote

Right now we are not supporting .enex import, but there are a few options. First you need to export .enex file from Evernote, [here](https://help.evernote.com/hc/en-us/articles/209005557) you can find the offical documentation for this.



**Convert .enex to markdown files with a 3rd party tool**

There are a handful of 3rd party options that let you convert enex file to markdown files. One of this tool is [https://github.com/akosbalasko/yarle](https://github.com/akosbalasko/yarle). It generally works well with simple documents.



**Migrate .enex with your existing note taking app**

If you are already using a note taking app that supports enex import and Markdown / TextBundle export you can use that app as a middle step.

---

### Notion

In Notion, you can export your pages into Markdown.

- First you have to open Notion and [export your page as a Markdown](https://www.notion.so/Export-a-page-as-Markdown-69b6031dd9454022abed8e23a86b0e1e)
- In Craft, import the Markdown files as described above.

---

### Apple Notes

Apple notes doesn’t allow easy export options, but you can use an app called Exporter

- Export your notes with app called [Exporter]( https://apps.apple.com/us/app/exporter/id1099120373?mt=12)
- In Craft, import the Markdown files as described above.

---

### Bear

Bear offers both Markdown and TextBundle export, we recommend to use TextBundle as it bundles Markdown text and all assets (e.g., images) into a single file.

- [Convert your Bear notes to Markdown](https://bear.app/faq/Markup%20%3A%20Markdown/How%20to%20convert%20your%20Bear%20notes%20to%20Markdown.html)
- In Craft, import the TextBundle files as described above.

---

### Roam Research

You can export your draft into markdown in Roam.

- In your document view in Roam, click on the three dots in the top-right corner, then “export” and choose the markdown option. You’ll get a zip file, that you can unzip.
- In Craft, import the Markdown files as described above.

---

### OneNote

OneNote offers [PDF export](https://support.microsoft.com/en-us/office/export-notes-from-onenote-as-a-pdf-13d173b5-7f4c-45a8-94eb-9354d63af5cd) only, so you can add these PDF files to your Craft documents as attachments. You can drag and drop multiple files at once to speed up this process.

---

## Current limitations

During import we have some built-in limits to make sure import will work performable - so you can’t import more than 2000 files at once at this point.

## Sharing, Export And Collaboration

#### Link Share

You’ve already seen that Craft is great for writing and organizing content - but what makes this even more powerful is that **you can share your notes with one tap**.

- On iOS, tap on the ... button on the top right corner, press share / secret link
- On Mac, from the sidebar tap on the share icon and press secret link.

This will generate you a **secret link** that you can share with others - and ::enable:: or ::disable:: any time. If you enable **::commenting::**, people with the link **can add comments** without them having to log in or sign up to Craft.

> #### You can also choose to share only a part of the document - for example, if you created notes for a meeting, only share a page with the summary in it.

And your content will look perfect both on desktop/laptop devices and on tablets/phones. Feel free to take a look at a few examples below:

---

[Design showcase](https://www.craft.do/s/cdOojqVSu8gGwo)

[Craft - What&#x27;s New &amp; Version History](https://www.craft.do/s/gy6m6pUAYiCxqA)

[Job Posting - Senior Mobile Product Designer](https://www.craft.do/s/2DN2FTz5e8mA)

---

Sending content from Craft via Secret Links is so much better than sharing long emails - you can easily send them in an iMessage, Slack or any other channel - and the others who receive these will be thankful for the clean and crisp format.

#### Export Options

Apart from Sharing content via Secret Links, Craft supports a wide variety of export options.

## Email

Craft can export your documents into pixel perfect and beautiful emails. Your output will look professional, beautiful, and everyone in the office will start asking you how to generate such amazing emails :). It’s also great for 🗞 newsletters, 💼 project proposals, or 👔 formal communication.

## Markdown

We’ve made sure that you can export and continue working on your Craft documents on any other platforms which use Craft. Our Markdown export options allow you to customize every aspect to ensure it fits perfectly into your workflow.

## PDF

Just as with other options, we’ve made sure that you get a pixel perfect and beautiful output. But we went a step further - Craft can export your hierarchical notes into a flat interactive PDF.

See some examples below:

[Job Posting - Senior Mobile Product Designer.pdf](Craft%20Handbook.assets/Job%20Posting%20-%20Senior%20Mobile%20Product%20Designer.pdf)

[1997 Letter To Shareholders.pdf](Craft%20Handbook.assets/1997%20Letter%20To%20Shareholders.pdf)

[Netflix Culture.pdf](Craft%20Handbook.assets/Netflix%20Culture.pdf)

## Coming Soon

We are planning to add the following formats soon, such as RTF.

Have a format you’d love to have? [Let us know](mailto:feedback@craft.do)!

---

## Join the Craft Community

> > #### Got questions about Craft?

> > #### Want inspiration on how to use Craft?

> > #### Need help with Craft?

Join our bustling community with over 800 Craft members from all around the world, sharing ideas, asking questions, giving and getting advice! **::Join the Craft Community::** here:

[Craft Community](https://community.craft.do/home)

---

