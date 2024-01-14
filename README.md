# Creative Imaginator
Perform artistic transformation on a given image using multimodal LLMs

## Live demo using a [Custom GPT](https://chat.openai.com/g/g-UpQkvuX7j-creative-imaginator) in OpenAI's GPT Store
Click on [this link](https://chat.openai.com/g/g-UpQkvuX7j-creative-imaginator) to open our custom GPT in your browser, and from there you will be able to upload your images and convert them to exciting art works!
<br>Please note as of January 2024, OpenAI still requires that you must have a GPT Plus subscription in order to access any GPT in their store. 

## How it works
This Custom GPT uses a given image as the inspiration for creating a new image, with the following steps:

* User provides an image
* A detailed textual description is extracted from the given image using OpenAI's multimodal GPT-4 model
* User selects the desired effect/style from a given list
* The extractd text and the given style are combined and given to OpenAI's DALL-E to generate an image.

This approach allows user to have control of the image generation process without having to learn prompt engineering, while still able to produce exciting images.

## Supported artistic styles
* Paper collage
* Japanese anime
* Pop art comic
* Simpsons
* Woodcut
* Glass sculpture
* Biomechanical sculpture
* Milk sculpture

## What this is not
This custom GPT is not meant for use as a beauty filter of style changer for human portraits, since the transformed face may not resemble the original.

## Effects demonstration
<table style="border-collapse:unset;">
  <tr>
    <td>Demo-1</td>
    <td>Demo-2</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td style="border-bottom:none;"><img src="images/dino0a.png" style="width:300px" alt="Original image"><br>Original Image</td>
    <td style="border-bottom:none;"><img src="images/fairy0a.jpeg" style="width:300px" alt="Original image"><br>Original Image</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino1.png" style="width:300px" alt="paper collage"><br>Paper collage</td>
    <td><img src="images/fairy1-5.png" style="width:300px" alt="paper collage"><br>Paper collage</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino2_anime.png" style="width:300px" alt="Japanese anime"><br>Japanese anime</td>
    <td><img src="images/fairy2.png" style="width:300px" alt="Japanese anime"><br>Japanese anime</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino3_popart.png" style="width:300px" alt="Pop art comics">Pop art comics</td>
    <td><img src="images/fairy3.png" style="width:300px" alt="Pop art comics">Pop art comics</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
    <td><img src="images/dino4.png" style="width:300px" alt="Simpsons">Simpsons</td>
    <td><img src="images/fairy4.png" style="width:300px" alt="Simpsons">Simpsons</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino5.png" style="width:300px" alt="Woodcut">Woodcut</td>
    <td><img src="images/fairy5.png" style="width:300px" alt="Woodcut">Woodcut</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino6-1.png" style="width:300px" alt="Glass sculpture">Glass sculpture</td>
    <td><img src="images/fairy6-3.png" style="width:300px" alt="Glass sculpture">Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino7-2.png" style="width:300px" alt="Biomechanical sculpture">Biomechanical sculpture</td>
    <td><img src="images/fairy7-2.png" style="width:300px" alt="Biomechanical sculpture">Biomechanical sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino8.png" style="width:300px" alt="Milk sculpture">Milk sculpture</td>
    <td><img src="images/fairy8.png" style="width:300px" alt="Milk sculpture">Milk sculpture</td>
  </tr>
</table>

## Gallery

<table>
  <tr>
    <td><img src="images/long_hair_lady_a.jpg" style="width:300px" alt=""></td>
    <td><img src="images/long_hair_lady_1.png" style="width:300px" alt=""></td>
  </tr>
  <tr>
    <td>Original Image</td>
    <td>Transformed: Paper collage </td>
  </tr>  
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/winter0a.jpg" style="width:300px" alt=""></td>
    <td><img src="images/winter8.png" style="width:300px" alt=""></td>
  </tr>
  <tr>
    <td>Original Image</td>
    <td>Transformed: Milk sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/girl0a.png" style="width:300px" alt=""></td>
    <td><img src="images/girl6.png" style="width:300px" alt=""></td>
  </tr>
  <tr>
    <td>Original Image</td>
    <td>Transformed: Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/sunflower0a.png" style="width:300px" alt=""></td>
    <td><img src="images/sunflower6.png" style="width:300px" alt=""></td>
  </tr>
  <tr>
    <td>Original Image</td>
    <td>Transformed: Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/dino4.png" style="width:300px" alt=""></td>
    <td><img src="images/cutedino7.png" style="width:300px" alt=""></td>
  </tr> 
  <tr>
    <td>Original Image</td>
    <td>Transformed: Biomechanical sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/cat0a.png" style="width:300px" alt=""></td>
    <td><img src="images/cat1.png" style="width:300px" alt=""></td>
  </tr> 
  <tr>
    <td>Original Image</td>
    <td>Transformed: Paper collage </td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/fish0a.png" style="width:300px" alt=""></td>
    <td><img src="images/fish6-3.png" style="width:300px" alt=""></td>
  </tr>
  <tr>
    <td>Original Image</td>
    <td>Transformed: Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="images/girl0a.png" style="width:300px" alt=""></td>
    <td><img src="images/girl6-5.png" style="width:300px" alt=""></td>
  </tr> 
  <tr>
    <td>Original Image</td>
    <td>Transformed: Glass sculpture</td>
  </tr>
</table>
