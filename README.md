# MANE4962-Project
Using VAE to synthsize piano.
Download data from https://magenta.tensorflow.org/datasets/nsynth - using the .wav and json format
Preprocess data using the Preprocess_and_save_npy file
Train VAE using the .npy files of spectrograms in the Training_and_visualize file
Use the trained VAE to explore latent space with the Explore_latent_space_sound_generation file
Uses Griffon Lim algorithm for phase recombination for sound generation also in the Training_and_visualize file

Code snipets taken from https://github.com/musikalkemist/generating-sound-with-neural-networks
Code snipets taken from https://keras.io/examples/generative/vae/
