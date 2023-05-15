<ol dir="auto">
<li>
<p dir="auto">Include the library as local library project:</p>
<div class="highlight highlight-source-groovy notranslate position-relative overflow-auto" dir="auto">
<pre><code id="depCodeGradle" class=" kode  language-css">maven <span class="token string">{url 'https://jitpack.io'}</span></code><span class="pl-s"><span class="pl-pds"><br /><br /></span></span></pre>
</div>
</li>
<li>
<p dir="auto">Include the library as local library project:</p>
<div class="highlight highlight-source-groovy notranslate position-relative overflow-auto" dir="auto">
<pre><code class=" kode  language-css">implementation <span class="token string">'</span></code><code id="depCodeGradle" class=" kode  language-css"><span class="token string">com.github.smartandroidcourse:CircleLoading</span></code><code id="depCodeGradle" class=" kode  language-css"><span class="token string">:1.0</span></code><span class="pl-s"><span class="pl-pds">'<br /><br /></span></span></pre>
</div>
</li>
<li>
<p dir="auto">Add view to your layout file:</p>
<div class="highlight highlight-text-xml notranslate position-relative overflow-auto" dir="auto">
<pre><span class="pl-c"><span class="pl-c">&lt;!--</span> ... <span class="pl-c">--&gt;</span></span></pre>
<pre>&lt;?xml version="1.0" encoding="utf-8"?&gt;<br />&lt;RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"<br />    xmlns:tools="http://schemas.android.com/tools"<br />    android:layout_width="match_parent"<br />    android:layout_height="match_parent"<br />    xmlns:app="http://schemas.android.com/apk/res-auto"<br />    android:layout_margin="25dp"<br />    tools:context=".MainActivity"&gt;<br /><br />    &lt;colorsfx.smart.android.courses.circleloading.Circleloader<br />        android:id="@+id/circularFillableLoaders"<br />        android:layout_width="150dp"<br />        android:layout_height="150dp"<br />        android:src="@drawable/ic_launcher_foreground"<br />        android:tint="#08A880"<br />        android:layout_centerInParent="true"<br />        android:scaleType="centerCrop"<br />        app:cfl_border="true"<br />        app:cfl_border_width="6dp"<br />        app:cfl_progress="70"<br />        app:cfl_wave_amplitude="0.06"<br />        app:cfl_wave_color="#08A880" /&gt;<br /><br />&lt;/RelativeLayout&gt;</pre>
<pre><span class="pl-c"><span class="pl-c">&lt;!--</span> ... <span class="pl-c">--&gt;</span></span></pre>
<div class="zeroclipboard-container position-absolute right-0 top-0">&nbsp;</div>
</div>
</li>
</ol>
