# English-to-French Translation and Image  Denoising
<p>This project demonstrates the implementation of deep learning models for two main tasks:</p>
<li>English-to-French Translation using RNN-based architectures (LSTM, RNN, and GRU)</li>
<li>Document Denoising using an autoencoder to remove noise from text data</li>

# Translation Models
<p>The following models are implemented to perform sequence-to-sequence translation from English to French</p>
<li>LSTM Model: Uses Long Short-Term Memory units to capture long dependencies in text sequences</li>
<li>Vanilla RNN Model: Basic Recurrent Neural Network model with standard RNN units</li>
<li>GRU Model: Uses Gated Recurrent Units to capture dependencies with fewer parameters than LSTM.</li>

# Image Denoising Autoencoder
<p>This autoencoder model is designed to remove noise from images. The architecture consists of</p>
<li>Encoder: Compresses the noisy image into a lower-dimensional latent representation.</li>
<li>Decoder: Reconstructs a cleaner version of the image from the encoded representation</li>
