# Closet
Closet Android app designed to store information on your clothes and suggest more that fit your aesthetic.



## loginView 
      -Pretty straightforward i mean its a log in page
      -Gotta set up DB schema to handle acc creation
   

## myCloset View 
    -Lists already owned clothing to a listview
    -QR scanned clothing from scannerView
    -Expanded myCloset View
        -Price
        -Size 
        -Image of clothing
        - (Above needs to be stripped) 
        
    -Analysation of data in order to create suggestions
    
## storeView
    -Lists number of brands that matches acc style (Diagram 1)  
        -From storeView goes to expanded storeView with suggestions (Diagram 2) 
        -Takes articles from stores and displays for customers 
        - (need a way to strip that data, hey shane ;] ) 
        
## scannerView 
    -Acts as a QR scanner for clothing (maybe machine learning if we can get initial demo running) 
    -Finds article from websites and adds details to myCloset
