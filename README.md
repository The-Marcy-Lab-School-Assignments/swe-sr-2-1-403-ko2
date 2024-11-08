# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Do some research on semantic and non-semantic elements and share your findings. Your response should include:

- Examples of semantic and non-semantic tags
- The differences between semantic and non-semantic tags
- The benefits of using semantic tags (when possible)

### Response 1

Semantic elements in HTML provide a structure to the document, things like <header>, <footer>, <main>, and more. These directly do something in the document, whether it be defining something or specifiying another. Non-Semantic elements on the other hand, are the opposite. The dont have any inherent meaning to the document but its used often for presentation. <div>, <span> are good examples of this. They're generic elements and dont provide additional context. It is recommended to ise semantic elements whenever possible and only use non-semantic elements sparingly. This way it improves the accessibility and search engine optimization.

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

### Response 2

Accessibility to me means: catering an experience to a wide range of users. This is important in multiple aspects, but in an overarching business aspect, you want the most traffic on you website as possible. Catering to a wide-range of users helps proliferate that by having a multitude of tools built into the site: including, the ability to navigate the website using only a keyboard, high contrast colors, screen reader compatibility for users with visual impairments, alt text and video transcriptions, regular accessibility audits and over all inclusive design!

## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html
<p style="color: red;" >hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

### Response 3

While still getting my bearings on the intricacies of HTML and CSS, I can see one way an inline style could be helpful. If you have only a single line of HTML that you need to look a certain way, like you want the text to be red. You can do that in a inline style rather than making a seperate CSS line just for the single elements or tag. Conversely, there are times when you want multiple styles on a single line or even multiple line, in this case you want to have it in a seperate CSS file to make your documents looking as neat and readable as possible.

## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

- An explanation of the concept of "classes" and "ids" with an analogy.
- An example of the usage using an HTML code block and a CSS code block.
- An explanation of the syntax using the terms: **attribute**, **selector**

### Response 4

When I think of `id` and `class` attributes I like to think of it as a student in a school. The student, lets say Logan has one `id`. There is no other Logan or no other students like him. And he can have one or multiple classes. This helps me remember that `id` are unique and can be applied to only one element. There are multiple classes in a school, so that tells me that the same `class` attribute can be assigned to one or more elements in a document. Logan can take one or more classes, that is to say you can nest or have an `id` and a `class` together.

```HTML
<student id="Logan">
    <p class="bio"> Folder </p>
    <p class="ELA"> Folder </p>
    <p class="math"> Folder </p>
</student>
```

```CSS

#Logan > .bio{ color: green;}
#Logan > .ELA{ color: red;}
#Logan > .math{ color: blue;}

```

This color coordinates Logans 'Folder' for class based on their html class!

## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

### Response 5

While building an entire site using JavaScript and the DOM API is possible it is not best practice. Doing so limits accessibility, its best when you are building a small, static website with minimal interactivity, or a single page application. Best practice is using HTML to structure the site, CSS to add styling to the your page and use JavaScript for dynamic behavior and interactions rather than using it for structure. This also makes your work space more neat, clear, and readable, to have each document for specific purposes.
