<!-- --- title: Using Altium Design with AISLER -->
# Using Altium Designer with AISLER
To use AISLER with Altium Designer you will need to export your project as a Gerber-Package. Please make sure you zip your Gerber-Files. 

### Most important design rules to use with Altium Designer ###
Use these design rules to get optimal results with AISLER's production. 

- Min. trace width: 100 μm
- Min. trace spacing: 100 μm
- Min. pitch between traces: 140 μm
- Spacing PCB edge to trace: 200 μm
- Spacing via to via: 0.30 mm
- Spacing drill to drill: 0.15 mm
- Min. drill diameter for vias: 0.2 mm
- Min. via pad diameter: Via drill + 0.25 mm
- Min. stroke width of legend print: 100 μm

### Exporting Gerber Files with Altium Designer ###
AISLER expects the gerber files in the following format:

<table>
<tr><th>Gerber Layer Name</th><th>Layer</th></tr>
<tr> <td>project_name.toplayer.ger</td><td>Top Layer</td> </tr>
<tr> <td>project_name.bottomlayer.ger</td><td>Bottom Layer</td> </tr>
<tr> <td>project_name.topsoldermask.ger</td><td>Top Soldermask</td> </tr>
<tr> <td>project_name.bottomsoldermask.ger</td><td>Bottom Soldermask</td> </tr>
<tr> <td>project_name.topsilkscreen.ger</td><td>Top Silkscreen</td> </tr>
<tr> <td>project_name.bottomsilkscreen.ger</td><td>Bottom Silkscreen</td> </tr>
<tr> <td>project_name.boardoutline.ger</td><td>Board Outline</td> </tr>
<tr> <td>project_name.xln</td><td>PTH Drills</td> </tr>
<tr> <td>project_name_npth.xln</td><td>NPTH Holes</td> </tr>
</table>

Make sure that in your export settings you select 2:4 precision and inches for your drill files.

**Please note:** Upload all your Gerbers in one ZIP-File for us to automatically detect your project's parameters. Also please do not include any other files that are not listed above.

### Steps to upload your project to AISLER ###

1. Navigate to [Start new project](https://go.aisler.net/p/new "Start new Project")
2. Upload your Gerber zip-file (*.zip)
3. Give your Project a nice name
4. (optional) order a copy of your board

### Steps to document your Bill-of-Materials
There are two ways to document your bill-of-materials

1. Navigate to the project you want to document 
2. Click the 'Edit' button under the Bill-of-Materials section
3. Click 'Manually add part' and assign a part
4. Repeat until you have everything documented
