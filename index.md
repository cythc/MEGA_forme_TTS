
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="theme-color" content="#157878">
    <link rel="stylesheet" href="/assets/css/style.css?v=e27bf585b9c641a881074e09853cb11204774c97">
  </head>
  <body>


<h2>Contents</h2>
<ol>
  <li><a href="#base">Base-Model</a></li>
  <li><a href="#spk">Base-Model+speaker Encoder</a></li>
</ol>

<h2>Base-Model<a name="base"></a></h2>
<h4>使用的spkid</h4>

<table>
    <thead>
    <tr>
      <th style="text-align: left">Speakers</th>
      <td style="text-align: left">GT</td>
      <td style="text-align: left">Generated</td>
      <td style="text-align: left">Generated</td>
    </tr>
    </thead>

    <!--女生-->
    <tr>
      <th style="text-align: left"><strong>SPEAKER3404(ZH->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\SPEAKER3403_00000016.WAV" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_SPEAKER3403_JXY.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>spk23(ZH->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\spk23_000001.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_spk23_JXY-27w.mp3" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_spk23_ENG.mp3" controls="" preload=""></audio></td>
    </tr>

     <tr>
      <th style="text-align: left"><strong>laoqu(ZH->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\laoqu_001_0000026.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_laoqu_ENG.mp3" controls="" preload=""></audio></td>
    </tr>
  
</table>

<!--｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜-->

<h2>Base-Model+speaker encoder<a name="spk"></a></h2>
<h3>使用不同人的音频作为输入</h3>


<table>
    <thead>
    <tr>
      <th style="text-align: left">speakers</th>
      <th style="text-align: left">GT</th>
      <th style="text-align: left">Generated</th>
    </tr>
    </thead>

    <tr>
     <th style="text-align: left"><strong>Yujie</strong></th>
     <td style="text-align: left"><audio src="wavs\spkenc_bert\yujie.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkenc_bert\vamix_yujie-30w_una.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>nanyou</strong></th>
      <td style="text-align: left"><audio src="wavs\spkenc_bert\nanyou10.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkenc_bert\vamix_nanyou-30w_una.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>华宇古风</strong></th>
      <td style="text-align: left"><audio src="wavs\华宇古风.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\v3mix_华宇古风_una.mp3" controls="" preload=""></audio></td>
    </tr>
  
</table>





  </body>
</html>


