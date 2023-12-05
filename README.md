### Hi there 👋

<svg id="hs" width="400" height="400" xmlns="http://www.w3.org/2000/svg">
 <defs>
    
    <filter id="glow">
          <fegaussianblur class="blur" result="coloredBlur" stddeviation="8"></fegaussianblur>
          <femerge>
            <femergenode in="coloredBlur"></femergenode>
            <femergenode in="coloredBlur"></femergenode>
            <femergenode in="coloredBlur"></femergenode>
            <femergenode in="SourceGraphic"></femergenode>
          </femerge>
   </filter>
   
   <filter id="filter-broken" filterUnits="objectBoundingBox" x="0" y="0" width="100%" height="100%" color-interpolation-filters="sRGB">
      <feImage preserveAspectRatio="xMidYMid meet" xlink:href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 800 800'%3E%3Crect width='70%25' height='70%25' fill='white'/%3E%3Ccircle cx='50%25' cy='50%25' r='500' %0Afill='none' stroke='black' stroke-width='950' stroke-dasharray='200'/%3E%3C/svg%3E" result="lense"/>
      <feDisplacementMap scale="10" xChannelSelector="B" yChannelSelector="G" in2="lense" in="SourceGraphic" result="glass-effect"/>
      <feMerge>
        <feMergeNode in="SourceGraphic"/>
        <feMergeNode in="glass-effect"/>
      </feMerge>
   </filter>
 </defs>
  
    <style type="text/css">
  <![CDATA[
    #svg_8{transform-origin:center;}
      
svg {
  position: absolute; 
  top: 50%; 
  left: 50%; 
  transform: translate(-50%, -50%); 
  filter: url('#filter-broken');
  /*
  url('#glow');
  */
}
#svg_12 {
  url('#glow');
  mix-blend-mode:multiply;
  transform-origin:center;
}
.path {
  animation:  animation1 3s ease-in-out 1s infinite alternate;
  fill-opacity: .25;
}
.p_0{
  animation:  animation2 3s ease-in-out .5s infinite alternate;
}

@keyframes animation1 {
  from {transform: perspective(400px) rotateX(20deg);}
  to {transform: perspective(400px) rotateX(-20deg);}
  from {transform: perspective(400px) rotateY(20deg);}
  to {transform: perspective(400px) rotateY(-20deg);}  
  from {stroke-width: 1;}
  to {stroke-width: 9;}
}

@keyframes animation2 {
  from {transform: perspective(400px) rotateX(20deg);}
  to {transform: perspective(400px) rotateX(-20deg);}
  from {transform: perspective(400px) rotateY(20deg);}
  to {transform: perspective(400px) rotateY(-20deg);}  
  from {stroke-width: 1;}
  to {stroke-width: 2;}
  from {stroke-opacity: .4;}
  to {stroke-opacity: 1;}
}

   ]]>
  </style>
  
 
  
 <g>   
 <g fill="#1a1b1f" id="svg_8">
   <path class="p_0" stroke-width="1.5" stroke="#000000" id="svg_6" d="m302.47663,282.55895c-11.5319,-4.19342 -12.58025,5.76595 -33.28525,-1.57253l-40.62373,-14.67696l40.62373,-14.67696c20.705,-7.60057 21.75335,2.62089 33.28525,-1.57253c4.71759,-1.57253 7.60057,-7.86266 5.76595,-12.58025c-1.57253,-4.71759 -2.88297,-4.19342 -4.45551,-8.91101c-1.57253,-4.71759 -0.52418,-4.97968 -2.09671,-9.69728c-1.57253,-4.71759 -7.86266,-7.60057 -12.58025,-5.76595c-11.5319,4.19342 -5.76595,12.58025 -26.47095,20.18082l-62.63917,22.27753l-62.63917,-22.80171c-20.705,-7.60057 -15.20114,-15.9874 -26.47095,-20.18082c-4.71759,-1.57253 -11.00772,1.31044 -12.58025,5.76595c-1.57253,4.71759 -0.52418,4.97968 -2.09671,9.69728c-1.57253,4.71759 -2.88297,4.19342 -4.45551,8.91101c-1.57253,4.71759 1.31044,11.00772 5.76595,12.58025c11.5319,4.19342 12.58025,-5.76595 33.28525,1.57253l40.62373,14.67696l-40.62373,14.67696c-20.705,7.60057 -21.75335,-2.62089 -33.28525,1.57253c-4.71759,1.57253 -7.60057,7.86266 -5.76595,12.58025c1.57253,4.71759 2.88297,4.19342 4.45551,8.91101c1.57253,4.71759 0.52418,4.97968 2.09671,9.69728c1.57253,4.71759 7.86266,7.60057 12.58025,5.76595c11.5319,-4.19342 5.76595,-12.58025 26.47095,-20.18082l62.63917,-22.27753l62.63917,22.80171c20.705,7.60057 15.20114,15.9874 26.47095,20.18082c4.71759,1.57253 11.00772,-1.31044 12.58025,-5.76595c1.57253,-4.71759 0.52418,-4.97968 2.09671,-9.69728c1.57253,-4.71759 2.88297,-4.19342 4.45551,-8.91101c1.83462,-4.71759 -1.04835,-11.00772 -5.76595,-12.58025z" fill="null"/>
   <path class="p_0" stroke-width="1.5" stroke="#000000" id="svg_7" d="m200,57.68695c-34.85778,0 -62.90126,28.04348 -62.90126,62.90126l0,55.0386c0,5.76595 3.40715,13.62861 7.60057,17.55993l18.60829,17.29785c4.19342,3.93133 8.91101,11.26981 10.22145,16.24949s7.33848,9.1731 13.10443,9.1731l26.20886,0c5.76595,0 11.79399,-4.19342 13.10443,-9.1731s6.02804,-12.31816 10.22145,-16.24949l18.60829,-17.29785c4.19342,-3.93133 7.60057,-11.79399 7.60057,-17.55993l0,-55.0386c0.52418,-34.85778 -27.5193,-62.90126 -62.37708,-62.90126zm-30.14019,128.4234c-10.22145,0 -17.03576,-8.38683 -17.03576,-17.03576c0,-8.64892 8.12475,-14.41487 18.3462,-14.41487s18.3462,5.50386 18.3462,14.41487c0,8.64892 -9.69728,17.03576 -19.65664,17.03576zm30.14019,23.58797c-5.24177,0 -7.86266,-2.62089 -7.86266,-7.86266s5.24177,-15.72531 7.86266,-15.72531s7.86266,10.48354 7.86266,15.72531s-2.62089,7.86266 -7.86266,7.86266zm30.14019,-23.58797c-10.22145,0 -19.65664,-8.38683 -19.65664,-17.03576c0,-8.64892 8.12475,-14.41487 18.3462,-14.41487s18.3462,5.50386 18.3462,14.41487c0,8.64892 -6.8143,17.03576 -17.03576,17.03576z" fill="null"/>
    
   <path id="svg_12" class="path" d="m88.5,80.45313l272.5,79.54688l-231,189l-41.5,-268.54688z" stroke-opacity="null" stroke-width="1.5" stroke="#000000" fill="none"/>
   
      <path id="svg_13" class="path" d="m88.5,80.45313l272.5,79.54688l-231, 189l-41.5, -268.54688z" stroke-opacity="null" stroke-width=".3" stroke="#e29e29" fill="none" transform="rotate(45)"/>


   </g>
 
 </g>
    <animateMotion dur="5s" repeatCount="indefinite" rotate="auto-reverse">
      <mpath href="#svg_13"/>
    </animateMotion>
</svg>

body { 
  overflow:hidden;
  height:100vh;
  width:100vw;
  background:#1d1e22;
  --c1: #1d1e22;
  --c2: #444857;
  background-image: -webkit-linear-gradient(top, var(--c1), var(--c2));
  background-image: -moz-linear-gradient(top, var(--c1), var(--c2)));
  background-image: -o-linear-gradient(top, var(--c1), var(--c2)));
  background-image: -ms-linear-gradient(top, var(--c1), var(--c2)));
  background-image: linear-gradient(top, var(--c1), var(--c2)));
}

function randomValues() {
  var timeline = anime.timeline({
    duration: function() {
        return anime.random(0, 270);
      },
    delay: [45, 250],
    direction: 'alternate',
    easing: 'easeInOutQuint',
    autoplay: true,
    loop:true,
  });
  timeline.add({
    targets: ['feDisplacementMap'],
    scale:[5 , 30]
    });
  timeline.add({
    targets: ['#svg_8'],
    fill: ['#150485', '#590995', '#c62a88', '#03c4a1'],
    scale: [.5, 1.05],
    complete: randomValues
    });
};

randomValues();

var stroke_anim1 = anime({
  targets: ['#svg_12'],
  strokeDashoffset: [anime.setDashoffset, 0],
  points: [
    { value: [
      '88.5,80.45313l272.5,79.54688l-231,189l-41.5,-268.54688z',
      '207.5,185.45313l156.5,-26.45313l,190l-44.5,-268.54687z']
    },
  ],
  fill: ['#150485', '#590995', '#c62a88', '#03c4a1'],
  stroke: ['#f1e7b6', '#fe346e', '#400082', '#00bdaa'],
  easing: 'easeOutQuad',
  duration: 2000,
  autoplay:true,
  loop: true,
});

var stroke_anim2 = anime({
  targets: ['.p_0'],
  strokeDashoffset: [anime.setDashoffset, 0],
  points: [
    { value: [
      '88.5,80.45313l272.5,79.54688l-231,189l-41.5,-268.54688z',
      '207.5,185.45313l156.5,-26.45313l,190l-44.5,-268.54687z']
    },
  ],
  stroke: ['#f1e7b6', '#fe346e', '#400082', '#00bdaa'],
  easing: 'easeOutQuad',
  delay:1000,
  duration: 2000,
  autoplay:true,
  loop: true,
});


var rotate_stroke_anime = anime({
  targets: ['#svg_13 path' ],
  easing: ['easeOutInCirc'],
  strokeDashoffset:  [10, 0],
  duration: 1000,
  opacity:.5,
  skewY:100,
  skewX:100,
  autoplay:true,
  direction:'normal',
  loop: true,
  stroke:[.3, 1],
});

<!--
**cph0r/cph0r** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
