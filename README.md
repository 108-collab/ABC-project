# ABC-project

1.Output the longest gene file: <chr> <start> <end> <gene name> <strand>
(the exons must be group by gene)

2.Output the promoter (+- 1kb) coordinate file: <chr> <start promoter> <end promoter> <gene name> <strand>

3.Output the enhancer coordinate file (H3K27ac: mm9, not intersect with promoter):  <chr> <enhancer start> <enhancer end coordinate>
(find Overlaps / countOverlaps)

4.Output the enhancer coordinates + nearest gene : <chr> <enhancer start> <enhancer end coordinate> <gene_name> <distance>
(distanceToNearest)

5.Output the enhancer coordinates + nearest gene (>20kb away): <chr> <enhancer start> <enhancer end coordinate> <gene_name> <distance>

6.Output the enhancer coordinates + nearest gene (within same TAD): <chr> <enhancer start> <enhancer end coordinate> <gene_name> <distance>
(findOverlaps)
