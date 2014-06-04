Build tool:

    gcc *.c -o imgdata

To use tool:

  Decompile:

    ./imgdata extract NameOfImage.img decompiled

  Build:

    ./imgdata build decompiled out

Flash:

    fastboot flash imgdata NameOfNewImage.img
