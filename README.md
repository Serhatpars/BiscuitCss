# BiscuitCss [Beta v0.1]
Next generation Css Framework. 

• Is Biscuit for you?

You should use Biscuit if you're embarking on a smaller project or just don't feel like you need all the utility of larger frameworks. Biscuit only styles a handful of standard HTML elements and includes a grid, but that's often more than enough to get started. In fact, this site is built on Biscuit and has ~600 lines of custom CSS (half of which is the docking navigation).

Love Biscuit and want to Tweet it, share it, or star it? Well, I appreciate that <3

• The grid

The grid is a 12-column fluid grid with a max width of 960px, that shrinks with the browser/device at smaller sizes. The max width can be changed with one line of CSS and all columns will resize accordingly. The syntax is simple and it makes coding responsive much easier. Go ahead, resize the browser. 

• Typography

Type is all set with the rems, so font-sizes and spacial relationships can be responsively sized based on a single <html> font-size property. Out of the box, Skeleton never changes the <html> font-size, but it's there in case you need it for your project. All measurements are still base 10 though so, an <h1> with 5.0remfont-size just means 50px.

The typography base is Raleway served by Google, set at 15rem (15px) over a 1.6 line height (24px). Other type basics like anchors, strong, emphasis, and underline are all obviously included.

Headings create a family of distinct sizes each with specific letter-spacing, line-height, and margins.

• Buttons

Buttons come in two basic flavors in Skeleton. The standard <button> element is plain, whereas the .button-primary button is vibrant and prominent. Button styles are applied to a number of appropriate form elements, but can also be arbitrarily attached to anchors with a .button class.
  
• Forms

Forms are a huge pain, but hopefully these styles make it a bit easier. All inputs, select, and buttons are normalized for a common height cross-browser so inputs can be stacked or placed alongside each other.

• Lists

    Unordered lists have basic styles
    They use the circle list style
        Nested lists styled to feel right
        Can nest either type of list into the other
    Just more list items mama san

    Ordered lists also have basic styles
    They use the decimal list style
        Ordered and unordered can be nested
        Can nest either type of list into the other
    Last list item just for the fun

• Code

Code styling is kept basic – just wrap anything in a <code> and it will appear like this. For blocks of code, wrap a <code> with a <pre>.

• Tables

Be sure to use properly formed table markup with <thead> and <tbody> when building a table.
  
• Media queries

Skeleton uses media queries to serve its scalable grid, but also has a list of queries for convenience of styling your site across devices. The queries are mobile-first, meaning they target min-width. Mobile-first queries are how Skeleton's grid is built and is the preferrable method of organizing CSS. It means all styles outside of a query apply to all devices, then larger devices are targeted for enhancement. This prevents small devices from having to parse tons of unused CSS. The sizes for the queries are:

    Desktop HD: 1200px
    Desktop: 1000px
    Tablet: 750px

    Phablet: 550px
    Mobile: 400px
• Utilities

Skeleton has a number of small utility classes that act as easy-to-use helpers. Sometimes it's better to use a utility class than create a whole new class just to float an element.
