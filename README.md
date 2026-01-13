<table>
  <thead>
    <tr>
      <th align="center">生成结果 (Output)</th>
      <th align="center"></th>
      <th align="center">参考/提示 (Reference)</th>
      <th align="left">歌词/文本 (Lyrics)</th>
    </tr>
  </thead>
  
  <tbody>
    <!-- 第一行: audio1.mp3 -->
    <tr>
      <td align="center" width="20%">
        <!-- 这里直接写文件名即可，因为它们和 README 在一起 -->
        <audio controls src="./audio1.mp3"></audio>
        <br>
        <b>audio1</b>
      </td>
      
      <td align="center" width="10%">
        <h1>⬅️</h1> 
      </td>
      
      <td align="center" width="25%">
        <audio controls src="./ref1.wav"></audio>
        <br>
        <code>ref:happy</code>
        <br>
        <code>emo_prompt:natural</code>
      </td>
      
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

    <!-- 第二行: audio2.wav -->
    <tr>
      <td align="center">
        <audio controls src="./audio2.wav"></audio>
        <br>
        <b>audio2<br>(tuning)</b>
      </td>
      
      <td align="center">
        <h1>⬅️</h1>
      </td>
      
      <td align="center">
        <audio controls src="./ref2.wav"></audio>
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
