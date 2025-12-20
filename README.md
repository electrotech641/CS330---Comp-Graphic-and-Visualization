# CS330---Comp-Graphic-and-Visualization

Final Reflection
Derick Silva
12/20/2025


	    In my scene I chose to depict a shelf I have here in my office. The objects include a levitating NFL helmet, a 
  snow globe, a stack of books, and a Rubik’s cube. I chose this scene because of the multiple types of objects 
  in it, as well as the complexity of the objects. The snow globe I knew would take multiple basic shapes to 
  recreate, while the Rubik’s cube and stack of books would be relatively easily to recreate the geometry. I ended 
  up replacing the levitating helmet with a levitating globe of the earth because as I started work on the 
  helmet, I quickly realized that It would ne extremely difficult to recreate convincingly using basic shapes 
  instead of modeling software. When applying textures, I took photos of the objects to try and realistically 
  recreate them in 3D. To apply the textures correctly, I had to utilize the SetTextureUV mapping method.
	    A user can navigate my scene using WASD for movement and the mouse to look around. Speed can be increased or 
  decreased using the scroll wheel. Using CTRL and SPACEBAR, the user can move up or down in the scene, while O 
  and P can be used to change perspectives. In addition to these controls, I added mouse sensitivity control 
  using + and – on the numpad. To increase sensitivity, the user can press + on the numpad and to decrease 
  sensitivity, the user can press – on the numpad. 
	In the given shader files, I made modifications to preserve the textures alpha channels. I did this so that 
  my snow globe would appear transparent in the correct places. I added a callback function for the MouseScrollWheel 
  that processes the scroll wheel and increases or decreases movement speed. This can easily be reused in future 
  projects anytime I need to use the scroll wheel for user input. When adding this function, I made sure I put 
  it near the other input processing functions to keep my code organized. This ensures the next time I visit 
  this code, I can easily navigate it and find what I am looking for. 
	    All in all, I learned a lot in completing this project and I thoroughly enjoyed the process. Texture mapping 
  is a big takeaway, as well as applying lighting. While I will be using everything I learned here extensively in 
  the future, these are two things I intend to explore further, since I feel there is still a lot to learn there. 
