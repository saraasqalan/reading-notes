# CSS
 Transforms, Transitions, and Animations
![CSS](https://miro.medium.com/max/1000/0*z-NzK5spBWCM5gp_.jpg)
**Transforms**
The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

**Transform Syntax**
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
![syntax](https://miro.medium.com/max/1440/1*_NVMTnvHTM9teQxrVRlDeg.png)
**2D Rotate**
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.
- first you should insert box or any thing in HTML 
  .  < figure class="box-1">Box 1< /figure>
- then you should write a transform rotate in CSS

    . box-1 {
  transform: rotate(20deg);
}
- now you can see the result

![rotate](https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2014/12/transform-origin-examples.png)

**2D Scale**
Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
- first you should insert box or any thing in HTML 
  .  < figure class="box-1">Box 1< /figure>
- then you should write a transform rotate in CSS
    . box-1 {
  transform: scale(.75);
}
- now you can see the result

**2D Translate**
The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis

- first you should insert box or any thing in HTML 
  .  < figure class="box-1">Box 1< /figure>
- then you should write a transform rotate in CSS

  .box-1 {
  transform: translateX(-10px);
}
- now you can see the result

![translate](https://www.gatevidyalay.com/wp-content/uploads/2019/08/2D-Translation-in-Computer-Graphics.png)

**2D Skew**
The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.%p

- first you should insert box or any thing in HTML 
  .  < figure class="box-1">Box 1< /figure>
- then you should write a transform rotate in CSS
.box-1 {
  transform: skewX(5deg);
}
- now you can see the result
![skew](https://cdn.educba.com/academy/wp-content/uploads/2020/06/CSS-skew.jpg)

***YOU CAN USE MORE THAN ONE TRANSFORM TOGETHER***



# 3D Transforms
Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements

**3D Rotate**
So far we’ve discussed how to rotate an object either clockwise or counterclockwise on a flat plane. With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ.
- first you should insert box or any thing in HTML 
  .  < figure class="box-1">Box 1< /figure>
- then you should write a transform rotate in CSS
  transform: perspective(200px) rotateX(45deg);
}
- now you can see the result

![rotate](https://media.24ways.org/2010/desandro/transforms01.png)

**3D Scale**
By using the scaleZ three-dimensional transform elements may be scaled on the z axis. This isn’t extremely exciting when no other three-dimensional transforms are in place, as there is nothing in particular to scale. In the demonstration below the elements are being scaled up and down on the z axis, however the rotateX value is added in order to see the behavior of the scaleZ value.
- first you should insert box or any thing in HTML 
  .  < figure class="box-1">Box 1< /figure>
- then you should write a transform rotate in CSS
 .box-1 {
  transform: perspective(200px) scaleZ(1.75) rotateX(45deg);
}
- now you can see the result

![Scale](https://www.tutorialrepublic.com/lib/images/css3-3d-scale-illustration.png)

**3D Translate**
Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element. Using a positive value will pull an element closer on the z axis, resulting in a larger element.

- first you should insert box or any thing in HTML 
  .  < figure class="box-1">Box 1< /figure>
- then you should write a transform rotate in CSS
  .box-1 {
  transform: perspective(200px) translateZ(-50px);
}
- now you can see the result

![translate](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2018/07/1530807976119-3d-transforms-02-translate-scene.png)




