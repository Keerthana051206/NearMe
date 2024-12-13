# Ex04 Places Around Me
## Date: 13.12.2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map Example</title>
</head>
<body>
    <h1>Interactive Image Map </h1>
    
    <!-- Ensure the usemap attribute points to the name of the map -->
    <img src="ootyhomepage.jpg" alt="Map" width="757" height="527" usemap="#image-map" style="display: block; margin: 0 auto;">
    
    <map name="image-map">
        <!-- Area for "My Home" -->
        <area target="_blank" alt="My Home" title="My Home" href="page1.html" coords="227,212,367,252" shape="rect">
        
        <!-- Area for "Garden" -->
        <area target="_blank" alt="Garden" title="Garden" href="page2.html" coords="234,175,303,198" shape="rect">
    </map>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 1</title>
</head>
<body>
    <h1>MY HOME</h1>
    <p>Nestled in the heart of the Nilgiris, your home in Ooty is a serene haven surrounded by the enchanting beauty of nature. The house exudes warmth and charm, with its cozy architecture blending harmoniously with the lush green hills around it. The sloping roof and wooden accents add a rustic yet elegant touch, reminiscent of a traditional mountain retreat.

        Inside, the rooms are filled with natural light streaming through large windows that frame stunning views of mist-covered valleys and tea plantations. The crisp, cool air is complemented by the occasional warmth of a roaring fireplace, perfect for gathering with loved ones on chilly evenings.</p>
    <img src="keerthu1.jpg" alt="Page 1 Image" width="500" height="300">

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 2</title>
</head>
<body>
    <h1>GARDEN</h1>
    <p>Nestled in the cool and fertile embrace of the Nilgiris, it thrives with an abundance of life and color. The garden is a vibrant tapestry of flowering plants, from bright marigolds and zinnias to delicate roses and lilies, their blooms painting the landscape in vivid hues.

        Towering ferns and lush shrubs create a layered greenery, while patches of lavender and daisies add charm with their soft colors and subtle fragrances. The pathways are lined with moss-covered stones, leading to cozy nooks where you can relax with a book or enjoy a cup of tea.</p>
    <img src="keerthu2.jpg" alt="Page 1 Image" width="500" height="300">

</body>
</html>
```


## OUTPUT
![WhatsApp Image 2024-12-13 at 10 13 28_2b9b13ca](https://github.com/user-attachments/assets/20fc5d6d-1fb1-42fb-bf3d-0fb3f553bdcc)
![WhatsApp Image 2024-12-13 at 10 13 54_c6023f78](https://github.com/user-attachments/assets/a8fe8dd1-29ad-415a-8f13-72b71641cbdc)
![WhatsApp Image 2024-12-13 at 10 14 21_bf68caf4](https://github.com/user-attachments/assets/53f51da5-1d4c-46cb-9015-454a0756c2b1)
![WhatsApp Image 2024-12-13 at 10 14 58_83ea0474](https://github.com/user-attachments/assets/118a61a2-e38d-466a-8590-7de76490f73c)
![WhatsApp Image 2024-12-13 at 10 15 55_d5c61cb4](https://github.com/user-attachments/assets/14da7820-1ebb-49e1-9606-f54bd17745c8)








## RESULT
The program for implementing image maps using HTML is executed successfully.
