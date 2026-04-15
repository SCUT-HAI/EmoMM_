

<h3 style="margin-bottom: 12px;">Experimental Results</h3>

<div style="overflow-x: auto; margin: 16px 0;">
  <table style="
    width: 100%;
    border-collapse: collapse;
    font-family: 'Times New Roman', Times, serif;
    font-size: 15px;
    line-height: 1.4;
    border-top: 2px solid #444;
    border-bottom: 2px solid #444;
  ">
    <thead>
      <tr>
        <th rowspan="2" style="padding: 10px 12px; text-align: left; border-bottom: 1px solid #666;">Model</th>
        <th colspan="3" style="padding: 10px 12px; text-align: center; border-left: 1px solid #999; border-bottom: 1px solid #666;">EmoMM (Overall)</th>
        <th colspan="3" style="padding: 10px 12px; text-align: center; border-left: 1px solid #999; border-bottom: 1px solid #666;">EmoMM-Align</th>
        <th colspan="3" style="padding: 10px 12px; text-align: center; border-left: 1px solid #999; border-bottom: 1px solid #666;">EmoMM-Conflict</th>
        <th colspan="3" style="padding: 10px 12px; text-align: center; border-left: 1px solid #999; border-bottom: 1px solid #666;">EmoMM-Missing</th>
      </tr>
      <tr>
        <th style="padding: 8px 10px; text-align: right; border-left: 1px solid #999; border-bottom: 1px solid #666;">Acc↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">F1↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">MAE↓</th>

        <th style="padding: 8px 10px; text-align: right; border-left: 1px solid #999; border-bottom: 1px solid #666;">Acc↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">F1↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">MAE↓</th>

        <th style="padding: 8px 10px; text-align: right; border-left: 1px solid #999; border-bottom: 1px solid #666;">Acc↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">F1↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">MAE↓</th>

        <th style="padding: 8px 10px; text-align: right; border-left: 1px solid #999; border-bottom: 1px solid #666;">Acc↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">F1↑</th>
        <th style="padding: 8px 10px; text-align: right; border-bottom: 1px solid #666;">MAE↓</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td colspan="13" style="padding: 8px 12px; font-style: italic; background: #f7f7f7; border-top: 1px solid #ccc;">Open-source Baselines</td>
      </tr>
      <tr>
        <td style="padding: 8px 12px; text-align: left;">Video-LLaMA2.1-7B-AV</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">22.46</td><td style="padding: 8px 10px; text-align: right;">21.33</td><td style="padding: 8px 10px; text-align: right;">0.579</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">23.94</td><td style="padding: 8px 10px; text-align: right;">21.12</td><td style="padding: 8px 10px; text-align: right;">0.611</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">25.84</td><td style="padding: 8px 10px; text-align: right;">20.60</td><td style="padding: 8px 10px; text-align: right;">0.527</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">21.55</td><td style="padding: 8px 10px; text-align: right;">21.52</td><td style="padding: 8px 10px; text-align: right;">0.587</td>
      </tr>
      <tr>
        <td style="padding: 8px 12px; text-align: left;">MiniCPM-o 2.6-8B</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">26.09</td><td style="padding: 8px 10px; text-align: right;">15.06</td><td style="padding: 8px 10px; text-align: right;">0.781</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">27.59</td><td style="padding: 8px 10px; text-align: right;">15.61</td><td style="padding: 8px 10px; text-align: right;">0.723</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">26.37</td><td style="padding: 8px 10px; text-align: right;">14.47</td><td style="padding: 8px 10px; text-align: right;">0.751</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">25.86</td><td style="padding: 8px 10px; text-align: right;">15.13</td><td style="padding: 8px 10px; text-align: right;">0.794</td>
      </tr>
      <tr>
        <td style="padding: 8px 12px; text-align: left;">Video-SALMONN2-7B</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">41.47</td><td style="padding: 8px 10px; text-align: right;">38.30</td><td style="padding: 8px 10px; text-align: right;">0.380</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">49.05</td><td style="padding: 8px 10px; text-align: right;">43.94</td><td style="padding: 8px 10px; text-align: right;">0.318</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">41.25</td><td style="padding: 8px 10px; text-align: right;">37.70</td><td style="padding: 8px 10px; text-align: right;">0.367</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">40.65</td><td style="padding: 8px 10px; text-align: right;">37.78</td><td style="padding: 8px 10px; text-align: right;">0.390</td>
      </tr>
      <tr>
        <td style="padding: 8px 12px; text-align: left;">Qwen2.5-Omni-7B</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">44.56</td><td style="padding: 8px 10px; text-align: right;">36.24</td><td style="padding: 8px 10px; text-align: right;">0.384</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">52.14</td><td style="padding: 8px 10px; text-align: right;">44.28</td><td style="padding: 8px 10px; text-align: right;">0.270</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">46.47</td><td style="padding: 8px 10px; text-align: right;">39.76</td><td style="padding: 8px 10px; text-align: right;">0.356</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">43.27</td><td style="padding: 8px 10px; text-align: right;">34.55</td><td style="padding: 8px 10px; text-align: right;">0.403</td>
      </tr>
      <tr>
        <td style="padding: 8px 12px; text-align: left;">VITA-1.5-8B</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">44.50</td><td style="padding: 8px 10px; text-align: right;">43.83</td><td style="padding: 8px 10px; text-align: right;">0.327</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">53.03</td><td style="padding: 8px 10px; text-align: right;">53.47</td><td style="padding: 8px 10px; text-align: right;">0.277</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">47.80</td><td style="padding: 8px 10px; text-align: right;">47.18</td><td style="padding: 8px 10px; text-align: right;">0.319</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">42.80</td><td style="padding: 8px 10px; text-align: right;">41.99</td><td style="padding: 8px 10px; text-align: right;">0.335</td>
      </tr>

      <tr>
        <td colspan="13" style="padding: 8px 12px; font-style: italic; background: #f7f7f7; border-top: 1px solid #ccc;">Closed-source API</td>
      </tr>
      <tr>
        <td style="padding: 8px 12px; text-align: left;">Gemini 3 Pro</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">56.41</td><td style="padding: 8px 10px; text-align: right;">53.58</td><td style="padding: 8px 10px; text-align: right;">0.236</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">59.85</td><td style="padding: 8px 10px; text-align: right;">59.07</td><td style="padding: 8px 10px; text-align: right;">0.191</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">56.23</td><td style="padding: 8px 10px; text-align: right;">51.16</td><td style="padding: 8px 10px; text-align: right;">0.236</td>
        <td style="padding: 8px 10px; text-align: right; border-left: 1px solid #eee;">56.06</td><td style="padding: 8px 10px; text-align: right;">53.47</td><td style="padding: 8px 10px; text-align: right;">0.241</td>
      </tr>
    </tbody>
  </table>
</div>

<p style="margin-top: 8px; font-size: 14px; font-style: italic;">
  Table 1. Main results on EmoMM and its subsets.
</p>
