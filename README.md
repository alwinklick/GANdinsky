# GANdinsky
A Generative Adversatial Net to generate Paintings inspired by the work of Wassily Kandinsky. 

## Wassily Kandinsky
Famous artist Wassily Kandinskys work can be divided in different phases. The early phase is in the tradition of impressionism/expressionism. Later, he developed a more and more abstract art style, for which he is most famous today, see https://en.wikipedia.org/wiki/Wassily_Kandinsky. There is a transitional phase in between. We are most intrested in his later work, so for now, we are only considering his work fronm the 1920s onwards. 

Kandinskys (nearly) full work is available at wikimedia commons (https://commons.wikimedia.org/wiki/Category:Wassily_Kandinsky). 

## Data preperation
Images of Kandinsky are downloaded from Wikimedia Commons on a year-by-year basis. Thus, a start-year can be picked, to only include paintings from this year on. 

The greatest obstacle to this kind of project is the image format: the image GAN needs a uniform image size, that is width and height, whereas real paintings do come in a variaty of sizes and aspect ratios. 
