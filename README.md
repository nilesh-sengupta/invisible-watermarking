# invisible-watermarking
An implementation of two invisible watermarking schemes using python.

To run the codes please run 'git clone https://github.com/nilesh-sengupta/invisible-watermarking.git' with the latest version of git pre-installed.

cd invisible-watermarking

To open jupyter notebook run 'jupyter notebook' in the terminal

Navigate to 'das et al' and open das.ipynb to run the scheme from das et al(2017)
To simulate the results for table 2 and 3 use das_scaled_table2.ipynb and das_scaled_table3.ipynb
To calculate PSNR use the Watermarked.png (as w), hostY.png (as H) and Watermarked_modified.png(as a) in ./tests/psnr.ipynb
To find the percentage of key that can be extracted for a specific watermark for das et al(2017), use key_identification.ipynb in ./das et al

To open jupyter notebook run 'jupyter notebook' in the terminal
Navigate to 'lin et al' and open lin_scaled.ipynb to run the scheme from lin et al(2009)
lin_scaled.ipynb will simulate results for table 1 by altering values of 'm' in the function 'C_star'
To calculate PSNR use the Watermarked.png (as w), hostY.png (as H) and Watermarked_modified.png(as a) in ./tests/psnr.ipynb
NB: The code lin_scaled.ipynb includes the random scaling attack on (0,2) and (2,0)

To compare results using PSNR (Peak Signal to Noise Ratio), use 'psnr.ipynb' from 'tests' after placing the original and compressed images in the folder 'tests'

'images' contains the host images and a few watermarks used during experimentation


