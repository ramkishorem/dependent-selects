# dependent-selects

Show filtered options on one select field depending on another. This is made with vanilla JavaScript. You don't need any library. See in action https://codepen.io/furalyon/pen/NzrXZL

## To use

1. Include this script
2. Use the markup format as shown in the example.html

## Usage eg

~~~~

Parent 1: <select name="parent" id="id_parent" data-child-id='id_child' class='dependent-selects__parent'>
    <option value="">--------</option>
    <option value="one" data-child-options="11|#twelve|#13">One</option>
    <option value="two" data-child-options="11|#14|#15">Two</option>
</select>

Child 1: <select name="child" id="id_child" class='dependent-selects__child'>
    <option value="">--------</option>
    <option value="11">Eleven</option>
    <option value="twelve">Twelve</option>
    <option value="13">Thirteen</option>
    <option value="14">fourteen</option>
    <option value="15">fifteen</option>
</select>

~~~~


Note: A page can have multiple sets of this. Works on Chrome, Firefox, Opera


## License

The MIT License (MIT)

Copyright (c) 2012-2017 Ramkishore M

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.