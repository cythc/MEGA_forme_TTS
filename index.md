
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
  <li><a href="#V3-mix">V3捏音色</a></li>
  <li><a href="#V3-data">V3加上第二期数据结果对比</a></li>
  <li><a href="#P2">第二期音色生成效果</a></li>
</ol>

<h2>Base-Model<a name="base"></a></h2>
<h4>使用的spkid</h4>

<table>
    <thead>
    <tr>
      <th style="text-align: left">Speakers</th>
      <td style="text-align: left">V2</td>
      <td style="text-align: left">V3</td>
    </tr>
    </thead>

    <!--女生-->
    <tr>
      <th style="text-align: left"><strong>una(F)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\una.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_una_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>chenqingxin(F)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\chenqingxin.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_chenqingxin_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

     <tr>
      <th style="text-align: left"><strong>yequmeng(F)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\yequmeng.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_yequmeng_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

     <tr>
      <th style="text-align: left"><strong>zhuwen(F)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\zhuwen.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_zhuwen_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <!--男生-->
    <tr>
      <th style="text-align: left"><strong>zhuhao(M)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\zhuhao.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_zhuhao_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>eason(M)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\eason.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_eason_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>

    <tr>
      <th style="text-align: left"><strong>yinge(M)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\yinge.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_yinge_kouyu.mp3" controls="" preload=""></audio></td>
    </tr>
    
    <tr>
      <th style="text-align: left"><strong>gulei(M)</strong></th>
      <td style="text-align: left"><audio src="wavs\V2-0626\gulei.wav" controls="" preload=""></audio></td>
      <td style="text-align: left"><audio src="wavs\V3-0626\v3mix_gulei_kouyu.mp3" controls="" preload=""></audio></td>
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


