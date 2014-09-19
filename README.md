jquery_drag
===========

jquery ui revert to original position functionality added to plugin


$('.drag').draggable({
    revert: 'invalid',
    revertToOgPos: true
});

//revertToOgPos values are 'true' or 'false'




$('.drop').droppable({
    singleItem: true  // this will allow only single item to be dropped into droppable and it will revert the Item which is already dropped.
});
