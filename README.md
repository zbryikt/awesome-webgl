# Awesome WebGL

Curated resources for WebGL / Three.js


### Maker
 * Misaki Nakano - https://twitter.com/misaki_mofu/status/849254334046978052
   - https://twitter.com/misaki_mofu?lang=en
   - https://mnmxmx.github.io/shadowmap-fog-demo/dst/
   - https://mnmxmx.github.io/halftone-effect/dst/
   - https://mnmxmx.github.io/rough-drawing-effect/dst/
   - https://twitter.com/misaki_mofu/status/849254334046978052 - use "postprocessing" shader
     e.g., https://threejs.org/examples/#webgl_postprocessing
 * Matt DesLauriers - https://twitter.com/mattdesl
 * Douglas Liliequist - https://twitter.com/DougLilliequist
 * Nadieh Bremer - https://twitter.com/NadiehBremer
 * Mathijs - https://twitter.com/mathijspb
 * Jaume Sanchez Elias - https://twitter.com/thespite/
 * Frank Reitberger - https://twitter.com/\_pwd\_
 * onom - https://twitter.com/onom
 * samsy - http://lab.samsy.ninja/

### For Your Inspiration
 * https://thebookofshaders.com/
 * http://www.davidcornette.com/glsl/noise.html
 * https://spite.github.io/looper/
 * twitter keyword: \#codevember - http://codevember.xyz/about
 * how to make water: https://twitter.com/thespite/status/1060343236538130437
   -  https://twitter.com/thespite/status/1059582577923756032
 * distortion transition - https://tympanus.net/codrops/2018/04/10/webgl-distortion-hover-effects/
 * http://lab.samsy.ninja/
 * https://medium.com/@gordonnl/fire-and-haze-b4561743b17
 * https://en.wikipedia.org/wiki/Spiral#See_also
 * animating noise - https://blog.demofox.org/2017/10/31/animating-noise-for-integration-over-time/

### Shader Library
 * Library
   - threejs Built-in: https://github.com/mrdoob/three.js/blob/master/src/renderers/shaders/ShaderLib.js
   - noise: https://gist.github.com/patriciogonzalezvivo/670c22f3966e662d2f83
     source: https://github.com/ashima/webgl-noise
     https://gist.github.com/megaton/13f6d8c856e9b02ea369
 * Gallery
   - http://glslsandbox.com/
   - https://www.shadertoy.com/
     - shadertoy to threejs - https://hackernoon.com/converting-shaders-from-shadertoy-to-threejs-fe17480ed5c6
   - https://www.geeks3d.com/shader-library/
   - https://assetstore.unity.com/packages/templates/packs/standard-shader-gallery-for-unity-58870
   - https://shaderfrog.com/app/?query=
   - http://lesleyvanhoek.nl/gallery/
   - https://www.vertexshaderart.com/
   - http://webglplayground.net/gallery
   - http://cargocollective.com/Noctuelles/Shader-Gallery
   - https://thebookofshaders.com/examples/
   * https://twitter.com/misaki_mofu/status/849254334046978052
   - some listed in README of https://github.com/glslify/glslify

### Tool
 * Online Shader Editor
   - http://editor.thebookofshaders.com/
   - editor + composer - https://shaderfrog.com/
   - GLSLWASMGIF - https://johan-nordberg.com/glslwasmgif/
   - http://glslb.in/
   - http://shdr.bkcore.com/

### JS Library:
 * good stuffs
   - volumetric file
     - https://github.com/yomotsu/VolumetricFire
     - https://github.com/mattatz/THREE.Fire
   - firework.js: flame, smoke, particles:  http://jeromeetienne.github.io/fireworks.js/
 * turn html into webgl: https://github.com/martinlaxenaire/curtainsjs
   - example: https://www.martin-laxenaire.fr/libs/curtainsjs/examples/simple-plane/index.html
 * unconventional text effect: https://blotter.js.org/
 * gl-shader - shader wrapper: https://www.npmjs.com/package/gl-shader
 * fss - http://matthew.wagerfield.com/flat-surface-shader/
 * three.ar.js - https://github.com/google-ar/three.ar.js
 * nodejs style module system for GLSL - https://github.com/glslify/glslify
   - 似乎只能在 build time 跑. runtime 則無法.

 * framework:
   - threejs
   - http://www.pixijs.com/
   - https://www.babylonjs.com/
   - low-level threejs alternative: https://twgljs.org/
   - http://scenejs.org/

### Miscellaneous
 * Helper
   - load shader into canvas - https://github.com/patriciogonzalezvivo/glslCanvas
 * for background
   - https://onomuta.github.io/onom-studio/warp.html
 * Raymarching
   - introduction - http://barradeau.com/blog/?p=575
   - https://computergraphics.stackexchange.com/questions/161/what-is-ray-marching-is-sphere-tracing-the-same-thing
 * minify threejs 
   - https://github.com/mrdoob/three.js/issues/7007 
     - https://github.com/mrdoob/three.js/issues/7007#issuecomment-131695212
   - https://github.com/mrdoob/three.js/issues/11003
   - unofficial builder: http://marcinwieprzkowicz.github.io/three.js-builder/
 * efficient gaussian blur
   - http://rastergrid.com/blog/2010/09/efficient-gaussian-blur-with-linear-sampling/
   - http://blog.ivank.net/fastest-gaussian-blur.html

### Algorithms and Mathematics
 * FBM: Fractional Brownian motion - https://en.wikipedia.org/wiki/Fractional_Brownian_motion
 * distance function
   - 3D: http://www.iquilezles.org/www/articles/distfunctions/distfunctions.htm
   - 2D: http://www.iquilezles.org/www/articles/distfunctions2d/distfunctions2d.htm
