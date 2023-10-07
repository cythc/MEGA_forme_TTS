
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
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_laoqu_ZH.mp3" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_laoqu_ENG.mp3" controls="" preload=""></audio></td>
    </tr>
  
</table>

<!--｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜-->

<h2>Base-Model+speaker encoder(from megatts2)<a name="spk"></a></h2>
<h3>【集外说话人】使用不同人的音频作为输入</h3>


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
      <td style="text-align: left"><audio src="wavs\spkenc_bert\v3mix_yujie-30w_una.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>nanyou</strong></th>
      <td style="text-align: left"><audio src="wavs\spkenc_bert\nanyou10.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkenc_bert\v3mix_nanyou-30w_una.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>华宇古风</strong></th>
      <td style="text-align: left"><audio src="wavs\华宇古风.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\v3mix_华宇古风_una.mp3" controls="" preload=""></audio></td>
    </tr>
  
</table>


<h2>Base-Model+speaker encoder+duradaptor<a name="spk"></a></h2>
<h3>【集外说话人】使用不同人的音频作为输入</h3>


<table>
    <thead>
    <tr>
      <th style="text-align: left">speakers</th>
      <th style="text-align: left">Reference audio</th>
      <th style="text-align: left">Generated</th>
    </tr>
    </thead>

     <tr>
     <th style="text-align: left"><strong>luoli</strong></th>
     <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\luoli.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_luoli-60w-noshuffle_luoli.mp3" controls="" preload=""></audio></td>
    </tr>


    <tr>
     <th style="text-align: left"><strong>Yujie</strong></th>
     <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\yujie.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_yujie-60w-noshuffle_yujie(1).mp3" controls="" preload=""></audio></td>
    </tr>

     <tr>
      <th style="text-align: left"><strong>喵系少女</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\喵系少女.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_喵系少女-60w-noshuffle_喵系少女.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>小白桑</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\yujie-小白桑.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_小白桑-60w-noshuffle_小白桑.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>A总</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\A 总.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_A总-60w-noshuffle_A总.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>华宇古风</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\华宇古风.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_华宇古风-60w-noshuffle_华宇古风.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>CV知弦</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\cvzhixian.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_CV知弦-60w-noshuffle_华宇古风.mp3" controls="" preload=""></audio></td>
    </tr>

</table>


<h2>Base-Model+speaker encoder<a name="spk"></a></h2>
<h3>【集内说话人】使用不同人的音频作为输入</h3>

<table>
    <thead>
    <tr>
      <th style="text-align: left">speakers</th>
      <th style="text-align: left">reference audio</th>
      <th style="text-align: left">GT</th>
      <th style="text-align: left">Generated</th>
    </tr>
    </thead>

     <tr>
     <th style="text-align: left"><strong>SSB0005</strong></th>
     <td style="text-align: left"><audio src="wavs\melstyle\SSB0005.wav" controls="" preload=""></audio></td>
     <td style="text-align: left"><audio src="wavs\melstyle\SSB0005_gt.wav" controls="" preload=""></audio></td>
     <td style="text-align: left"><audio src="wavs\melstyle\v3mix_SSB0005-41w-noshuffle_SSB0005.mp3" controls="" preload=""></audio></td>
    </tr>


    <tr>
     <th style="text-align: left"><strong>SSB1956</strong></th>
     <td style="text-align: left"><audio src="wavs\melstyle\SSB1956.wav" controls="" preload=""></audio></td>
     <td style="text-align: left"><audio src="wavs\melstyle\SSB1956_gt.wav" controls="" preload=""></audio></td>
    <td style="text-align: left"><audio src="wavs\melstyle\v3mix_SSB1956-41w-noshuffle_SSB1956.mp3" controls="" preload=""></audio></td>
    </tr>

     <tr>
      <th style="text-align: left"><strong>laoqu</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle\laoqu.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle\laoqu_gt.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle\v3mix_laoqu-41w-noshuffle_laoqu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>spk15</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle\spk15.wav" controls="" preload=""></audio></td>
      
      <td style="text-align: left"><audio src="wavs\melstyle\v3mix_spk15-41w-noshuffle_laoqu_jiwai.mp3" controls="" preload=""></audio></td>
    </tr>
</table>

<h3>【集外说话人】使用不同人的音频作为输入</h3>


<table>
    <thead>
    <tr>
      <th style="text-align: left">speakers</th>
      <th style="text-align: left">Reference audio</th>
      <th style="text-align: left">Generated</th>
    </tr>
    </thead>

     <tr>
     <th style="text-align: left"><strong>luoli</strong></th>
     <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\luoli.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle\v3mix_luoli-60w-noshuffle_luoli.mp3" controls="" preload=""></audio></td>
    </tr>


    <tr>
     <th style="text-align: left"><strong>Yujie</strong></th>
     <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\yujie.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle\v3mix_yujie-60w-noshuffle_yujie(1).mp3" controls="" preload=""></audio></td>
    </tr>

     <tr>
      <th style="text-align: left"><strong>喵系少女</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\喵系少女.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle\v3mix_喵系少女-60w-noshuffle_喵系少女.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>小白桑</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\yujie-小白桑.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstylev3mix_小白桑-60w-noshuffle_小白桑.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>A总</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\A 总.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_A总-60w-noshuffle_A总.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>华宇古风</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\华宇古风.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_华宇古风-60w-noshuffle_华宇古风.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>CV知弦</strong></th>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\cvzhixian.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\melstyle-duradaptor\v3mix_CV知弦-60w-noshuffle_华宇古风.mp3" controls="" preload=""></audio></td>
    </tr> 
</table>


  </body>
</html>


