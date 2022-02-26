# Case studies

## Automatic Fingerprint Identification System (AFIS) Simulation
An innovative upstart offering Forensic Training and hand on crime scene experiences under the direction of an experienced Fingerprinting and Forensic Expert.
The only catch was that there are no AFIS samples out there, so we needed to build one from scratch.

The AFIS system allows users to upload a fingerprint sample, mark the identifying features on the fingerprint and search for similar prints from the database and identify the suspect.

The system was built using a Django backend with jQuery and JavaScript libraries to provide the user with the required UX interractions.

## Vote recognition and capture system
An election management company felt restricted by the aging vote recognition software and licensing limitations and were in need of a refreshing change.
The existing Election Management Software was built in Django so the replacement voting paper processing system was built into the existing system.

The final solution read the barcodes from the voting paper to identify the location of each issue and candidate.
Contour recognition locates the voting locations, then either determines if theire is a tick or reads the handwritten digit for a preference vote.
All of this is done in the browser session, with a separate web worker thread doing the heavy lifting to keep the user session running smoothly.
OpenCV.js does the image manipulation and detecting ticks on the vopting paper
TensorflowJS reads the hand written digits, including double digit numbers

CodeSandBox examples:
- [Training a CNN to read MNIST handwritten digits (tutorial)](https://bzsi3.csb.app/)
- [Reading multi-digit hand written numbers](https://vb1bn.csb.app/)


[resume](cv.md)
