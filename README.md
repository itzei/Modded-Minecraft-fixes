CodeChickenLib is a fixed version, where the unpatched .jar throws an "java.lang.NoSuchFieldError: lastBrightnessY", this patch just eliminates the use of lastBrightnessY with a fullbright value (there are probably better fixes for this specific issue but I couldn't be bothered)


bma.class is a fix for Intel integrated GPUs where modern drivers completely corrupts textures in older versions of Minecraft
(Tested on UHD 620)
To apply this fix you need to open up your minecraft versions .jar file, using WinRar or other tools and then just replace the existing bma.class file.


Disclaimer: all of these fixes aren't mine, pulled from the internet, uploaded here for ease of access and archival purposes.
