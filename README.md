Audio-Anomaly-Detection-by-Variational-Autoencoders

Audio refers to sound within the range of human hearing, or the electronic recording, transmission, and reproduction of sound waves.
It covers everything from spoken voice and music to the physical and digital signals used to capture, process & play back sound.

An audio signal anomaly is an unexpected change or outlier in a sound wave. 
It shows up as a sudden spike, a strange frequency, or broken patterns that do not match normal background noise or standard operation.

Audio anomaly detection is the process of using machine learning or signal processing to spot unusual or unexpected sounds. 
It is widely used for industrial machine health monitoring, identifying equipment failures, or tracking environmental changes by flagging anything that deviates from normal baseline audio patterns

Here, I have done a project on detection of anamolies in raw audio data by variational autoencodders.

The data used for the project is raw generated data. Rather than processing the raw waveform directly, this project represents audio by  Mel spectrograms.
A Mel spectrogram captures how the energy of different frequency components changes over time while using a frequency scale that is more closely related to human auditory perception.
This representation also makes audio compatible with CNN-based architectures, allowing the model to learn local time-frequency patterns.

A Variational Autoencoder is a generative neural network consisting of an encoder and decoder.
Unlike a conventional autoencoder, which maps an input directly to a latent vector, a VAE learns a probability distribution in the latent space.



