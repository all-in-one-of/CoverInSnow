
# StaticSnow.hdanc is a Houdini Digital Asset which allows the user to cover an object in snow.

An example showing the digital asset in use is given in SnowCover_Example.hipnc and an example geometry to cover is given by Quercus_Rubra_Mature.obj


In Digital Asset Help Card:

NOTE:
   For snow to appear, the frame must be set to 240 as the snow particles must be shot to sky to verify where the snow will land. 
   
NOTE: 
   Some of the steps can be quite slow since a large number of particles are being used and a fluid surface is being generated to create a snow mesh.
   
NOTE:
    There are two other rendering options available inside the digital asset, but the asset must be unlocked to turn these on. 
    Their variables also need to be tweaked to give a good result.


Parameters:  

    Select View:
        There are 4 options:
        0 - Geometry to be covered with snow, in the form of fluid, covering it.
        1 - Geometry to be covered.
        2 - Snow particles.
        3 - Snow in the form of a fluid surface.
    
    Input Geometry:
        Geometry to be covered:
        0 - Torus
        1 - Geometry from geometry file
    
    Geometry File: 
        .bgeo file giving the object to be covered in snow.
    
    Slope Limit:
        Limit of the slope that snow will rest on. 0 will cover the entire object in snow, 1 will give no snow. 
    
    Height of snow:
        Gives height of snow above the surface of the covered geometry
    
    Up Direction:
        Direction along which the snow is heightened. Set to 010 initially, but can be changed to give a slight effect of wind. 
