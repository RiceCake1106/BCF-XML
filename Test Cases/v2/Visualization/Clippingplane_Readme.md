# Clipping Plane

This test case verifies support for clipping plane in the viewpoint

## Testing process

1. Load _Architectural.ifc_ from the test cases root directory
2. Import _Clippingplane.bcfzip_
3. Verify the bcfzip was imported correctly:

> Verification paragrpah 1
> 1. Bcfzip file has one issue with one viewpoint
> 2. The viewpoint has one clipping plane that is cutting the model horizontally

> Verification paragrpah 2 

4. Export the topic(s) you imported to _exported.ifc_
5. Verify that no information was lost during the export

## (Optional) special notes

This is an optional section 

