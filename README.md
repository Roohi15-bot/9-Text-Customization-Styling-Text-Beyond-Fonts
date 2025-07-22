#   1. Text Alignment

     p {
         text-align: center;
     }
     
Value	                  Description
> left	               Aligns text to the left (default)

> right	               Aligns text to the right

> center             	Centers the text horizontally

> justify           	Aligns text to both edges

 Useful for layout adjustments, especially in centered designs.

#  2. Text Decoration

       a {
           text-decoration: none;
      }
      
Value	               Description
> none	                Removes underline (commonly for links)

> underline            	Underlines the text

> overline	            Line above the text

> line-through	        Strikes through the text

 Combine with pseudo-classes like :hover for interactive styling.

#  3. Text Transformation

           h2 {
               text-transform: uppercase;
           }
           
Value             	Description
> uppercase	         Converts all letters to uppercase

> lowercase         	Converts all letters to lowercase

> capitalize	         Capitalizes the first letter

Great for headings, buttons, and UI consistency.

#  4. Text Shadow

Add depth or highlight text:

      h1 {
          text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
      }
      
Syntax:
     text-shadow: x-offset y-offset blur color;
     
 Can be subtle (accessibility) or creative (headlines).

 # 5. Letter Spacing & Word Spacing
 
          h2 {
              letter-spacing: 1px;
              word-spacing: 5px;
          }
          
Property	               Purpose
> letter-spacing	       Controls space between characters

> word-spacing	         Controls space between words

 Enhances readability in logos, headings, or decorative titles.

 # 6. White Space Control
 
           p {
             white-space: nowrap;
          }
          
Value	                Description
> normal             	Default, text wraps normally

> nowrap             	Prevents wrapping

> pre	                Preserves whitespace and line breaks like pre tag

> pre-line	          Collapses whitespace but keeps line breaks

 Use nowrap in buttons, badges, or dynamic tables to avoid broken lines.

 # Bonus: Multi-Line Text Truncation
 
           .ellipsis {
                     white-space: nowrap;
                     overflow: hidden;
                     text-overflow: ellipsis;
            }
            
 Useful for preview cards or mobile UIs.

 # Summary
Property	                What It Does
> text-align	                  Aligns the text

> text-decoration             	Underline, strike, overline

> text-transform              	Changes casing (uppercase/lowercase/etc.)

> text-shadow                 	Adds shadow behind text

> letter-spacing	              Spacing between letters

> word-spacing	                Spacing between words

> white-space	                  Manages text wrapping and spacing

> text-overflow               	Truncates overflowing text with ellipsis







