# hwcat
Rotates multiple JPEG files 90 degrees clockwise and stitches them together into a single pdf file.

I often need to write formulas and other work using a pencil on paper. However, I often then need to take pictures / a scan of this work and create a completed pdf with all of the pictures in the proper orientation. It has become cumbersome to do so repeatedly, hence this script.

`hwcat` is short for "homework cat," cat here referring to the linux bash command `cat`.

## Usage
Calling `hwcat pic1.jpg pic2.jpg pic3.jpg paper.pdf` will rotate pictures `pic1`, `pic2`, and `pic3` by 90 degrees clockwise, and concatenate them together into a pdf file called `paper.pdf`.

## Dependenies
Requires `convert`. Install via `dnf install convert` `apt install convert` etc. 
