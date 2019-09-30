---
layout: single
author_profile: true
---



Interactive and Automatic Navigation for 360° Video Playback

Kyoungkook Kang, Sunghyun Cho



<!doctype html>
<html>
<head>
    <title> Interactive and Automatic Navigation for 360° Video Playback </title>
</head>

<LINK media=all href= "../glab.css" type=text/css rel=StyleSheet>
<STYLE type=text/css media=all>

#primarycontent {
    MARGIN-LEFT: auto; ; WIDTH: expression(document.body.clientWidth >
800? "800px": "auto" ); MARGIN-RIGHT: auto; TEXT-ALIGN: left; max-width:
800px }
BODY {
    TEXT-ALIGN: center
}
.style1 {font-size: x-small}
</STYLE>






<body>
<DIV id=primarycontent>
<H1 align="center"> Interactive and Automatic Navigation for 360° Video Playback </H1>
<!-- Author header -->
  <table width="90%" border="0" align="center" cellpadding="0" cellspacing="3">
    <tr>
        <td><p align="center"><a href=https://kyoungkookkang.github.io/ target="_blank">Kyoungkook Kang</a><br>DGIST</p></td>
        <td><p align="center"><a href=https://vclab.dgist.ac.kr/scho/ target="_blank">Sunghyun Cho</a><br>DGIST</p></td>
    </tr>
    <tr>
      <td colspan="5">      <p align="center"><strong> ACM Transactions on Graphics, vol. 38, no. 4, Article 108 (SIGGRAPH 2019) </strong></p><br></td>
    </tr>
  </table><br>

<!-- Teasure -->
<table>
    <table width="95%" border="0" align="center" cellpadding="0" cellspacing="0">
    <tr>
        <td><img src=teaser.jpg width=95%></td></tr>
</table><br>

<!-- body -->
    <table width = "95%" border="0" align="center" cellpadding="0" cellspacing="5">
        <tr>
            <td width="70%"><h2 align="left">Abstract</h2>
                <p align="justify"> This paper presents a novel filtering-based method for decomposing an image into structures and textures. Unlike previous filtering algorithms, our method adaptively smooths image gradients to filter out textures from images. A  new  gradient  operator,  the  interval  gradient,  is  proposed  for  adaptive  gradient  smoothing.  Using  interval gradients, textures can be distinguished from structure edges and smoothly varying shadings. We also propose an effective gradient-guided algorithm to produce high quality image filtering results from filtered gradients. Our method avoids gradient reversal in the filtering results and preserves sharp features better than existing filtering approaches, while retaining simplicity and highly parallel implementation. The proposed method can be utilized for various applications that require accurate structure-texture decomposition of images.</p></td>
            <td width="30%" rowspan="3" valign="top"><br>
                <table width="95%" border="0" align="right" cellpadding="0" cellspacing="6">
                <tr>
<td><a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.12875">Paper (Wiley Online Library)</a>
</td></tr>
<tr>
<td><a href="https://github.com/JunhoJeon/interval_gradient">Source code (github)</a>
</td>
</tr>
<tr><td width=50%><div align="right"></td></tr>
<tr><td width=50%><div align="right"></td></tr>            
</tr>
            </table>
            </td>
        </tr>
        <tr>
        <td>
          <!-- <table align="middle"> <tr> <td> <a href="http://coupe.postech.ac.kr"> <img src="../coupelogo.png"> </a> </td> <td> see the new features in coupe website  <a href="http://coupe.postech.ac.kr"> [link] </td></tr> </a> </table> -->
        </td>
        </tr>
    </table>

</DIV>
</body></html>
