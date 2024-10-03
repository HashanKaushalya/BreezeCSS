# BreezeCSS

BreezeCSS is a lightweight CSS framework built with Sass, designed for easy customization and a consistent user experience across web projects.

## Installation

You can easily install BreezeCSS using npm or by downloading it directly from the repository.

### Using npm

1. Navigate to your project directory.
2. Run the following command:

   ```bash
   npm install breeze-css

Direct Download
Go to the [BreezeCSS GitHub repository](https://github.com/HashanKaushalya/BreezeCSS).
Click on the "Code" button and select "Download ZIP."
Extract the files and place them in your project directory.

Usage
Including BreezeCSS in Your Project
To use BreezeCSS, include the compiled CSS file in the <head> section of your HTML file:
<link rel="stylesheet" href="path/to/breeze.css">

Applying Styles to HTML Elements
BreezeCSS provides a consistent theme for standard HTML elements. Here are some examples of how to use it:

Headings
<h1 class="heading">Main Title</h1>
<h2 class="heading">Subtitle</h2>

Lists
<ul class="list">
    <li>Item 1</li>
    <li>Item 2</li>
</ul>

Buttons
<button class="btn btn-primary">Click Me</button>

Forms
<form>
    <label for="name">Name:</label>
    <input type="text" class="input" id="name" name="name">
</form>

Tables
<table class="table">
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
    </tbody>
</table>

## Utility Classes

BreezeCSS includes utility classes for quick styling. Here are some examples:

<p class="text-primary">This text is in the primary color.</p>
<p class="font-weight-bold">This text is bold.</p>
<p class="font-size-lg">This text is larger.</p>
<div class="m-3 p-3 border">This div has margin, padding, and a border.</div>

## Customization

### Using Sass Variables

To customize BreezeCSS, modify the Sass variables defined in the _variables.scss file. Here are some key variables you can change:

$primary-color: #3498db;  // Change the primary color  
$font-size-base: 16px;     // Change the base font size  
$heading-font-weight: 700; // Change the font weight for headings  


### Compiling Sass

After making your changes, you will need to compile the Sass files into CSS. Use the following command:

sass input.scss output.css

Replace input.scss with your main Sass file and output.css with the desired output filename.

### Including Customized CSS

After compiling, include your customized CSS in your HTML file:

<link rel="stylesheet" href="path/to/your-custom-breeze.css">

# Conclusion

By following these instructions, you can easily install, use, and customize BreezeCSS for your web projects.

