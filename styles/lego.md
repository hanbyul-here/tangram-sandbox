Style by [@patriciogv](https://twitter.com/patriciogv)

Source Code: [style](https://github.com/tangrams/tangram-sandbox/blob/gh-pages/styles/lego.yaml) | [tangram](https://github.com/tangrams/tangram) | [patterns](http://tangrams.github.io/ProceduralTextures/)

Inspiration: [The Lego Movie](http://www.imdb.com/title/tt1490017/?ref_=fn_al_tt_1)

```glsl
vec2 st = fract(v_world_position.xy*0.07);

if (dot(v_normal,vec3(0.,0.,1.)) == 0.0){
    // Is a wall
} else {
    // Is a roof
}
```

<a href="code.html#shaders/brick.frag"><canvas class="canvas" data-fragment-url="shaders/brick.frag" width="200px" height="200px"></canvas></a>
#### Procedural brick wall pattern

<a href="code.html#shaders/lego-pattern.frag"><canvas class="canvas" data-fragment-url="shaders/lego-pattern.frag" width="200px" height="200px"></canvas></a>
#### Procedural lego pattern
