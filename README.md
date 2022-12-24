## Functions

Functions to make development faster

1. showToast()

• Takes config. object as an argument and displays a toast on the screen.
• Currently availabe customizations ( These are defaults ) :-
  {
    text: "Lorem Ipsum Text",   // Text to display on toast
    posi: 3,                    // Position of toast on the screen.
    time: 4,                    // Display for N seconds.
    fontSize: "1.1rem",         // Text size
    backgroundColor: "#353a40", // Toast BG color
    borderRadius: "4px",        // Border radius
    color: "#fefefe",           // Text color
    fontWeight: "600",          // Font weight
    padding: "1.4vh 3vh",       // Padding
    fontFamily: "Arial",        // Font
  }

• For Position of toast, chosse a number between 0-8 to show on various poistions of screen.
       1---------2---------3
       |         |         |
       8---------0---------4
       |         |         |
       7---------6---------5

• Simple usage : Use the source code as is in your projects or use the following CDN link.
  
  CDN : 
  
  Useage : showToast( { text: "This is a toast", posi: 7 } )
  
  
• Open for suggestions if you have any other feature in mind. 

Thank You 😇
  
