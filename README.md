Steganography is the art and science of communicating in a way which hides the existence of the communication. In contrast to Cryptography, where the enemy is allowed to detect, intercept and modify messages without being able to violate certain security premises guaranteed by the cover message with the embedded cryptosystem. The goal of Steganography is to hide messages inside other harmless messages in a way that does not allow any enemy to even detect that there is a second message present.

Steganography is employed in various useful applications, e.g. secret communication among agencies / people, copyright control of materials, enhancing robustness of image search engines and smart IDs (identity cards) where individuals’ details are embedded in their photographs. Other applications are video-audio synchronization, companies’ safe circulation of secret data, TV broadcasting, TCP/IP packets. In steganography many different carrier file formats can be used, but digital images are the most popular because of their frequency on the Internet.

Digi-Stegano implements following steganographic methods-

->  1 bit, 2 bits, 3 bits and 4 bits LSB (hiding as well as extraction)
->  24 bits plane (Red, Green, Blue) and 32 bits plane (Red, Green, Blue, Alpha) analysis of image
->  Bitwise XOR Implementation between LSB and payload
->  Steganography Based on File Format.

To run this application download the source code from this repository, extract it.
In linux, 
  cd Download 
  -> select the extracted folder
  -> goto bin folder 
  -> finally java -jar ImageStegeno.jar.
  
  
  
  
