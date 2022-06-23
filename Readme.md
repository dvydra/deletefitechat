# Delete fite.tv chat block extension

  Delete the fite.tv chat block on any https://www.fite.tv/watch/ page. That's it.

  This extension is extremely simple. This is the whole thing.
  ```
     var element = document.querySelector('#chat-block');
     element.parentElement.removeChild(element);
  ```
  
  This is a self-signed extension. It may not install on your browser. If there's enough interest I might put it in the various extension stores. 

## Installation

  Download the source and follow your browser's instructions for installing unpacked extensions. 


## License

  The MIT License (MIT)

  Copyright (c) 2022, Daniel Vydra

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in
  all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
  THE SOFTWARE.
