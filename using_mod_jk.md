layout: page
title: "Using mod_jk"
permalink: /URL-PATH/

<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 12">
<meta name=Originator content="Microsoft Word 12">
<link rel=File-List href="using_mod_jk_files/filelist.xml">
<link rel=Preview href="using_mod_jk_files/preview.wmf">
<link rel=Edit-Time-Data href="using_mod_jk_files/editdata.mso">
<!--[if !mso]>
<style>
v\:* {behavior:url(#default#VML);}
o\:* {behavior:url(#default#VML);}
w\:* {behavior:url(#default#VML);}
.shape {behavior:url(#default#VML);}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:DocumentProperties>
  <o:Author>kavin</o:Author>
  <o:Template>Normal</o:Template>
  <o:LastAuthor>kavin</o:LastAuthor>
  <o:Revision>2</o:Revision>
  <o:TotalTime>22</o:TotalTime>
  <o:Created>2020-06-30T14:16:00Z</o:Created>
  <o:LastSaved>2020-06-30T14:16:00Z</o:LastSaved>
  <o:Pages>3</o:Pages>
  <o:Words>560</o:Words>
  <o:Characters>3198</o:Characters>
  <o:Lines>26</o:Lines>
  <o:Paragraphs>7</o:Paragraphs>
  <o:CharactersWithSpaces>3751</o:CharactersWithSpaces>
  <o:Version>12.00</o:Version>
 </o:DocumentProperties>
</xml><![endif]-->
<link rel=themeData href="using_mod_jk_files/themedata.thmx">
<link rel=colorSchemeMapping href="using_mod_jk_files/colorschememapping.xml">
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:TrackMoves>false</w:TrackMoves>
  <w:TrackFormatting/>
  <w:PunctuationKerning/>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>EN-US</w:LidThemeOther>
  <w:LidThemeAsian>X-NONE</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:BreakWrappedTables/>
   <w:SnapToGridInCell/>
   <w:WrapTextWithPunct/>
   <w:UseAsianBreakRules/>
   <w:DontGrowAutofit/>
   <w:SplitPgBreakAndParaMark/>
   <w:DontVertAlignCellWithSp/>
   <w:DontBreakConstrainedForcedTables/>
   <w:DontVertAlignInTxbx/>
   <w:Word11KerningPairs/>
   <w:CachedColBalance/>
  </w:Compatibility>
  <w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="--"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="true"
  DefSemiHidden="true" DefQFormat="false" DefPriority="99"
  LatentStyleCount="267">
  <w:LsdException Locked="false" Priority="0" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" Name="toc 9"/>
  <w:LsdException Locked="false" Priority="35" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" Priority="10" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" Priority="1" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" Priority="11" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" Priority="22" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" Priority="59" SemiHidden="false"
   UnhideWhenUsed="false" Name="Table Grid"/>
  <w:LsdException Locked="false" UnhideWhenUsed="false" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" UnhideWhenUsed="false" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" SemiHidden="false"
   UnhideWhenUsed="false" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" SemiHidden="false"
   UnhideWhenUsed="false" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" SemiHidden="false"
   UnhideWhenUsed="false" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" SemiHidden="false"
   UnhideWhenUsed="false" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" SemiHidden="false"
   UnhideWhenUsed="false" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" QFormat="true" Name="TOC Heading"/>
 </w:LatentStyles>
</xml><![endif]-->
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-536870145 1107305727 0 0 415 0;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-520092929 1073786111 9 0 415 0;}
@font-face
	{font-family:Tahoma;
	panose-1:2 11 6 4 3 5 4 4 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-520081665 -1073717157 41 0 66047 0;}
@font-face
	{font-family:"Segoe UI";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-520084737 -1073683329 41 0 479 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin-top:0in;
	margin-right:0in;
	margin-bottom:10.0pt;
	margin-left:0in;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
a:link, span.MsoHyperlink
	{mso-style-priority:99;
	color:blue;
	mso-themecolor:hyperlink;
	text-decoration:underline;
	text-underline:single;}
a:visited, span.MsoHyperlinkFollowed
	{mso-style-noshow:yes;
	mso-style-priority:99;
	color:purple;
	mso-themecolor:followedhyperlink;
	text-decoration:underline;
	text-underline:single;}
p.MsoAcetate, li.MsoAcetate, div.MsoAcetate
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-link:"Balloon Text Char";
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:8.0pt;
	font-family:"Tahoma","sans-serif";
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	margin-top:0in;
	margin-right:0in;
	margin-bottom:10.0pt;
	margin-left:.5in;
	mso-add-space:auto;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0in;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:.5in;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0in;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:.5in;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0in;
	margin-right:0in;
	margin-bottom:10.0pt;
	margin-left:.5in;
	mso-add-space:auto;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
span.BalloonTextChar
	{mso-style-name:"Balloon Text Char";
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Balloon Text";
	mso-ansi-font-size:8.0pt;
	mso-bidi-font-size:8.0pt;
	font-family:"Tahoma","sans-serif";
	mso-ascii-font-family:Tahoma;
	mso-hansi-font-family:Tahoma;
	mso-bidi-font-family:Tahoma;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
.MsoPapDefault
	{mso-style-type:export-only;
	margin-bottom:10.0pt;
	line-height:115%;}
@page Section1
	{size:8.5in 11.0in;
	margin:1.0in 1.0in 1.0in 1.0in;
	mso-header-margin:.5in;
	mso-footer-margin:.5in;
	mso-paper-source:0;}
div.Section1
	{page:Section1;}
 /* List Definitions */
 @list l0
	{mso-list-id:166099461;
	mso-list-type:hybrid;
	mso-list-template-ids:-793491278 67698703 67698713 67698715 67698703 67698713 67698715 67698703 67698713 67698715;}
@list l0:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-.25in;}
@list l1
	{mso-list-id:393431641;
	mso-list-template-ids:-297219544;}
@list l1:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:.5in;
	mso-level-number-position:left;
	text-indent:-.25in;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
ol
	{margin-bottom:0in;}
ul
	{margin-bottom:0in;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Table Normal";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-qformat:yes;
	mso-style-parent:"";
	mso-padding-alt:0in 5.4pt 0in 5.4pt;
	mso-para-margin-top:0in;
	mso-para-margin-right:0in;
	mso-para-margin-bottom:10.0pt;
	mso-para-margin-left:0in;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
table.MsoTableGrid
	{mso-style-name:"Table Grid";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-priority:59;
	mso-style-unhide:no;
	border:solid black 1.0pt;
	mso-border-themecolor:text1;
	mso-border-alt:solid black .5pt;
	mso-border-themecolor:text1;
	mso-padding-alt:0in 5.4pt 0in 5.4pt;
	mso-border-insideh:.5pt solid black;
	mso-border-insideh-themecolor:text1;
	mso-border-insidev:.5pt solid black;
	mso-border-insidev-themecolor:text1;
	mso-para-margin:0in;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:shapedefaults v:ext="edit" spidmax="2050"/>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <o:shapelayout v:ext="edit">
  <o:idmap v:ext="edit" data="1"/>
 </o:shapelayout></xml><![endif]-->
</head>

<body lang=EN-US link=blue vlink=purple style='tab-interval:.5in'>

<div class=Section1>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid black .5pt;
 mso-border-themecolor:text1;mso-yfti-tbllook:1184;mso-padding-alt:0in 5.4pt 0in 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=638 valign=top style='width:6.65in;border:solid black 1.0pt;
  mso-border-themecolor:text1;mso-border-alt:solid black .5pt;mso-border-themecolor:
  text1;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'>From tomcat:</p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='mso-no-proof:yes'><!--[if gte vml 1]><v:shapetype id="_x0000_t75"
   coordsize="21600,21600" o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe"
   filled="f" stroked="f">
   <v:stroke joinstyle="miter"/>
   <v:formulas>
    <v:f eqn="if lineDrawn pixelLineWidth 0"/>
    <v:f eqn="sum @0 1 0"/>
    <v:f eqn="sum 0 0 @1"/>
    <v:f eqn="prod @2 1 2"/>
    <v:f eqn="prod @3 21600 pixelWidth"/>
    <v:f eqn="prod @3 21600 pixelHeight"/>
    <v:f eqn="sum @0 0 1"/>
    <v:f eqn="prod @6 1 2"/>
    <v:f eqn="prod @7 21600 pixelWidth"/>
    <v:f eqn="sum @8 21600 0"/>
    <v:f eqn="prod @7 21600 pixelHeight"/>
    <v:f eqn="sum @10 21600 0"/>
   </v:formulas>
   <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"/>
   <o:lock v:ext="edit" aspectratio="t"/>
  </v:shapetype><v:shape id="Picture_x0020_1" o:spid="_x0000_i1027" type="#_x0000_t75"
   style='width:463.5pt;height:75pt;visibility:visible' o:gfxdata="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
9yAAAAAA
">
   <v:imagedata src="using_mod_jk_files/image001.png" o:title=""/>
   <o:lock v:ext="edit" aspectratio="f"/>
  </v:shape><![endif]--><![if !vml]><img width=618 height=100
  src="using_mod_jk_files/image002.gif" v:shapes="Picture_x0020_1"><![endif]></span></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'>We would like Apache httpd to act as frontend that receive user
  request and forward to the tomcat instance.</p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='mso-no-proof:yes'><!--[if gte vml 1]><v:shape id="Picture_x0020_4"
   o:spid="_x0000_i1026" type="#_x0000_t75" style='width:411.75pt;height:67.5pt;
   visibility:visible' o:gfxdata="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
cG5nUEsFBgAAAAAGAAYAfAEAACUeAAAAAA==
">
   <v:imagedata src="using_mod_jk_files/image003.png" o:title=""/>
   <o:lock v:ext="edit" aspectratio="f"/>
  </v:shape><![endif]--><![if !vml]><img width=549 height=90
  src="using_mod_jk_files/image004.gif" v:shapes="Picture_x0020_4"><![endif]></span></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><u>Use Case:<o:p></o:p></u></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='mso-no-proof:yes'><!--[if gte vml 1]><v:shape id="Picture_x0020_7"
   o:spid="_x0000_i1025" type="#_x0000_t75" style='width:437.25pt;height:312.75pt;
   visibility:visible;mso-wrap-style:square'>
   <v:imagedata src="using_mod_jk_files/image005.png" o:title=""/>
  </v:shape><![endif]--><![if !vml]><img width=583 height=417
  src="using_mod_jk_files/image006.jpg" v:shapes="Picture_x0020_7"><![endif]></span></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'>Based on the context root eg: /Dep1 /Dep2 /Dep3 it would redirect to
  the different tomcat instances.</p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-top:28.05pt;margin-right:0in;margin-bottom:
  0in;margin-left:0in;margin-bottom:.0001pt;line-height:normal;mso-outline-level:
  3;background:white'><b><span style='font-size:15.0pt;font-family:"Segoe UI","sans-serif";
  mso-fareast-font-family:"Times New Roman";color:#172B4D;letter-spacing:-.05pt'>Why
  should I integrate Apache HTTP Server with Apache Tomcat? (or not)<o:p></o:p></span></b></p>
  <p class=MsoNormal style='margin-top:9.35pt;margin-right:0in;margin-bottom:
  0in;margin-left:0in;margin-bottom:.0001pt;line-height:normal;background:white'><span
  style='font-size:13.0pt;font-family:"Segoe UI","sans-serif";mso-fareast-font-family:
  "Times New Roman";color:#172B4D'>There are many reasons to integrate Tomcat
  with Apache. And there are reasons why it should not be done too. Needless to
  say, everyone will disagree with the opinions here. With the performance of
  Tomcat 5 and 6, performance reasons become harder to justify. So here are the
  issues to discuss in integrating vs not.<o:p></o:p></span></p>
  <p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
  margin-left:.25in;text-indent:-.25in;line-height:normal;mso-list:l1 level1 lfo1;
  tab-stops:list .5in;background:white'><![if !supportLists]><span
  style='font-size:10.0pt;mso-bidi-font-size:13.0pt;font-family:Symbol;
  mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:#172B4D'><span
  style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span></span><![endif]><span style='font-size:13.0pt;font-family:
  "Segoe UI","sans-serif";mso-fareast-font-family:"Times New Roman";color:#172B4D'>Clustering.
  By using Apache as a front end you can let Apache act as a front door to your
  content to multiple Tomcat instances. If one of your Tomcats fails, Apache
  ignores it and your Sysadmin can sleep through the night. This point could be
  ignored if you use a hardware loadbalancer and Tomcat's clustering
  capabilities.<o:p></o:p></span></p>
  <p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
  margin-left:.25in;text-indent:-.25in;line-height:normal;mso-list:l1 level1 lfo1;
  tab-stops:list .5in;background:white'><![if !supportLists]><span
  style='font-size:10.0pt;mso-bidi-font-size:13.0pt;font-family:Symbol;
  mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:#172B4D'><span
  style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span></span><![endif]><span style='font-size:13.0pt;font-family:
  "Segoe UI","sans-serif";mso-fareast-font-family:"Times New Roman";color:#172B4D'>Clustering/Security.
  You can also use Apache as a front door to different Tomcats for different
  URL namespaces (/app1/, /app2/, /app3/, or virtual hosts). The Tomcats can
  then be each in a protected area and from a security point of view, you only
  need to worry about the Apache server. Essentially, Apache becomes a smart
  proxy server.<o:p></o:p></span></p>
  <p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
  margin-left:.25in;text-indent:-.25in;line-height:normal;mso-list:l1 level1 lfo1;
  tab-stops:list .5in;background:white'><![if !supportLists]><span
  style='font-size:10.0pt;mso-bidi-font-size:13.0pt;font-family:Symbol;
  mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:#172B4D'><span
  style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span></span><![endif]><span style='font-size:13.0pt;font-family:
  "Segoe UI","sans-serif";mso-fareast-font-family:"Times New Roman";color:#172B4D'>Security.
  This topic can sway one either way. Java has the security manager while
  Apache has a larger mindshare and more tricks with respect to security. I
  won't go into this in more detail, but let Google be your friend. Depending
  on your scenario, one might be better than the other. But also keep in mind,
  if you run Apache with Tomcat - you have two systems to defend, not one.<o:p></o:p></span></p>
  <p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
  margin-left:.25in;text-indent:-.25in;line-height:normal;mso-list:l1 level1 lfo1;
  tab-stops:list .5in;background:white'><![if !supportLists]><span
  style='font-size:10.0pt;mso-bidi-font-size:13.0pt;font-family:Symbol;
  mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:#172B4D'><span
  style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span></span><![endif]><span style='font-size:13.0pt;font-family:
  "Segoe UI","sans-serif";mso-fareast-font-family:"Times New Roman";color:#172B4D'>Add-ons.
  Adding on CGI, perl, PHP is very natural to Apache. Its slower and more of a
  kludge for Tomcat. Apache also has hundreds of modules that can be plugged in
  at will. Tomcat can have this ability, but the code hasn't been written yet.<o:p></o:p></span></p>
  <p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
  margin-left:.25in;text-indent:-.25in;line-height:normal;mso-list:l1 level1 lfo1;
  tab-stops:list .5in;background:white'><![if !supportLists]><span
  style='font-size:10.0pt;mso-bidi-font-size:13.0pt;font-family:Symbol;
  mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:#172B4D'><span
  style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span></span><![endif]><span style='font-size:13.0pt;font-family:
  "Segoe UI","sans-serif";mso-fareast-font-family:"Times New Roman";color:#172B4D'>Decorators!
  With Apache in front of Tomcat, you can perform any number of decorators that
  Tomcat doesn't support or doesn't have the immediate code support. For
  example, mod_headers, mod_rewrite, and mod_alias could be written for Tomcat,
  but why reinvent the wheel when Apache has done it so well?<o:p></o:p></span></p>
  <p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
  margin-left:.25in;text-indent:-.25in;line-height:normal;mso-list:l1 level1 lfo1;
  tab-stops:list .5in;background:white'><![if !supportLists]><span
  style='font-size:10.0pt;mso-bidi-font-size:13.0pt;font-family:Symbol;
  mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:#172B4D'><span
  style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span></span><![endif]><span style='font-size:13.0pt;font-family:
  "Segoe UI","sans-serif";mso-fareast-font-family:"Times New Roman";color:#172B4D'>Speed.
  Apache is faster at serving static content than Tomcat. But unless you have a
  high traffic site, this point is useless. But in some scenarios, tomcat can
  be faster than Apache httpd. So benchmark YOUR site.&nbsp;</span><b><span
  style='font-size:13.0pt;mso-bidi-font-size:11.0pt;font-family:"Segoe UI","sans-serif";
  mso-fareast-font-family:"Times New Roman";color:#172B4D'>Tomcat can perform
  at httpd speeds when using the proper connector (APR with sendFile enabled).
  Speed should not be considered a factor when choosing between Apache httpd
  and Tomcat</span></b><span style='font-size:13.0pt;font-family:"Segoe UI","sans-serif";
  mso-fareast-font-family:"Times New Roman";color:#172B4D'><o:p></o:p></span></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:13.0pt;font-family:"Segoe UI","sans-serif";
  mso-fareast-font-family:"Times New Roman";color:#172B4D'>Socket
  handling/system stability. Apache has better socket handling with respect to
  error conditions than Tomcat. The main reason is Tomcat must perform all its
  socket handling via the JVM which needs to be cross platform. The problem is
  socket optimization is a platform specific ordeal. Most of the time the java
  code is fine, but when you are also bombarded with dropped connections,
  invalid packets, invalid requests from invalid IP's, Apache does a better job
  at dropping these error conditions than JVM based program. (YMMV)</span></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><o:p>&nbsp;</o:p></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid black .5pt;
 mso-border-themecolor:text1;mso-yfti-tbllook:1184;mso-padding-alt:0in 5.4pt 0in 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=638 valign=top style='width:6.65in;border:solid black 1.0pt;
  mso-border-themecolor:text1;mso-border-alt:solid black .5pt;mso-border-themecolor:
  text1;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'>S/w Used</p>
  <p class=MsoListParagraphCxSpFirst style='margin-bottom:0in;margin-bottom:
  .0001pt;mso-add-space:auto;text-indent:-.25in;line-height:normal;mso-list:
  l0 level1 lfo2'><![if !supportLists]><span style='mso-bidi-font-family:Calibri;
  mso-bidi-theme-font:minor-latin'><span style='mso-list:Ignore'>1.<span
  style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]>httpd-2.2.8</p>
  <p class=MsoListParagraphCxSpMiddle style='margin-bottom:0in;margin-bottom:
  .0001pt;mso-add-space:auto;text-indent:-.25in;line-height:normal;mso-list:
  l0 level1 lfo2'><![if !supportLists]><span style='mso-bidi-font-family:Calibri;
  mso-bidi-theme-font:minor-latin'><span style='mso-list:Ignore'>2.<span
  style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]>apache-tomcat-7.0.25</p>
  <p class=MsoListParagraphCxSpLast style='margin-bottom:0in;margin-bottom:
  .0001pt;mso-add-space:auto;text-indent:-.25in;line-height:normal;mso-list:
  l0 level1 lfo2'><![if !supportLists]><span style='mso-bidi-font-family:Calibri;
  mso-bidi-theme-font:minor-latin'><span style='mso-list:Ignore'>3.<span
  style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span></span><![endif]>tomcat-connectors-1.2.32</p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'>URLS</p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><a
  href="https://archive.apache.org/dist/tomcat/tomcat-7/v7.0.25/bin/apache-tomcat-7.0.25.tar.gz">https://archive.apache.org/dist/tomcat/tomcat-7/v7.0.25/bin/apache-tomcat-7.0.25.tar.gz</a></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><a
  href="https://archive.apache.org/dist/tomcat/tomcat-connectors/jk/tomcat-connectors-1.2.32-src.tar.gz">https://archive.apache.org/dist/tomcat/tomcat-connectors/jk/tomcat-connectors-1.2.32-src.tar.gz</a></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><a href="http://archive.apache.org/dist/httpd/httpd-2.2.8.tar.bz2">http://archive.apache.org/dist/httpd/httpd-2.2.8.tar.bz2</a></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><o:p>&nbsp;</o:p></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><o:p>&nbsp;</o:p></p>

<p class=MsoNormal><o:p>&nbsp;</o:p></p>

</div>

</body>

</html>