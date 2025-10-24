# PA-1-CS5672

# Q1d Prompt Answer

Positional encoding helps increase the PSNR as the training becomes more accomodated to fine details in training images. The number of frequencies measures how much positional encoding we are applying. When applying positional encoding, the MLP is better able to deal with high frequency features in the image. The image does contain some sharp movements and oscillating aspects which would be better represented when the MLP utilizes positional encodings. The positional encoding will vectorize these high frequency features so the MLP can learn them better. When we add more frequencies, the PSNR gets larger (so better).
