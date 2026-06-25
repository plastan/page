+++ 
title="meee"
js="https://cdn.jsdelivr.net/npm/p5@1.11.13/lib/p5.min.js"
sk="sketch.js"
+++

A self proclaimed chill person. 

_There are a lot of cools stuffs everywhere._

*und ich glaube , dass unser welt ist ambesser mit cool sachen.*


<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.0/p5.min.js"></script>


<script>
new p5(function(p) {
  p.setup = function() {
    p.canvas = p.createCanvas(p.windowWidth,p.windowHeight).parent('sketch-container');
    p.canvas.position= (0,0);
  };

  p.draw = function() {
    p.background(220);
    p.ellipse(p.mouseX, p.mouseY, 50, 50);
  };
});
</script>


