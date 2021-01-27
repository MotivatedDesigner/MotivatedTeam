# html breakdown

### Layout : 
        -> navbar : fixed in the left side
        -> home section
        -> about section
        -> portfolio section
        -> skills section
        -> experiences section
        -> contact section

### general remarks :
        - use of semantic tag like (nav,section) is great for easy access lik for users with screen reader & also for SEO
        - wrapping elements with <div> for easy styling & layout controll
        - missing "../" in the img[src] needed for relative paths

### missing head : 
        - doctype which let the browser know what version of HTML you are using 
        - language of the website & other SEO meta
        - title
        -  meta content to handle the scale of the website on other devices 

### section : 
        - <h2> as section title

### home section :
        - there is an empty p.text-animation, why?
        - missing #port & #exp for the href value in anchor links pointing to portfolio & experiences 
        - div. medias wrap 3 anchor links each one of them has an attribute target=" blank" to open the link in a new tab

### about section :
        - using <span> to style list numbers insteade of div to keep them inline
    
### experiences section :
        - there is five icons but only four jobs
    
### contact section :
        - using <strong> in the section title for the word "stay" to make it standout more
        - missing email label for email text input & using placeholder attribute instead