<html>
<head>
<meta http-equiv="Content-Language" content="en-us">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">

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
<h1>Python Processing Notebook</h1>
    <a href="https://colab.research.google.com/drive/1vbgQ7lF-Oe08eZkaGZXv2QN-toJOIVVv" target="_blank">
    Open the Python Processing Notebook on Colab
</a>

<table border="0" width="1024">
	<tr>
		<td>
		<p>last update: 11/11/2024</p>
		</td>
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


	<script language="javascript">
 

</script>

</table>

		<br>
		<table border="0">
			<tr>
				<td>Sequence information</td>
				<td></td>
			</tr>
		</table>

		Enter mRNA ID (e.g NM_000000):
		<input type="text" name="mrna_id" size="12">
		
		<table border="0">
			<tr>
					<td>Output information</td>
					<td></td>
			</tr>
		</table>

		<input type="checkbox" value="ON" name="format_text"> Output as a plain text file
		<p><input type="checkbox" value="ON" name="byemail"> Please send results to: 
		<input type="text" name="email" size="22"></p>
		
<p><input type="submit" value="Send" name="submit">
		<input type="reset" value="Restore defaults" name="reset"></p>
</form>
		
<table border="0">
			
</table>
<br>

</td>
	</tr>
	<tr>
		<td>
		<p align="center">
		<a href="https://www.mpi-hlr.de/developmental-genetics">Stainier Lab</a><br>
		<a href="https://www.mpi-hlr.de/en">Max Planck Institute for Heart and Lung Research</a><br>
		Questions/suggestions email: <a href="muzzammilbhaisaheb@gmail.com">Muzzammil B</a>.
		</p></td>
	</tr>
</table>

</body>
</html>