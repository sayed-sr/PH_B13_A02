/* When we want two photos to overlap: 
   The second (upper) photo will be centered over the first (background) photo.
   Example: the hero section.
*/

.parent {  
    /* the container holding both images */
    position: relative;
}

.first-photo { 
     /* background photo */
       <!-- set the height and width as our need -->
}

.child {  
    /* the top photo that overlaps */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 1;      
    object-fit: contain;  
     <!-- set the height and width as our need -->
}

<!-- ================================================================================================ -->





#hero{
vertical-align: middle;
background-image: url(assets/hero-bg.png) ;
background-repeat: no-repeat;
background-position: center;      /* center the image */
width: 100%;                       /* full width of screen */
height: as need;

}
