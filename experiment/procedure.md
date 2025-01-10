<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <title>Signal Processing Interface</title>
</head>
<body>
  <ul class="list-disc pl-6">
    <li>
      <strong>Input Parameters:</strong>
      <ul class="list-disc pl-6">
        <li>
          <strong>Operations:</strong> Select various operations such as addition, subtraction, multiplication, convolution, differentiation, and integration properties using the input field.
        </li>
        <li>
          <strong>Input Signal(s):</strong> Specify and input the frequency values for the signal(s).
        </li>
        <li>
          <strong>Sampling Frequency (Hz):</strong> Enter the sampling frequency in Hertz (Hz) in the provided input field.
        </li>
        <li>
          <strong>SNR (in dB):</strong> Specify the desired Signal-to-Noise Ratio (SNR) in decibels (dB).
        </li>
        <li>
          <strong>AR Model Order(s):</strong> Enter the order(s) of the autoregressive (AR) model to compute the power spectral density (PSD).
        </li>
      </ul>
    </li>
    <li>
      <strong>Generate Input Signal(s):</strong> Click the <em>“Generate Input Signal”</em> button to create the specified input signals.
    </li>
    <li>
      <strong>Generate Combined Signal:</strong> Click the <em>“Generate Combined Signal”</em> button to produce the combined signal, if applicable.
    </li>
    <li>
      <strong>Generate Autoregressive (AR) Filtered Signal:</strong> Click the <em>“Generate AR Filtered”</em> button to display the autoregressive-filtered version of the input signal.
    </li>
    <li>
      <strong>Generate Noisy Signal:</strong> Click the <em>“Generate Noisy Signal”</em> button to add Additive White Gaussian Noise (AWGN) to the input signal and generate the noisy signal.
    </li>
    <li>
      <strong>Display Power Spectral Density (PSD):</strong> Click the <em>“Generate PSD”</em> and <em>“Generate PSD for Noisy Signal”</em> buttons to visualize the PSD of the input signal and the noisy signal, respectively.
    </li>
  </ul>
</body>
</html>
