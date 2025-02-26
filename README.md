Download Link : https://programming.engineering/product/project-shading-and-diffuse-reflection-for-advanced-microprocessor-3d-ge-design/

# Shading-and-Diffuse-Reflection-for-Advanced-Microprocessor-3D-GE-Design
Project: Shading and Diffuse Reflection for Advanced Microprocessor 3D GE Design
This project counts total 10 points.

    This project is for 3D shading model and diffuse reflection computation on LPC1769 micro processor platform for the purpose of design 3D Graphics Processing Engine, you will need to

        generate a solid cube and a top half of a sphere;

        The size of the cube with side length of 50 to begin with, and the virtual camera location E = (ex,ey,ez) = (150, 150, 100) for example. You can make some changes of these parameters to optimize visual display;

The size for the sphere is defined with a radius R = 100. You can make some changes of their sizes to optimize visual display;

Note: (a) place the top half sphere on the origin of xw-yw-zw; (b) the orientation of the cube is defined with one of its side in parallel with zw-axis. The cube floats from xw-yw plane by 10 unit, see illustration in Figure 1. and the center of the cube is at (80,80,35) to make room for the half sphere in the back.

            Define an arbitrary vector with P_i(0,0,35) and P_{i+1}=(200,220,40), and rotate the cube by 5 degree clockwise.

Fig. 1.

    compute diffuse reflection on the top surface of the cube, use one primitive color, for example red.

    place a point light source P_s(xs, ys, zs) in the world coordinate system, you design its location, as a reference, you may consider P_s(xs, ys, zs) = (-20,-20,220) as a testing location and you can make adjustment of its location later accordingly.

    compute the ray equation and its intersection with the x_w-y_w plane.

For the top surface of the cube there are 4 ray equations, each of the ray equations forms intersection point on the x_w-y_w plane.

keep track this set of 4 points and produce a shade of dark blue by plotting a polygon.

    compute diffuse reflection on the top surface of the cube. Assuming

reflectivity for red is 0.8 and for blue and green are 0.0.

        use scaling linear equation to scale up the diffuse reflection color from 20 to 255 for example with an offset = 20 or higher to

make diffuse reflection with the best dynamic range of the color.

    Use linear decoration algorithm to

        to place a tree on one of the 2 frontal surfaces of the cube per your

choice.

Option Bonus Points (3 pts): (a) compute diffuse reflection on visible part of the half sphere; or (b) decorate the half sphere by placing letter S (for SJSU) with you created font.

    What to submit:

        project readme to describe how to compile and run the code and describe your implementation, please write the readme using IEEE paper template given in the class github

(https://github.com/hualili/CMPE240-Adv-Microprocessors/blob/master/2018F/ Guidelines%20for%20Report%20Writing%20v2%20HL%202015-9-9.doc)

        source code and all development environment as an exported project. The submitted work (source code) are subject to testing and verification;

        photo of the finished display;

        15-20 second video clips, please name your video clip with your first and last name, 4 digits student ID, and cmpe240 class. Example: john-doe-1234-cmpe240.mp4

    Rubrics for project report (option with 2 pts):

        the report should cover (hardware part):

system block diagrams of the entire system setup including laptop computer; system block diagram of the SPI colour LCD interface

Schematics of the LPC1769 interface to LCD colour display panel

table(s) of the pin connectivity

photo(s) of the implementation

    the report (software part) should cover Algorithm description

Flow chart(s) Pseudo code

testing and verification section

source code listing (appendix)

(END)
