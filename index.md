
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
    </tr>
    </thead>

    <!--女生-->
    <tr>
      <th style="text-align: left"><strong>SPEAKER3404(ZH->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\SPEAKER3404_00000016.WAV" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_SPEAKER3403_JXY.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>spk23(ZH->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\\chenqingxin.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_spk23_JXY.mp3" controls="" preload=""></audio></td>
    </tr>

     <tr>
      <th style="text-align: left"><strong>laoqu(ZH->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\yequmeng.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_laoqu_JXY.mp3" controls="" preload=""></audio></td>
    </tr>
     
     <!--ZH->EN-->
      
     <tr>
      <th style="text-align: left"><strong>SPEAKER3404(ZH->EN)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\zhuwen.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_zhuwen_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>spk23(ZH->EN)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\\chenqingxin.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_spk23_JXY.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>laoqu(ZH->EN)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\yequmeng.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_laoqu_JXY.mp3" controls="" preload=""></audio></td>
    </tr>

   <!--EN->EN-->

   <tr>
      <th style="text-align: left"><strong>SPEAKER3404(EN->EN)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\zhuwen.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_zhuwen_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>spk23(EN->EN)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\\chenqingxin.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_spk23_JXY.mp3" controls="" preload=""></audio></td>
    </tr>


   <!--EN->ZH-->

   <tr>
      <th style="text-align: left"><strong>SPEAKER3404(EN->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\zhuwen.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_zhuwen_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>spk23(EN->ZH)</strong></th>
      <td style="text-align: left"><audio src="wavs\spkid_bert\\chenqingxin.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\spkid_bert\v3mix_spk23_JXY.mp3" controls="" preload=""></audio></td>
    </tr>

  
</table>

<!--｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜｜-->

<h2>Base-Model+speaker encoder<a name="spk"></a></h2>
<h3> 女生混合</h3>

<div style="overflow-x: auto;">
<table>
    <thead>
    <tr>
      <th style="text-align: left">混合比例</th>
      <th style="text-align: left">una</th>
      <th style="text-align: left">zhuwen</th>
      <td style="text-align: left">混合</td>
    </tr>
    </thead>

    <tr>
      <th style="text-align: left"><strong>0.2*Una(F) + 0.8*zhuwen(F)</strong></th>
      <td rowspan="3" style="text-align: left"><audio src="wavs\V3-0626\v3mix_una_kouyu.mp3" controls="" preload=""></audio></td>
      <td rowspan="3" style="text-align: left"><audio src="wavs\V3-0626\v3mix_zhuwen_kouyu.mp3" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-mix-0628\v3mix_una0.2_zhuwen0.8_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>0.5*Una(F) + 0.5*zhuwen(F)</strong></th>
      
      <td style="text-align: left"><audio src="wavs\V3-mix-0628\v3mix_una0.5_zhuwen0.5_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>0.8*Una(F) + 0.2*zhuwen(F)</strong></th>
      
      <td style="text-align: left"><audio src="wavs\V3-mix-0628\v3mix_una0.8_zhuwen0.2_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>
  
</table>
</div>

  </body>
</html>


