## Rendering DOM Within WebGL

For this project I wanted to learn more about shaders, how WebGL renders, and possibly using GLSLify on the project. I did this by reading through a case study by a developer from the Agency Firstborn about a project they’d done for the video game Titanfall. The case-study was about how they’d rendered the DOM in a WebGL texture. Their reasoning for using this method came from the want to have a WebGL heavy site but allow people with “a slow connection or slow computer” to view the content. I read over the case study and then got to work. The project centered around an SVG with a foreign object containing all the HTML and CSS, it was to be converted into a base64 image and then sent to a texture where I was able to use it inside WebGL. The process was a lot of me looking up terms and how to do what the actually case studied mentioned and then implementing what they talked about. I had no idea what things like Blobs were but I had to use it. Through the creation of this project I learned about taking apart shaders from ShaderToy and using them with Three.js as well as the OpenGL 2 rendering process. The shaders I used started with basic post processing ones like an RGB shift but then I tried to figure out more interesting ones. I ended up not doing anything with GLSLify because of the complexity of using it the vector shaders in my project. I also wanted to create my own shader to work with the image but in the end I got too busy with finals and thought that learning the way other people made their own shaders through shader toy was probably more beneficial. I’m happy that I took on this project but I definitely should’ve done a bit more research into what I wanted to accomplish before I started and got locked in. I know I could’ve scoped this better and I’m happy that I know that now. Thanks for a good semester.