# Media-Query-Tricks-CSS

Responsive Web design is the basic necessity in todays IT Development as it should be appropriate in Desktops, Laptops, IPads, Phones and all sort of devices. So it is mandatory for all development. Media Query is one of the best way to make a web page responsive. This project might be helpful to one need a responsive layouts.

## Installation

1. Clone or download the repository.
2. Run index.html page
3. Try to resize the webpage, you will find media query effects
4. Note to see the pixels in google chrome you wan to apply do right click, and inspect element(You will find pixels written in top righ t of the page)

## Snippet1

```
@media only screen and (max-width:768px) {		applies from 0px to 768px
	h1 {                                        //Apply this media query when you want to apply styling from 0px to some max px specified
		font-size: 22px;
	}
	h3 {
		font-size:18px ;
	}
	p {
		margin-left: 30px;
		margin-right: 30px;
	}
}

```

## Snippet2

```
@media screen and (min-width:480px) and (max-width:768px) {
										/* applies from 480 to 768px */
										//Apply this media query when you want to apply styling from min px specified to some max px specified
	h1 {
		font-size: 22px;
	}
	h3 {
		font-size:18px ;
	}
	p {
		margin-left: 30px;
		margin-right: 30px;
	}
}

```

## Looks

![Screenshot of Media Query Project ](https://cloud.githubusercontent.com/assets/15896579/26284184/04c840c8-3e53-11e7-9fde-70f74c492dc8.png?raw=true "Screenshot of Media Query Project")
<br/><br/><br/>

![Screenshot of Media Query Project ](https://cloud.githubusercontent.com/assets/15896579/26284187/08564f3c-3e53-11e7-99bf-41e51712ffbe.png?raw=true "Screenshot of Media Query Project")
<br/><br/><br/>

![Screenshot of Media Query Project ](https://cloud.githubusercontent.com/assets/15896579/26284188/0b4db82e-3e53-11e7-9f60-ef9054acecff.png?raw=true "Screenshot of Media Query Project")
<br/><br/><br/>

![Screenshot of Media Query Project ](https://cloud.githubusercontent.com/assets/15896579/26284189/0ee2b3cc-3e53-11e7-811c-196d4aca3617.png?raw=true "Screenshot of Media Query Project")
<br/><br/><br/>

## License

(The MIT License)

Copyright (c) 2016 Amir Mustafa

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

