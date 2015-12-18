## Nullify Image Perspective

### A fun illustration of affine transform and bilinear interpolation

Given a photograph taken off-axis of a planar subject, we can reverse the perspective effect of the camera angle and display the subject without the geometric distortions due to perspective.

<table border="0" style="width:80%;border:0px"> <tr style="border:0px">
    <td style="width:50%;border:0px">
        <img src="images/tapestry.jpg" width="200px"/>
    </td>
    <td style="width:50%;border:0px">
        <img src="images/tapestry rectified.jpg" width="265px"/>
    </td>
</tr> </table>

This repository discusses and demonstrates how this is done. The presentation <b>perspective.ipynb</b> is in the form of an IPython Notebook, which allows a user to modify parameters and to apply the code to his own data. Its interactive features are only available, if the IPython Notebook App and a suitable Python development environment have been installed. Installing Anaconda is an excellent way to prepare a system for Python coding and for using IPython Notebooks. Anaconda is a completely free Python distribution for scientific purposes. It manages the installation of optional packages and can even do so for multiple configuration environments. Download Anaconda <a href=“http://continuum.io/downloads”>here</a>. 

A static html copy of the presentation is also included.