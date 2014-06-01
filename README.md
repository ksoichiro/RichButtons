RichButtons
===

'RichButtons' is a set of button styles for Android applications. All of the styles are made of XML.

![Screenshot](richbuttons-samples/images/screenshot.png "Screenshots")


Install
===

### Eclipse

* The 'library' folder is the main library.
Please import it into the Eclipse or other IDEs.
* Or just copy files in the library folder into your project.

### Gradle

```groovy
dependencies {
    compile 'com.github.ksoichiro:richbuttons:0.1.0@aar'
}
```


Usage
===

Styles of the buttons such as background and text color are defined as `<style>`. Apply the styles which name starts with `RbButton.` to the your buttons like following:

```xml
    <Button
        style="@style/RbButton.Blue"
        android:text="RbButton.Blue" />
```

If you want to customize styles, directly modify the definition in the library or inherit styles.


Samples
===

* Sample applications using this library are included in the samples folder.


Developed By
===

* Soichiro Kashima - <soichiro.kashima@gmail.com>


License
===

    Copyright (c) 2013 Soichiro Kashima.

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
