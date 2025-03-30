# KAF_icml466_SupplementaryMaterials

## Figure 1: KAF overall framework description
<div style="text-align: center;">
  <img src="52f6809f27580c5ea8f3fd07300cd9e.png" alt="Updated Figure 2">
</div>

## Figure 2: Compare two models : KAF/MLP  (Updated Figure 1)
<div style="text-align: center;">
  <img src="d606489092e79771354d571860fd459.png" alt="Updated picture of the knowledge graph">
</div>

## Table 1: Comparison of Experiment 4.2 after regularization is turned on

<div style="display: flex; justify-content: center;">
  <table>
    <thead>
      <tr>
        <th>MODEL</th>
        <th>DATASETS</th>
        <th>FEATURE MIXER</th>
        <th>#PARAM.</th>
        <th>FLOPS</th>
        <th>TOP-1 (ORIGINAL)</th>
        <th>TOP-1 (W/ REG.)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ResNet/18</td>
        <td>CIFAR-10</td>
        <td>MLP</td>
        <td>11.1M</td>
        <td>0.56G</td>
        <td>91.19</td>
        <td>91.32</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td><b>12.0M<b></td>
        <td><b>0.63G<b></td>
        <td><b>91.72<b></td>
        <td><b>91.88<b></td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>11.3M</td>
        <td>0.56G</td>
        <td>90.98</td>
        <td>91.15</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>8M</td>
        <td>0.42G</td>
        <td>90.69</td>
        <td>90.82</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>KAN</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <td>MLP_Mixer/S</td>
        <td>ImageNet1k</td>
        <td>MLP</td>
        <td>18.2M</td>
        <td>3.8G</td>
        <td>63.5</td>
        <td>63.7</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td><b>18.8M<b></td>
        <td><b>4.2G<b></td>
        <td><b>64.7<b></td>
        <td><b>65.0<b></td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>18.8M</td>
        <td>4.0G</td>
        <td>62.9</td>
        <td>63.2</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>15.7M</td>
        <td>3.2G</td>
        <td>58.2</td>
        <td>58.6</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>KAN</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <td>ViT-T/16</td>
        <td>ImageNet1K</td>
        <td>MLP</td>
        <td>5.7M</td>
        <td>1.08G</td>
        <td>72.3</td>
        <td>72.5</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td><b>5.9M<b></td>
        <td><b>1.12G<b></td>
        <td><b>73.2<b></td>
        <td><b>73.5<b></td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>5.7M</td>
        <td>1.13G</td>
        <td>74.6</td>
        <td>74.8</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>4.2M</td>
        <td>0.96G</td>
        <td>65.7</td>
        <td>66.0</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>KAN</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <td>MLP_KAN (Deit)</td>
        <td>Cifar100</td>
        <td>MLP</td>
        <td>1.3M</td>
        <td>0.12G</td>
        <td>49.0</td>
        <td>49.3</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td><b>1.4M<b></td>
        <td><b>0.15G<b></td>
        <td><b>53.8<b></td>
        <td><b>54.2<b></td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>KAN</td>
        <td>1.9M</td>
        <td>0.19G</td>
        <td>51.2</td>
        <td>51.6</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>1.4M</td>
        <td>0.14G</td>
        <td>54.3</td>
        <td>54.6</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>1M</td>
        <td>0.1G</td>
        <td>46.7</td>
        <td>47.1</td>
      </tr>
    </tbody>
  </table>
</div>

## Table 2: Experiment 4.1 t-test results of visual dataset

<div style="display: flex; justify-content: center;">
  <table border="1" cellpadding="8" cellspacing="0">
    <thead>
      <tr>
        <th>Dataset</th>
        <th>KAF vs MLP (p-value)</th>
        <th>KAN vs MLP (p-value)</th>
        <th>KAF vs MLP (Significance)</th>
        <th>KAN vs MLP (Significance)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>MNIST</td>
        <td>0.03</td>
        <td>0.08</td>
        <td>Significant</td>
        <td>Not Significant</td>
      </tr>
      <tr>
        <td>EMNIST</td>
        <td>0.02</td>
        <td>0.10</td>
        <td>Significant</td>
        <td>Not Significant</td>
      </tr>
      <tr>
        <td>KMNIST</td>
        <td>0.04</td>
        <td>0.09</td>
        <td>Significant</td>
        <td>Not Significant</td>
      </tr>
      <tr>
        <td>CIFAR-10</td>
        <td>0.01</td>
        <td>0.07</td>
        <td>Significant</td>
        <td>Not Significant</td>
      </tr>
      <tr>
        <td>CIFAR-100</td>
        <td>0.02</td>
        <td>0.12</td>
        <td>Significant</td>
        <td>Not Significant</td>
      </tr>
      <tr>
        <td>SVHN</td>
        <td>0.03</td>
        <td>0.11</td>
        <td>Significant</td>
        <td>Not Significant</td>
      </tr>
      <tr>
        <td>Bean Dataset</td>
        <td>0.02</td>
        <td>0.06</td>
        <td>Significant</td>
        <td>Significant</td>
      </tr>
      <tr>
        <td>AG News</td>
        <td>0.01</td>
        <td>0.05</td>
        <td>Significant</td>
        <td>Significant</td>
      </tr>
    </tbody>
  </table>
</div>

## Table 2: Noise Robustness Experiment Results (Corrected High-Frequency Noise Scenario)

<div style="display: flex; justify-content: center;">
  <table>
    <thead>
      <tr>
        <th>Noise Type</th>
        <th>Noise Level (SNR)</th>
        <th>Architecture</th>
        <th>Model</th>
        <th>Test RMSE (Mean ± STD)</th>
        <th>Training Time (s)</th>
      </tr>
    </thead>
    <tbody>
      <Gaussian Noise 10dB>
      <tr>
        <td rowspan="3">Gaussian Noise</td>
        <td rowspan="3">10dB</td>
        <td>FNO</td>
        <td>MLP</td>
        <td>1.23e-2 ± 8.7e-4</td>
        <td><strong>0.8</strong></td>
      </tr>
      <tr>
        <td></td>
        <td>KAF</td>
        <td>9.8e-3 ± 6.2e-4</td>
        <td>0.9</td>
      </tr>
      <tr>
        <td></td>
        <td>KAN</td>
        <td><strong>7.1e-3 ± 4.5e-4</strong></td>
        <td>1.2</td>
      </tr>
      <Gaussian Noise 20dB>
      <tr>
        <td rowspan="3">Gaussian Noise</td>
        <td rowspan="3">20dB</td>
        <td>PINN</td>
        <td>MLP</td>
        <td>8.4e-3 ± 5.3e-4</td>
        <td><strong>1.1</strong></td>
      </tr>
      <tr>
        <td></td>
        <td>KAF</td>
        <td>6.7e-3 ± 4.1e-4</td>
        <td>1.3</td>
      </tr>
      <tr>
        <td></td>
        <td>KAN</td>
        <td><strong>5.2e-3 ± 3.2e-4</strong></td>
        <td>1.6</td>
      </tr>
      <Impulse Noise>
      <tr>
        <td rowspan="3">Impulse Noise (20% Corruption)</td>
        <td rowspan="3">-</td>
        <td>FNO</td>
        <td>MLP</td>
        <td>1.5e-2 ± 1.1e-3</td>
        <td><strong>0.8</strong></td>
      </tr>
      <tr>
        <td></td>
        <td>KAF</td>
        <td>1.1e-2 ± 8.5e-4</td>
        <td>0.9</td>
      </tr>
      <tr>
        <td></td>
        <td>KAN</td>
        <td><strong>8.9e-3 ± 6.7e-4</strong></td>
        <td>1.2</td>
      </tr> 
      <High-Frequency Noise>
      <tr>
        <td rowspan="3">High-Frequency Noise (Fourier Domain)</td>
        <td rowspan="3">30dB</td>
        <td>PINN</td>
        <td>MLP</td>
        <td>9.7e-3 ± 7.2e-4</td>
        <td><strong>1.1</strong></td>
      </tr>
      <tr>
        <td></td>
        <td>KAF</td>
        <td><strong>5.5e-3 ± 3.8e-4</strong></td>
        <td>1.2</td>
      </tr>
      <tr>
        <td></td>
        <td>KAN</td>
        <td>5.8e-3 ± 4.1e-4</td>
        <td>1.6</td>
      </tr>
    </tbody>
  </table>
</div>
