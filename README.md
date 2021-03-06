Online Version: http://hellerve.github.com/gevent-tutorial-de/
=========================================================

Diese Übersetzung ist noch im Entstehen. Es wird keinerlei Garantie
für ihre Richtigkeit gegeben.

Du willst ein Beispiel hinzufügen? Das ist super einfach.

1. Forke das Repo.
2. ``pip install -r requirements.txt``
3. Editiere ``tutorial.md``.

Füge deinen Text als Markdown hinzu.

Füge deinen Code als Cog hinzu.

     [[[cog

     print("Hello World!")
     for i in xrange(25):
         print(i)

     ]]]
     [[[end]]]


wird das als HTML ausspucken:

    <pre>
    <code class="python">

    print("Hello World!")
    for i in xrange(5):
        print(i)

    </code>
    </pre>

    <pre><code class="python">
    Hello World!
    0
    1
    2
    3
    4
    </code>
    </pre>

4. Führe ``./build`` aus.
5. Eröffne einen Pull Request.
6. Bekomme gutes gevent Karma.

Released under MIT License.

    Copyright (c) 2011 Stephen Diehl, <stephen.m.diehl@gmail.com>

    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
    LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
    OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
    WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
