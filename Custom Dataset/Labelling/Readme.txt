1. Download the Labelling File.
2. Create 3 files with name "Images", "Labels" and "Multiple_Images" in the labelling folder only.
3. Create folder with name of the classes in the Images folder and the Labels folder.
4. In the label folder make folder like "output_classname" for each class.
5. Paste all the images the respective folder.
6. Run the code in the command prompt "python bbox_tool.py"
7. Label the images with the bbox tool.
8. Now go in the convert.py file and change the classes names in the 13th line. It will contain all our classes.
9. For every class the convert file will run once. So each time for converting the label in which YOLO understand edit the code from 32 to 39.
10.Now copy each of the images and the .txt file from the output_classname folder and paste all of them in the Multiple_Images Folder.
11. Our dataset is ready in Multiple_Images folder.