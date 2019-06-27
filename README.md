# IMAGE-PRO-PYTHON

import matplotlib.pyplot as plt
import matplotlib.pyplot as img

#reading png image file
im= img.imread('Desert.png')

#show image
plt.imshow(im)
plt.show()

#IMAGE PRO PYTHON 2

from PIL import Image
import matplotlib.pyplot as plt
import matplotlib.pyplot as img

#reading png image file
img= Image.open('Desert.png')
#resizing the image
img.thumbnail((50,50),Image.ANTIALIAS)
imgplot= plt.imshow(img)



plt.show()
