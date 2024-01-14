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

## Effect demonstration
<table>
  <tr>
    <td>Image</td>
    <td>Notes</td>
  </tr>
  <tr>
    <td>
      <img src="images/dino0.png" style="width:300px" alt="Original image">
    </td>
    <td>Original Image</td>
  </tr>
  <tr>
    <td><img src="images/dino1.png" style="width:300px" alt="paper collage"></td>
    <td>Effect: Paper collage</td>
  </tr>
  <tr>
    <td><img src="images/dino2_anime.png" style="width:300px" alt="Japanese anime"></td>
    <td>Effect: Japanese anime</td>
  </tr>
  <tr>
  <tr>
    <td><img src="images/dino3_popart.png" style="width:300px" alt="Pop art comics"></td>
    <td>Effect: Pop art comics</td>
  </tr>
    <td><img src="images/dino4.png" style="width:300px" alt="Simpsons"></td>
    <td>Effect: Simpsons</td>
  </tr>
  <tr>
    <td><img src="images/dino5.png" style="width:300px" alt="Woodcut"></td>
    <td>Effect: Woodcut</td>
  </tr>
  <tr>
    <td><img src="images/dino6-1.png" style="width:300px" alt="Glass sculpture"></td>
    <td>Effect: Glass sculpture</td>
  </tr>
  <tr>
    <td><img src="images/dino7-2.png" style="width:300px" alt="Biomechanical sculpture"></td>
    <td>Effect: Biomechanical sculpture</td>
  </tr>
  <tr>
    <td><img src="images/dino8.png" style="width:300px" alt="Milk sculpture"></td>
    <td>Effect: Milk sculpture</td>
  </tr>
</table>

## Gallery

<table>
  <tr>
    <td>Original Image</td>
    <td>Transformed image</td>
    <td>Effect applied</td>
  </tr>
  <tr>
    <td><img src="images/long_hair_lady.jpg" style="width:300px" alt=""></td>
    <td><img src="images/long_hair_lady_1.png" style="width:300px" alt=""></td>
    <td>Paper collage</td>
  </tr>
  <tr>
    <td><img src="images/winter0.jpg" style="width:300px" alt=""></td>
    <td><img src="images/winter8.png" style="width:300px" alt=""></td>
    <td>Milk sculpture</td>
  </tr>
  <tr>
    <td><img src="images/girl0.png" style="width:300px" alt=""></td>
    <td><img src="images/girl6.png" style="width:300px" alt=""></td>
    <td>Glass sculpture</td>
  </tr>
  <tr>
    <td><img src="images/sunflower0.png" style="width:300px" alt=""></td>
    <td><img src="images/subflower6.png" style="width:300px" alt=""></td>
    <td>Glass sculpture</td>
  </tr>
  <tr>
    <td><img src="images/dino4.png" style="width:300px" alt=""></td>
    <td><img src="images/cutedino7.png" style="width:300px" alt=""></td>
    <td>Effect: Biomechanical sculpture</td>
  </tr>  
  <tr>
    <td><img src="images/cat0.png" style="width:300px" alt=""></td>
    <td><img src="images/cat1.png" style="width:300px" alt=""></td>
    <td>Effect: Paper collage</td>
  </tr> 
  <tr>
    <td><img src="images/fish0.png" style="width:300px" alt=""></td>
    <td><img src="images/fish6-3.png" style="width:300px" alt=""></td>
    <td>Effect: Glass sculpture</td>
  </tr>  
  <tr>
    <td><img src="images/girl0.png" style="width:300px" alt=""></td>
    <td><img src="images/girl6-5.png" style="width:300px" alt=""></td>
    <td>Effect: Glass sculpture</td>
  </tr>  
</table>
