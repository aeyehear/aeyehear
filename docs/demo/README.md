# AEyeHear vs MIT-VM-RS Baseline Audio Recoveries

Both methods receive the same fixed 55-4000 Hz analysis filter to ensure equivalent bandwidth comparison. The 4000 Hz upper bound reflects the attenuation limit imposed by exposure. No signal-adaptive speech enhancement or post-processing is applied.

### Quantitative Performance

<table>
  <thead>
    <tr>
      <th rowspan="2">Surface</th>
      <th rowspan="2">Method</th>
      <th colspan="2">Mary (Music)</th>
      <th colspan="3">TIMIT (Speech)</th>
    </tr>
    <tr>
      <th>SI-SDR</th>
      <th>Log-spec</th>
      <th>SI-SDR</th>
      <th>STOI</th>
      <th>PESQ-WB</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">Checkerboard</td>
      <td>MIT-VM-RS</td>
      <td>-10.28</td>
      <td>0.74</td>
      <td>-21.78</td>
      <td>0.40</td>
      <td>1.04</td>
    </tr>
    <tr>
      <td><strong>AEyeHear</strong></td>
      <td><strong>-9.21</strong></td>
      <td><strong>0.85</strong></td>
      <td><strong>-15.78</strong></td>
      <td><strong>0.46</strong></td>
      <td><strong>1.04</strong></td>
    </tr>
    <tr>
      <td rowspan="2">Glossy Chip</td>
      <td>MIT-VM-RS</td>
      <td>-17.14</td>
      <td>0.51</td>
      <td>-26.10</td>
      <td>0.33</td>
      <td>1.03</td>
    </tr>
    <tr>
      <td><strong>AEyeHear</strong></td>
      <td><strong>-10.50</strong></td>
      <td><strong>0.77</strong></td>
      <td><strong>-20.04</strong></td>
      <td><strong>0.33</strong></td>
      <td><strong>1.11</strong></td>
    </tr>
  </tbody>
</table>

---

### Clip 1: Mary Had a Little Lamb - Checkerboard
<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/mary/frame.png" width="250" alt="DSLR Frame - Checkerboard Mary">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/mary/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/mary/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/mary/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/mary/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/mary/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/mary/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 2: TIMIT Male (MCCS0) SA1 - Checkerboard
**Transcript:** "She had your dark suit and greasy wash water all year."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa1/frame.png" width="250" alt="DSLR Frame - Checkerboard Male SA1">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa1/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa1/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa1/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa1/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa1/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa1/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 3: TIMIT Male (MCCS0) SA2 - Checkerboard
**Transcript:** "Don't ask me to carry an oily rag like that."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa2/frame.png" width="250" alt="DSLR Frame - Checkerboard Male SA2">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa2/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa2/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa2/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa2/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa2/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/male_sa2/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 4: TIMIT Female (FADG0) SA1 - Checkerboard
**Transcript:** "She had your dark suit and greasy wash water all year."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa1/frame.png" width="250" alt="DSLR Frame - Checkerboard Female SA1">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa1/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa1/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa1/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa1/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa1/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa1/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 5: TIMIT Female (FADG0) SA2 - Checkerboard
**Transcript:** "Don't ask me to carry an oily rag like that."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa2/frame.png" width="250" alt="DSLR Frame - Checkerboard Female SA2">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa2/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa2/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa2/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa2/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa2/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/checkerboard/female_sa2/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 6: Mary Had a Little Lamb - Glossy Chip
<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/mary/frame.png" width="250" alt="DSLR Frame - Chip Mary">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/mary/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/mary/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/mary/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/mary/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/mary/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/mary/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 7: TIMIT Male (MCCS0) SA1 - Glossy Chip
**Transcript:** "She had your dark suit and greasy wash water all year."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa1/frame.png" width="250" alt="DSLR Frame - Chip Male SA1">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa1/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa1/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa1/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa1/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa1/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa1/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 8: TIMIT Male (MCCS0) SA2 - Glossy Chip
**Transcript:** "Don't ask me to carry an oily rag like that."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa2/frame.png" width="250" alt="DSLR Frame - Chip Male SA2">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa2/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa2/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa2/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa2/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa2/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/male_sa2/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 9: TIMIT Female (FADG0) SA1 - Glossy Chip
**Transcript:** "She had your dark suit and greasy wash water all year."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa1/frame.png" width="250" alt="DSLR Frame - Chip Female SA1">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa1/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa1/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa1/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa1/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa1/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa1/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

---

### Clip 10: TIMIT Female (FADG0) SA2 - Glossy Chip
**Transcript:** "Don't ask me to carry an oily rag like that."

<img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa2/frame.png" width="250" alt="DSLR Frame - Chip Female SA2">

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Recovered Audio</th>
      <th>Spectrogram</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Ground Truth</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa2/gt_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa2/gt_spec.png" width="300" alt="Ground-truth spectrogram"></td>
    </tr>
    <tr>
      <td><strong>MIT-VM-RS (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa2/mit_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa2/mit_raw_spec.png" width="300" alt="MIT-VM-RS spectrogram"></td>
    </tr>
    <tr>
      <td><strong>AEyeHear (Filtered)</strong></td>
      <td><a href="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa2/aeye_raw_audio.wav">Download WAV</a></td>
      <td><img src="https://raw.githubusercontent.com/aeyehear/aeyehear/main/demo/chip/female_sa2/aeye_raw_spec.png" width="300" alt="AEyeHear spectrogram"></td>
    </tr>
  </tbody>
</table>

