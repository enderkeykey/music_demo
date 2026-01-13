<table>
  <!-- 表头（可选，不需要可以删掉） -->
  <thead>
    <tr>
      <th align="center">生成结果 (Output)</th>
      <th align="center"></th>
      <th align="center">参考/提示 (Reference)</th>
      <th align="left">歌词/文本 (Lyrics)</th>
    </tr>
  </thead>
  
  <!-- 第一行: audio1 -->
  <tbody>
    <tr>
      <!-- 第一列：生成的音频 -->
      <td align="center" width="20%">
        <!-- 如果您想放截图里的图标，用 img；如果想直接播放，用 audio -->
        <audio controls src="path/to/audio1.wav"></audio>
        <br>
        <b>audio1</b>
      </td>
      
      <!-- 第二列：箭头 -->
      <td align="center" width="10%">
        <!-- 这是一个巨大的箭头字符，也可以换成图片 -->
        <h1>⬅️</h1> 
      </td>
      
      <!-- 第三列：参考音频和参数 -->
      <td align="center" width="25%">
        <audio controls src="path/to/ref1.wav"></audio>
        <br>
        <code>ref:happy</code>
        <br>
        <code>emo_prompt:natural</code>
      </td>
      
      <!-- 第四列：歌词 -->
      <td align="left" width="45%">
        <pre>
[00:00.00]Now how bout you
[00:02.50]Sweet home alabama
[00:08.00]Where the skies are so blue
[00:13.00]Sweet home alabama
[00:18.50]Lord I'm coming home to you
        </pre>
      </td>
    </tr>

    <!-- 第二行: audio2 (tuning) -->
    <tr>
      <td align="center">
        <audio controls src="path/to/audio2.wav"></audio>
        <br>
        <b>audio2<br>(tuning)</b>
      </td>
      
      <td align="center">
        <h1>⬅️</h1>
      </td>
      
      <td align="center">
        <audio controls src="path/to/ref2.wav"></audio>
        <br>
        <code>ref:tuning_natural</code>
        <br>
        <code>emo_prompt:(none)</code>
      </td>
      
      <td align="left">
        <pre>
[00:00.00]Now how bout you
[00:02.36]Sweet home alabama
[00:07.55]Where the skies are so blue
[00:12.26]Sweet home alabama
[00:17.45]Lord I'm coming home to you
        </pre>
      </td>
    </tr>
  </tbody>
</table>
