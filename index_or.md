    ese_finder_copy01
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN Transitional" "http://www.w3.org/TR/html4/loose.dtd">
<html>

<head>
<meta http-equiv="Content-Language" content="en-us">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<link rel=stylesheet type="text/css" HREF="/tools/ESE3/TRED.css">

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

<body bgcolor="#C0C0C0">

<table border="0" width="1024" id="table1" bgcolor="#FFFFFF" cellpadding="5" style="border:1px solid #000000; padding:3px; border-collapse: collapse" height="664">
	<tr>
		<td height="29">
		<p align="right"><font face="Arial" size="2">last update:
				<!--webbot bot="Timestamp" S-Type="EDITED" S-Format="%m/%d/%Y" -->02/27/2007<!--webbot bot="Timestamp" endspan i-checksum="12522" -->
		</font></td>
	</tr>
	<tr>
			<td height="150" align="center">
					<img border="0" src="/tools/ESE3/images/eselogo.gif" width="450" height="150"><br>
	</tr>
	<tr>
		<td height="19" align="center" bgcolor="#282828">
				<!--//	<p align="center"> //-->
				
		<font color="#E6E6E6" face="Arial" size="2">
		<a class="topnav" href="/cgi-bin/tools/ESE3/esefinder.cgi?process=home"><font size="3" color="#FFFFFF">Search</font> </a>|
		<a class="topnav" href="/cgi-bin/tools/ESE3/esefinder.cgi?process=background">background</a> |
		<a class="topnav" href="/cgi-bin/tools/ESE3/esefinder.cgi?process=matrices">matrices &amp; 
		thresholds</a> | 
		<a class="topnav" href="/cgi-bin/tools/ESE3/esefinder.cgi?process=output">
		input & output</a> | 
<a class="topnav" href="/cgi-bin/tools/ESE3/esefinder.cgi?process=caveats">caveats</a></font></td>
	</tr>
	<tr>
			<td valign= "top" height="600">

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
Go to <a href="/tools/ESE2/">ESEfinder2.0</a><p>


<form method="POST" action="/cgi-bin/tools/ESE3/esefinder.cgi" name="query_form"  enctype="multipart/form-data">
<input type="hidden" name="process" value="search">
<table border="0" width="100%" id="table4" cellpadding="0" style="border-collapse: collapse; border-left-width: 1px; border-right-width: 1px; border-top-width: 1px; border-bottom: 1px dotted #0000FF">
			<tr>
					<td width="165" bgcolor="#0066CC">
				<font face="Arial" color="#E6E6E6">Matrix information</font></td>
				<td width = "635"></td>
			</tr>
		</table>
		<p><font face="Arial" size="2">Please choose a matrix library:
			</font>
			
			<select size="1" name="db" onchange="refreshPage(); return true;">
<option value="SRProteins"selected>SRProteins</option>
<option value="SpliceSites">SpliceSites</option>
<option value="hnRNP">hnRNP</option>
</select>


		<font size="2"> </font></p>
		<p><font face="Arial" size="2">Choose the matrix and the threshold to be 
		used:</font></p>
	<script language="javascript">
function resetThresholds ()
{
	this.document.query_form.threshold_sf2.value=1.956;
	this.document.query_form.threshold_sf2_igm_brca1.value=1.867;
	this.document.query_form.threshold_sc35.value=2.383;
	this.document.query_form.threshold_srp40.value=2.67;
	this.document.query_form.threshold_srp55.value=2.676;
}
</script>
<table border="0" width="60%" style="border: 1px solid #000000; padding:0; border-collapse: collapse" cellpadding="0">
<tr>
<td  style="border: 1px solid #C0C0C0" width="33" bgcolor="#282828"></td>
<td style="border: 1px solid #C0C0C0" bgcolor="#282828"><b><font face="Arial" color="#E6E6E6">Matrices (select one or more)</font></b></td>
<td style="border: 1px solid #C0C0C0" width="192" align="center" bgcolor="#282828"><b><font face="Arial" color="#E6E6E6">Threshold</font></b></td>
</tr>
<tr>
<td style="border: 1px solid #C0C0C0" width="33" bgcolor="#E6E6E6"><input type="checkbox" name="check_sf2" value="ON" checked></td>
<td style="border: 1px solid #C0C0C0" bgcolor="#E6E6E6"><b>SF2/ASF</b> (SF2/ASF round 3 winner)</td>
<td style="border: 1px solid #C0C0C0" width = "192" bgcolor="#E6E6E6"><input type="text", name="threshold_sf2" value="1.956"></td>
</tr>
<tr>
<td style="border: 1px solid #C0C0C0" width="33" ><input type="checkbox" name="check_sf2_igm_brca1" value="ON" checked></td>
<td style="border: 1px solid #C0C0C0" ><b>SF2/ASF (IgM-BRCA1)</b> (Smith06-HMG-matrix)</td>
<td style="border: 1px solid #C0C0C0" width = "192" ><input type="text", name="threshold_sf2_igm_brca1" value="1.867"></td>
</tr>
<tr>
<td style="border: 1px solid #C0C0C0" width="33" bgcolor="#E6E6E6"><input type="checkbox" name="check_sc35" value="ON" checked></td>
<td style="border: 1px solid #C0C0C0" bgcolor="#E6E6E6"><b>SC35</b> (SC35 round 3 winner)</td>
<td style="border: 1px solid #C0C0C0" width = "192" bgcolor="#E6E6E6"><input type="text", name="threshold_sc35" value="2.383"></td>
</tr>
<tr>
<td style="border: 1px solid #C0C0C0" width="33" ><input type="checkbox" name="check_srp40" value="ON" checked></td>
<td style="border: 1px solid #C0C0C0" ><b>SRp40</b> (SRp40 round 3 winner)</td>
<td style="border: 1px solid #C0C0C0" width = "192" ><input type="text", name="threshold_srp40" value="2.67"></td>
</tr>
<tr>
<td style="border: 1px solid #C0C0C0" width="33" bgcolor="#E6E6E6"><input type="checkbox" name="check_srp55" value="ON" checked></td>
<td style="border: 1px solid #C0C0C0" bgcolor="#E6E6E6"><b>SRp55</b> (SRp55 round 3 winner)</td>
<td style="border: 1px solid #C0C0C0" width = "192" bgcolor="#E6E6E6"><input type="text", name="threshold_srp55" value="2.676"></td>
</tr>
<tr>
<td style="border: 1px solid #C0C0C0" width="33"></td>
<td style="border: 1px solid #C0C0C0"></td>
<td style="border: 1px solid #C0C0C0" width = "192"><input type="button" value="Reset thresholds" name="reset Thresholds" onClick="resetThresholds(); return true"></td>
</tr>
</table>

		<br>
		<table border="0" width="100%" id="table5" cellpadding="0" style="border-collapse: collapse; border-left-width: 1px; border-right-width: 1px; border-top-width: 1px; border-bottom: 1px dotted #0000FF">
			<tr>
				<td width="165" bgcolor="#0066CC">
				<font face="Arial" color="#E6E6E6">Sequence information</font></td>
				<td width="635"></td>
			</tr>
		</table>
		<p><font face="Arial" size="2">Enter here your input data in FASTA or 
				MULTI-FASTA format (<b><font color="blue"><5000nt, accept both 'T' and 'U' as being equivalent)</font></b><br>
		(please read important information about 
		<a href="/cgi-bin/tools/ESE3/esefinder.cgi?process=output">search 
		format description</a>)</font></p>
		<p><font face="Arial">
		<textarea rows="10" name="seq" cols="83"></textarea></font></p>
		<p><font face="Arial"><font size="2">alternatively, upload a text file:
		</font>
		<input type="file" name="upload" size="53"></font></p>
		<p></p>
		<table border="0" width="100%" id="table6" cellpadding="0" style="border-collapse: collapse; border-left-width: 1px; border-right-width: 1px; border-top-width: 1px; border-bottom: 1px dotted #0000FF">
			<tr>
					<td width="165" bgcolor="#0066CC">
				<font face="Arial" color="#E6E6E6">Output information</font></td>
				<td width="635"></td>
			</tr>
		</table>
		<p><font size="2" face="Arial">Override the thresholds above and use one 
		of the following two options: </font><font size="2"><br>
		</font><input type="checkbox" value="ON" name="report_max_only"><font size="2" face="Arial"> 
		Report only the best hit in each sequence (instead of hits above the 
		thresholds)</font><font size="2"><br>
		</font><input type="checkbox" value="ON" name="report_all_score"><font size="2" face="Arial"> 
		Report all scores in each sequence (instead of hits above the 
		thresholds)</font><font size="2"> </font></p>
		<p><font size="2" face="Arial">(<b>Note</b>: if you check both, the 
		program will report the best hit in each sequence.)</font><font size="2">
		</font></p>
		<p></p>
		<p><input type="checkbox" value="ON" name="format_text"><font size="2" face="Arial">Output 
		as a plain text file</font><font size="2"> </font></p>
		<p><font size="2"><!--
		<font face="Arial">2. Output format: </font><br>
		<input type="radio" name="format" value="text">To a TEXT file
		(<font face="Arial">Output perspective: </font><input type="radio" name="perspective" value="gene" checked>gene,
		<input type="radio" name="perspective" value="motif">motif)<br>
		<input type="radio" name="format" value="html" checked>To a HTML file
		</p>													
		<p><font face="Arial">
		//--></font><font face="Arial">
		<input type="checkbox" value="ON" name="byemail"><font size="2">please 
		send the results to the following e-mail address:</font>
		<input type="text" style="BACKGROUND-COLOR: #ffffa0" name="email" size="29"></font></p>
<p><font face="Arial"><input type="submit" value="Send" name="submit">
		<input type="reset" value="Restore defaults" name="reset"></font></p>
</form>
		<p></p>
		<p></p>
		<p></p>
		<br><br>
<table border="0" width="100%" id="table4" cellpadding="0" style="border-collapse: collapse; border-left-width: 1px; border-right-width: 1px; border-top-width: 1px; border-bottom: 1px dotted #0000FF">
			<tr>
					<td width="165" bgcolor="#0066CC">
							<font face="Arial" color="#E6E6E6">Citation information</font></td>
				<td width = "635"></td>
			</tr>
		</table>
<br>

</td>
	</tr>
	<tr>
		<td height="61">
		<p align="center"><font face="Arial" size="1">
		<a href="http://gradschool.cshl.edu/krainer_.html">Krainer Lab</a> and
		<a href="http://rulai.cshl.edu/">Zhang Lab</a>,
		<a href="http://www.cshl.edu">Cold Spring Harbor Laboratory</a>, all 
		rights reserved <br>
		Questions/suggestions email: <a href="mailto:wangjh@umn.edu">Jinhua Wang</a>. </font></td>
	</tr>
</table>

</body>

</html>

