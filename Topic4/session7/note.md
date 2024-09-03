# Image properties

## Scale

* Scale means to <em>resize an image with respect to its original size</em>.
* Syntax:
	* `\includegraphics[scale=0.5]{parrot.png}`
	* Here `scale=0.5` means that we will reduce the size of the image by half of its original size.

## Crop

* Crop means to remove unwanted areas of an image and display the important ones.
* Syntax:
	* `\includegraphics[clip=true, trim=15mm 5mm 7mm 3mm]{parrot.png}`
	* In order to crop the image, we need to first set the `clip` argument to true.
	* The `trim` argument takes 4 values:
		* Left.
		* Bottom.
		* Right.
		* Top.
	* Here, our image will be cropped by 15mm from the left, 5mm from the bottom, 7mm from the right and 3mm from the top.

## Rotate

* For rotating an image:
	* `\includegraphics[angle=60]{parrot.png}`
	* The argument `angle` rotates the image.
	* Here the image is rotated by 60 degrees.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session7/doc1.tex).

---
