<html>
<head>
<meta http-equiv="Content-Language" content="en-us">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<title>ESEfinder 3.0 -- </title>

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-PR10KZ63WV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-PR10KZ63WV');
</script>
</head>

<body>
<table border="0" width="1024">
	<tr>
		<td>
		<p>last update: 11/11/2024</p>
		</td>
	</tr>
	<tr>
			<td align="center">
					<img src="/tools/ESE3/images/eselogo.gif" width="450" height="150"><br>
	</tr>
	<tr>
		<td align="center">
		<p>
		<a href="/cgi-bin/tools/ESE3/esefinder.cgi?process=home">Search</a> |
		<a href="/cgi-bin/tools/ESE3/esefinder.cgi?process=background">background</a> |
		<a href="/cgi-bin/tools/ESE3/esefinder.cgi?process=matrices">matrices &amp; thresholds</a> | 
		<a href="/cgi-bin/tools/ESE3/esefinder.cgi?process=output">input & output</a> | 
		<a href="/cgi-bin/tools/ESE3/esefinder.cgi?process=caveats">caveats</a></p>
		</td>
	</tr>
	<tr>
			<td>
<script language="javascript">
function refreshPage()
{
	var dbName=this.document.query_form.db.value;
	document.db_select_form.db.value = dbName;
	document.db_select_form.submit();
}
</script>

<form method="POST" name="db_select_form" action="/cgi-bin/tools/ESE3/esefinder.cgi" ENCTYPE="multipart/form-data">
		<input type="hidden" name="db" value="">
		<input type="hidden" name="process" value="home">
</form>

<br><br>

<form method="POST" action="/cgi-bin/tools/ESE3/esefinder.cgi" name="query_form"  enctype="multipart/form-data">
<input type="hidden" name="process" value="search">
<table border="0">
			<tr>
					<td>Matrix information</td>
					<td></td>
			</tr>
		</table>


		<p>Choose the matrix and the threshold to be used:</p>
	<script language="javascript">
 

</script>
<table border="0">
<tr>

<td><input type="button" value="Reset thresholds" name="reset Thresholds" onClick="resetThresholds(); return true"></td>
</tr>
</table>

		<br>
		<table border="0">
			<tr>
				<td>Sequence information</td>
				<td></td>
			</tr>
		</table>
		<p>Enter your input data in FASTA or MULTI-FASTA format (5000nt max):</p>
		<textarea rows="10" name="seq" cols="83"></textarea>

		<p>Alternatively, upload a text file:
		<input type="file" name="upload" size="53"></p>
		
		<table border="0">
			<tr>
					<td>Output information</td>
					<td></td>
			</tr>
		</table>
		<p>Override thresholds and use one of the options: </p>
		<input type="checkbox" value="ON" name="report_max_only"> Report only the best hit in each sequence<br>
		<input type="checkbox" value="ON" name="report_all_score"> Report all scores in each sequence<br>
		<input type="checkbox" value="ON" name="format_text"> Output as a plain text file</p>
		
		<p><input type="checkbox" value="ON" name="byemail">Please send results to:
		<input type="text" name="email" size="29"></p>
		
<p><input type="submit" value="Send" name="submit">
		<input type="reset" value="Restore defaults" name="reset"></p>
</form>
		
<table border="0">
			<tr>
					<td>Citation information</td>
					<td></td>
			</tr>
		</table>
<br>

</td>
	</tr>
	<tr>
		<td>
		<p align="center">
		<a href="https://www.mpi-hlr.de/developmental-genetics">Stainier Lab</a>
		<a href="https://www.mpi-hlr.de/en">Max Planck Institute for Heart and Lung Research</a><br>
		Questions/suggestions email: <a href="muzzammilbhaisaheb@gmail.com">Muzzammil B</a>.
		</p></td>
	</tr>
</table>

</body>
</html>
