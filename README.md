# repo
<br>
maven repository project don't commit code <br>
maven仓库项目，不要提交代码<br>

for maven:<br>
&lt; repositories&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;repository&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;id>bigzhao&lt;/id&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;url>https://raw.githubusercontent.com/l741589/repo/master&lt;/url&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;/repository&gt;<br>
&lt;/repositories&gt;<br>
<br>
for gradle:<br>
repositories {<br>
&nbsp;&nbsp;&nbsp;&nbsp;maven { url "https://raw.githubusercontent.com/l741589/repo/master" }  <br>
}  <br>
