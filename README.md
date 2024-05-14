<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [CSS BOX MODEL DOCUMENTATION](#css-box-model-documentation)
  - [Content:](#content)
  - [Padding:](#padding)
  - [Boarder:](#boarder)
  - [Margin:](#margin)
  - [Width and Height:](#width-and-height)
  - [Box Sizing:](#box-sizing)
  - [Display Types:](#display-types)
  - [CSS Box Model Image:](#css-box-model-image)
  - [Conclusion:](#conclusion)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# CSS BOX MODEL DOCUMENTATION  

The CSS Box Model is a fundamental concept in web development that defines the layout and design of elements on a webpage. It comprises several components, each affecting how elements are displayed and interact with each other. Here's a breakdown of the CSS Box Model:  
## Content:  
- The innermost part of the box model.  
- Represents the actual content of the element, such as text, images, or other media.  
- Its size is determined by the width and height properties.  
## Padding:  
- Space between the content and the border of the element.  
- Can be set using the padding property.  
- Helps create space around the content, enhancing readability and aesthetics.  
  ### Padding Code Example:  
  ```css
  .box {
        padding: 10px;
      }

  ```
## Boarder:  
- A line that surrounds the padding and content of an element  
- Defined by properties such as:  
__border-width, border-style,__ and __border-color.__  
- Borders can be __solid, dashed, dotted,__ etc., and can have different thicknesses and colors.  
    ### Boarder Code Example:  
    ```css
    .box {
        border: 1px solid black;
      }

  ```
## Margin:  
- Space outside the border of an element.  
- Created using the margin property.  
- Determines the distance between the element and its adjacent elements.  
- Useful for controlling layout and spacing between elements on a webpage.  
  ### Margin Code Example:  
  ```css
  .box {
          margin: 10px;
        }

  ```
## Width and Height:  
- Specifies the dimensions of the content box.  
- Width refers to the horizontal dimension, while height refers to the vertical dimension.  
- Can be set explicitly using the width and height properties.
- Determines the size of the content area, excluding __padding, border, and margin.__   
  ### Width and Height Code Example:
  ```css
  .box {
      width: 200px; /* Sets the width of the box to 200 pixels */
      height: 150px; /* Sets the height of the box to 150 pixels */
  }
  ```
## Box Sizing:  
- Determines how the total width and height of an element are calculated.  
- By default, the width and height properties only apply to the content area.  
- With box-sizing, you can include padding and border in the total width and height calculation.  
- Values for box-sizing include __content-box (default) and border-box.__    
  ### Box Sizing Code Example:  
  ```css
  .box {
      box-sizing: border-box; /* Includes padding and border in the total width and height */
      width: 200px; /* Sets the width of the content area to 200 pixels */
      padding: 20px; /* Adds 20 pixels of padding */
      border: 2px solid #000; /* Adds a 2px solid black border */
  }```

## Display Types:  
- Elements can be displayed as __block, inline, inline-block, flex, grid,__ etc.  
- The display type affects how the element interacts with other elements and its box model properties.  
- Block elements span the full width of their container by default, while inline elements only take up as much width as their content.  
  ### Display Types Code Examples:
    ```css
      .block {
        display: block; /* Renders the element as a block-level element */
    }

    .inline {
        display: inline; /* Renders the element as an inline-level element */
    }

    .inline-block {
        display: inline-block; /* Renders the element as an inline-level block container */
    }

    .flex-container {
        display: flex; /* Creates a flex container */
        /* Other flex properties like justify-content, align-items, etc. can be applied */
    }

    .grid-container {
        display: grid; /* Creates a grid container */
        /* Other grid properties like grid-template-columns, grid-gap, etc. can be applied */
    }
  ```    
## CSS Box Model Image:
![CSS Box Model Image](./assets/CSS-Box-Model.webp)  
## Conclusion:  

Understanding the CSS Box Model is crucial for creating consistent and visually appealing layouts on webpages. By mastering the above, developers can effectively control the spacing, sizing, and positioning of elements to achieve the desired design.
