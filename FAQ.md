## Will We Give You A Virus?

**Disclaimer:** The Information provided in this section is obtained through reverse-engineering and NOT verfied for it's accuracy. Therefore it might be outdated aswell.
<details>
  <summary>Expand</summary>

### Discord Token Syntax

<details>
<table>
  <tr><th></th><th>Example</th></tr>
  <tr><td>User ID Encoded in Base64</td><td>NTzQvPcLBacBmgajXQc7QAaU</td></tr>
  <tr><td>Dot</td><td>.</td></tr>
  <tr><td>Timestamp -epoch(1293840000) converted to base64</td><td>XCgboz</td></tr>
  <tr><td>Dot</td><td>.</td></tr>
  <tr><td>HMAC consiting of 27 chars (uppercase/lowercase letters, numbers, - or _)</td><td>c4t51kFWSEmdmaPnKoyUuu8E78E</td></tr>
</table>
There is this awesome diagram from <a href="https://github.com/hxr404/Discord-Console-hacks/issues/2">#2</a> wich shows the exact token structure:<br><br>
<img src="https://user-images.githubusercontent.com/34555296/120932740-4ca47480-c6f7-11eb-9270-6fb3fbbd856c.png"></img> <br>
</details>
<br>
