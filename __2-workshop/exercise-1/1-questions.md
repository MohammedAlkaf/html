# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>`

b) [False]

```html
<ul>
<li>one</li>
</ol>
```

c) [False] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

Answer:
A screen reader is software that renders the text and images of a website into speech synthesizer or braille display.It is very important to have websites accessible to the blind by using the right HTML elements and care about the 
elements or attributes that are not rendered dirctly in the screen.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
    Answer: <img> tag and use src attribute to add the links for photos 

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
    Answer: <ul> and <li> tags will be needed to create the list and <a> for the links inside each <li>

c) You want to sell designer hats. You need to receive orders from the user.
    Answer: Using <input> tags inside a <form> element. The order information are then sent to a server in a form.

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
    Answer: No, a <button> can not be a chile of another <button>.  A good analogy of that is you can not have a link inside a link ( it dose not make sense at all). Therefore, <button> can not have any clickable element inside it.

## Q5 - What is the most generic tag you can use?
    Answer: <div> is the most generic tag

## Q6 - What do the following achronyms stand for?

a) `a` -> anchor element

b) `ol` -> ordered list

c) `ul` -> unordered list

d) `li` -> list item

e) `tr` -> table row

f) `th` -> table head

g) `td` -> table data

## Q7 - Usually, `td` elements are children of what kind of elements?
    Answer:'td' elements are usually child of 'tr' elements

## Q8 - What is the difference between td and th?
    Answer:'td' is the data or cell in the table, whilist 'th' is the head of a column or the whole table ( example, table name, column name, etc ...)

## Q9 - Which tag makes the text appear bigger: h1 or h3?
    Answer: h1 since it shows the main header of a website.

## Q10 - In which situation can you use self closing tags?
    Answer: slef-closing tags can be used inline with other childern in an element. For example, adding an image, or clickable are, or braking a line. There is no content inside self-closing tags.

## Q11 - What is autofilling and why is it important?
    Answer: Data stored in user broswer such as: username & passpord, credit card infomation, or address information, is autofilled when the proper HTML element is used such: <form> element. That's why very conveinent to have this data filled out automically by users.

## Q12 - Which attributes are always present in an img element?
    Answer: 'src' attribute, to obtain img reference, should always be present in img element,otherwise no image will shown. Also, it is a good practice to add 'alt' to provide a title for the image so it can be readable by screenreaders.

## Q13 - Which attribute is always present for an anchor tag?
    Answer: <a> element is mainly used to create a link in text. Therefore, 'href' is important to refer the user to a website when text is clicked.
