#SASS Library

##Basic Project setup


Read about [Content First](https://www.everydaydesigner.net/design/change-your-focus-and-design-content-first)

###Typography Rule:  Modular Scale and Vertical Rhythm

Read about [modular-scale](http://www.modularscale.com/) which exists as a [library](https://github.com/modularscale/modularscale-sass) and how it is implemented in [Bourbon](http://bourbon.io/docs/#modular-scale).  Modular scale forms the basis of _Vertical Rhythm_ preset based on modular scales.  

3 Libraries for establishing Vertical Rhythm

*   [Gridlover](https://github.com/LndnMdiaLb/Sassy-Gridlover.git) preffered. clean codebase

*   [Sassline](https://demo.sassline.com/) Sassline may have best setup for Overide section

*   [Typeplate](http://typeplate.com/) provides styling for specific font (Ampersand)


###Responsive Layout

Flexbox is the future

Float based Libraries

*   Singularity

*   Bourbon Neat


###File Setup

    Project
    |
    |-- base.scss
    |    
    +-- utils
    |  |  
    |  |-- reset.scss
    |  |-- media-queries.scss    
    |    
    +-- typography
    |  |  
    |  |-- base.scss  modular-scale/vertical-rhythm - GridLover
    |  |-- custom.scss  project fonts etc
    |
    +-- layout
    |  |  
    |  |-- custom.scss
    |    
    +-- libs
    |  |  
    |  +-- Sassy-Gridlover/        
    |  +-- bourbon/  
    |  +-- neat/

       variables - colors schemes etc?
       layouts - Responsive Structure base on Neat
