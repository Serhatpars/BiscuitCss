# BiscuitCss
Next generation Css Framework. 

• Is Biscuit for you?

You should use Biscuit if you're embarking on a smaller project or just don't feel like you need all the utility of larger frameworks. Biscuit only styles a handful of standard HTML elements and includes a grid, but that's often more than enough to get started. In fact, this site is built on Biscuit and has ~600 lines of custom CSS (half of which is the docking navigation).

Love Biscuit and want to Tweet it, share it, or star it? Well, I appreciate that <3

• The grid

The grid is a 12-column fluid grid with a max width of 960px, that shrinks with the browser/device at smaller sizes. The max width can be changed with one line of CSS and all columns will resize accordingly. The syntax is simple and it makes coding responsive much easier. Go ahead, resize the browser. 
<!-- .container is main centered wrapper -->
<div class="container">

  <!-- columns should be the immediate child of a .row -->
  <div class="row">
    <div class="one column">One</div>
    <div class="eleven columns">Eleven</div>
  </div>

  <!-- just use a number and class 'column' or 'columns' -->
  <div class="row">
    <div class="two columns">Two</div>
    <div class="ten columns">Ten</div>
  </div>

  <!-- there are a few shorthand columns widths as well -->
  <div class="row">
    <div class="one-third column">1/3</div>
    <div class="two-thirds column">2/3</div>
  </div>
  <div class="row">
    <div class="one-half column">1/2</div>
    <div class="one-half column">1/2</div>
  </div>

</div>

<!-- Note: columns can be nested, but it's not recommended since Skeleton's grid has %-based gutters, meaning a nested grid results in variable with gutters (which can end up being *really* small on certain browser/device sizes) -->

Typography

Type is all set with the rems, so font-sizes and spacial relationships can be responsively sized based on a single <html> font-size property. Out of the box, Skeleton never changes the <html> font-size, but it's there in case you need it for your project. All measurements are still base 10 though so, an <h1> with 5.0remfont-size just means 50px.

The typography base is Raleway served by Google, set at 15rem (15px) over a 1.6 line height (24px). Other type basics like anchors, strong, emphasis, and underline are all obviously included.

Headings create a family of distinct sizes each with specific letter-spacing, line-height, and margins.

<!-- Standard Headings -->
<h1>Heading</h1>
<h2>Heading</h2>
<h3>Heading</h3>
<h4>Heading</h4>
<h5>Heading</h5>
<h6>Heading</h6>

<!-- Base type size -->
<p>The base type is 15px over 1.6 line height (24px)</p>

<!-- Other styled text tags -->
<strong>Bolded</strong>
<em>Italicized</em>
<a>Colored</a>
<u>Underlined</u>

Buttons

Buttons come in two basic flavors in Skeleton. The standard <button> element is plain, whereas the .button-primary button is vibrant and prominent. Button styles are applied to a number of appropriate form elements, but can also be arbitrarily attached to anchors with a .button class.
  
  <!-- Standard buttons -->
<a class="button" href="#">Anchor button</a>
<button>Button element</button>
<input type="submit" value="submit input">
<input type="button" value="button input">

<!-- Primary buttons -->
<a class="button button-primary" href="#">Anchor button</a>
<button class="button-primary">Button element</button>
<input class="button-primary" type="submit" value="submit input">
<input class="button-primary" type="button" value="button input">

<button class="button-success">Button SUCCESS</button>
<button class="button-warning">Button Warning</button>
<button class="button-danger">Button Danger</button>
<button class="button-info">Button info</button>

<!-- Social Media Buttons -->

<button class="button-facebook">
                <i class="fab fa-facebook-f"></i>
                Facebook
            </button>
            <button class="button-twitter">
                <i class="fab fa-twitter"></i>
                Twitter
            </button>
            <button class="button-instagram">
                <i class="fab fa-instagram"></i>
                instagram
            </button>
            <button class="button-github">
                <i class="fab fa-github"></i>
                github
            </button>
