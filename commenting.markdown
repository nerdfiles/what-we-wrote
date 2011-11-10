# Headers

## Python

### File Header

    # -*- coding: utf-8 -*-
    #
    # ======================================= filename.py == #

    """
      ...

      @project          projectname
      @contributor      handle (handle@domain.com)
      @contributor      handle (handle@domain.com)
      @datetime         11.4.2011.11.56.a
      @devlogin         admin/password
    """

### Alt File Header

    # -*- coding: utf-8 -*-
    #
    # mode_indexes.py
    #
    # ...
    #
    # @project          projectname
    #
    # =================================================== #

### Long Section Header with Documentation

    # == CLASS ======================================= #
    
    """
      @author           spinoza
    """

### Long Section Header

    # == IMPORTS ======================================= #

### Subsection Header

    # == pythonpath inserts == #

### Django

#### Large Comment

    {#

      This is a large comment.

    #}

## Templating

### Include Filepaths

Helpful for tracing in templates. Wrap in function using general language to toggle visibility, say through `DEBUG_MODE`, etc.

    <!-- == @src ./themes/themename/header-base.html == -->

## JavaScript

@see JsDoc Toolkit (http://code.google.com/p/jsdoc-toolkit/w/list)

## CSS

@see cssdoc0.2.22 (http://cssdoc.net/wiki/CssdocDraft)

### Disclaimer

Not sure if the following syntactic constructions are consistent w/ or amenable to cssdoc. Consider them proposals.

### File Header

    /* ====================================== filename.scss ==
     *
     * Main Stylesheet for domain.com
     *
     * ...
     *
     * @package         core
     * 
     * == */

### Alt File Header

    /* ====================================== filename.css ==

      Main Stylesheet ''

      ...

      @version          0.0.1

    == */

### Long Section Header

    /* ==
     *
     * SECTION
     *
     * ...
     * 
     * @version         0.0.1
     *  
     * ====================================== */

### Alt Long Section Header

    /* ==

      SECTION

      ...

      @version          0.0.1

    ====================================== */

### Short Section Header

    /* == SECTION ====================================== */

### SASS/SCSS Section Header

    // == SECTION ====================================== 

### Endings

Optional SASS/SCSS endings. In case you nest like a son-of-a-bitch. 

#### Section, Blank

    /* ====================================== */
     
     

### Section, Short & Sweet

    /* == */
     
     

### Section, Alt SASS/SCSS Short & Sweet

    // == 
     
     

#### Section

    /* == End body._template ====================================== */
     
     

#### Section, Alt SASS/SCSS

    // == End .container.[widget1|widget2].ul.li ====================================== 
     
     
    
### Notes

#### Alt SASS/SCSS

Quick, meaningful notes (or tags) to find codeblocks.

    // #ie-bug

## HTML

### File Header

Usually after `<!DOCTYPE>`.

    <!-- ======================================= FILE DETAILS ==

    /**
     * Base Template for domain.com
     *
     * @file            base.html
     *
     * @author          
     * @designer        
     * @org             
     * @copyright       [CC INSERT]
     * @date            09.25.2011.1.09.p.cst
     * @project         project-name
     */

    == -->

### Short Section Header 

    <!-- == BEHAVIOR: ANALYTICS ======================================= -->

### Long Section Header

    <!-- == CONTENT ======================================= 

            CONTENT UI

            Put a website here or something.

    ======================================================= -->

### Alt Long Section Header

    <!-- == CONTENT ======================================= 

            CONTENT UI

            Put a website here or something.

    == -->

### Begin Dev Section

I read `@class` and `@id` as doubles for beginnings of sections. The closings are harding to find.

### End Dev Section

    <!-- End #elem.class.class -->

### Note

For finding codeblocks; tagging. Search for `// #...`.

    <!-- // #fix -->

### Dev Blank Page

Usually just before `</body>` and just after `<body>`; consider just after `<!DOCTYPE>` as well.

    <!--










              This section has been intentionally left blank.










    -->
     

