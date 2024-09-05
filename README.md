# 3DRender

This program is for use with ARIA/Eclipse, which is a commerical radiation treatment planning software suite made by Varian Medical Systems which is used in Radiation Oncology. This is one of several programs which I have made while working in the Radiation Oncology department at Lahey Hospital and Medical Center in Burlington, MA. I have licensed it under GPL V3 so it is open-source and publicly available.

There is also a .docx README file in the repo that describes what the program does and how it is organized.

This is a helper program for CollisionCheck. It displays a 3D image of the path of the linac gantry head and the patient and the treatment table for each beam in an RT plan that CollisionCheck has been asked to analyze.
The image appears automatically when CollisionCheck is done with its analysis for each beam. This helps the dosimitrists visualize the situation and understand what the CollisionCheck program is doing.

The CollisionCheck program explicitly notifies users of any potential collisions it detects per beam. The images displayed by 3DRender are to help the dosimitrists visualize the potential collision.

Please note that 3DRender uses a library called HelixToolkit to render 3D images.
