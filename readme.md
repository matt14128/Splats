# Splatting

To make a splat, use an app such as scaniverse.

The easiest way to edit splats is with the [SuperSplat editor](https://superspl.at/editor).


To convert them into a good format or compress them so they are not as large, use [splat-transform](https://github.com/playcanvas/splat-transform).

```
splat-transform assets/LSLBoilerRoom_V2.splat -H 1 -N -F 60%  LSLBoilerRoom_V2_compressed60_SuperSplat.html
```

You can use our a-frame examples to bring a gaussian splat into an aframe scene from a .ply or .splat file, or the supersplat scenes are also viewable in VR.

You can also just upload your model to SuperSplat and then open it in VR.

easiest way to test is


``````
python -m http.server
``````