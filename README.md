jquery_drag
===========

jquery ui revert to original position functionality added to plugin<br><br>


$('.drag').draggable({<br>
    revert: 'invalid',<br>
    revertToOgPos: true<br>
});

//revertToOgPos values are 'true' or 'false'<br><br>




$('.drop').droppable({<br>
    singleItem: true<br>
});
<br>
// this will allow only single item to be dropped into droppable and it will revert the Item which is already dropped.
