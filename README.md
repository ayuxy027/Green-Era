# Green Era

**Note: Readme is yet to be made but comments are added in the index.html file.**

Meanwhile, if you want to contribute something from your side, please follow these steps:

## Contribution Instructions

1. Run the following command in the terminal:

   ```bash
   npx tailwindcss -i ./src/input.css -o ./Frontend/page2.css --watch

2. Add detailed comments about the changes which you have made ;)

Hi, I am excited to say that I fixed your problem!

What I did:

   1. I switched lines 66 and 67 to this: 

   ```bash
    <div style="background: linear-gradient(to right, #d0f0ff 0%, #bae7ff 50%, #9be8b0 100%);"> 
      <div id="page2" id="flexbox" class="w-[100vw] h-[100vh] flex padding: [20px]">
   ```
   2. As you have probably noticed from the code above, I moved the id="flexbox" and class to the line with div id=page2.
   3. in page2.css I added the following on line 651: 

   ```bash
      #page2 {
      background-image: url("../Assets/corner-flower.png");
      background-repeat: no-repeat;
      background-size: cover;
      }
   ```
   4. I downloaded the image and placed it in the Assets folder with the name: corner-flower.png.
   5. Once you run it on the server, the image will overlap with the image on the right hand side. So one suggestion for you to fix that: 
   
   in page2.css on line 651 add the following:
   ```bash
   background-position: bottom;
