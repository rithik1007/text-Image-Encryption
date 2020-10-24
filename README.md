# text-Image-Encryption
Using Double encryption modules to encrypt a text within an image which then is encrypted again , the process uses foyr different algorithms 
First unzip the file in a new seprate folder,open cmd in that location
run img2img.py which consist of two images lines and batman 
after the first encryption we then have an output pic3in2.png
then run the watermarking.py to encode the encrypted image with a text inside it.
then run the encrypt.py with the image name , for example python encrypt.py pic3in2.png
after some time you will find the ewncrypted image inside the encrypted image folder , we used rubix cube principal to make the encrypted image
then to decrypt we run decryption, for example python decrypt.py pic3in2.png 
then we will have to enter the two keys value and iteration value  in order to decrypt.
