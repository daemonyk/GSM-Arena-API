# GSM-Arena-API
<p>PHP Class untuk grab data di website gsm arena dan output berbentuk Array atau JSON menggunakan cURL dan simple html dom.</p>
<br>
<h4>Usage:</h4>
 

<pre>&lt;?php

// Include class gsm.php
require("gsm.php");

// Create objek
$gsm = new gsm();</pre>
 <br>
<h4>Search:</h4>
 

<pre>$data = $gsm-&gt;search('zenfone'); // Keyword</pre>
 <br>
<h4>Detail:</h4>
 

<pre>$data = $gsm-&gt;detail('asus_zenfone_max_zc550kl-7476'); // Slug</pre>
 <br>
<h4>Return Array:</h4>
 

<pre>print_r($data);<br>
</pre>
 <br>
<h4>Return JSON:</h4>
 

<pre>// Convert ARRAY to JSON<br>
header('Content-Type: application/json');<br>
echo json_encode($data, JSON_PRETTY_PRINT);</pre>
 <a href="http://ibacor.com/widget/smartphone-spesifikasi"><h2>DEMO</h2></a>
