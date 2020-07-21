
<div align="center">
	
#  Neural Architecture Search for Deep Image Prior
\
Kary Ho<sup>[1]</sup>, [Andrew Gilbert](https://www.surrey.ac.uk/people/andrew-gilbert)<sup>[1]</sup>, [Hailin Jin](https://research.adobe.com/person/hailin-jin/)<sup>[2]</sup>, [John Collomosse](http://personal.ee.surrey.ac.uk/Personal/J.Collomosse/index.php)<sup>[1,2]</sup> \
<sup>[1]</sup> Centre for Vision Speech and Signal Processing, University of Surrey \
<sup>[2]</sup> Creative Intelligence Lab, Adobe Research \
\
\
 [arXiv:2001.04776](https://arxiv.org/abs/2001.04776)
</div>


<div align="center">
<a href="http://www.youtube.com/watch?feature=player_embedded&v=6JbqKdbHZb8
" target="_blank"><img src="http://img.youtube.com/vi/6JbqKdbHZb8/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="640" height="480" border="10" /></a>
</div>

## Abstract

We present a neural architecture search (NAS) technique to enhance the performance of image de-noising, in-painting, and super-resolution tasks under the recently proposed Deep Image Prior (DIP).  We show that evolutionary search can automatically optimize the encoder-decoder (E-D) structure and meta-parameters of the DIP network, which serves as a content-specific prior to regularize these single image restoration tasks.  Our binary representation encodes the design space for an asymmetric E-D network that typically converges to yield a content-specific DIP within 10-20 generations using a population size of 500. The optimized architectures consistently improve upon the visual quality of classical DIP for a diverse range of photographic and artistic content.

## Paper

[![alt text](https://github.com/wackygerbs/NAS-DIP/blob/master/FrontPage.png)](https://arxiv.org/abs/2001.04776) 
[![alt text](https://github.com/wackygerbs/NAS-DIP/blob/master/PDF_file_icon.png)](https://arxiv.org/abs/2001.04776) 

## Citation
```
				@INPROCEEDINGS{Ho20,
				title = {Neural Architecture Search for Deep Image Prior},
				year={2020},
				booktitle={arXiv preprint arXiv:2001.04776}, 
				author={Ho, K. and Gilbert, A. and Jin, H. and Collomosse, J.} 
				}
```
