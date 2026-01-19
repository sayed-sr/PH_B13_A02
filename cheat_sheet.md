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
 <!-- ================================================================================================== -->






#choose .container .card-ctn{
    display: grid;
   grid-template-columns: 1.2fr 1fr 1fr;
    grid-template-rows: auto auto  auto;
    grid-template-areas:
        "card1 card21 card21"
        "card1 card22 card22"
        "card3 card3 card4";
    /* gap:30px; */

}
.card1 {
    grid-area: card1;

}

.card21 {
    grid-area: card21;
}

.card22 {
    grid-area: card22;
}

.card3 {
    grid-area: card3;
}

.card4 {
    grid-area: card4;
}


