For our Computer Graphics Exam I have been tasked with enhancing Mario Land 3 with Shaders. 

1st shader
For the first shader I included was a stencil shader. This stencil was very useful for this scene. I wanted to try and show a broken down 
warehouse/building. The stencil shader allows me to do this without complicated geomtery in modelling. It enhances the scene with complex looking
"Geomtry" When really its just covering up those pieces. I like how it looks broken down without as much effort. 

<img width="329" height="290" alt="Screenshot 2025-12-09 140100" src="https://github.com/user-attachments/assets/f47ce832-0692-4b60-9ed8-04aab440a88a" />
<img width="433" height="244" alt="Screenshot 2025-12-09 135600" src="https://github.com/user-attachments/assets/c2f7afdd-6eb7-4919-b8d5-ff803a45a05b" />

2nd shader 
For the second shader I included the vertex extrusion shader for polygon surface deformation. I did not have time to properly input coding but my plan for this 
shader would be to increase warios midsection when he collects the donuts. Similarly to the orginal game when he bulks upo to twice his size when he eats a donut but I added
a comical twist for a humor aspect as it is a game for all ages and Wario, although "evil" is often viewed in a comical way! * I include my early version of this idea and my final version of this idea.

EARLY VERSION:

<img width="379" height="203" alt="progress" src="https://github.com/user-attachments/assets/4007aec5-e103-4e88-86c5-3a97b74d3e6c" />
<img width="374" height="217" alt="Screenshot 2025-12-09 125742" src="https://github.com/user-attachments/assets/1dac2467-c2e8-4111-b81f-feb15090c5e2" />

FiNAL VERSION:

<img width="433" height="244" alt="Screenshot 2025-12-09 135600" src="https://github.com/user-attachments/assets/c208b6b1-3e39-41eb-b272-c8fa310e82b9" />
<img width="434" height="248" alt="Screenshot 2025-12-09 140721" src="https://github.com/user-attachments/assets/53663e67-ed3e-4870-ab97-1cf228a62662" />

For the final version I modified the script so that it includes both the vertex extrusion and the toon shading the rest if him has!
I have attached my code with starred changes:

![Screenshot 2025-12-09 133724](https://github.com/user-attachments/assets/d1878841-8990-400d-a322-d267f9f94119)

3rd shdaer: 
The thrid shader incluided along side he vertex extrusion shader was the toon shader. The toon shader felt most appriorate to rekindle the same feeling the orignal
cartoon style game has. I felt hyper realistic shading or graphics would feel out of place in this game. I have the toon shading applied in 2 areas:
firstly it is applied
to Wario; my creative choice to make him golden was based on 2 things. 1. the model I downloaded was poorly spilt up and 2. While looking at game references I saw "Wario Statues" from other Wario games
therefore felt fitting to add as an easter egg to other wario game players. 

<img width="335" height="218" alt="Screenshot 2025-12-09 133011" src="https://github.com/user-attachments/assets/a62b7e24-90da-4ae4-b4e4-8ba4f97f8325" />
<img width="150" height="183" alt="150px-MP9_StepItUp_GoldStatue_Wario" src="https://github.com/user-attachments/assets/f3523d6a-6b88-4b1d-8e10-2f7e76d1b11f" />

Secondly a modified version of the toon shader has been implemented on to the ground. I started with a basic toon shader than added some propeties from the specular PBR shader to add some metalness. 
I felt like in an old factory they wouldve had metal floors so it seemed appropriate.

![Screenshot 2025-12-09 141947](https://github.com/user-attachments/assets/f6bdd454-17ad-4d02-a720-dd37e5f2c3ca)
<img width="429" height="133" alt="Screenshot 2025-12-09 141622" src="https://github.com/user-attachments/assets/8514882b-8c87-4262-af20-c18dda91bd63" />

4th Shader: 
This shader is another mix between Toon Ramp and specular PBR shader but this one is very different from the pervious one. This one focuses on the specular PBR shader much more to have a metal effect but has the toon ramp image implemented as an additional texture so it is still metallic but had a added cartoon effect. This once again contributes to wanting to keep the game more on the toon side and less realistic while still having new and improved graphics. I applied this shader on some poles in the scene to add more props to the enviroment and making it look like th ebuilding is being held up by very little. This could come into play futher into game play when the building collaspes or wario has to break a pole to get to another area. 

<img width="329" height="290" alt="Screenshot 2025-12-09 140100" src="https://github.com/user-attachments/assets/4eb77830-f484-42e7-8593-7aa893e0bb6b" />

ADDITIONAL SHADERS!! 
I included additional shaders that are to enhacne the scene overall. 

- The donut has a basic transparency shader on it to make just the donut stand out without having to do complex geomtery.
- The wall has a brick texture applied to it within the stencil behind shader
- Finally the sky behind the wall in the background has a Multi UV shader applied with a enhanced blue tint.

IMAGES REFERENCED: 
![41+AXidWIWL _AC_UF1000,1000_QL80_](https://github.com/user-attachments/assets/02d3c16d-90d1-4483-85c0-ed9f4fa884ba)
<img width="263" height="235" alt="Screenshot 2025-12-09 133921" src="https://github.com/user-attachments/assets/8b0c729a-12aa-4001-b5ec-4f8a0eb27b5a" />
