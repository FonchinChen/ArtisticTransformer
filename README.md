# Creative Imaginator
This tool performs transformation on a given image to a new one using multimodal LLMs. 

## Target audience
This tool is designed for those seeking a straightforward method to generate DALL-E images without the need to master complex prompts. \
<br/>
Key features of this tool include:

- **Easy to use**. A user uplaods an image, select one of the serveral predefined styles/effects, and this tool will then proceed to re-imagine many aspects of the given image to create a new one. 
- Produces creative results within the bounds of the given image. This tool first converts the given image to text (which removes many visual details), then recreates new visual details following the guidance of the text and the selected style.\
\
Note that this tool is not intended for doing style transfer. For example, if you wish to convert your mugshot to have a certain particular style (e.g., cartoonized, impressionist, pencil drawing, etc.) while keeping face recognizable as you, then this tool is not for you.
- **Supports incremental refinement**. For example, once you have the following image created with this tool:\
![Image](images/girl&flowers_paper%20collage.png)\
then if you enter additional text instruction "redo the image with calla lilies in the background", then you may get something similar to the following:\
![Image](images/girl&flowers_redo%20image%20with%20calla%20lilies%20in%20background.png)\
It is worth noting that while many aspects of this image is different from the last one, such as compsition, posture, details in clothing, etc., much of the general style and character features are preserved.
- **Style composition**. It is easy to combine multiple effects in order to achieve more complex transformation. For example, given the following start image:\
![Image](images/dino0.png)\
we can turn it into the following:\
![Image](images/cutedino7.png)\
This is achieved by first applying the Simpsons effect on the starting image to get this:
![Image](images/dino4.png)\
then apply the Biomechanical Sculpture effect to get the final result.

## Live demo using a [Custom GPT](https://chat.openai.com/g/g-UpQkvuX7j-creative-imaginator) in OpenAI's GPT Store
Click on [this link](https://chat.openai.com/g/g-UpQkvuX7j-creative-imaginator) to open our custom GPT in your browser, and from there you will be able to upload your images and convert them to exciting art works!
<br>Please note as of January 2024, OpenAI still requires that you must have a GPT Plus subscription in order to access any GPT in their store. 

<!--
## How it works
This Custom GPT uses a given image as the inspiration for creating a new image, with the following steps:

* User provides an image
* A detailed textual description is extracted from the given image using OpenAI's multimodal GPT-4 model
* User selects the desired effect/style from a given list
* The extractd text and the given style are combined and given to OpenAI's DALL-E to generate an image.

This approach allows user to have control of the image generation process without having to learn prompt engineering, while still able to produce exciting images.
-->

## Supported artistic styles

* Reimage (original style)
* Illustration
* Photograph
* Oil painting
* Japanese anime style
* 3D animation style
* Linocut
* Paper diorama collage
* Biomechanical sculpture
* Glass sculpture
* Milk sculpture

## Effects demonstration
Each column below is a demo series to showcase the effects.

<table style="border-collapse:unset;">
  <tr>
    <td>DEMO-1</td>
    <td>DEMO-2</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td style="border-bottom:none;"><img src="images/dino600_original.png" style="width:300px" alt="Original image"><br>Original Image</td>
    <td style="border-bottom:none;"><img src="images/fairy0a.jpeg" style="width:300px" alt="Original image by Tú Nguyễn"><br>Original Image by Tú Nguyễn</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td><img src="images/dino600_reimage.png" style="width:300px" alt="Reimage (original style)"><br>Reimage (original style)</td>
    <td><img src="images/fairy600_reimage.png" style="width:300px" alt="Reimage (original style)"><br>Reimage (original style)</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><img src="images/dino600_illustration.png" style="width:300px" alt="Illustration"><br>Illustration</td>
    <td><img src="images/fairy600_illustration.png" style="width:300px" alt="Illustration"><br>Illustration</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><img src="images/dino600_photo.png" style="width:300px" alt="Photograph"><br>Photograph</td>
    <td><img src="images/fairy600_photo.png" style="width:300px" alt="Photograph"><br>Photograph</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><img src="images/dino600_oil.png" style="width:300px" alt="Oil painting"><br>Oil painting</td>
    <td><img src="images/fairy600_oil.png" style="width:300px" alt="Oil painting"><br>Oil painting</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
    
  <tr>
    <td><img src="images/dino2_anime.png" style="width:300px" alt="Japanese anime style"><br>Japanese anime</td>
    <td><img src="images/fairy2.png" style="width:300px" alt="Japanese anime style"><br>Japanese anime</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><img src="images/dino600_3d.png" style="width:300px" alt="J3D animation style"><br>3D animation style</td>
    <td><img src="images/fairy600_3d.png" style="width:300px" alt="3D animation style"><br>3D animation style</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
      
  <tr>
    <td><img src="images/dino600_linocut.png" style="width:300px" alt="Linocut"><br>Linocut</td>
    <td><img src="images/fairy5.png" style="width:300px" alt="Linocut"><br>Linocut</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
   
  <tr>
    <td><img src="images/dino600_paper.png" style="width:300px" alt="Paper diorama collage"><br>Paper diorama collage</td>
    <td><img src="images/fairy1-5.png" style="width:300px" alt="Paper diorama collage"><br>Paper diorama collage</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td><img src="images/dino7-2.png" style="width:300px" alt="Biomechanical sculpture"><br>Biomechanical sculpture</td>
    <td><img src="images/fairy600_bio.png" style="width:300px" alt="Biomechanical sculpture"><br>Biomechanical sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td><img src="images/dino600_glass.png" style="width:300px" alt="Glass sculpture"><br>Glass sculpture</td>
    <td><img src="images/fairy6-3.png" style="width:300px" alt="Glass sculpture"><br>Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td><img src="images/dino8.png" style="width:300px" alt="Milk sculpture"><br>Milk sculpture</td>
    <td><img src="images/fairy8.png" style="width:300px" alt="Milk sculpture"><br>Milk sculpture</td>
  </tr>
</table>

## Gallery

Each row below is a pair of images showcasing interesting transformation achieved during our experimentation.

<table>
  <tr>
    <td><img src="images/long_hair_lady_a.jpg" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/long_hair_lady_1.png" style="width:300px" alt=""><br>Transformed: Paper collage</td>
  </tr> 
  <tr>
    <td></td>
    <td></td>
  </tr>
 
  <tr>
    <td><img src="images/winter0a.jpg" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/winter8.png" style="width:300px" alt=""><br>Transformed: Milk sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td><img src="images/girl0a.png" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/girl6.png" style="width:300px" alt=""><br>Transformed: Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td><img src="images/sunflower0a.png" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/sunflower6.png" style="width:300px" alt=""><br>Transformed: Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <!--tr>
    <td><img src="images/dino4.png" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/cutedino7.png" style="width:300px" alt=""><br>Transformed: Biomechanical sculpture</td>
</tr-->  
  <!--tr>
    <td></td>
    <td></td>
  </tr-->
 
  <tr>
    <td><img src="images/cat0a.png" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/cat1.png" style="width:300px" alt=""><br>Transformed: Paper collage</td>
  </tr> 
  <tr>
    <td></td>
    <td></td>
  </tr>
  
  <tr>
    <td><img src="images/fish0a.png" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/fish6-5.png" style="width:300px" alt=""><br>Transformed: Glass sculpture</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
 
 <!--tr>
    <td><img src="images/girl0a.png" style="width:300px" alt=""><br>Original Image</td>
    <td><img src="images/girl6-5.png" style="width:300px" alt=""><br>Transformed: Glass sculpture</td>
  </tr--> 
</table>

<!--
## A note to Gen-AI practioners

We believe that beyond fun and creative pursue, this image-to-text-to-image approach can find useful technical applications in the realm of Gen-AI development.

Let's say we have a multimodal LLM for converting image to text, 
-->
