# Full-Stack-MERN-AI-Image-Generator

I created my own improved version of an AI Image Generator using the OpenAI API.

AI image generation tools such as MidJourney and DALL-E have taken over the tech space. These tools are able to create a wide range of images, everything from memes and art to UI and UX designs. 

This application was made using React, MongoDB, Cloudinary, and Node.

The website was live at one point - however due to numerous complications with firebase (hosting service), I have decided to take it down.

This application is still possible to be used on a local server - The steps in which to do so are down below:

To run this application after downloading and unzipping the source code:

1. Press Ctrl + j to open the terminal 

2. cd into 'client' 

3. Type 'npm create vite' 

4. Enter y 

5. Select React as framework and JavaScript as variant

6. Run 'npm install'

7. Run 'npm run dev'

8. Ctrl + click localhost

9. Click 'Create' in the top right of localhost

10. Input 'Your Name' and enter your own prompt or click 'surprise me'

11. If 'SyntaxError: Unexpected token 'B', "Billing ha"... is not valid JSON' - This means that the application is out of credits as OpenAI gives $18 to new users. Other people have probably already spent the allocated credits using this service. To get rid of this error,  a new api key must be generated and added to a newly created .env file inside 'server'.

12. In the .env file it should read: OPENAI_API_KEY='x'- You can generate a new api by going to https://openai.com/api/ and click 'GET STARTRED'

13. Enter your details and then click on your profile in the top right and click 'View API Key'

14. Click 'Create new secret key'

15. In the .env file you created inside 'server', input the newly generated API key as OPENAI_API_KEY='x' and the application should work
