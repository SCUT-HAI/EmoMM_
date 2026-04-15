<h3>Experimental Results</h3>

<table>
  <thead>
    <tr>
      <th rowspan="2">Model</th>
      <th colspan="3">EmoMM (Overall)</th>
      <th colspan="3">EmoMM-Align</th>
      <th colspan="3">EmoMM-Conflict</th>
      <th colspan="3">EmoMM-Missing</th>
    </tr>
    <tr>
      <th>Acc↑</th>
      <th>F1↑</th>
      <th>MAE↓</th>
      <th>Acc↑</th>
      <th>F1↑</th>
      <th>MAE↓</th>
      <th>Acc↑</th>
      <th>F1↑</th>
      <th>MAE↓</th>
      <th>Acc↑</th>
      <th>F1↑</th>
      <th>MAE↓</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="13"><em>Open-source Baselines</em></td>
    </tr>
    <tr>
      <td>Video-LLaMA2.1-7B-AV</td>
      <td>22.46</td><td>21.33</td><td>0.579</td>
      <td>23.94</td><td>21.12</td><td>0.611</td>
      <td>25.84</td><td>20.60</td><td>0.527</td>
      <td>21.55</td><td>21.52</td><td>0.587</td>
    </tr>
    <tr>
      <td>MiniCPM-o 2.6-8B</td>
      <td>26.09</td><td>15.06</td><td>0.781</td>
      <td>27.59</td><td>15.61</td><td>0.723</td>
      <td>26.37</td><td>14.47</td><td>0.751</td>
      <td>25.86</td><td>15.13</td><td>0.794</td>
    </tr>
    <tr>
      <td>Video-SALMONN2-7B</td>
      <td>41.47</td><td>38.30</td><td>0.380</td>
      <td>49.05</td><td>43.94</td><td>0.318</td>
      <td>41.25</td><td>37.70</td><td>0.367</td>
      <td>40.65</td><td>37.78</td><td>0.390</td>
    </tr>
    <tr>
      <td>Qwen2.5-Omni-7B</td>
      <td>44.56</td><td>36.24</td><td>0.384</td>
      <td>52.14</td><td>44.28</td><td>0.270</td>
      <td>46.47</td><td>39.76</td><td>0.356</td>
      <td>43.27</td><td>34.55</td><td>0.403</td>
    </tr>
    <tr>
      <td>VITA-1.5-8B</td>
      <td>44.50</td><td>43.83</td><td>0.327</td>
      <td>53.03</td><td>53.47</td><td>0.277</td>
      <td>47.80</td><td>47.18</td><td>0.319</td>
      <td>42.80</td><td>41.99</td><td>0.335</td>
    </tr>

    <tr>
      <td colspan="13"><em>Closed-source API</em></td>
    </tr>
    <tr>
      <td>Gemini 3 Pro</td>
      <td>56.41</td><td>53.58</td><td>0.236</td>
      <td>59.85</td><td>59.07</td><td>0.191</td>
      <td>56.23</td><td>51.16</td><td>0.236</td>
      <td>56.06</td><td>53.47</td><td>0.241</td>
    </tr>
  </tbody>
</table>

<p><em>Table 1.</em> Main results on EmoMM and its subsets.</p>
