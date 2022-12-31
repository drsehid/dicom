# Working with DICOM files in python.
## What is DICOM?
DICOM stands for Digital Imaging and Communications in Medicine. DICOM files were introduced to maintain uniformity among varied types of medical image modalities. It is a standard format to view, store, share and retrieve medical images.

# Structure of DICOM:
1. Header:
- Device information(modalitye/scanner)
- Patient information
- Study UID
- Image information(shape, slice thickness,..)
- ...
2. Body:
- Image pixel data(2D, 3D, 4D)

## How to deal with DICOM files in python?
