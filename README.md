# slider

1)Insert the slider html code into the required place;

2)connect a file with styles or add them to an existing file;

3)connect the slider js-script or insert it into an existing file;

4)init slider "slideShow('.slider')";

5)extra options:

    slideShow('.slider', {
      isAutoplay: false, // false (default) or true
      directionAutoplay: 'next', // 'next' (default) or 'prev'
      delayAutoplay: 3000, // 3000 (default) or any other number
      isPauseOnHover: true // true (default) or false
    });

    isAutoplay - automatic change of elements;
    directionAutoplay - direction of changing slides;
    delayAutoplay - delay in ms before automatically changing from one slide to another;
    isPauseOnHover - whether it is necessary to stop the automatic change of slides when the cursor is in the slider area;
    


slide control using methods:

        let sliderOne = slideShow('.slider');


Then you can use slide techniques. For example, in order to move to the next slide, you just need to call the show method:

      sliderOne.next();

Methods slide:

      stop - cancle automatic slide change;
      next - moves to the next slide;
      prev - goes to the previous slide;
      cycle - goes automatic slide change;
  

