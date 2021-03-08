automax

---

3/8/2021: tested with latest version of Max8. Have not connected to OBD sensor - but the patch, itself works. Although there are dozens of pictctl error messages in the Max Console. I'm not sure what's causing them. Probably the nanocontroller panel - but it doesn't affect the operation of the patch. Will be testing OBD sensor again soon.

6/25/2014 Documentation at: [http://reactivemusic.net/?p=16708](http://reactivemusic.net/?p=16708)

Example of using OBD-II diagnostic port to read RPM data and control Max/MSP engine simulation

---

Instructions:

- download or clone the archive
- in Max add the automax folder to your file preferences.
- load the patch: automax.maxpat

At this point you can play the engine sounds - if you have an ELM-327 bluetooth OBD-II device, you should be able to get it to read RPM from your car. If you have a Korg nanocontroller you can use it to control the patch.

---

Acknowledgements:

- Uses Max versions of patches by Andy Farnell from "Designing Sound"
- Uses Fourier Filter patch from Katja Vetter
- Uses Max abstractions to replicate various Pd objects 

---

Disclaimer: drive carefully!
  
