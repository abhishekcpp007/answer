# answer

**1.Static:**

The default position value. Elements with position: static; are rendered in the normal flow of the document.

Example:

  html
  <div class="static-position">
    This element has static position.
  </div>

  css
  
  .static-position {
    position: static;
  }
  
**2.Relative:**
The element is positioned relative to its normal position. You can use properties like top, right, bottom, and left to adjust its position relative to itself.
Example:
   
    html
    
    <div class="relative-position">
      This element has relative position.
    </div>
  
    css
    
    .relative-position {
      position: relative;
      top: 20px;
      left: 30px;
    }
    

**3.Absolute**:

The element is positioned relative to its nearest positioned ancestor. If no positioned ancestor exists, it is positioned relative to the initial containing block.
Example:

html
    <div class="relative-parent">
      <div class="absolute-child">
        This element has absolute position.
      </div>
    </div>

css

    .relative-parent {
      position: relative;
      height: 200px;
    }

    .absolute-child {
      position: absolute;
      top: 50px;
      left: 20px;
    }

    
**4.Fixed:**
The element is positioned relative to the browser window. It remains fixed even when the page is scrolled.
Example:

html
    
    <div class="fixed-position">
      This element has fixed position.
    </div>

css
    
    .fixed-position {
      position: fixed;
      top: 20px;
      right: 30px;
    }

    
**5.Sticky:**
The element is positioned based on the user's scroll position. It acts like relative until the specified threshold is met, and then it becomes fixed and remains fixed until the user scrolls past the element.
Example:

html
    <div class="sticky-position">
      This element has sticky position.
    </div>

css
    
    .sticky-position {
      position: sticky;
      top: 50px;
    }












