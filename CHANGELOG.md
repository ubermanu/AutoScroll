<h1>AutoScroll Changelog</h1>
<h2 title="2020-12-16">Version 5.1</h2>
<ul>
  <li>Fixed scrolling on pages with smooth scroll behavior enabled.</li>
</ul>
<h2 title="2020-12-16">Version 5.0</h2>
<ul>
  <li>Reworked and cleaned up the whole project.</li>
  <li>The "Options" page is now bootstrapped by React.</li>
  <li>Optimized SVG and PNG images.</li>
</ul>
<h2 title="2018-11-21">Version 4.10</h2>
<ul>
  <li>Fixing a regression that caused it to incorrectly activate on various things. (Thanks to <a href="https://github.com/Tynach">Tynach</a>)</li>
  <li>AutoScroll now works on Windows (it will disable the built-in autoscroll).</li>
</ul>
<h2 title="2018-11-03">Version 4.9</h2>
<ul>
  <li>Fixing deprecation warning in Chrome. (Thanks to <a href="https://github.com/joepvl">joepvl</a>)</li>
  <li>Changing <code>&lt;area&gt;</code> to be treated the same as links. (Thanks to <a href="https://github.com/Fry-kun">Fry-kun</a>)</li>
  <li>Enabling scrolling on disabled and readonly text inputs. (Thanks to <a href="https://github.com/Fry-kun">Fry-kun</a>)</li>
</ul>
<h2 title="2016-07-12">Version 4.8</h2>
<ul>
  <li>Changing the scroll images to be SVG. (Thanks to <a href="https://github.com/metarmask">metarmask</a>)</li>
  <li>Improving the quality of the scroll images and the icons.</li>
</ul>
<h2 title="2016-02-03">Version 4.7</h2>
<ul>
  <li>Fixed AutoScroll not working on some sites.</li>
</ul>
<h2 title="2016-01-08">Version 4.6</h2>
<ul>
  <li>Added in partial support for scrolling SVG documents.</li>
  <li>Middle clicking on the horizontal scrollbar no longer activates autoscroll.</li>
</ul>
<h2 title="2015-10-03">Version 4.5</h2>
<ul>
  <li>Fixed middle click paste not working on YouTube comments.</li>
  <li>"Scroll by using (Ctrl/⌘ + Left Click)" is now enabled by default.</li>
</ul>
<h2 title="2015-09-28">Version 4.4</h2>
<ul>
  <li>Fixed it so that textboxes are unfocused when scrolling starts.</li>
  <li>Fixed AutoScroll not working in Chrome versions 29 to 34.</li>
</ul>
<h2 title="2015-09-27">Version 4.3</h2>
<ul>
  <li>Fixed a bug that caused scrolling to not work on some websites.</li>
</ul>
<h2 title="2015-09-26">Version 4.2</h2>
<ul>
  <li>Fixed a serious bug that caused scrolling to get "stuck".</li>
</ul>
<h2 title="2015-09-25">Version 4.1</h2>
<ul>
  <li>Fixed a bug that caused scroll to not work on certain sites.</li>
</ul>
<h2 title="2015-09-25">Version 4.0</h2>
<ul>
  <li>Removed support for extremely old versions of Chrome (version 28 or older).</li>
  <li>It should now be impossible for a site or extension to break the styles for AutoScroll.</li>
  <li>Improved the performance of scrolling on all sites.</li>
  <li>Changed the default move speed to 10, because of the improved performance.</li>
</ul>
<h2 title="2014-12-21">Version 3.9</h2>
<ul>
  <li>Fixed scrolling not working on most sites.</li>
</ul>
<h2 title="2014-04-07">Version 3.8</h2>
<ul>
  <li>Fixed scrolling not working on most sites.</li>
</ul>
<h2 title="2014-04-06">Version 3.7</h2>
<ul>
  <li>Fixed a bug where scrolling did not work on <a href="https://plus.google.com/">Google+</a>.</li>
  <li>Fixed the options page not working.</li>
</ul>
<h2 title="2014-03-16">Version 3.6</h2>
<ul>
  <li>Fixed a bug where certain sites (like <a href="http://blog.dogecoin.com/">this one</a>) would get stuck scrolling.</li>
</ul>
<h2 title="2014-02-01">Version 3.5</h2>
<ul>
  <li>Added in the ability to scroll using (Ctrl/⌘ + Left Click)</li>
  <li>Added in the ability to disable scrolling using (Middle Click)</li>
</ul>
<h2 title="2013-12-27">Version 3.4</h2>
<ul>
  <li>Fixed scrolling not working on old versions of Chrome (&lt; 24.0)</li>
</ul>
<h2 title="2013-12-25">Version 3.3</h2>
<ul>
  <li>Have to revert from document_start to document_end in order to fix <a href="https://easywebsoc.td.com/waw/idp/login.htm?execution=e1s1">this website</a> constantly refreshing.</li>
</ul>
<h2 title="2013-12-25">Version 3.2</h2>
<ul>
  <li>The scroll icon should now be completely fixed for all websites, hopefully.</li>
</ul>
<h2 title="2013-12-24">Version 3.1</h2>
<ul>
  <li>Fixed <a href="http://9to5mac.com/">http://9to5mac.com/</a> not working.</li>
  <li>Fixed some sites allowing scrolling in both directions, but the icon only showing horizontal/vertical.</li>
</ul>
<h2 title="2013-12-20">Version 3.0</h2>
<ul>
  <li>Use <a href="https://developer.mozilla.org/en/docs/Web/API/window.requestAnimationFrame">requestAnimationFrame</a> for smoother scrolling.</li>
  <li>Fixed a bug with Change Colors.</li>
  <li>Fixed a bug with <a href="http://www.willhaben.at">www.willhaben.at</a></li>
  <li>Fixed being unable to click links on <a href="http://www.wind.it/it/privati/">http://www.wind.it/it/privati/</a></li>
  <li>Fixed being unable to click links on XML pages (like <a href="http://www.opengl.org/sdk/docs/man/xhtml/glDrawElements.xml">this one</a>)</li>
  <li>Cursor should now return to normal when scroll ends.</li>
</ul>
<h2 title="2012-10-23">Version 2.9</h2>
<ul>
  <li>Fixed a bug where scrolling while a text field is focused causes Chrome to scroll to the text field.</li>
  <li>Changed the default cursor to "move" from "crosshair".</li>
</ul>
<h2 title="2012-06-01">Version 2.8</h2>
<ul>
  <li>Worked around a bug in Chrome where the icon and crosshair wouldn't show up.</li>
  <li>Fixed a bug where changing certain settings in the options page was severely broken.</li>
</ul>
<h2 title="2010-11-06">Version 2.7.5</h2>
<ul>
  <li>AutoScroll is now much stricter about how it applies styles to the cursor element. This fixes issues with extensions like <a href="https://chrome.google.com/extensions/detail/jbmkekhehjedonbhoikhhkmlapalklgn">Change Colors</a>.</li>
</ul>
<h2 title="2010-10-23">Version 2.7</h2>
<ul>
  <li>Changes made in the options page are now synced immediately. You no longer need to refresh the page!</li>
  <li>Fixing some bugs with sticky scroll and speed cap.</li>
</ul>
<h2 title="2010-10-23">Version 2.6</h2>
<ul>
  <li>Updating to the latest version of the Options API. Your settings should still be saved.</li>
  <li>Re-enabling the ability to change move speed and timer interval.</li>
</ul>
<h2 title="2010-08-14">Version 2.5.5</h2>
<ul>
  <li>AutoScroll broke in the latest dev channel. This update fixes it.</li>
</ul>
<h2 title="2010-06-23">Version 2.5</h2>
<ul>
  <li>Licensing under the X11/MIT License.</li>
  <li>Tweaking some stuff to make scrolling smoother. I'm still working on making it as smooth as I can, but this should help.</li>
  <li>Users can no longer change the scroll speed or timer interval. I plan to re-enable scroll speed later, but I need to do some option refactoring first.</li>
</ul>
<h2 title="?">Version 2.4</h2>
<ul>
  <li>Previously, when holding down the middle mouse button, moving the mouse, then moving it back to the disc and releasing the button, it would remain in autoscroll mode. This has been fixed.</li>
</ul>
<h2 title="?">Version 2.3</h2>
<ul>
  <li>Added in an option to cap the speed (so it doesn't scroll faster than you specify).</li>
  <li>Also added in the ability to make it scroll at the same speed (ignoring mouse movement).</li>
  <li class="developer">Added in two new functions that should allow for a feature I wanted to add in earlier...</li>
</ul>
<h2 title="?">Version 2.2</h2>
<ul>
  <li>Fixes AutoScroll not working on images. Scrolling works, but the round "disc" doesn't show up. This is a bug in Chrome.</li>
  <li>Make sure the cursor is set correctly when AutoScroll ends.</li>
  <li class="developer">We only append the element if it isn't already a child of <code>document.body</code>.</li>
</ul>
<h2 title="?">Version 2.1</h2>
<ul>
  <li>Fixes a bug where AutoScroll activated when it shouldn't (but only on XML pages).</li>
  <li>Fixes a bug where the scroll-wheel claims you can scroll both horizontally and vertically, even though it is only possible to scroll vertically.</li>
</ul>
<h2 title="?">Version 2.0.5</h2>
<ul>
  <li>Quick fix for AutoScroll not scrolling on pages that do not have scrollbars. This is a regression from <span class="version">Version 2.0</span>. I would love to have this feature, but Chrome is reporting incorrect <code>scrollWidth</code> and <code>scrollHeight</code>, causing all sorts of problems.</li>
</ul>
<h2 title="?">Version 2.0</h2>
<ul>
  <li>AutoScroll no longer activates on pages that do not have scrollbars.</li>
  <li>Adds two new images. The autoscroll circle now changes based on whether horizontal scroll is available or not.</li>
  <li class="developer">Splits <code>hasScroll</code> into <code>hasScroll</code> and <code>canScroll</code>.</li>
  <li class="developer">Adds functions to check individually for horizontal and vertical scroll.</li>
  <li class="developer">Rearranges the "find" and "scroll" functions into objects (more organized).</li>
</ul>
<h2 title="?">Version 1.9</h2>
<ul>
  <li>We now append the cursor element to the body on every <code>mousedown</code>. This fixes an issue with pages that are dynamically created.</li>
  <li class="developer">Reorganizes the <code>findScroll</code> function by adding in a new <code>hasScroll</code> function.</li>
</ul>
<h2 title="?">Version 1.8</h2>
<ul>
  <li class="critical">User's settings are reset back to the defaults. This is necessary due to a new Options API. Luckily, this new API prevents user's settings from getting overwritten in a future update.</li>
</ul>
<h2 title="?">Version 1.7.5</h2>
<ul>
  <li>No longer scrolls on <code>&lt;a&gt;</code> tags that do not have a <code>href</code> attribute.</li>
</ul>
<h2 title="?">Version 1.7</h2>
<ul>
  <li>Scrolling on inner elements is forced on for all users until the new Options API is finished. This was previously disabled because of a bug in WebKit, until I found a workaround. This fixes AutoScroll not working on certain sites. It also allows for scrolling of elements contained within the page that have scrollbars.</li>
</ul>
<h2 title="?">Version 1.6</h2>
<ul>
  <li>Re-enables <code>https://</code> URLs.</li>
</ul>
<h2 title="?">Version 1.5</h2>
<ul>
  <li>Sticky scroll now exits on <code>mousedown</code>, rather than <code>mouseup</code>.</li>
</ul>
<h2 title="?">Version 1.4</h2>
<ul>
  <li>No longer scrolls when clicking on the scrollbar.</li>
</ul>
<h2 title="?">Version 1.3.5</h2>
<ul>
  <li class="developer">Actually disables the mousewheel (this was broken in <span class="version">Version 1.3</span>).</li>
</ul>
<h2 title="?">Version 1.3</h2>
<ul>
  <li>Disables using the mousewheel to scroll while AutoScroll is active.</li>
  <li>Disables <code>https://</code> URLs.</li>
  <li>Adds a checkbox for enabling/disabling sticky scroll.</li>
</ul>
<h2 title="?">Version 1.2</h2>
<ul>
  <li>No longer scrolls on password fields.</li>
</ul>
<h2 title="?">Version 1.1</h2>
<ul>
  <li>Fixes it so it continues scrolling without needing to move the mouse.</li>
</ul>
