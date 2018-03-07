Planar coastlines (0...360) in VTK format that can be used with ParaView.
The coastlines will usually have to be scaled and/or translated to match the position 
of any dataset included in the ParaView project.

The coastlines were generated with GMT in two versions: without rivers and with rivers, 
each version at low, high, intermediate and full resolution. 

The GMT poly files were converted to VTK with a modified version of
Thorsten Becker's AWK script: gmtpoly2vtk.awk, 
available at https://github.com/thwbecker/grd2vtk
