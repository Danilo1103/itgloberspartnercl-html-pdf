# PDF Reader

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)]


Pdf reader allows you to render the pdf you want by passing it through children.

![image](https://user-images.githubusercontent.com/94373834/220145528-7fe2daad-3fb6-4a47-9a98-70bab5e770c2.png)

## Configuration 

1. Import the Bullet pdf-reader's app to your theme's dependencies in the manifest.json, for example:
```json
  "dependencies": {
    "vendor.pdf-reader": "0.x"
  }
 ```
 
 2. Add the pdf-reader block to the store-theme. For example:
```json
  "pdf-reader":{
    "props": {
      "pdfURL": "*Here goes your pdf*" ,
      "width": "*PDF Width*",
      "height": "*PDF Height*"
    }
  }
   ```
| Block name     | Description                                     |
| -------------- | ----------------------------------------------- |
| `pdf-reader` | ![https://img.shields.io/badge/-Mandatory-red](https://img.shields.io/badge/-Mandatory-red)  Top level block that must be declared in the store-theme block to render a default pdf reader viewer.   |

### PDF Reader

| Prop name    | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------- | ---------- | 
| `pdfURL`        | `string`       |  Define the url to render in the pdf-reader file       | `undefined`              |
| `width`        | `number`       | Define the width  to render pdf-reader      | `undefined`              |
| `height`        | `number`       | Define the height to render pdf-reader         | `undefined`              |


## Customization

No CSS Handles are available yet for the app customization.


## Contributors

1. [Danilo Ibañez](https://www.linkedin.com/in/danilo-ib%C3%A1%C3%B1ez-519a4023a/)

---- 

Check out some documentation models that are already live: 
- [Breadcrumb](https://github.com/vtex-apps/breadcrumb)
- [Image](https://vtex.io/docs/components/general/vtex.store-components/image)
- [Condition Layout](https://vtex.io/docs/components/all/vtex.condition-layout@1.1.6/)
- [Add To Cart Button](https://vtex.io/docs/components/content-blocks/vtex.add-to-cart-button@0.9.0/)
- [Store Form](https://vtex.io/docs/components/all/vtex.store-form@0.3.4/)