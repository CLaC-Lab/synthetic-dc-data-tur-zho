# synthetic-dc-data-tur-zho
Synthetic discourse connective datasets in Turkish and Chinese. 

Was initially created in the context of [DISRPT 2021](https://sites.google.com/georgetown.edu/disrpt2021/home)

Contains annotated discourse connective text.

The start of a connective is marked by `Seg=B-Conn` any word that is still part of the connective is marked by `Seg=I-Conn`

## Turkish 
### setimes_agreement_crf_tur
- Based off of a English-Turkish parallel corpus [SETimes](http://nlp.ffzg.hr/resources/corpora/setimes/)
- Created using annotation agreement between an English model trained on the PDTB and a Turkish model trained on TDB

### setimes_projection_crf_tur
- Based off of a English-Turkish parallel corpus [SETimes](http://nlp.ffzg.hr/resources/corpora/setimes/)
- Created using annotation projection from an English model trained on the PDTB to the SETime parallel corpus

## Chinese
### TsinghuaAlignmentEvalSet_agreement_crf_zho
- Based off of a English-Chinese word aligned parallel [corpus](https://nlp.csai.tsinghua.edu.cn/~ly/systems/TsinghuaAligner/TsinghuaAligner.html)
- Created using annotation agreement between an English model trained on the PDTB and a Chinese model trained on CDTB
### TsinghuaAlignmentEvalSet_projection_crf_zho
- Based off of a English-Chinese word aligned parallel [corpus](https://nlp.csai.tsinghua.edu.cn/~ly/systems/TsinghuaAligner/TsinghuaAligner.html)
- Created using annotation projection from an English model trained on the PDTB to the Tsinghua Alignment Eval Set parallel corpus

