# DM-ESPCA

1.filter metadata for each subtype in the cancer dataset. 
2.based on metadata, use known subtype classification information as prior information, calculate the correlation degree of each gene probe corresponding to each subtype. 
3.using the quantita-tive value of correlation as a parameter to generate a unique biolog-ical network for each subtype. 
1.build DM-ESPCA model using a dynamic gene network to select biomarkers for each sub-type.

#function

DM_ESPCA = function(X, k=2, overlap.group, k.group=2, we=0.5, t = 0.1, niter=20, err=0.01, Num.init=5, w_l)

#parameter

X: gene expression data, n*p, n is sample and p is gene.
k: the amount of PCs and PC loadings.
overlap.group: data of gene pathway. 
k.group: the amount of edges reserved。
we:
t:
niter:
err:
Num.init:
w_l: t_value data of each subtype.

#output

return (list(U, D, V))

#example

There is a gastric cancer data set as an example in the 'data' folder, which can be used directly after decompression.
And the result of the example is saved in the 'result' folder.
