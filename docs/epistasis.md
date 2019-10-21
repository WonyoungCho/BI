# Linkage analysis
- Parametric linkage
> - 일반적으로 질병에 대한 유전 모형 값을 알고 있을 때 분석하는 방법이며, 분석력(power)이 크고 주로 단이 유전자 질병의 원인 유전자 발굴에 사용.
> - LOD score >= 3.0
- Non-parametric linkage
> - 복합적 질병의 원인 유전자 발굴에 많이 사용. 
> - p-value < 0.00002

# Single variant test
## Hardy-Weinberg eq test
Some variant are in disequilibrium.

- Heterozygote excess : 생존에 이로울 경우 발생할 수 있지만 정상적인 시료에는 두 대립 유전자형의 분리가 제대로 이루어지지 않은 genotyping error.
- homozygote excess : 이질적인 집단의 시료가 사용되었거나 특정 homozygote 가 치사(null allele)를 유발하여 실제 집단에서는 그 유전형이 존재하지 않는 경우가 있으나 정상적인 집단의 시료가 사용되었다면 두 대립 유전자형 중에서 특정 유전자형의 genotyping error (allele dropout).

# Multiple comparison test
## Bonferroni correction
- 개별적인 SNP가 모두 독립적으로 관여하는 경우에는 N으로 눌 수 있지만 많은 SNP는 LD block 내에 서로 연관되어 있기 때문에 N으로 나누면 너무 엄격하게 적용됨.

## FDR (false discovery rate)
- FDR = false positive / total positive
- p-value가 높은 것부터 정렬하고, p-value가 낮아질 수록 엄격한 alpha값을 적용함.


## T-test
- n < 30
- Used to compare two means or proportions
- Unknown standard deviation

## Wilcoxon Signed-Rank test
- n < 30
- Unknown distribution
- Unable to adjust to normal distribution
- Use median

## Z-test
- n >= 30
- Normal distribution
- Known standard deviation

## Permutation test


## Bootstrap


# Linkage Disequilibrium
- Non-random association of allele at different loci in a given population.
- R2 is nothing but Pearson's correlation coefficient. That is, the covariance of two variables by product of their standard deviations. ([Pearson correlation coefficient](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient#For_a_population))
