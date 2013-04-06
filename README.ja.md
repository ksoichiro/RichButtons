RichButtons
===

RichButtonsは、Androidアプリケーションで使うボタンのスタイルのセットです。全てXMLで作っています。

![Screenshot](https://raw.github.com/ksoichiro/RichButtons/master/samples/images/screenshot.png "Screenshots")


インストール
===

* libraryフォルダがライブラリ本体です。EclipseなどのIDEでAndroid Library Projectとして取り込んでください。
* もしくは、ライブラリ内のファイルをあなたのプロジェクトへそのままコピーしてください。


使い方
===

ボタンの背景、文字色等のスタイルは`<style>`として定義されています。以下のように、`RbButton.`で始まるスタイルをボタンに適用してください。

```xml
    <Button
        style="@style/RbButton.Blue"
        android:text="RbButton.Blue" />
```

スタイルをカスタマイズしたい場合は、ライブラリ内のスタイルの定義を変更するか、定義済みのスタイルをカスタマイズしたスタイルを作成してください。


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
