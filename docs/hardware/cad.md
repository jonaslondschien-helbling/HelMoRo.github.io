# CAD 

## Downloads

In addition to the [Fusion 360 Widget ](https://helbling2.autodesk360.com/shares/public/SHd38bfQT1fb47330c99f726a386eb5b24d0) (HelMoRo with Raspberry Pi 5), we provide the model in the following formats:

- [Solidworks 2021](https://github.com/Helbling-Technik/HelMoRo/tree/master/cad/solidworks) 
- [STEP](https://github.com/Helbling-Technik/HelMoRo/tree/master/cad/step) 
- [STL](https://github.com/Helbling-Technik/HelMoRo/tree/master/cad/stl) 

Some files extend the file limit of 100 Mb, and therefore, we use [GitHub LFS](https://git-lfs.com/) (Large File Storage) to manage these large files effectively. Instructions how to use GitHub LFS can be found under [Collaboration](../../collaboration#accessing-the-repository).


## Naming Convention


The file names are in the following format:
**HEL-XX-UUYYY-RR.xyz**

- **HEL**: This prefix represents the client.
    <div style="margin-left: 20px;">
        <strong>&nbsp;&nbsp;&nbsp;HEL:</strong> Helbling (internal project)<br>
    </div>


- **XX**: This section indicates the type of the CAD file.
    <div style="margin-left: 20px;">
        <strong>&nbsp;&nbsp;&nbsp;01:</strong> Main assembly<br>
        <strong>&nbsp;&nbsp;&nbsp;03:</strong> Sub-assembly<br>
        <strong>&nbsp;&nbsp;&nbsp;04:</strong> Generative part or sheet metal<br>
        <strong>&nbsp;&nbsp;&nbsp;06:</strong> Purchased electronic part
    </div>


- **UU**: The creator of the part is specified here. User **01** up to **04** exist.

- **YYY**: The number of the part is composed of a three-digit code that starts from **000** and increments by one for each new part.

- **RR**: The revision number is a two-digit code that starts from **00** and increases with each subsequent revision of the CAD file.

- **xyz**: File type.
    <div style="margin-left: 20px;">
        <strong>&nbsp;&nbsp;&nbsp;sldsasm:</strong> SolidWorks assembly file<br>
        <strong>&nbsp;&nbsp;&nbsp;sldprt:</strong> SolidWorks part file<br>
        <strong>&nbsp;&nbsp;&nbsp;step:</strong> STEP file<br>
        <strong>&nbsp;&nbsp;&nbsp;stl:</strong> STL file<br>
    </div>
 

### Additional Notes

- The part number (**YYY**) resets to 000 for different part types (**XX**) and for each user (**UU**). For example, both HEL-04-01000-00 and HEL-06-01000-00 may exist as one is a generative part or sheet metal and the other is an electronic part.

- Fasteners, such as screws and nuts, do not have a part number.

### Example

**HEL-06-01000-01.sldprt**

- **HEL**: Helbling
- **06**: Purchased electronic part
- **01**: User 1
- **000**: Part number 0
- **000**: Revision number 1
- **sldprt**: SolidWorks part file





