# Using custom marker:
- use aframe v0.6.0 <br>
`<script src="https://aframe.io/releases/0.6.0/aframe.min.js"></script>`
- use ar.js v1.5.5 <br>
`<script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.5.5/aframe/build/aframe-ar.js"></script>`
- use link to .patt file on a hosted server <br>
`<a-marker-camera preset="custom" type="pattern" url="https://raw.githubusercontent.com/alexxss/custom-marker/master/marker.patt"></a-marker-camera>`
- use gray instead of white in custom marker img

# Using animated gltf:
- use aframe extras<br>
`<script src="https://cdn.rawgit.com/donmccurdy/aframe-extras/v4.0.2/dist/aframe-extras.min.js"></script>`
- use animation-mixer<br>
`<a-entity gltf-model="#boxes" scale="0.5 0.5 0.5" position="0 1 0" animation-mixer></a-entity>`
