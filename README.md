# Developing-Layouts-for-five-Responsive-Breakpoints
Developing Layouts for five Responsive Breakpoints
Bootstrap Grid System |Cheat Sheet
1. CSS Box Properties
1.1 Margin
We can get spacing between the two HTML elements with the CSS Box property margin.

To get space only on one particular side, we use Margin Variants.

margin-top
margin-right
margin-bottom
margin-left

2. Bootstrap Spacing Utilities
2.1 Margin
CSS Margin property	Bootstrap class 

CSS Margin property	Bootstrap class name
margin				m-*
margin-top			mt-*
margin-right			mr-*
margin-bottom			mb-*
margin-left			ml-*
The asterisk (*) symbol can be any number in the range of 0 to 5. For example, m-5, mr-2, mb-3, etc.

2.1.1 Margin Values
Size	Value
0	0
1	0.25 * spacer
2	0.5 * spacer
3	1 * spacer
4	1.5 * spacer
5	3 * spacer

The spacer is a variable and has a value of 16 pixels by default.

For example,

mb-3 = 1 * 16px = 16px
m-5 = 3 * 16px = 48px


2.2 Padding
CSS Padding property	Bootstrap class name
padding				p-*
padding-top			pt-*
padding-right			pr-*
padding-bottom			pb-*
padding-left			pl-*

The asterisk (*) symbol can be any number in the range of 0 to 5. For example, p-3, pr-1, pb-5, etc.

2.2.1 Padding Values

Size	Value
0	0
1	0.25 * spacer
2	0.5 * spacer
3	1 * spacer
4	1.5 * spacer
5	3 * spacer

The spacer is a variable and has a value of 16 pixels by default.

For example,

p-1 = 0.25 * 16px = 4px
pt-4 = 1.5 * 16px = 24px
3. Bootstrap Background Color Utilities
You can use one of the below Bootstrap class names to apply a background color to an HTML element.

4. Developing Layouts for five Responsive Breakpoints
4.1 Color Palette

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
<style>  
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <h1 class="color-palette-heading">Color Palette</h1>
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-primary">
            <p class="color-name">Primary</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-secondary">
            <p class="color-name">Secondary</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-success">
            <p class="color-name">Success</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-info">
            <p class="color-name">Info</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-warning">
            <p class="color-name">Warning</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-danger">
            <p class="color-name">Danger</p>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
</style>
</head>
  <body>
    <h1 class="color-palette-heading">Color Palette</h1>
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-primary">
            <p class="color-name">Primary</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-secondary">
            <p class="color-name">Secondary</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-success">
            <p class="color-name">Success</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-info">
            <p class="color-name">Info</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-warning">
            <p class="color-name">Warning</p>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xl-3 mb-3">
          <div class="color-box bg-danger">
            <p class="color-name">Danger</p>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
