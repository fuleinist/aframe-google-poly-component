# aframe-google-poly-component
Include models from [Google Poly](https://poly.google.com) in your [A-Frame](https://aframe.io) projects!
![image](https://i.imgur.com/a91t4gO.gif)



## Getting Started

[Google Poly](https://poly.google.com) is a 3D model hosting service that allows creators to upload, remix and share 3D models. You can include these models directly in your aframe projects with this component.

### Prerequisites

You will need a Google Poly API key, which can be obtained here: [Google Poly API Key](https://developers.google.com/poly/develop/api)


### Installation (Scripts)

Download [the script](). Include it on your page after A-Frame, and all components will be registered automatically.

```html
<script src="aframe.min.js"></script>
<script src="aframe-google-poly-component.min.js"></script>
```

### Usage

In your `a-scene` tag, include the `google-poly` attribute with the `src:` property set as your google poly api key:

```html
<a-scene google-poly="api_key: GOOGLE_POLY_API_KEY" ></a-scene>
```

Once you've added your google poly api key to the scene tag, add the `google-poly` attribute to an entity. set the `src:` attribute to the id from a google poly url (example: poly.google.com/view/<span style="color:black; background-color: yellow;"><u>7U-93vxPOER</u></span>)

```html
<a-entity google-poly="src: 7U-93vxPOER;" ></a-entity>
```
You can also use the wrapped component:
```html
<a-google-poly src="7U-93vxPOER" ></a-google-poly>
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [Supermedium](https://github.com/supermedium) for [A-Frame](https://github.com/aframevr/aframe)

* [SAP SE](https://github.com/SAP) for supporting WebVR development
