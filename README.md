# DM-ESPCA

1.filter metadata for each subtype in the cancer dataset. \n
2.based on metadata, use known subtype classification information as prior information, calculate the correlation degree of each gene probe corresponding to each subtype. \n
3.using the quantita-tive value of correlation as a parameter to generate a unique biolog-ical network for each subtype. \n
1.build DM-ESPCA model using a dynamic gene network to select biomarkers for each sub-type.\n

#function

DM_ESPCA = function(X, k=2, overlap.group, k.group=2, we=0.5, t = 0.1, niter=20, err=0.01, Num.init=5, w_l)

#parameter

X: gene expression data, n*p, n is sample and p is gene.\n
k: the amount of PCs and PC loadings.\n
overlap.group: data of gene pathway. \n
k.group: the amount of edges reserved.\n
we:\n
t:\n
niter:\n
err:\n
Num.init:\n
w_l: t_value data of each subtype.\n

#output

return (list(U, D, V))

#example

There is a gastric cancer data set as an example in the 'data' folder, which can be used directly after decompression.\n
And the result of the example is saved in the 'result' folder.
