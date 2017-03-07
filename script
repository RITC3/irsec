$(document).ready(function(){
    var currentMousePos = { x: -1, y: -1 };
    $('#out').mousemove(function(e) {
        currentMousePos.x = e.pageX;
        currentMousePos.y = e.pageY;
      
      $('#in').css('-webkit-mask-position-x', currentMousePos.x - 75);
      $('#in').css('-webkit-mask-position-y', currentMousePos.y - 75)
    });
});
