# midterm2

function setup() {
  createCanvas(700, 700);
  angleMode(DEGREES);
  colorMode(HSB,100);
}
var x = 50
var y = 10
var i = 10
var z = 10
var j = 40
function draw()
{
  background(0,5)
  translate(width/2,height/2);
  colorMode(HSB,100);
  var r = random(255)
  
  
  rotate(y);
  noFill() 
  stroke(r,100,100)
  ellipse(y,y,y,y)
  y = y+2
  //rotate(y)
  //ellipse(y,y,y,y)
  //y = y+2
  //stroke(random)
  rotate(-y)
  rotate(-y)
  ellipse(i,i,i,i)
  i = i+1
  
   rotate(-y)
   rotate(-y)
   ellipse(z,z,z,z)
   z = z+1
   rotate(y)
   ellipse(j,j,j,j)
   j = j+1
  
  if(y>600){
    y=1;
    
  if(i>600){
    i=1;
    
  if(z>600){
    z=1;
    
  if (j>600){
    j=1;
  }
  }
  }
  }
}
