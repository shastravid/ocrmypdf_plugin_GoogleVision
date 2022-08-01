# ocrmypdf_plugin_GoogleVision
A very minimalistic approach for an ocrmypdf plugin to use Google Vision as OCR engine.
Tesseract is currently used for rotation, so if Tesseract is not able to determine the correct rotation, there are some problems.
It doesn't matter for my particular use case, but it might for yours.

A cloudkey is also needed and must be in the same directory as cloudkey.json.
https://cloud.google.com/vision/docs/before-you-begin

Also borrowed some code from https://github.com/dinosauria123/gcv2hocr. Thanks a lot for your work.

1. copy all files to a directory
2. get the cloudkey and save it as cloudkey.json
3. pip3 install google-cloud-vision
4. call ocrmypdf from the currect diretory with --plugin gvision.py
