# Mapping Geotagged Images  v1.0

This script requires JPG images with geotagged information in the header, stored in a Dropbox folder that is publicly shared and an ArcGIS Online account capable of publishing services and maps.

To use:
1. Code block 1, line 20: Point to a local Dropbox folder with photos.  Photos can be in subdirectories.  Non-JPG files are ignored. A CSV file is gernated int he folder and used to create the ArcGIS Online layer. 
3. From the Dropbox.com website, share your folder and copy the shared folder URL. 
4. Code block 1, line 6: Add "&preview=" to the end of the URL and insert into script below (baseDropBoxSharefolder=).  It will look like: https://www.dropbox.com/sh/6icw00y0uuuiszc/AADIl61HVsZuzc5i3MuPZfv1a?dl=0&preview=
5. Code block 2, line 5: Add your ArcGIS Online username, password and subdomain.
6. Access your AGO account after running this script to find your new layer.  Createa new map and add the layer to it. Set sharing as needed.

-Tom, October 2018
