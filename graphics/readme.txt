*in eagle
**export silkscreen using CAM job, GTO(top), GTB(bottom) layers
**show only silkscreen layers (seperate for top and bottom)
**print to PDF (set to all black)

*in iknkscape
**import PDF
**edit
**object to path

*in Cenon
**select all
**change stroke width to 0.006(?) on non polygons
**group
*scale to 80%
*select group and drag group to left bottom corner. 
*reletive move to 0.016,0.016 (mil)
**export to gerber

*in gerbv (checking alignment)
**import gerber
**import original GTO layer from eagle CAM job
**check:)
