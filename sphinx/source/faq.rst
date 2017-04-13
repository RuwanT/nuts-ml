FAQ
===

What is the default image representation in nuts-ml?
----------------------------------------------------

The standard formats for image data in **nuts-ml** are Numpy arrays
of shape ``(h,w,3)`` for RGB images, ``(h,w)`` for gray-scale images
and ``(h,w,4)`` for RGBA image.



What image formats can nuts-ml read?
------------------------------------

The ``ReadImage`` nut can read images in the following formats
GIF, PNG, JPG, BMP, TIF, NPY, where NPY are plain Numpy arrays.