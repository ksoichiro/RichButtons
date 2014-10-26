# ![](richbuttons-samples/demos/res/drawable-ldpi/ic_launcher.png) RichButtons
[![Build Status](https://travis-ci.org/ksoichiro/RichButtons.svg?branch=master)](https://travis-ci.org/ksoichiro/RichButtons)
[![Maven Central](http://img.shields.io/maven-central/v/com.github.ksoichiro/richbuttons.svg)](https://github.com/ksoichiro/RichButtons/releases/latest)

RichButtonsは、Androidアプリケーションで使うボタンのスタイルのセットです。全てXMLで作っています。

![Screenshot](richbuttons-samples/images/screenshot.png "Screenshots")


インストール
===

### Eclipse

* libraryフォルダがライブラリ本体です。EclipseなどのIDEでAndroid Library Projectとして取り込んでください。
* もしくは、ライブラリ内のファイルをあなたのプロジェクトへそのままコピーしてください。

### Gradle

```groovy
dependencies {
    compile 'com.github.ksoichiro:richbuttons:0.1.1@aar'
}

使い方
===

ボタンの背景、文字色等のスタイルは`<style>`として定義されています。以下のように、`RbButton.`で始まるスタイルをボタンに適用してください。

```xml
    <Button
        style="@style/RbButton.Blue"
        android:text="RbButton.Blue" />
```

スタイルをカスタマイズしたい場合は、ライブラリ内のスタイルの定義を変更するか、定義済みのスタイルをカスタマイズしたスタイルを作成してください。

## Blue

![](richbuttons-samples/images/blue.png "default")  
![](richbuttons-samples/images/blue_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Blue"
        android:text="RbButton.Blue" />
```

## Purple

![](richbuttons-samples/images/purple.png "default")  
![](richbuttons-samples/images/purple_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Purple"
        android:text="RbButton.Purple" />
```

## Green

![](richbuttons-samples/images/green.png "default")  
![](richbuttons-samples/images/green_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Green"
        android:text="RbButton.Green" />
```

## Yellow

![](richbuttons-samples/images/yellow.png "default")  
![](richbuttons-samples/images/yellow_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Yellow"
        android:text="RbButton.Yellow" />
```

## Red

![](richbuttons-samples/images/red.png "default")  
![](richbuttons-samples/images/red_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Red"
        android:text="RbButton.Red" />
```

## Glossy

![](richbuttons-samples/images/glossy.png "default")  
![](richbuttons-samples/images/glossy_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Glossy"
        android:text="RbButton.Glossy" />
```

## Inverse

![](richbuttons-samples/images/inverse.png "default")  
![](richbuttons-samples/images/inverse_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse"
        android:text="RbButton.Inverse" />
```

## Inverse.Red

![](richbuttons-samples/images/inverse.red.png "default")  
![](richbuttons-samples/images/inverse.red_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Red"
        android:text="RbButton.Inverse.Red" />
```

## Inverse.Blue

![](richbuttons-samples/images/inverse.blue.png "default")  
![](richbuttons-samples/images/inverse.blue_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Blue"
        android:text="RbButton.Inverse.Blue" />
```

## Inverse.LightBlue

![](richbuttons-samples/images/inverse.lightblue.png "default")  
![](richbuttons-samples/images/inverse.lightblue_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.LightBlue"
        android:text="RbButton.Inverse.LightBlue" />
```

## Inverse.Green

![](richbuttons-samples/images/inverse.green.png "default")  
![](richbuttons-samples/images/inverse.green_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Green"
        android:text="RbButton.Inverse.Green" />
```

## Inverse.Orange

![](richbuttons-samples/images/inverse.orange.png "default")  
![](richbuttons-samples/images/inverse.orange_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Orange"
        android:text="RbButton.Inverse.Orange" />
```

## Inverse.Gray

![](richbuttons-samples/images/inverse.gray.png "default")  
![](richbuttons-samples/images/inverse.gray_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Gray"
        android:text="RbButton.Inverse.Gray" />
```

## Inverse.Black

![](richbuttons-samples/images/inverse.black.png "default")  
![](richbuttons-samples/images/inverse.black_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Black"
        android:text="RbButton.Inverse.Black" />
```

## Inverse.Rounded

![](richbuttons-samples/images/inverse.rounded.png "default")  
![](richbuttons-samples/images/inverse.rounded_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded"
        android:text="RbButton.Inverse.Rounded" />
```

## Inverse.Rounded.Red

![](richbuttons-samples/images/inverse.rounded.red.png "default")  
![](richbuttons-samples/images/inverse.rounded.red_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded.Red"
        android:text="RbButton.Inverse.Rounded.Red" />
```

## Inverse.Rounded.Blue

![](richbuttons-samples/images/inverse.rounded.blue.png "default")  
![](richbuttons-samples/images/inverse.rounded.blue_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded.Blue"
        android:text="RbButton.Inverse.Rounded.Blue" />
```

## Inverse.Rounded.LightBlue

![](richbuttons-samples/images/inverse.rounded.lightblue.png "default")  
![](richbuttons-samples/images/inverse.rounded.lightblue_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded.LightBlue"
        android:text="RbButton.Inverse.Rounded.LightBlue" />
```

## Inverse.Rounded.Green

![](richbuttons-samples/images/inverse.rounded.green.png "default")  
![](richbuttons-samples/images/inverse.rounded.green_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded.Green"
        android:text="RbButton.Inverse.Rounded.Green" />
```

## Inverse.Rounded.Orange

![](richbuttons-samples/images/inverse.rounded.orange.png "default")  
![](richbuttons-samples/images/inverse.rounded.orange_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded.Orange"
        android:text="RbButton.Inverse.Rounded.Orange" />
```

## Inverse.Rounded.Gray

![](richbuttons-samples/images/inverse.rounded.gray.png "default")  
![](richbuttons-samples/images/inverse.rounded.gray_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded.Gray"
        android:text="RbButton.Inverse.Rounded.Gray" />
```

## Inverse.Rounded.Black

![](richbuttons-samples/images/inverse.rounded.black.png "default")  
![](richbuttons-samples/images/inverse.rounded.black_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Inverse.Rounded.Black"
        android:text="RbButton.Inverse.Rounded.Black" />
```

## Darken

![](richbuttons-samples/images/darken.png "default")  
![](richbuttons-samples/images/darken_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Darken"
        android:text="RbButton.Darken" />
```

## Recessed

![](richbuttons-samples/images/recessed.png "default")  
![](richbuttons-samples/images/recessed_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Recessed"
        android:text="RbButton.Recessed" />
```

## ICS

![](richbuttons-samples/images/ICS.png "default")  
![](richbuttons-samples/images/ICS_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.ICS"
        android:text="RbButton.ICS" />
```

## ICS.Black

![](richbuttons-samples/images/ICS.black.png "default")  
![](richbuttons-samples/images/ICS.black_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.ICS.Black"
        android:text="RbButton.ICS.Black" />
```

## Plastic

![](richbuttons-samples/images/plastic.png "default")  
![](richbuttons-samples/images/plastic_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Plastic"
        android:text="RbButton.Plastic" />
```

## Plastic.Rounded

![](richbuttons-samples/images/plastic.rounded.png "default")  
![](richbuttons-samples/images/plastic.rounded_pressed.png "pressed")  

```xml
    <Button
        style="@style/RbButton.Plastic.Rounded"
        android:text="RbButton.Plastic.Rounded" />
```


サンプル
===

* ライブラリを使用したサンプルアプリケーションは、samplesフォルダに含まれています。


開発者
===

* Soichiro Kashima - <soichiro.kashima@gmail.com>


ライセンス
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
