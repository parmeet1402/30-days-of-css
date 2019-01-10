# Notes
* ### __Day - 28__ - Optimizing CSS
    1. Code Better    
     Crap in, Crap Out _i.e. if you write bad code, bad output will be coming out._
        
        1. Use Shallow selectors  
            Try to be as general as possible when using selectors. 
        
        1. Organize your code  
            Put Table of Contents in top of stylesheet.
        
        1. Use shorthand property  
            Wherever possible, try to use shorthand property.

    1. Validate your code  
         Use Tools like CSS Optimizer
    1. Compress your CSS  
        Have a developer CSS file named ``app.css`` and have a folder named production where you will have another ``app.css``
    1. Preload your CSS in browser  
        ``<link rel="preload" href="app.css" as "style">``  
        _The above code will tell the browser to load the file a bit early._
    1. Lighten up the framework  
        Ony have files which are required from the framework, remove the rest of all the files.

    1. Learn a Pre-Processor Language
        * It will save coding time.
        * Give flexibilty while styling.
        * Export Highly Optimized images
---
