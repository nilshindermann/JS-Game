---
layout: post
title:  "Eine neue Seite!"
date:   2020-09-24 09:45:00 +0200
categories: jekyll update
---
Heute ging es richtig an die Arbeit!

Diese Website, die gleichzeitig ein Blog ist, haben wir mit Jekyll erstellt.
Auf diesem Blog werden wir weitere Posts machen, die beschreiben, wie wir arbeiten.
Dies ist der erste Eintrag, der von uns erstellt wurde.
Weiter unten wird noch ein bisschen herumgetestet.

### Ein paar Testversuche in einem Blogeintrag
#### Highlight Java ####
{% highlight java %}
public class Ball {
  public static final int SPEED = 50;

  private int x, y;

  public Ball(int x, int y) {
    this.x = x;
    this.y = y;
  }

  public void update() {
    x += SPEED;
    y += SPEED;
  }
}
{% endhighlight %}
#### Highlight C# ####
{% highlight csharp %}
public void TestMe() {
  const int tested = new Tester().TestInt(500);

  System.Console.WriteLine("Result: " + tested);
}
{% endhighlight %}
#### Highlight C++ ####
{% highlight cpp %}
#include <bla>
using namespace bla;

public int main() {

  return 0;
}
{% endhighlight %}
#### Highlight HTML ####
{% highlight html %}
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Test Page</title>
  </head>
  <body>
    <h1>Page Title</h1>
    <p>
      This is a test page.
    </p>
  </body>
</html>
{% endhighlight %}
#### Highlight CSS ####
{% highlight css %}
body {
  background-color: #eee;
  background-image: url('assets/bg.png');
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  font-family: Verdana, sans-serif;
}
h1 {
  font-size: x-large;
}
p {
  font-size: 20px;
  line-height: 30px;
}
{% endhighlight %}
#### Highlight JavaScript ####
{% highlight js %}
function clickTheButton() {
  alert("You clicked the button!");
}
{% endhighlight %}

---
Fertig! `Das waren einige Highlight-Tests.` Jetzt kann es losgehen.
