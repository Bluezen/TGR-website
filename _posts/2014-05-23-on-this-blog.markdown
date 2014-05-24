---
layout: post
title:  "On this blog"
categories: blog
date: 2014-05-23
description:
  About what you can expect to find here.
---

If you can overcome the fact that I'm not a native english speaker and that you might encounter terrible grammar (and jokes) here and there, you will be able to find on this blog some -- humble -- insight on the making of the TGR app.

I guess this blog might also be used at some point to give public excuses on the terrible bugs users might face using the app.

Nah, I'm joking. I won't give excuses.



{% highlight objc %}
- (void)application:(UIApplication *)application didFailMiserably:(NSError *)error {
    if (error.code == notFunny) {
        NSLog(@"Act as if nothing hapened.");
    } else {
        // Oh crap unknown error
        NSLog(@"Throw to closest black hole.");
	}
}
{% endhighlight %}

Occasionally, in the same way that just occur above, you might come across some (dirty and diabolical) extract of the app code. To be more precise, there will only be the nicely crafted parts that I am not ashamed to expose. I'm sure I can find some interesting stuff between two bloated view controllers.

For the time being, I will share some very personal data related to the making of this app (let's break it right now for the NSA, they are not this valuable)... the hours in a day I spent on the app!!

Hang on, there is more than you think that comes out of this.

If you are not a developer but have read so far, you will need to know what a commit is to understand the following data. Let's say that in my case it simply means the end of a working day.

<table class="table table-striped table-hover "><tbody><tr><th>Hour</th><th>0</th><th>1</th><th>2</th><th>3</th><th>4</th><th>5</th><th>6</th><th>7</th><th>8</th><th>9</th><th>10</th><th>11</th><th>12</th><th>13</th><th>14</th><th>15</th><th>16</th><th>17</th><th>18</th><th>19</th><th>20</th><th>21</th><th>22</th><th>23</th></tr>
<tr><th>Commits</th><td style="color: white; background-color: rgb(167, 0, 0)">8</td><td style="color: white; background-color: rgb(198, 0, 0)">14</td><td style="color: white; background-color: rgb(208, 0, 0)">16</td><td style="color: white; background-color: rgb(255, 0, 0)">25</td><td style="color: white; background-color: rgb(193, 0, 0)">13</td><td style="color: white; background-color: rgb(167, 0, 0)">8</td><td style="color: white; background-color: rgb(132, 0, 0)">1</td><td>0</td><td>0</td><td>0</td><td style="color: white; background-color: rgb(132, 0, 0)">1</td><td>0</td><td style="color: white; background-color: rgb(142, 0, 0)">3</td><td style="color: white; background-color: rgb(157, 0, 0)">6</td><td style="color: white; background-color: rgb(137, 0, 0)">2</td><td style="color: white; background-color: rgb(188, 0, 0)">12</td><td style="color: white; background-color: rgb(147, 0, 0)">4</td><td style="color: white; background-color: rgb(152, 0, 0)">5</td><td style="color: white; background-color: rgb(183, 0, 0)">11</td><td style="color: white; background-color: rgb(193, 0, 0)">13</td><td style="color: white; background-color: rgb(152, 0, 0)">5</td><td style="color: white; background-color: rgb(137, 0, 0)">2</td><td style="color: white; background-color: rgb(152, 0, 0)">5</td><td style="color: white; background-color: rgb(157, 0, 0)">6</td></tr>
<tr><th>%</th><td style="color: white; background-color: rgb(167, 0, 0)">5.00</td><td style="color: white; background-color: rgb(198, 0, 0)">8.75</td><td style="color: white; background-color: rgb(208, 0, 0)">10.00</td><td style="color: white; background-color: rgb(255, 0, 0)">15.62</td><td style="color: white; background-color: rgb(193, 0, 0)">8.12</td><td style="color: white; background-color: rgb(167, 0, 0)">5.00</td><td style="color: white; background-color: rgb(132, 0, 0)">0.62</td><td>0.00</td><td>0.00</td><td>0.00</td><td style="color: white; background-color: rgb(132, 0, 0)">0.62</td><td>0.00</td><td style="color: white; background-color: rgb(142, 0, 0)">1.88</td><td style="color: white; background-color: rgb(157, 0, 0)">3.75</td><td style="color: white; background-color: rgb(137, 0, 0)">1.25</td><td style="color: white; background-color: rgb(188, 0, 0)">7.50</td><td style="color: white; background-color: rgb(147, 0, 0)">2.50</td><td style="color: white; background-color: rgb(152, 0, 0)">3.12</td><td style="color: white; background-color: rgb(183, 0, 0)">6.88</td><td style="color: white; background-color: rgb(193, 0, 0)">8.12</td><td style="color: white; background-color: rgb(152, 0, 0)">3.12</td><td style="color: white; background-color: rgb(137, 0, 0)">1.25</td><td style="color: white; background-color: rgb(152, 0, 0)">3.12</td><td style="color: white; background-color: rgb(157, 0, 0)">3.75</td></tr></tbody></table>


Same data in a graph:


![chart]({{ site.url}}/assets/img/hour_of_day.png)


I spent a lot time working during the night. These quiet hours are certainly those on which I have been the most productive. But I have to agree that this was at the expense of an healthy lifestyle.

Why sharing this personal stuff? Firstly because I feel like it's enough unusual (at least for me) to be mentioned but more importantly because this is my way to involve you in the human story of this app.  I want you to be aware that this is a "human size" app.

I now expect from you not to yell when reporting an issue, whatever the fuck happened. 

If you are polite, I might even start working immediately on it to fix it and this at any time of the day ;)


I feel like I succeeded selling you the app! What a great idea to start the first post by mentionning bugs an issues!

Please enjoy it when it comes out.