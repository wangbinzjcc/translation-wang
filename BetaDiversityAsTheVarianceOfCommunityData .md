        Beta diversity as the variance of community data: dissimilarity coefficients and partitioning 
                    β多样性是群落数据变异指标：相异系数及分解
                          Pierre Legendre， Miquel De Cáceres  
                       Centre-ville, Montréal, Québec, Canada H3C 3J7  
                            Solsona, Catalonia, Spain. 
 
Keywords: beta diversity, community ecology, community composition data, dissimilarity coefficients, local contributions to beta diversity, properties of dissimilarity coefficients, species contributions to beta diversity, variance partitioning 
关键词：β多样性，群落生态学，群落结构数据，相异系数，对β多样性的本地贡献，相似系数的性质，β多样性的物种贡献，变异分解

Abstract  摘要
   Beta diversity can be measured in different ways. Among these, the total variance of a community data matrix Y can be used as an estimate of beta diversity. We show how the total variance of Y can be calculated either directly or through a dissimilarity matrix. This measure can be generalized to any community dissimilarity index. We address the question of which index to use by coding 17 indices using 14 properties that are necessary for beta assessment, comparability among data sets, sampling issues, and ordination. Our comparison analysis classified the coefficients under study into five types, four of which are appropriate for beta diversity assessment. The total variance of Y links beta diversity with the analysis of community data by commonly used methods like ordination and ANOVA. Total beta can be partitioned in different ways: one can compute the contributions of individual species and sites to beta; local contributions to beta diversity (LCBD) are comparative indicators of the degree of ecological uniqueness of the sites under study. Moreover, total beta can be split into within( and among）group components by MANOVA, into orthogonal axes by ordination, into spatial scales by eigenfunction analysis, or among explanatory data sets by variation partitioning.  
  β多样性可以使用不同的方法测量。在这些方法中群落数据矩阵Y的总方差可以作为一种β多样性的测量方法。我们显示了怎样使用Y的总方差来直接或者通过相异矩阵来计算。这些方法可以产生任何群落相异指数。我们提出问题，具有14个属性的17个指数中哪些适合β评估，并用于数据集，取样问题，以及排序等之间的比较。我们通过对比分析把所研究的这些系数分成了5类，它们之中的4类用于β多样性测度是合适的。群落数据中与β多样性相关的Y的总方差经常使用像排序和方差分析这样的方法。总β可以被分解成不同的部分：可以计算一个物种或样方对beta的贡献；β多样性的本地贡献（ＬＣＢＤ）可以作为研究样方生态独特程度的指数。此外，总方差可以通过多变量方差分析将组内或组间成分分解成，排序的正交轴，特征分析的空间尺度，或者方差分解的解释数据集。

INTRODUCTION 介绍

  A most interesting property of species diversity is its organization through space. This phenomenon, now well known to community ecologists, was first discussed by Whittaker in two seminal papers (1960, 1972) where he described the alpha, beta and gamma diversity levels of natural communities. Alpha is local diversity, beta is spatial differentiation, and gamma is regional diversity. The interest of community ecologists for beta diversity stems from the fact that spatial variation in species composition allows them to test hypotheses about the processes that generate and maintain biodiversity in ecosystems. Sampling through space, time, or along gradients representing processes of interest is a way of carrying out mensurative experiments (Hurlbert 1984) involving natural. 
   物种多样性最有趣的性质就是它们在空间上的组织。群落生态学家都知道，这个现象在Whittaker的两篇影响深远的文章中(1960,1972)被第一次讨论，在这里他描述了自然群落中α、β、γ水平的多样性。α是指本地的多样性，β是指空间变异，γ区域多样性。群落生态学家对β多样性的兴趣起源于物种结构的空间变异让他们能测试生态系统中产生和维持生物多样性过程的理论。通过空间、时间、不同纬度之间的取样而表现出有趣的过程，是一种开展自然测量实验(Hurlbert，1984)的方法。

  Beta diversity is conceptually the variation in species composition among sites within a geographic area of interest (Whittaker 1960). Vellend (2001) and Anderson et al. (2011) pointed out that studies of beta diversity might focus on two aspects of community structure, distinguishing two types of beta diversity. The first is turnover, or the directional change in community composition from one sampling unit to another along a predefined spatial, temporal, or environmental gradient. The second is a non-directional approach to the study of community variation through space; it does not refer to any explicit gradient but simply focuses on the variation in community composition among the ampling units. Both approaches are legitimate. 
  β多样性被认为是有趣的地理范围内不同样方之间物种结构的变异（whittaker 1960）。vellend（2001）和anderson等（2011）指出β多样性的研究可能集中在群落结构两个方面，将β多样性可分成两类。第一类叫做流动，即测量沿一个预定的空间、时间或者环境梯度从一个到另一个取样单位群落结构的直接变化。另一类是一种非定向的去研究空间上的群落变异；它不涉及明确的梯度，只是单纯的集中在取样单元内群落结构的变异。这两种方法都是合理的。

   Regardless of whether beta diversity is defined as directional or non-directional, one can be interested in summarizing it by a single number. A lot of interest has been centred on the choice of the best index to produce that number. In the directional approach, the slope of the similarity decay in species composition with geographical distance can be used as a measure of beta. In his 1960 paper, Whittaker suggested to compute a non-directional beta for index for species richness as β = γ/α where γ is the number of species in the region and α is the mean number of species at the study sites within the region. Since then, several other indices have been suggested to estimate a value corresponding to beta in the turnover and non-directional frameworks; see Vellend (2001) and Koleff et al. (2003) for reviews. Currently, the most popular indices belong to two families that can be labelled the additive (Hα+Hβ=Hγ) and multiplicative (Hα×Hβ=Hγ) approaches (Jost 2007, Chao et al. 2012). A detailed discussion of these two families is found in a Forum section published by Ecology (2010:1962-1992).  
   无论β多样性被定义为定向或者非定向，都可以有兴趣的用一个单独的数字来总结它。更多人的兴趣是集中在选择最好的指数来产生这些数字。在定向方法中，一定地理距离内的物种结构相似度衰减率可作为一种β的测量方法。在1960年的文章中，whittaker建议计算非定向β作为物种丰富度的指标，即β=γ/α，这里γ是区域物种的数量，α是区域内研究样地的物种平均值。从此以后，一些其他指标被建议用来估计一个定向和非定向框架内的β相关的值；见vellend（2001）和koleff等（2003）的点评。最近，最流行的指数被认为是两个家族，加法（Hα+ Hβ=Hγ）和乘法（Hα×Hβ=Hγ）（Jost2007，chao等2012）。这两个家族详细的讨论被发表在Ecology专题部分（2010：1962-1992）

  In his introduction to the Forum, Ellison (2010) noted that in the additive and multiplicative approaches, beta is a derived quantity that is numerically related to alpha and gamma. He concluded that it would be most useful (he wrote: “a real breakthrough”) to have a method to estimate beta diversity without calling upon alpha and gamma (computational independence, which does not imply statistical independence). Such an approach exists: the total variance in the community data table Y is a single-number estimate of beta diversity (Pelissier et al. 2003, Legendre et al. 2005, Anderson et al. 2006). It is computed without reference to the values of alpha and gamma and its statistical dependence on gamma can be removed (Kraft et al. 2011, De Cáceres et al. 2012). Most importantly, it allows ecologists to partition the spatial variation in several ways to answer precise ecological questions and test hypotheses about the origin and maintenance of beta diversity in ecosystems. 
  在专题介绍中，ellison（2010）记录了加法和乘法途径，β是一种与α和γ数量相关的衍生量。他总结说最有用的（他写道：“真正的突破”）是有一种方法不需要借助α和γ来计算β多样性（计算上的独立，并不意味着统计上的独立）。这个方法是：群落数据表Y的总方差作为一个β多样性的测量值（pelissier等2003，legendre等2005，anderson等2006）。它的计算可以不涉及到α和γ值，并且可以去除γ依赖性（kraft等2011，de caceres等2012）。更重要的是，它可以让生态学家将空间变异分解成不同的部分来回答精确的生态学问题并测试生态系统中一些β多样性来源及维持机理。

 
  This paper focuses on exploring the advantages of estimating beta diversity as the total variation of the community data Y (BDTotal). (1) In a first section, we will show that BD Total can be obtained in two equivalent ways, i.e. by computing the sum of squares of the species occurrence or abundance data or via a dissimilarity matrix. The second method is appealing because it derives the beta estimate using a dissimilarity function designed for the analysis of community data. (2) There are, however, many different dissimilarity coefficients, and users are faced with the problem of choosing from among them. A detailed analysis of dissimilarity coefficients will be undertaken in the following sections. (3) We will then present an example to illustrate the calculation of beta as the total variance in Y and the contributions of individual species and sampling units. (4) We will show that the proposals of Whittaker (1972) and Ricotta & Marignani (2007) are special cases of BDTotal computed from a dissimilarity matrix, and that the beta diversity statistic of Anderson et al. (2006) is closely related to BDTotal. (5) Finally, we will show that the total variance of Y links beta diversity assessment with the description (through ordination) and hypothesis testing (through regression and canonical analysis) phases of community ecology, as well as other variance partitioning methods.  
   这篇文章主要是探究使用群落数据Y总方差（总β）作为β多样性测量的有利方面。（1）在第一部分，我们显示了总BD可以存在两种相同的方式，如，通过使用物种出现或多度数据以及相异矩阵来计算平方和。而后一种方法是很吸引人的是因为它使用了群落数据分析中设计好的相异函数里评估β多样性。（2）然而，有很多不同的相异系数，使用者将要面临选择它们的困难。相异系数的具体分析将在接下来的章节进行讨论。（3）我们将举一个例子，通过Y总变异计算β以及计算个体物种与随机样方的贡献率。（4）我们将展示Whittaker (1972)和Ricotta & Marignani (2007)对使用相异矩阵计算BDtotal的特例，以及anderson等和BDtotal相关β多样性统计。（5）最后，我们将通过群落生态学的描述（借助排序）和理论测试阶段（借助回归和CA分析）以及其它方差分解方法，来展示与β多样性相关的Y的总方差。

BETA DIVERSITY AS THE TOTAL VARIANCE OF THE SPECIES DATA  
用物种数据的总变异作为β多样性
Equivalent ways of computing Var(Y).This section demonstrates that there are two equivalent ways of computing the total variance of community composition data Y. The first one is straight forward, it is simply the variance of Y. The second one is based upon the dissimilarity measures developed by ecologists during more than a century of field surveys. It also shows that the total variance can be divided into the contributions of individual species and individual sampling sites. Readers can follow the explanation on the diagram in Fig. 1.    Let Y = [yij] be a data table containing the presence-absence or the abundance values of p species (column vectors y1, y2, … yp of Y) observed in n sampling units (row vectors x1, x2, … xn of Y). We will use indices i and h for sampling units, index j for species, and yij for individual values in Y. The total variance of Y, noted Var(Y), can be computed as follows: 
  和计算Y的方差的方式相同。这一节来示范计算群落结构数据Y总变异的两种等价的方式。第一种是直接向前计算，简单的Y的方差。第二种是基于一个多世纪以来生态学家们在野外调查中开发的相异性测量。它也显示总方差能被分成物种个体以及随机样方的贡献率。读者可以参考图表1中的公式描述。让Y=[yij]作为一个数据集，包括了在第n个取样方内（横排为Y的x1,x2,...xn等），第p个物种（纵列为Y的y1,y2,...yp）的多度值或出现-不出现数据。我们使用i和h作为随机样方，j作为物种指标，yij作为Y中的个体值。Y的总变异，即为Var（Y），可以使用下列公式计算：

  1. Sums of squares. — The usual way to obtain Var(Y) consists in computing a matrix of squared deviations from the column means. Let S be a n × p rectangular matrix where each element sij contains the square of the difference between the yij value and the mean value of the corresponding jth species: 
sij=(yij−mean(yj))^2 ;  (1) sij is zero if all sites have the same abundance for species j. If we sum all values of S, we obtain the total sum of squares of the species composition data: 
        SSTotal=(∑i=1:n)(∑j=1:p)sij  .     (2) 
  1.方差和。-- 通常的方法是通过计算纵列的离差平方矩阵来得到Var（Y）。让S成为一个n×p的矩阵，这里的每个Sij包括了yij值与物种j相关平均值之间的离差平方。sij=（yij-mean（yj）)^2; (1)如果物种j在所有的样方内具有同样的多度，那么sij等于0 。如果统计所有S的数值之和，我们能得到物种结构数据的总方差和：
        SSTotal=(∑i=1:n)(∑j=1:p)sij  .     (2) 

This quantity forms the basis of BDTotal, which is the index of beta diversity whose properties are developed in this section: 
        BDTotal=Var(Y) = SSTotal/(n−1) .   (3) 
这个量形成的基础是BDtotal，这就是本节发展的计算β多样性的指数：BDTotal=Var(Y) = SSTotal/(n−1) .   (3) 

Equation 3 converts the sum of squares into the usual unbiased estimator of the variance, whose values can be compared between data matrices having different numbers of sampling units. SSTotal and Var(Y) = BDTotal were both proposed by Legendre et al. (2005) as measures of beta diversity. The two indices are equally useful to compare repeated surveys of a region involving the same sites, or for simulation studies, although there is a clear advantage in using Var(Y) for comparisons among regions.  
  公式3是把平方和转化为方差的无偏估计，其值可以比较不同数量取样单元之间的数据矩阵。SStotal和Var(Y)=BDtotal被Legendre等（2005）推荐作为一种β多样性的测度。两种指数都可以比较在相同样方区域内重复调查或做仿真研究的数据，不过使用var(Y)来做不同区域内的比较是有明显好处的。

  An advantage of conceiving beta as the total variation in Y is that SSTotal allows the assessment of the contributions of individual species or individual sampling units to the overall beta diversity.That is, one can compute the sum of squares corresponding to the jth species,which is the contribution of species j to the overall beta diversity.          SSj=∑(i=1:n)sij              (4a) 
The relative contribution of species j to beta, which we can call Species Contribution to Beta diversity (SCBD), is thus:               SCBDj=SSj/SSTotal             (4b) 
  将Y的总方差作为理想β的一个好处是SStotal可以测定单个物种或者单个样方对整个β多样性的贡献率。即，可以计算物种j相关的方差之和，这就是物种j对整个β多样性的贡献率。
                  SSj=∑(i=1:n)sij              (4a) 
而一个物种对于β多样性的相对贡献率，我们可以称之为β多样性的物种贡献（Species Contribution to Beta diversity ，SCBD)，如：
                 SCBDj=SSj/SSTotal              (4b) 
         
In an analogous way, one can compute the sum of squares corresponding to the ith sampling unit,    
SSi= ∑(j=1:p)sij  .  (5a)  
Because the sij values are squared deviations from the species means, SSi is the squared distance of sampling unit i to the centroid of the distribution of sites in species space. The SSi values thus represent a genuine partitioning of beta diversity among the sites. SSi also measures the leverage of site i in a PCA ordination. The relative contribution of sampling unit i to beta diversity, which we can call Local Contribution to Beta diversity (LCBDi), is thus:      LCBDi=SSi/SSTotal .  (5b) 
    一个相似的方法我们可以计算第i个取样方相关的平方和，SSi= ∑(j=1:p)sij (5a)  
因为sij值是物种平均值的离差平方和，SSi是物种空间中样方分布中心到取样单元i之间的距离的平方。SSi值因此代表了不同样地之间真正的β多样性分解。SSi也测量了PCA排序中样方i的作用。取样单元i对β多样性的相对贡献，我们可以称为β多样性的地方贡献率（LCBDi），如：LCBDi=SSi/SStotal 

LCBD values can be mapped, as in the ecological illustration below. They represent the degree of uniqueness of the sampling units in terms of community composition. Mapping the centred values using different symbols would highlight the sites with LCBD values higher and lower than the mean. 
  Hence, the two decompositions of SSTotal are:      
  SSTotal=∑(j=1:p)SSj   and  SSTotal=∑(i=1:n)SSi .  (6a,b) 
    LCBD值可以被绘图，作为一个生态学插图。它们表示群落结构中随机取样单元的独特性度量。使用不同的符号来绘制中心值将会增亮哪些LCBD值明显高于或者低于平均值的样方。因此，SStotal有两种形式：
  SSTotal=∑(j=1:p)SSj   和  SSTotal=∑(i=1:n)SSi .   (6a,b) 

  2. Dissimilarity. — There is an alternative path starting from Y and leading to SS Total(Fig. 1). That is, SSTotal can also be obtained from an n × n symmetric dissimilarity matrix D = [Dhi] containing Euclidean distances among points, computed using the classical Euclidean distance formula: 
        Dhi= D(xh,xi)= [∑(j=1:p)(yhj−yij)^2]^0.5   (7) 
  2.相异性。 - 一个可选择的途径是从Y导出SStotal（图1）。即，SStotal能从n×n个对称的相异矩阵D=[Dhi]中获得。包括了通过经典的欧几里德距离公式来计算点与点之间的欧几里德距离。
        Dhi= D(xh,xi)= [∑(j=1:p)(yhj−yij)^2]^0.5   (7) 

The following equivalence is described in Legendre et al. (2005) and in Legendre & Legendre 
(2012, Chapter 8):   SSTotal = 1/n×(∑h=1:n−1)(∑i=h+1:n)Dhi^2   (8) 
   在Legendre等（2005）以及Legendre和Legendre（2012，第8章）介绍过下列公式：
                     SSTotal = 1/n×(∑h=1:n−1)(∑i=h+1:n)Dhi^2   (8)

That is, one can obtain SSTotal by summing the squared distances in the upper or lower half of matrix D and dividing by the number of objects n (not by the number of distances). This equality (eq. 8) is demonstrated in Appendix 1 of Legendre & Fortin (2010). This statistic will be generalized below to other dissimilarity indices, which may or may not have the Euclidean property (P13 below). Working with matrix D instead of the matrix of squared centred values S entails the drawback of loosing track of the species. Because D is computed among eview sampling units over all species, the contributions of individual species cannot be recovered from D.  
   即，可以计算矩阵D上半部分或者下半部分的距离的平方和来获得SStotal，并把它分成n份（并不是距离的数量）。这个公式（式8）在Legendre和Fortin（2010）的附录1中被证明了。这个统计的广泛性将低于其它包括或者不包括欧几里德过程（p13下面）的相异指数。使用矩阵D代替中心平方值矩阵S会带来丢失物种特点的缺陷。因为D计算的是在观测样方之间所有物种，而物种个体的贡献率则不能从D中得到。
 
  It is still possible, however, to calculate the contribution of individual sampling units from D. Indeed, the algebra of principal coordinate analysis (PCoA, Gower 1966) offers a way of computing the sum of squares SSi, corresponding to each sampling unit i, directly from D. In PCoA, prior to eigen-decomposition, the distance matrix is transformed into matrix A = [ahi] = −0.5Dhi^2, then centred using the equation 
          △1=(I-ll'/n)A(I-ll'/n)   (9) 
   然而，仍然有可能计算D中随机样方个体的贡献率。事实上主坐标分析（PCoA,Gower 1966）提供了一个计算SSi平方和的方法，直接从D中对应每一个取样单位i。在PCoA中，前面的特征值分解，距离矩阵被转化成矩阵A=[ahi]=-0.5Dhi^2,然后使用公式中心化。
          △1=(I-ll'/n)A(I-ll'/n)   (9)

where I is an identity matrix of size n, 1 is a vector of ones (length n) and 1' is its transpose 
(Legendre & Legendre 2012, eqs 9.40 and 9.42). The diagonal elements of matrix △1 are the 
SSi values, or the squared distances of the points to the multivariate centroid of Y, and also to 
the centroid of the principal coordinate space: 
          [SSi]=diag(△1)             (10a) 
The vector of local contributions of the sites to beta diversity (LCBD) is computed as follows: 
          [LCBDi]=diag(△1)/SSTotal   (10b) 
   这里的I是一个大小为n单位矩阵，l是一个长度为n的向量，而l’是它的变换形式（Legendre & Legendre 2012, eqs 9.40 and 9.42）。SSi值是矩阵△1对角元素，或者是到Y的多元中心的点的距离平方，并且也是主坐标空间的中心：
          [SSi]=diag(△1)             (10a)
β多样性的样地贡献率（LCBD）的向量可以使用下列公式计算：
          [LCBDi]=diag(△1)/SSTotal   (10b)

To summarize: 总结：
• One can compute the total sum of squares in the community data Y, SSTotal, from either the community composition matrix Y (eq. 2) or from a Euclidean distance matrix D among sites (eq. 8). The two modes of calculation produce the same statistic, SSTotal, and from it one can compute the total variance, BDTotal=Var(Y) (eq. 3).  
• 可以通过群落数据结构矩阵Y（公式2）或者样地之间的欧几里德距离矩阵D（公式8）来计算群落数据Y的方差总和SStotal。有两种计算方法可以产生相同的统计量，SStotal，通过它可以计算总方差，BDtotal=Var（y）（公式3）。

• The contribution of the ith sampling unit to overall beta diversity can be computed using eq. 5a. The SSi values are also found in the diagonal elements of matrix △1 (eqs 9 and 10a). The relative contributions are computed using eqs 5b and 10b. 
• 可以使用公式5a来计算第i个取样单元对整个β多样性的贡献率。SSi值可以再矩阵△1的对角元素（公式9和10a）来找到。而相对贡献率可以使用公式5b和10b。

• The contribution of species j to the overall beta diversity, SSj, is computed using eq. 4a, and the relative contributions are computed using eq. 4b. Individual contributions of species and sampling units are useful complements to BDTotal. They are new and valuable tools for the assessment and interpretation of beta diversity, as will be shown in the illustrative example. 
• 物种j对整个β多样性的贡献，SSj，使用公式4a计算，而相对贡献率使用公式4b来计算。物种个体及样方的贡献率是BDtotal的重要组成部分。它们是一种新的，对β多样性估计和解释很有价值的工具，并将会举例说明。

From the Euclidean distance to ecological dissimilarities.
从欧几里德距离到生态相异性
 The Euclidean distance is known to be inappropriate for the analysis of community composition data sampled under varying environmental conditions (Orlóci 1978; Legendre & Gallagher 2001) because such data contain many double zeros, which should be analysed using double-zero asymmetrical coefficients (property P3 in “Properties of dissimilarity coefficients”). The Euclidean distance is not double-zero asymmetrical (sensu Legendre & Legendre 2012, Section 7.4.1) and is thus inappropriate in most instances. An appropriate method consists in computing a dissimilarity matrix D using a chosen coefficient, instead of the Euclidean distance, and applying eq. 8 to obtain SSTotal, then eq. 3 to calculate BDTotal. How to choose an appropriate dissimilarity coefficient for a study is described in the next section. 
欧几里德距离被认为不适合分析变异性很大的样方中的群落结构数据（Orlóci 1978; Legendre & Gallagher 2001）因为这样的数据包含了太多的零值，而应该使用双零不对称系数来分析（相异系数的属性P3）。欧几里德距离不是双零不对称（见legendre和legendre2012, 7.4.1章）因此在大部分时候是不适合的。一个合适的方法是使用选择系数来代替欧几里德距离计算相异矩阵D，应用公式8来获得SStotal，然后使用式3来计算BDtotal。而怎样选择一个合适的相异系数将在下一节讨论。

DISSIMILARITY COEFFICIENTS AND BETA ASSESSMENT  
相异系数与β评估
Since the description of the first floristic similarity coefficient by Paul Jaccard (1900), 
community ecologists have developed a broad array of similarity and dissimilarity 
coefficients. Ecologists are often faced with the question: Which community data 
transformation or (dis)similarity coefficient should I use in my study? When assessing beta 
diversity using community composition variance, one needs to specify what is meant by 
“variation in community composition”. The answer will determine the choice of a community 
data transformation and/or dissimilarity measure, and must be carefully articulated (Anderson 
et al. 2006).  
自从Paul Jaccard（1900）关于植物相似系数的第一次描述，群落生态学家开始发展出来一系列广泛的相似或者相异系数。生态学家经常面对的问题是：哪个群落数据转化形式或者相似（相异）系数在我的研究中可以使用？当我们使用群落结构变异来评估β多样性的时候，我们需要具体说明“群落结构变异”的意义。这个问题将决定对群落数据转化形式或向异性测量的选择，所以必需仔细的明确有力的表达（anderson等2006）

  There is no single coefficient that is appropriate in all occasions. Choice should be 
guided by the properties of coefficients and the objective of the research. Several studies have 
compared resemblance coefficients, focussing on their linearity and resolution along 
simulated gradients (e.g. Bloom 1981, Hajdu 1981, Gower & Legendre 1986, Faith et al. 
1987, Legendre & Gallagher 2001), or investigating theoretical properties (e.g. Janson & 
Vegelius 1981, Hubálek 1982, Wilson & Shmida 1984, Gower & Legendre 1986, Koleff et 
al. 2003, Chao et al. 2006, Clarke et al. 2006). Complementing these studies, we present in 
this section a comparative review of several abundance- and incidence-based dissimilarity 
coefficients, listed in Table 1. Our aim is to determine which coefficients are the most 
appropriate for assessing beta diversity under the present approach. We restricted the list to 
the coefficients originally designed for pairwise comparisons, thus excluding multiple-site 
measures (e.g. Baselga 2010). In addition, we focused on properties that are easy to 
understand and interpret ecologically, with preference for those that could be checked 
unequivocally.  
并没有一个单独的系数可以适合所有的情况。需要通过研究的对象以及系数的特点为指南来进行选择。有很多研究可以计算相似系数，重点在它们的线性或明确的近似梯度（如，Bloom 1981, Hajdu 1981, Gower & Legendre 1986, Faith et al. 1987, Legendre & Gallagher 2001），或者调查数据的理论特征（如，Janson & 
Vegelius 1981 , Hubálek 1982, Wilson & Shmida 1984, Gower & Legendre 1986, Koleff 等 2003, Chao 等 2006, Clarke 等 2006）。为了弥补这些研究，我们在这一节提出了几个基于多度和发生率的相异系数，在表1中列出。我们的目标是确定在现有方法中哪些系数最适合评估β多样性。我们仅仅列出了最初设计的两两比较的系数，因此并不包括多样地测量（如，Baselga 2010）。另外，我们重点放在那些容易理解以及容易生态学解释的指数上，并且偏爱那些容易检验的指数。

Properties of dissimilarity coefficients 
We describe four groups of properties and indicate the reason why we consider them relevant. 
The first two groups (i.e. from P1 to P7) contain the minimum requirements for assessing beta 
diversity. The remaining two groups (i.e. P8 to P14) are not necessarily required in all beta 
diversity assessments. Practitioners should determine whether the context of their analyses 
requires these properties or not. Similarity coefficients should be transformed into 
dissimilarities before assessing the following properties. 
相异系数的特征
我们描述了四组特征值，并指出了我们为什么要选择它们相关的指数来讨论。前两组（如，从P1到P7）包括了测量β多样性的最小需求。而后两组（如，p8到p14）并不是所有的β多样性评估所需要的。专业人员需要决定是否它们分析的范围需要这些特征。而在评估之后的属性之前，相似系数将要被转化为相异系数。

  Property class 1: Basic necessary properties. —Properties P1 to P3 must be fulfilled by 
all resemblance coefficients used for beta diversity assessment. P1 and P2 are actually 
mathematical axioms that define a dissimilarity function. Thus, they are fulfilled by all 
coefficients considered in this paper and are therefore not shown in Table 1. 
  第一类属性：基础必要的属性。用于β多样性评估时属性P1到P3必须包含在所有的相似系数之内。P1和P2实际上是定义向异性功能的数学公式。因此它们被包括在本文的所有指数之中，而并没有在表1中显示。

   P1 – Minimum of zero and positiveness. A dissimilarity value should never be negative and 
it should be zero when comparing a site to itself. When comparing two different sites, it can 
be zero or greater than zero, depending on the species abundance values and how the 
dissimilarity is defined. For example, with some coefficients, D is zero when comparing two 
site vectors whose abundance values are proportional to each other; that is the case with the 
profile, chi-square, chord, and Hellinger distances. Dissimilarities that violate this property by 
taking negative values are called nonmetric, by opposition to the metric and semimetric 
coefficients described below.  
   P1 - 最小为零或正值。相异系数将不可能是负值，当计算样方自己的时候数值为零。当计算两个不同样地时，其值可能为零或者比零大，这取决于物种多度值以及相异性的定义。比如，一些系数，当两个样地的多度值的比例相同时D的数值为零；这就取决于使用配置，卡方，弦距，以及Hellinger距离。相异系数通过使用被叫做非度量的负值来违背这个属性，通过阻止下列度量及半度量系数来描述。

   P2 – Symmetry. Consider two community abundance vectors, x1 and x2, whose dissimilarity 
is to be assessed. In symmetric indices, D(x1,x2) = D(x2,x1). In the incidence-based counterparts of these coefficients (Table 1), the values b and c play identical (symmetric)roles . When studying beta diversity, there is no reason to make a distinction between the two sampling units that are compared using a coefficient. Therefore, dissimilarity coefficients must be symmetric. The property of being double-zero symmetrical, referred to in P3, is a different property. 
   P2 - 对称性。考虑两个群落多度向量，x1和x2，它们的相异性被估测。在对称性指数中，D（x1，x2）=D（x2，x1）。这些系数（表1）的相关，b和c的值扮演了相同的（对称的）角色。当研究beta多样性，没有理由使用系数来计算两个随机样方之间的距离。然而，相异系数必须是对称的。而P3中提到的双零对称性的特性又是不同的性质。

P3 – Independence from double-zeros. Species that are absent in both sampling units 
produce double zeros in the data table. Double zeros in community composition data should 
not be interpreted, and should not affect dissimilarity coefficients, because a species may be 
absent from two sites either for the same reason (e.g. pH too high at both sites for that 
species) or for opposite reasons (e.g. pH too low at one site and too high at the other). The 
fact that some coefficients change their values in the presence of double-zeros in a 
comparison is referred to as the double-zero problem (Legendre & Legendre 2012, Section 
7.2.2). Coefficients that produce smaller dissimilarity values when there are more double 
zeros in a comparison of sites are called symmetrical (or double-zero symmetrical) because 
they treat double zeros like any other pair of identical values. Double-zero asymmetrical 
coefficients, e.g. most of the coefficients discussed in the present paper, treat double absences 
in a different way than double presences; any number of double zeros do not change the 
values of these coefficients. Whereas P1 and P2 are mathematical axioms, P3 is, for 
ecological reasons, a necessary property for beta diversity studies. 
P3 - 双零的独立性。在随机样地中不存在的物种在数据中产生了双零。群落结构数据中的双零不能被解释，不能影响相异系数，因为一个物种可能因为同样的原因（如，物种出现样方的PH太高）或者相反的原因（一个样地的PH太高而另一个样地的PH太低）而在两样方之间缺失。事实上很多系数在一个比较的双零存在时会改变它们的数值，这被称之为双零问题（Legendre & Legendre 2012, Section7.2.2）。产生最小的相异值的系数，当在相比较样方有更多的双零时，被叫做对称（或者双零对称），应为它们处理双零就像其它相同值一样。双零不对称系数，如大多数在现在文章中研究的系数，处理双缺失比双出现有更不同的方法；任何双零都不会改变它们的系数值。这里P1和P2是数学公式，而P3，因为生态学原因，是一个可能的beta多样性研究的特征值。

  Independence from double-zeros can easily be established for coefficients that are 
bounded by a maximum value (Dmax in Table 2). For coefficients that do not have an upper 
bound, like the Euclidean and Manhattan distances, the fact that they are double-zero 
symmetrical (code 0 in column P3) is more difficult to establish. The demonstration is based 
on the binary form of the coefficient (Table 1, column 3), which is the one-complement of the 
simple matching coefficient multiplied by the number of species p for the Manhattan 
distance, and its square root for the Euclidean distance. The simple matching coefficient is the 
archetype of double-zero symmetrical coefficients. The modified mean character difference is 
asymmetrical; its binary form is the Jaccard coefficient where double-zeros are explicitly 
excluded by division by pp=a+b+c. 
   从双零中独立出来可以很容易的建立一个由最大值界定的系数（表2中Dmax）。这些没有最大边线的系数，像欧几里德和麦哈顿距离，事实上它们构建双零对称（P3列，代码0）更难。物种是基于二进位的系数（表1，第3列），通过物种p的数量乘以一个补充的简单的匹配系数来求曼哈顿距离，以及欧氏距离的平方根。这个简单的匹配系数就是双零匹配系数的原型。修改的平均性状差异是对称的；它的二进制结构就是捷卡达系数，双零被明确的通过 pp=a+b+c分开并排除在外。

  Property class 2: Comparability between data sets. — The following properties are 
needed to appropriately compare beta diversity values calculated for different data tables, 
even if the sampling methods are the same. 
  特征类型2：数据集中的相似性。 - 下面的特征值是适合通过不同的数据表来计算beta多样性的，甚至取样方法可以是相同的。

P4 – Invariance to the number of sampling units (n) in the data table. Because it 
measures the average dispersion per sampling unit, variance is, by definition, independent of 
the number of sampling units in the data set. Similarly, if the variance estimate is computed 
from a dissimilarity coefficient through eqs 8 and 3, the number of sampling units in the data 
table should not influence the dissimilarity between pairs of sampling units. If that is not the 
case, the comparison of beta values between data tables of different sizes is not valid.  
P4 - 数据表中取样单元数量的恒定性。因为它测量了每个取样单元的平均扩散，变异是被定义为数据集中取样单元的数量的独立性。相同的，如果评估变异是使用公式8和3通过相异系数来计算的，数据表中取样单元的数量将不能影响两对随机样地之间的向异性。如果这并不是一个问题，不同大小的数据表中β值的比较是无效的。

P5 – Invariance to the number of species in the data table. This property of incidence-
based indices, referred to as homogeneity by several authors (e.g. Janson and Vegelius 1981, 
Koleff et al. 2003, Chao et al. 2006), allows the comparison of beta values computed from 
data tables containing different total species richness. We checked this property on the binary 
form of the coefficients, by multiplying a, b and c by a constant factor and checking whether 
the resulting index value was changed.  
P5 - 数据表中物种数量的恒定性。几位作者（如. Janson 和 Vegelius 1981, Koleff 等. 2003, Chao 等. 2006）同时提到的基于指数的发生率特征，使beta值的比较通过包含不同的总物种丰富度的数据表来计算。我们核查这些在二元数据系数上的特征值，通过a、b、c以及一个常数相乘，并核对是否一个结果系数值被改变。

P6 – Invariance to the total abundance in the data table. This property concerns abundance-based formulas only. It allows the comparison of beta values between data tables (e.g. regions) with different productivities (abundance or biomass), or where biomass has been measured using different units (e.g. in g and mg). To see whether a given quantitative coefficient is invariant to changes of measurement scale, we multiplied the abundance values by a constant factor and checked whether the resulting index was altered.  
P6 - 数据表中所有多度的不变性。这个值数值包括基于多度的公式。允许比较使用不同的生产力（如多度或生物量）的数据表（如，区域）之间的beta值，或者这里的生物量也可以使用不同的单位（如，g或者mg）。看一下是否一个给定量纲的系数随着测量尺度的改变而稳定，我们把多度值乘以一个给定的因子，并核对指数结果是否改变。

P7 – Existence of a fixed upper bound. The existence of an upper bound for a coefficient 
facilitates the interpretation and comparison of beta values because an upper bound in the 
dissimilarity coefficient leads to an upper bound in the beta diversity value. The maximum 
beta value for a region is obtained when all site pairs have the maximum dissimilarity Dmax 
permitted by the chosen coefficient, and this happens when each site has no species in 
common with any other site. 
P7 - 存在一个固定的上限。一个存在上限的系数会更有利于beta值的解释和比较，因为一个相异系数会导致一个beta多样性值的上限。一个区域内最大beta值被获得，当所有样地对允许选择系数拥有最大相异值Dmax，这将发生在一个物种在一个样地不存在而在其它样地普遍存在的情况下。

In practice, this also requires that p ≥ n. One can apply eq. 8 to 
that situation to compute the maximum sum of squares: 
    SSmax = 1/n [n(n−1)/2  × Dmax^2] =(n−1)/2 × Dmax^2  (11) 
and then eq. 3 to obtain the maximum beta diversity value: 
    BDmax = [(n−1)/2 × Dmax^2] 1/n−1 =1/2 Dmax^2  (12) 
在练习中，这需要P≥n。可是应用公式8来计算这种情况下的最大平方和：
    SSmax = 1/n [n(n−1)/2  × Dmax^2] =(n−1)/2 × Dmax^2  (11)
而公式3又获得了最大的beta多样性值：
    BDmax = [(n−1)/2 × Dmax^2] 1/n−1 =1/2 Dmax^2  (12)

The upper bound varies among dissimilarity coefficients (Table 2). For coefficients with 
Dmax= 1, BDmax = 0.5; if Dmax =  2^0.5, BDmax = 1; 
and for the chi-square distance where Dmax = (2y++)^0.5, BDmax = y++
 which is the sum of the species abundances in Y. Hence, for the 
coefficients that have a fixed maximum (see section The dissimilarity measures), we can 
compute a relative value of beta diversity, 
BDrel, as follows:     BDrel=BDTotal/BDmax  (13) 
which is a value between 0 and 1. BDrel is useful to compare beta values computed using 
different coefficients. 
相异系数之间的上限会变化（表2）。这里的系数Dmax= 1, BDmax = 0.5; if Dmax =  2^0.5, BDmax = 1; 
而卡方距离 Dmax = (2y++)^0.5, BDmax = y++，这里是Y的物种多度之和。然而，这里的系数有最大值（见，相异值测量的章节），我们可以计算beta多样性的相对值，BDrel，像这样： BDrel=BDTotal/BDmax  (13) 
这里的只是在0和1之间。通过计算不同的系数，BDrel对beta值比较是有用的。

  Property class 3: Sampling unit size, nestedness and undersampling. — This group of 
properties is mostly related to sampling issues. The fulfilment of properties P8 and P9 
facilitates (but does not ensure) the comparison of beta values obtained from sampling unit 
with different sizes. Indeed, both the number of species and the total abundance should be 
strongly affected by changes in the size of the sampling units. The remaining two properties 
deal with nestedness (P10) and correction for undersampling (P11) of the community 
composition. These properties are also related to sampling unit size, because small sampling 
units can lead to undersampling the targeted community richness, and differences in sampling 
unit sizes can produce nestedness in the community composition of sampling units, even 
when these come from the same community type. 
第三类特征：采样单位的大小，嵌套方式以及采样过疏。-- 这一组特征主要是与取样问题有关系。P8和P9的性质可以促进（但不能保证）使用不同大小的随机取样所获得的beta值之间的比较。事实上，物种数和总多度将会受到随机单元变化而产生强烈的影响。剩下的两个特征值是处理群落结构的嵌套式（P10）以及取样过疏修正式（P11）的。这些值都跟取样单元的大小有关，因为小的取样单元会导致目标群落丰富度的取样过疏，而取样单元大小的不同会产生取样单元内群落结构的潜逃性，虽然它们来自同一个群落类型。

P8 – Invariance to the number of species in each sampling unit. We checked this property 
on the incidence-based forms of the coefficients using the method described in Appendix S1 
in Supporting Information. 
P8 - 每个取样单元内物种的数量不变。我们使用附录S1中所描述的方法来测试了这些机遇发生率形式的系数。

P9 – Invariance to the total abundance in each sampling unit. Except when researchers 
only count and identify a fixed number of individuals (which is often the case in plankton or 
palaeoecological studies), sampling units in the data table are likely to have different total 
abundances. Some abundance-based dissimilarity indices are only sensitive to relative 
abundances per site whereas others reflect differences in site total counts. This property was 
called “density invariance” by Jost et al. (2011). It is not the same as property P6 above. One 
can check property P9 by determining whether a coefficient is altered when the abundances 
are multiplied by a constant factor that is different for each sampling unit.  
P9 - 每个取样单元内总多度不变。除非研究者只记录及鉴定固定数目的个体（这在浮游生物和古生物研究中经常发生），数据表中的取样单元总会有不同的总多度。一些基于多度的相异指数只是对不同总计数的样方内的相对多度敏感
。这个特征被Jost等（2011）叫做‘密度恒定’。她也并不像上面所说的P6那样的特征。可以使用同一个取样单元内不同的因子乘以多度的时候这个系数是不是会改变，来检验P9的特征。

P10 – Zero-value for nested species composition. If all species in a sampling unit are also 
found in another sampling unit (that is, if either b = 0 or c = 0 but not both), some 
dissimilarity coefficients produce a zero value (i.e. they are nestedness-independent) whereas 
most others do not. When both b and c are 0, all coefficients return a dissimilarity of 0. Some 
authors consider that separating nestedness from species replacement is important for beta 
diversity assessment (Baselga 2010). 
P10 - 嵌套式物种结构的零值。如果一个取样单元内的所有物种也同样在另一个取样单元出现时，（即，b=0或者c=0或者都等于零），相同的相异系数产生一个零值（如，它们是独立的嵌套式）而其它情况不产生零值。当b和c都是0，所有的系数将回到一个为0的相异值。一些学者认为分离物种替代的嵌套式，是一个对beta多样性评估非常重要的事情。

P11 – Coefficients with corrections for undersampling. With higher sampling effort, i.e. 
larger sampling units, rare species, and in particular those that are not found at the two sites 
under comparison, are more likely to be observed (Chao et al. 2006, Cardoso et al. 2009). For 
that reason, dissimilarity coefficients generally underestimate the dissimilarities among sites, 
the bias decreasing when sampling effort increases. For some binary similarity coefficients, 
Chao et al. (2006) and Jost et al. (2011) suggested abundance-based counterparts that 
incorporate corrections for undersampling bias.
P11 -   取样过疏相关的系数。随着取样效应的增高，如，取样单元增大，稀有物种，尤其是那些在比较两个样方都没有发现的物种，将更容易被发现（Chao 等 2006, Cardoso 等 2009）。因为这个原因，相异系数会低估了不同样方之间的向异性，当取样效应增加是偏差会减小。在一些二元的相似系数中，Chao等(2006)以及Jost等(2011)建议使用基于多度的统计方式，这样就包括了取样过疏偏差的修正。

  Property class 4: Ordination-related properties. — The remaining properties are not 
related to the ecological interpretation of a coefficient or the comparability of beta diversity 
values. They are, however, useful for ordination of community composition data. 
特征类型4：排序相关的特征。下列的特征值将和生态学系数的解释以及相似的beta多样性值有关。然而，它们对群落结构数据的排序是很有用的。
P12 metric and P13 Euclidean properties of D or D(0.5). A dissimilarity matrix D is metric 
if it has the following metric properties: positiveness (P1), symmetry (P2), and triangle 
inequality, i.e. for any triplet of distance values, D(x1,x2)+D(x2,x3)≥D(x1,x3). Metric 
dissimilarities are also called distances. D is Euclidean if it can be embedded in an Euclidean 
space of real axes such that the Euclidean distances among points are equal to the 
dissimilarity values in D. When this property is satisfied, ordination by principal coordinate 
analysis of D does not generate negative eigenvalues. Gower and Legendre (1986) checked 
the metric and Euclidean properties of several binary and quantitative coefficients. The 
original dissimilarity coefficient may have the metric property (P12). Coefficients that have 
properties P1 and P2 but may violate the triangle inequality property are not metric; they are 
called semimetric. For some of these, metricity can be obtained by taking the square root of 
the dissimilarity values; the resulting matrix, which contains values [Dij^0.5], is noted D(0.5). 
Likewise for the Euclidean property (P13). Legendre & Legendre (2012, Tables 7.2 and 7.3) describe the metric and Euclidean properties of 43 commonly-used similarity and dissimilarity coefficients, including several of the coefficients listed in Table 1. 
D或D^0.5的P12标准或P13欧几里德特征。如果具有以下标准特征时相异矩阵D是标准的：正的（P1），对称的（P2），三角形不等式，如，对于距离值的三条边，D(x1,x2)+D(x2,x3)≥D(x1,x3)。标准的相一致也叫做距离。如果它被嵌套进入一个真实轴的欧几里德空间，这个真实轴在两点之间的欧几里德距离等于D中的相异值，那么D就是欧几里德。当这个特征被统计通过PCA排序，D不会产生负的特征值。Gower 和 Legendre (1986)核对了很多二元以及定量参数的标准及欧几里德特征。这些原始的相异系数将有标准的特征（P12）。那些具有P1和P2的特征但可能打破三角形不等式特征的系数被认为是不标准的；它们叫作半度量。它们中的这些，标准的可以包括相异值的平方根。矩阵的结果，包括[Dij^0.5]，被叫做D（0.5）。同样的也适合欧几里德特征（P13）。Legendre和Legendre (2012,表7.2和7.3) 描述了包括一些在表1中列出的系数在内的43个常用的相似或相异系数的标准及欧几里德特征。

P14 – Emulated by transformation of the raw frequency data. Legendre & Gallagher 
(2001) described how some distance coefficients can be obtained by computing the Euclidean 
distance (eq. 7) after transforming the raw data values in some appropriate way. Another 
distance coefficient can be obtained by applying the Manhattan distance to transformed data; 
see next section. The transformations are described in Appendix S2. These transformations 
are important because they allow one to easily compute a dissimilarity coefficient and, at the 
same time, identify the beta diversity contributions of individual species through eqs 4a and 
4b, and of sites through eqs 5a and 5b. One can also use the transformed data directly in linear 
modelling of community composition data, e.g. by simple (PCA) or canonical (RDA) 
ordination, K-means partitioning, or multivariate regression tree analysis (MRT), because 
these methods implicitly preserve the Euclidean distance among sites. They are useful to 
describe and explain the observed patterns of beta diversity (Legendre & Legendre 2012, 
Section 7.7). 
P14 -  模仿真实频率数据的转换。Legendre 及 Gallagher(2001)描述了怎样通过一些可行的方法转化原始数据之后使用欧几里德距离（公式7）来获得一些距离系数。另外距离系数可以使用曼哈顿距离转化数据来获得；见下一节。转化形式在附录S2中被描述。这里的转化是非常重要的，因为他们必须使用一个容易计算的相异系数，同时，要通过公式4a和4b来鉴定物种个体对beta多样性的贡献，而使用5a和5b来检验样方贡献率。可以使用群落数据的线性模型来直接转换数据，如，使用简单的（PCA）或者（RDA）排序，K-均值分区，或多元回归树（MRT），因为这些方法隐形的保存了样方之间的欧几里德距离。它们用来描述及解释beta多样性的观测格局（Legendre和Legendre2012，第7.7章节）
 
The dissimilarity coefficients  
相异矩阵
A selection of 17 quantitative dissimilarity coefficients commonly used for beta diversity 
assessment was considered in the comparison (Table 1). They represent a broad hand among 
the available coefficients. Equations are shown for community composition abundance and 
also for presence-absence (i.e. incidence) data. The properties (P3 to P14) of these 
coefficients are listed in Table 2, as well as their Dmax values when they exist. 
17个可选择的经常被用于beta多样性测量的量化相异系数被比较和考虑（表1）。它们在可用的系数值简体动了一个广阔的帮助。方程经常在群落结构多度即出现缺席（如，发生率）数据中。这些系数P3到P14的特征以及它们出现的最大值Dmax被列在表2中。
  
The first in the list is the Euclidean distance. Although this distance is known to be 
inappropriate for the analysis of community composition data sampled under varying 
environmental conditions (Orlóci 1978, Legendre & Gallagher 2001), it is included in the 
comparison where it will serve as a reference point. It is the failure of the Euclidean distance 
to correctly account for beta diversity (it lacks P3) that makes it necessary for ecologists to 
rely on the other dissimilarity measures investigated in this paper. The Euclidean distance 
may, however, become appropriate after transformation of the community data (Appendix 
S2). The Manhattan distance, which is also inappropriate per se, is included in the comparison 
because, like the Euclidean distance, it may become appropriate after data transformation. 
 首先列出来的是欧几里德距离。虽然这个距离被认为是不适合在环境条件变化样方的群落结构数据分析之中（Orlóci 1978, Legendre 和 Gallagher 2001）， 它可以作为一个参考点进行比较。由于欧几里德距离矫正解释beta多样性的失败之处（它缺少P3），使得生态学家依赖本文中提到的其他相异性测量。然而，欧几里德距离适合转化过的群落数据（附件S2）。曼哈顿距离，本身也不合适，包括比较，因为像欧氏距离一样，它会适合转化后的数据。

The other coefficients included in the comparative study are double-zero asymmetrical 
(property P3); they have been recommended and used for community composition assessment 
or beta diversity studies. Two groups of coefficients deserve additional comments. 
比较研究中的其他系数是双零不对称型（P3的特征）；它们可以被推荐用于群落结构测试或beta多样性研究。两种系数值得更多的评论。

Five of the distances can be computed using the formula in Table 1, or through the 
alternative method corresponding to property P14. For the species profile, Hellinger, chord, 
and chi-square distances, the data are first transformed using the same-name transformation 
(Appendix S2); computing the Euclidean distance (eq. 7) on the transformed data produces 
the targeted distance. In the same way, computing the Manhattan distance on data 
transformed into species profiles produces twice Whittaker’s index of association; for that 
reason, Whittaker’s index was dubbed “relativized Manhattan” by Faith et al. (1987). 
Actually, the four transformations described in Appendix S2 could be used before calculation 
of the Manhattan distance. 
有5个距离可以使用表1中的公式计算，或者选择和P14相关的方法。对物种特点，Hellinger，弦式及卡方距离，数据先使用相同名字的转换方式转化（附件S2）；使用转换过的数据计算欧几里德距离（公式7）产生对象距离。使用同样的方法，使用物种资料转换过的数据来计算曼哈顿距离并产生二次whittaker相关指数；由于这个原因，whittaker指数被Faith等（1987）称为是‘相对的曼哈顿’。实际上，附录S2中描述的4种转换方式都能在计算曼哈顿距离之前使用。

   A consequence of this observation is that SSTotal corresponding to the species profile, 
Hellinger, chord, and chi-square distances can be obtained by computing the transformation in 
Appendix S2, then applying eqs 1 and 2 to the transformed data. This is simpler than 
computing the distance matrix, then using eq. 8 to obtain SSTotal. Furthermore, it allows the 
computation of SCBD statistics (eq. 4b), which cannot be obtained from a distance matrix. 
观测的后果是与物种本身，海灵格，弦式，方差距离相关的SStotal都能通过附录S2中的转换计算而得到，然后应用公式1和2转换数据。这比计算距离矩阵要简单，然后使用公式8获得SStotal。另外，它允许使用SCBD统计（公式4b）计算，这并不能通过距离矩阵获得。
  The last four dissimilarities in Table 1, proposed by Chao et al. (2006), implement 
corrections for undersampling bias (P11). These coefficients are not Euclidean in quantitative 
form, although the Jaccard, Sørensen and Ochiai similarities, which are the binary 
counterparts of the first three, produce coefficients with the Euclidean property (P13) when 
transformed to D= （1−similarity）^0.5 (Legendre & Legendre 2012, Table 7.2).  
表1中的四个相异值，由chao等2006年提出，进行千篇之矫正（P11）。这些系数并不是量化结构的欧几里德，虽然，
Jaccard, Sørensen 以及 Ochiai 相似性，它们是前三个的二元形式，当转换成D=（1−similarity）^0.5时，产生欧几里德特征（P13）的系数。（Legendre 和 Legendre 2012, 表 7.2）

  When applied to presence-absence data, several quantitative dissimilarity functions in 
Table 1 produce either the one-complement of the Jaccard similarity index, 
(b+c)/(a+b+c), or the one-complement of the Sørensen index, (b+c)/(2a+b+c). The 
Hellinger and chord distances both produce D= [2(1−Ochiai similarity)]^0.5. 
当使用存在缺失数据，表1中很多量化的相异函数产生一个完整的Jaccard相似指数，(b+c)/(a+b+c)，或者一个完整的
Sørensen指数，(b+c)/(2a+b+c)。海灵格以及弦式距离都会产生D=[2(1−Ochiai相似性)]^0.5
Comparative study 
比较研究
The properties of the selected coefficients were coded into a data matrix with the coefficients 
as rows and properties P3 to P14 as columns. Most properties were coded as presence-absence (0-1), except for coefficients P12 and P13 which were coded on a semiquantitative 0-1-2 scale (0 = property absent, 1 = present for D(0.5), 2 = present for D(0.5) and D). NA values in Table 2 were treated as zeros since the coefficient did not have the property in question. The data matrix was subjected to principal component analysis (PCA) of the correlation matrix.  
选择系数特征将被记录在数据矩阵中，系数作为行，P3到P14的特征作为列。大部分特征值被记录为存在缺失（0-1），除了P12和P13系数被记录为半量化0-1-2等级（0为特征缺失，1为D0.5出现，2为D0.5和D出现）。当系数在问题中没有特征时表2中的NA值被当作零来处理。数据矩阵可以使用矩阵相关的组成分分析（PCA）处理。

  The analysis produced an ordination of the dissimilarities (Fig. 2) where similar 
coefficients are close to one another and dissimilar ones are more distant. Properties P3 to 
P14, which formed the variables of the matrix subjected to PCA, are shown as red arrows. 
One can identify five types of coefficients in the ordination diagram:  
分析方法产生了一个相异性排序（表2），这里的相似系数很接近于另一个，而相异系数则差距很大。p3到P14中特征值，产生PCA对象的数据变异，使用红色箭头显示。在排序图中可以区分成5种类型。

• Type I contains the Euclidean and Manhattan distances as well as the mean character 
difference. The first two coefficients lack property P3 (asymmetric treatment of double-zeros) 
which makes them unsuitable for beta diversity assessment. All three lack P6 (invariance 
with respect to y++) and P7 (fixed upper bound); these coefficients would not allow 
comparison of beta diversity estimates among data sets. 
  Coefficients in types II to V provide asymmetrical treatment of double-zeros (P3). They 
also all have properties P6 and P7, which are required for comparability of beta estimates 
among data sets. They are thus all appropriate for beta diversity assessment. 
•类型1包括了欧几里德和曼哈顿距离以及平均特征差异。前两个系数缺少属性P3（双零不对称处理）这让它们不适合作为beta多样性评估。这三个都缺少P6属性（Y++的不恒定），P7（固定上线）；这些系数不能用于数据集之间的beta多样性评估比较。类型2到5中的系数都提供了双零不对称处理（P3）。他们也都有P6和P7属性，它们可以进行不同数据集之间的Beta评估比较。因此，他们都是和Beta多样性评估。

• Type II contains the profile, Hellinger, chord, chi-square and Whittaker distances. They 
share properties P12 (metric), P13 (Euclidean) and P14 (emulated by transformation of the 
raw frequency data). D matrices computed using these coefficients (D(0.5) in the Whittaker 
case) are fully suitable for ordination by principal coordinate analysis (PCoA), which will not 
produce negative eigenvalues and complex axes. Furthermore, species frequency (or frequency-like, such as biomass) data transformed using the profile, Hellinger, chord, or chi-square transformations can be used directly in principal component analysis (PCA) and in canonical ordination by RDA; this is not the case for type III-V coefficients. 
• 类型2包括了描述，海灵格，弦式，方差，whittaker距离。它们都有属性P12（标准），P13（欧几里德），P14（模拟原始频率转换）。矩阵D非常适合使用这些系数（whittaker中的D0.5）进行PCoA排序，它不会产生负的特征值以及复杂的排序轴。另外，物种频率（或者拟频率，像生物量）数据经过描述，海灵格，弦式，方差转换后可以直接使用RDA或PCA或CA分析。这是第3到5类系数所不行的。
• Type III contains the divergence, Canberra, percentage difference (alias Bray-Curtis), and 
Wishart dissimilarities. The coefficient of divergence, which is Euclidean, can be used 
directly in PCoA ordination. For the other three coefficients, the square root of the distances 
must be taken before they are used in PCoA. The matrix of principal coordinates can be used 
as the response data in RDA; this is the distance-based RDA method proposed by Legendre & 
Anderson (1999). 
• 第3类包括了分离，Canberra，百分差（别名Bray-Curtis），以及Wishart相异值。分离系数，是一个欧几里德，可以直接用于PCoA排序。而其它3个系数，可以再使用PCoA之前计算距离的平方根。PCoa矩阵可以作为RDA的反应数据；这就是Legendre和Anderson（1999）所说的基于距离的RDA模式。

• Type IV contains the abundance-based quantitative forms of the Jaccard, Sørensen, Ochiai 
and Simpson indices. They share properties P9 (invariance to total abundance in individual 
sampling unit) and P11 (correction for undersampling), but not properties P12, P13 and P14, 
which are desirable for ordination. 
• 第4类包括了基于多度的量化类型，Jaccard, Sørensen, Ochiai以及 Simpson指数。它们具有P9属性（独立取样单元中的总多度恒定）以及P11（修正取样过疏），但是没有P12，P13，P14属性，不利于做排序。

• The Kulczynski coefficient forms a type of its own (type V). It is suitable for beta 
diversity assessment, but not for ordination, and it does not correct for undersampling. This 
coefficient does not offer any particular advantage not available in other coefficients.
• Kulczynski系数结构是他所独有的类型（第五类型）。他适合beta多样性评估，但是不适合排序，他不能修正取样过疏。这个系数并未提供任何特殊的利处，和其他系数相比并不有利。

ECOLOGICAL ILLUSTRATION: FISH BETA DIVERSITY IN DOUBS RIVER 
生态学例子：杜河内鱼的beta多样性
Freshwater fish were collected by Verneaux (1973) in the Doubs River, a tributary of the 
Saône that runs near the France-Switzerland border in the Jura Mountains in eastern France. 
In his paper, Verneaux proposed to use fish communities to characterize ecological zones 
along European rivers and streams. The data include fish community composition at 30 sites 
along the 453 km of the river, the site geographic coordinates, and environmental data 
(source: http://www.bio.umontreal.ca/numecolR/). 27 species were captured and identified. 
No fish were caught at site 8, hence that site was excluded from the reanalyses made by 
Borcard et al. (2011), as well as here. As in that book, we subjected the fish data to a chord 
transformation before analysis (Appendix S2). 
1973年杜河内淡水鱼被verneaux收集，Saône的一个支流，流经法国瑞士到达法国东部的侏罗山脉边界。在他的文章中，verneaux使用鱼类群落描述了欧洲河及小溪的生态学区域。数据包括沿着453km的河中的30个样地中鱼的群落结构，以及样地的地理坐标，环境数据（资源：http://www.bio.umontreal.ca/numecolR/）。27个物种被捕获和鉴定。在样地8中没有不到鱼，因此这个位置在borcard等2011年分析的时候被排除在外，现在这里也一样。在那本书中，我们在分析之前使用了一个chord转换（附录S2）。

  SSTotal (eq. 2) was 15.243 and BDTotal (eq. 3) was 0.544 for the fish data. The local contributions of individual sites were computed; the values of SSi (eq. 5a) ranged from 0.291 to 0.971 and the relative contributions (LCBDi, eq. 5b) were in the range [0.0191, 0.0637]; 
LCBD indices, which indicate the uniqueness of the fish community at each site, are plotted 
on a map of the river in Fig. 3a. Comparison with species richness (Fig. 3b) showed that 
LCBD was negatively related to richness (r = –0.60), indicating that high LCBD (i.e. high 
uniqueness of species composition) was often related to a small number of species.  
使用鱼的数据SStotal（公式2）是15.243，BDtotal（公式3）是0.544 。每个样地的当地贡献率被计算：SSi（公式5a）的值从0.291到0.971，相对贡献率（LCBDi，公式5b）在范围[0.0191,0.0637];LCBD指数，指示了每个样地内与群落的特殊性，并画出了一幅图（图3a）。比较鱼的丰富度（表3b）显示LCBD与丰富度是负相关（r=-0.60），指示高的LCBD（如，高的物种结构独特性）经常导致少的鱼种类。
  Environmental variables were also available for each site. They describe distance from 
the source, altitude, slope, mean minimum discharge, pH, concentrations in calcium, 
phosphate, nitrate, ammonium and dissolved oxygen, and biochemical oxygen demand 
(BOD). The LCBD values were regressed on the environmental variables to determine the 
 factors that make LCBD vary along the river. Only two environmental variables were 
retained by backward elimination: slope of the riverbed and BOD. The regression model had 
an adjusted R2 of 0.58; both variables had positive coefficients in the model, indicating that 
sites contributing highly to BDTotal either had a large slope (specially true at the headwaters) 
or were strongly eutrophic (high BOD). Note that regressing LCBD values on environmental 
variables is not the same as canonical ordination of the community data. For the chord-transformed Doubs fish data, forward selection of environmental variables in RDA produced a different model (adjusted R2 of 0.61) containing five significant variables at the 0.05 level: distance from the source, altitude, slope, dissolved oxygen, and BOD. The question in RDA is to identify the factors driving the observed variation in community composition; RDA truly analyses beta diversity by decomposing the total variance of the species data, i.e. the BDTotal statistic, into explained and residual components. By contrast, in regression analysis of the LCBD vector, the question is why some sites have higher degrees of uniqueness in species composition than others. 

每个样地的环境差异是可以使用的。他们记录了从水源，海拔，坡度，平均最小交换律，PH，ca，p，n含量，氨基盐，交换氧 ，可用氧（BOD）等。LCBD值被环境变量回归，来决定什么因子导致了河中的LCBD变化。只有两个环境变量被淘汰；坡度及BOD。回归模型的调整后R2是0.58；模型中的变量都是一个正的系数，显示了样地贡献了很高的BDtotal，不管是高的坡度（尤其在水源地）还是在强的营养物质（高BOD）。说明的是LCBD回归至在环境变异和群落数据的CA排序是不同的。使用Chord转化过的杜河鱼类数据，使用RDA环境变量的向前选择产生了一个不同的模型（调整后的R2等于0.61）包括了五个在0.05水平上的显著变量；距离水源，海拔，坡度，溶解氧，以及BOD。RDA显示因子导致了明显的群落结构变异；RDA真的通过方差分解来分析了beta多样性可解释的和不可解释的部分，如，BDtotal统计。相对比，LCBD因子的回归分析，问题是为什么一些样地有高的鱼类结构独特性呢？

  Five species contributed to beta diversity more than the mean of the 27 species: the 
common roach (Cyprinidae) with the lowest value of SCBD above the mean, the stone loach 
(Balitoridae), the common bleak (Cyprinidae), the Eurasian minnow (Cyprinidae), and the 
brown trout (Salmonidae) with the highest SCBD value. The chord-transformed abundances 
of these species varied the most among the sites. The brown trout, Eurasian minnow and stone 
loach are found in the high LCBD sites upriver, whereas the common roach and common 
bleak are abundant in the eutrophic sites in the middle course of the river that also have high 
LCBD values. 
有五种鱼对beta多样性的贡献率高于27个物种的平均值：常见鲤（Cyprinidae）有着比平均值低的SCBD值，
石头鳅（Balitoridae），Cyprinidae，（Cyprinidae),以及 (Salmonidae)有着高的SCBD值。这些物种的多度的chord转化在大部分样地是变化的。 The brown trout, Eurasian minnow 以及stone loach发现在上游有高的LCBD，而 common roach以及common bleak在在中游的营养地带较丰富，同时又高的LCBD值。

   Calculation of LCBD was repeated using the 17 coefficients in Table 1 using the 
software in Appendix S3. A cluster analysis was carried out from the Spearman correlation 
matrix among the 17 LCBD vectors. The results (Fig. 4) indicate that the LCBD vectors 
computed using the 14 coefficients pertaining to types II to V form a large cluster separated 
from the first three coefficients. LCBDs were quite homogeneous in that large group: the 
mean Spearman correlation among the 14 LCBD vectors was 0.869. Kendall concordance 
analysis with a posteriori tests (Legendre 2005) showed that the contributions of all 14 
vectors to the concordance of the large group were significant. (These are not genuine tests of 
significance since the LCBD vectors were all computed from the same data; these results 
provide, however, a clustering validation criterion.) We conclude that, for this example, 
LCDB indices computing using all dissimilarities that were found suitable for beta diversity 
assessment were highly concordant. 

使用附录S3软及表1中的17个系数重复计算LCBD。使用spearman相关系数对17个LCBD因子进行聚类分析。结果表明（表4）显示使用第二类到第五类中的14个系数计算出的LCBD很明显的和前三个系数计算出的分离开。同一类型中的LCBD值具有很高的同质性：14个LCBD之间的Spearman相关系数是0.869.Legendre2005年使用的经过检验的Kendall分析显示一大组中的14个因子一致性的贡献率是显著的。（这里并没有真的显著性检验，因为LCBD是由同一个数据计算出来的；然而，结果提供了一个分类的验证标准）。我们指出，这些例子中，使用所有的相异系数计算的LCDB指数都适合beta多样性的评估，都具有很高的一致性。

DISCUSSION 
讨论
   Related approaches to beta diversity assessment In this paper, we used the total variance of Y as an estimate of beta diversity (DBTotal) for a region of interest (eq. 3). Alternative equations have been proposed by Whittaker (1972), Ricotta & Marignani (2007) and Anderson et al. (2006). We will now show that these proposals are special cases of eq. 3. In section “Equivalent ways of computing Var(Y)”, we 
saw that SS(Y) can be computed as the sum of the squared dissimilarities divided by n (eq. 8). 
This is appropriate for the Euclidean distance and also for dissimilarities that have the 
property of being Euclidean (P13). Several dissimilarity indices, coded 1 for property P13 in 
Table 2, are Euclidean only when taking their square roots; the transformed distances form 
matrix D(0.5)=[Dij^0.5]. That group includes Whittaker’s index, the Canberra metric, the 
widely-used percentage difference (alias Bray-Curtis) and Wishart’s coefficient. Many of the 
incidence-based (i.e. binary) coefficients used in community ecology are also in that situation, 
including the widely-used Jaccard, Sørensen and Ochiai coefficients (Legendre & Legendre 
 2012, Table 7.2). The method of calculation of beta diversity proposed in other papers is 
equivalent to DBTotal of the present paper if D(0.5) is used for the calculations: 
   在本文中提到了与beta多样性测量相关的方法，我们使用了Y的总方差（公式3）来作为研究区域beta多样性（DBtotal）的测量。关于公式的选择Whittaker (1972), Ricotta & Marignani (2007) 及Anderson等人(2006)已经推荐过。我们将展示公式3中特殊案例的特征值。在‘计算Var（Y）的等价方法’一节，我们看到SS（y）可以用n个（公式8）所分开的相异平方和来计算。这是欧几里德距离的特征也是被欧几里德特（公式13）征化的相异值。有很多相异指数，如表2中P13的代码1，是只有使用它们的平方根的时候才使用欧几里德距离；同时矩阵D(0.5)=[Dij^0.5]进行距离转换。这个组内包括了Whittaker指数，Canberra标准，广泛使用的百分比差异（别名为Bray-Curtis）以及Wishart系数。在群落生态学中使用的很多机遇发生率的系数（如，binary）也是在那种情况下，包括了广泛使用的Jaccard, Sørensen以及Ochiai系数（legendre以及legendre2012，表7.2）。当D（0.5）使用以下方法时，其它文章中的beta多样性计算方法和本文中的DBtotal是等价的。

(a) Whittaker (1972, p. 233) stated that “The mean CC [Jaccard’s coefficient of community] 
for samples of a set compared with one another [...] is one expression [of] their relative 
dissimilarity, or beta differentiation”. The mean is obtained by summing the dissimilarities 
and dividing by the number of dissimilarities in the half-matrix, n(n−1)/2. This is equivalent 
to computing eqs 8 and 3 on the square-rooted dissimilarities (matrix D^0.5) and multiplying by 2. Hence, Whittaker’s formula only differs by a factor 2 from DBTotal computed from D(0.5).   
(a) Whittaker (1972, p. 233)阐述‘CC的意义[Jaccard的群落系数]对于一组样品和其他[...]相比较时，是一个他们相对相异值的表达或者是beta分化’。这个意义是计算相异值之和以及将半矩阵n（n-1）/2的相异值数分开而获得的。在平方根的相异矩阵（D^0.5）使用公式8和3或者乘以2是等价的。然而，Whittaker的公式只是由于因子2以及由D（0.5）计算的DBtotal而不同。

(b) There is also a relationship between the equation for DBTotal used in this paper and the suggestion of Ricotta & Marignani (2007) to estimate beta diversity by Rao’s (1982) quadratic entropy, Q=∑(h=1:n−1)∑(i=h+1:n)δhi×Ph×Pi, where pi and ph contain the relative abundance of sampling units i and h, respectively, and δhi is the dissimilarity between i and h computed with any measure of one’s choice. If all plots are considered to be equally important, say pi = 1/n, then Q =1/n^2 (∑h=1:n−1)(∑i=h+1:n)δhi , which is very close to DBTotal computed from D(0.5) through eq. 8 followed by eq. 3. The difference is that the last division is by n in Q instead of (n–1) in eq. 3.  
(b)这里也有本文使用DBtotal的公式以及Ricotta & Marignani (2007)建议的使用Rao（1982）二次熵来评估β多样性之间的关系。Q=∑(h=1:n−1)∑(i=h+1:n)δhi×Ph×Pi，这里Pi和Ph分别包括了随机样方i和h的相对多度，而δhi 是通过选择尺度来计算i和h之间的相异值。如果所有位点被看作是同等重要，也就是说pi=1/n,而 Q =1/n^2 (∑h=1:n−1)(∑i=h+1:n)δhi，这就非常接近使用公式8以随后的公式3通过D（0.5）来计算的DBtotal。他们之间的不同是最后通过n/Q来代替公式3中的（n-1）来做被除数。

(c) The beta diversity statistic developed by Anderson et al. (2006) belongs to the same family as DBTotal. It is the sum of the dissimilarities from the sampling units to the group centroid in multivariate space divided by n. It differs from DBTotal, which is the sum of the squared dissimilarities from the sampling units to the group centroid (eq. 10a) divided by (n−1)(eq. 3). Because it is computed from any dissimilarity matrix (eqs 9 and 10a; the square root of the values in vector [SSi] provide the dissimilarities of the sampling units to the centroid), the Anderson et al. (2006) statistic can be obtained from D as well as D(0.5). 
(c)beta多样性统计使用Anderson 等 (2006)开发的和DBtotal同属于一个家族。它是多层空间中随机样方到组中心的相异值之和除以n。它是和DBtotal是由区别的，它是随机样方对组中心的相异平方之和（公式10a）除以（n-1）（公式3）。因为它是通过不同的相异矩阵计算（公式9和10a；向量[SSi]的值的平方根提供了随机样方到中心点的相异性），而anderson等（2006）使用和D（0.5）差不多的D来进行统计的。
 
  Regarding the choice of a dissimilarity measure and the equivalence of the beta 
diversity approaches described in the last paragraphs, different situations should be 
considered. 
关于相异性测量以及beta多样性方法的等价性选择在下一段描述，需要考虑不同的情况。

(a) For dissimilarity measures that are not Euclidean for D but are Euclidean for 
D(0.5), then the approaches of Whittaker (1972) and Ricotta & Marignani (2007) are 
essentially equivalent to the calculation of DBTotal in the present paper. The beta statistic of 
Anderson et al. (2006), which is closely related to DBTotal, can be computed from D or D(0.5). 
(a) 相异性测量并不是使用D的欧几里德，而是使用D0.5的欧几里德。Whittaker (1972)以及 Ricotta 和 Marignani (2007)的方法实际上与本文中DBtotal的计算是一致的。Anderson等（2006）的beta统计，很接近DBtotal，可以使用D或D0.5计算。
(b) If the dissimilarity measure can be obtained by applying a transformation to the original 
data (Appendix S2) followed by the computation of the Euclidean distance, the equivalence 
between these methods holds in the transformed space and BDTotal can be computed by applying eqs 2 and 3 to the transformed data. 
(b) 如果向异性测量能应用原始数据（附录S2）的转化使用欧几里德距离计算的话，这些转化空间方法和BDtotal之间的等价将会应用公式2和3去转化数据。
(c) If the dissimilarity measure cannot be obtained by applying a transformation to the original data followed by Euclidean distance calculation, the distances to the centroid can still be computed using the square root of eq. 10a. This result holds for non-Euclidean embeddable dissimilarities as well, although with some additional complexities (Anderson 2006).
(c) 如果相异性歇凉不能获得使用原始数据转化而随后使用欧几里德距离计算，到中心距离仍然可以使用公式10a的平方根计算。这个结构使非欧几里德很好的嵌入相异值中，虽然也伴随着一些额外的复杂化（anderson2006）。

Multiple ways of partitioning total beta diversity 
beta多样性的多层分解
The strongest advantage of adopting the present approach to the analysis of beta diversity lies in the possibility of partitioning the total sum-of-squares of the community composition data into additive components. The total variance is the basic currency of many statistical methods, univariate and multivariate, through which Var(Y) can be partitioned in different ways. Available partitioning methods include the following. 
应用当前方法分析beta多样性的最强大好处是可以将群落结构总方差之和分解成独立的部分。总变异是很多统计方法、单变量及多变量的基本货币，虽然这里的Var（Y）可以使用不同的方式分解。可用的额分解方法包括下列。

1. Contributions of individual species. — The SSTotal statistic can be partitioned into species contributions to beta diversity (SCBDj, eq. 4b). This can be done whether the calculation of SSTotal has been done from the raw or transformed abundance data. The centred SCBD values, 
which are signed, indicate the species that vary more [or less] than the mean across the sites. 
1.物种个体的贡献率。- SStota了统计可以将物种对beta多样性的贡献率(SCBDj,公式 4b)分解出来。这样能做，是否SStota可以使用原始的或转化过的多度数据计算。SCBD值的中心，被标记出来，指示了物种在样方之间比平均值多还是少的变异情况。

2. Contributions of individual sampling units. — Likewise, the SSTotal statistic can be partitioned into local contributions of individual sampling units to beta diversity (LCBDi, eq. 5b or 10b). The LCBD values, which can be mapped, indicate the sites that contribute more [or less] than the mean to beta diversity. LCBD represents site uniqueness; hence, large LCBD values indicate sites that have strongly different species compositions. In conservation biology, LCBD could be used as an indicator of the site conservation value. LCBD may be inversely correlated with species richness, as in our example, but in other ecosystems large LCBDs may indicate rare species combinations that are worth studying in more detail. In data analysis, sites with high LCBD may be removed before simple or canonical 
ordination because they may have an undue influence on the results. This may prove a useful 
criterion to remove sites prior to ordination, instead of other criteria like small species 
richness.  
2. 独立随机样方的贡献率。- 同样的，SStotal统计可以分解出独立随机样方对beta多样性的贡献率（LCBDi，公式5b或者10b）。LCBD值可以被绘图，来只是出哪些对beta多样性的贡献率比平均值多或者少的样方。LCBD代表了样方的独特性。因此，较大的LCBD指示出哪些有强烈物种结构差异的样方。在保护生物学中，LCBD可以作为有保护价值的样地。LCBD可能跟物种丰富度有负相关，向我们的例子中一样，但是在其他生态系统中大的LCBD可能只是一些值得做更多研究的稀有物种的组合。在数据分析中，具有高的LCBD的样方在简单的分析或排序中可能被移除，因为它们可能会过度干扰结果。在排序之前将有个有用的标准,而不是像使用小物种丰富度来作为其他标准那样。

3. Within- and among-group contributions. — Groups of sites may be known a priori from 
the sampling design, or they may be obtained by clustering based on the environmental 
variables. For these groups of sites, the total sum-of-squares of the species data can be divided 
by multivariate analysis of variance (computed using MANOVA or canonical analysis) into 
within- and among-group sums of squares. Alternatively, groups of sites where the species 
respond in the same way to environmental variables can be identified by multivariate 
regression tree analysis. 
3. 组内或组间贡献率。- 样方组合可以由随机设计的先验知识来得到，或者使用环境变异进行分类来得到。在这些样方的分组中，物种数据的总方差之和可以除以变异的多因素分析（使用Manova或者CA分析）来得到组内或组间的方差之和。可选择的是，那些物种对环境变异具有相同反应的样方组可以使用多元回归树来鉴定。

4. Simple and canonical ordination. — The total sum-of-squares, which estimates beta 
diversity, can be partitioned into orthogonal axes by simple ordination methods (PCA, CA, 
PCoA). Alternatively, SSTotal can be partitioned by canonical analysis (RDA or CCA) into orthogonal axes related to the environmental variables. 
4. 简单或者CA排序。 -  估测贝塔多样性的方差总和可以使用一些简单的排序（PCA, CA, PCoA）来分解到排序轴上。可选择的是，SStota了可以使用CA排序（RDA或者CCA）被分成可环境相关的排序轴。

5. Spatial scales. — SSTotal can be partitioned as a function of different spatial scales by spatial eigenfunction analysis. See Legendre & Legendre (2012, Chapter 14) for a review of these methods. These and other methods of multivariate multiscale analysis were also reviewed by Dray et al. (2012). 
5. 空间尺度。 - SStotal可以使用空间特征值分析被分解成不同的空间尺度功能。参考Legendre和Legendre（2012，第14章）对这个方法的评论。而关于多变量多尺度分析可以参考Dray等（2012）的评论。

6. Contributions of sets of explanatory factors. — SSTotal can be partitioned as a function of different sets of explanatory variables by variation partitioning (Borcard et al. 1992; Peres(Neto et al. 2006). Partitioning can be done, for example, between different sets of environmental variables, or between explanatory matrices representing environmental and spatial variables (e.g. sets of spatial eigenfunctions), depending on the hypotheses under study. This is a major approach for estimating the relative contributions of groups of explanatory variables representing different hypotheses about the origin of beta diversity. 
6. 关于解释因子的贡献率。 - SStotal被当作一个不同解释因子集合的函数而使用方差分解方法进行分解（Borcard et al. 1992; Peres(Neto et al. 2006）。比如，方差分解根据研究的理论，可以在不同的环境因子变量之间进行，也可以是在表示环境和空间因子的解释数组之间进行（如，空间特征值集合）。这是一个主要的方法来估测由关于beta多样性起源的不同理论所代表的解释因子变异集合的相对贡献率。

7. Multivariate variogram and ordination. — SSTotal can be partitioned into spatial scales by multivariate variogram analysis (Wagner 2003). The species-environment relation, which represents a portion of SSTotal, can also be partitioned into spatial scales by multiscale ordination. See Wagner (2003, 2004) and Legendre & Legendre (2012, Section 14.4).  
7.多变量变异及排序。- SStotal可以通过多变量分析来分解成不同的空间尺度（Wagner 2003）。物种与环境相关性，可以看作是SStotal的一部分，也能够通过多层排序被分解成不同的空间尺度。见Wagner（2003,2004）以及Legendre和Legendre（2012，第14.4章）

Choosing a dissimilarity index for beta diversity assessment 
选择beta多样性评估的相异指数
Analyzing the spatial variation in species composition necessarily implies choosing a dissimilarity coefficient, either implicitly or explicitly (Legendre et al. 2005, Anderson et al. 2006). Choosing an appropriate coefficient is crucial to ensure the interpretation of the results and allow the comparison of beta diversity estimates among regions and types of organisms. 
分析物种结构空间变异暗示着要选择一个相异系数，既不能太含蓄又不能太明显（Legendre 等. 2005, Anderson 等. 2006）。选择一个合适的系数对结果的解释是至关重要的，也可以是beta多样性结构在不同的生物类型及区间之间进行评估。

  In this paper, we studied several properties of coefficients, separating those that were 
purely mathematical from those that had an ecological interpretation. This conceptual 
separation was important to help users make choices on ecological grounds. Comparison of 
the 17 selected dissimilarity coefficients based on 14 ecological, statistical and mathematical 
properties led to a model where the coefficients were divided into five main types. Four of 
those types are suitable for beta diversity studies and comparison of beta diversity estimates 
computed from different ecological data sets. These different types of coefficients can be used 
to address different questions. When choosing a coefficient, users should check the properties 
the coefficient has, and determine whether they are suitable for the objectives of the study. 
Further research is needed about the mathematical and ecological properties of dissimilarity 
coefficients, and the situations where these properties are desirable or needed. 
在本文中，我们研究了多个特征值系数，把那些纯数学的公式和有生态学解释意义的公式分开。把概念分开对帮助使用者选择生态学原理是非常有用的。比较了基于14个生态学统计学数学特征值的17个可选择的相异系数，使用了模型将这些系数分成了5大类。他们中的4类是适合使用不同生态学数据集来进行beta多样性研究以及beta多样性组成评估。这些不同类型的指数可以回答不同的生态学问题。当选择一个系数，使用者将要核查系数的特征，决定它们是不是合适研究对象。关于相异系数的数学和生态学特征以及在什么情况下这些特征是有利的或需要的，这些都需要做进一步的研究。

ACKNOWLEDGEMENTS 
致谢
Our thanks to Daniel Borcard who provided comments on the manuscript before submission. 
感谢Daniel Borcard在手稿还未提交之前给以的意见。
This research was supported by a NSERC grant no. 7738 to P. Legendre.
本研究由 P. Legendre的 NSERC基金支持。
M. De Cáceres was supported by research projects BIONOVEL (CGL2011(29539/BOS) and MONTES 
(CSD2008(00040) funded by the Spanish Ministry of Education and Science.
 由M. De Cáceres的BIONOVEL及 MONTES研究项目支持。

REFERENCES 
参考文献
1. 
Anderson, M.J. (2006). Distance(based tests for homogeneity of multivariate dispersions. 
Biometrics, 62, 245–253. 
2. 
Anderson, M.J., Ellingsen, K.E. & McArdle, B.H. (2006). Multivariate dispersion as a 
measure of beta diversity. Ecol. Lett., 9, 683–693. 
3. 
Anderson, M.J., Crist, T.O., Chase, J.M., Vellend, M., Inouye, B.D., Freestone, A.L. et al. 
(2011). Navigating the multiple meanings of b diversity: a roadmap for the practicing 
ecologist. Ecol. Lett., 14, 19–28. 
4. 
Baselga, A. (2010). Partitioning the turnover and nestedness components of beta diversity. 
Global Ecol. Biogeogr., 19, 134–143. 
5. 
Bloom, S.A. (1981). Similarity indices in community studies: potential pitfalls. Mar. Ecol. 
Progr. Ser., 5, 125–128. 
6. 
Borcard, D., Gillet, F. & Legendre, P. (2011). Numerical ecology with R. Use R! series, 
Springer Science, New York.  
7. 
Borcard, D., Legendre, P. & Drapeau, P. (1992). Partialling out the spatial component of 
ecological variation. Ecology, 73, 1045–1055. 
8. 
Bray, R.J. & Curtis, J.T. (1957). An ordination of the upland forest communities of southern 
Wisconsin. Ecol. Monogr., 27, 325–349. 
9. 
Cardoso, P., Borges, P.A.V. & Veech, J.A. (2009). Testing the performance of beta diversity 
measures based on incidence data: the robustness to undersampling. Divers. Distrib., 
15, 1081–1090. 
10. 
Chao, A., Chazdon, R.L., Colwell, R.K. & Shen, T.J. (2006). Abundance(based similarity 
indices and their estimation when there are unseen species in samples. Biometrics 62, 
361–371.  
11. 
Chao, A., Chiu, C.(H. & Hsieh, T.C. (2012). Proposing a resolution to debates on diversity 
partitioning. Ecology, 93, 2037–2051. 
12. 
Clark, P.J. (1952). An extension of the coefficient of divergence for use with multiple 
characters. Copeia, 1952, 61–64. 
13. 
Clarke, K.R., Somerfield, P.J. & Chapman, M.G. (2006). On resemblance measures for 
ecological studies, including taxonomic dissimilarities and a zero(adjusted Bray–
Curtis coefficient for denuded assemblages. J. Exp. Mar. Biol. Ecol., 330, 55–80. 
14. 
Czekanowski, J. (1909). Zur Differentialdiagnose der Neandertalgruppe. Korrespondenz-Blatt 
deutsch. Ges. Anthropol. Ethnol. Urgesch., 40, 44–47.  
15. 
De Cáceres, M., Legendre, P., Valencia, R., Cao, M., Chang, L.(W., Chuyong, G. et al. 
(2012). The variation of tree beta diversity across a global network of forest plots. 
Global Ecology and Biogeography. DOI: 10.1111/j.1466(8238.2012.00770.x 
16. 
Dray, S., Pélissier, R., Couteron, P., Fortin, M.(J., Legendre, P., Peres(Neto, P.R. et al. 
(2012). Community ecology in the age of multivariate multiscale spatial analysis. 
Ecol. Monogr., 82, 257–275. 
17. 
Ellison, A.M. (2010). Partitioning diversity. Ecology, 91, 1962–1963. 
18. 
Faith, D.P., Minchin, P.R. & Belbin, L. (1987). Compositional dissimilarity as a robust 
measure of ecological distance. Vegetatio, 69, 57–68. 
19. 
Gower, J.C. (1966). Some distance properties of latent root and vector methods used in 
multivariate analysis. Biometrika, 53, 325–338. 
20. 
Gower, J.C. & Legendre, P. (1986). Metric and Euclidean properties of dissimilarity 
coefficients. J. Classif., 3, 5–48. 
21. 
Hajdu, L.J. (1981). Graphical comparison of resemblance measures in phytosociology. 
Vegetatio, 48, 47–59.  
22. 
Hubálek, Z. (1982). Coefficients of association and similarity, based on binary (presence(
absence) data: an evaluation. Biol. Rev., 57, 669–689. 
23. 
Hurlbert, S.H. (1984). Pseudoreplication and the design of ecological field experiments. Ecol. 
Monogr., 54, 187–211. 
24. 
Jaccard, P. (1900). Contribution au problème de l’immigration post(glaciaire de la flore 
alpine. Bull Soc. Vaudoise Sci. Nat., 36, 87–130. 
25. 
Janson, S. & Vegelius, J. (1981). Measures of ecological association. Oecologia, 49, 371–
376. 
26. 
Janssen, J.G.M. (1975). A simple clustering procedure for preliminary classification of very 
large sets of phytosociological relevés. Vegetatio, 30, 67–71.  
27. 
Jost, L. (2007). Partitioning diversity into independent alpha and beta components. Ecology, 
88, 2427–2439. 
28. 
Jost, L., Chao, A. & Chazdon, R.L. (2011). Compositional similarity and beta diversity. In: 
Biological diversity: frontiers in measurement and assessment [eds Magurran, A. & 
McGill, B.]. Oxford University Press, Oxford, England, pp. 66–84. 
29. 
Koleff, P., Gaston, K.J. & Lennon, J.J. (2003). Measuring beta diversity for presence(absence 
data. J. Anim. Ecol., 72, 367–382.  
30. 
Kraft, N.J.B., Comita, L.S., Chase, J.M., Sanders, N.J., Swenson, N.G., Crist, T.O. et al. 
(2011). Disentangling the drivers of diversity along latitudinal and elevational 
gradients. Science, 333, 1755–1758. 
31. 
Kulczynski, S. (1928). Die Pflanzenassoziationen der Pieninen. Bull. Int. Acad. Pol. Sci. Lett. 
Cl. Sci. Math. Nat. Ser. B, Suppl. II (1927), 57–203. 
32. 
Lance, G.N. & Willams, W.T. (1967). Mixed(data classificatory programs. I. Agglomerative 
systems. Aust. Comput. J., 1, 15–20. 
33. 
Lebart, L. & Fénelon, J.P. (1971). Statistique et informatique appliquées. Dunod, Paris, France.  
34. 
Legendre, P. (2005). Species associations: the Kendall coefficient of concordance revisited. J. 
Agr. Biol. Envir. S., 10, 226–245. 
35. 
Legendre, P. & Anderson, M.J. (1999). Distance(based redundancy analysis: testing 
multispecies responses in multifactorial ecological experiments. Ecol. Monogr., 69, 1–
24. 
36. 
Legendre, P., Borcard, D. & Peres(Neto, P.R. (2005). Analyzing beta diversity: partitioning 
the spatial variation of community composition data. Ecol. Monogr., 75, 435–450. 
37. 
Legendre, P. & Fortin, M.(J. (2010). Comparison of the Mantel test and alternative 
approaches for detecting complex multivariate relationships in the spatial analysis of 
genetic data. Mol. Ecol. Resour., 10, 831–844. 
38. 
Legendre, P. & Gallagher, E.D. (2001). Ecologically meaningful transformations for 
ordination of species data. Oecologia, 129, 271–280. 
39. 
Legendre, P. & Legendre, L. (2012). Numerical ecology. 3rd English edition. Elsevier 
Science BV, Amsterdam. 
40. 
Odum, E.P. (1950). Bird populations of the Highlands (North Carolina) Plateau in relation to 
plant succession and avian invasion. Ecology, 31, 587–605.  
41. 
Oksanen, J., Blanchet, F.G., Kindt, R., Legendre, P., Minchin, P.R., O’Hara, R.B. et al. 
(2012). vegan: Community ecology package. R package version 2.0-3. Available at: 
http://cran.r(project.org/web/packages/vegan/. 
42. 
Orlóci, L. (1967). An agglomerative method for classification of plant communities. J. Ecol., 
55, 193–206. 
43. 
Orlóci, L. (1978). Multivariate analysis in vegetation research. 2nd edition. Dr. W. Junk B. 
V., The Hague, The Netherlands. 
44. 
Pelissier, R., Couteron, P., Dray, S. & Sabatier, D. (2003). Consistency between ordination 
techniques and diversity measurements: two strategies for species occurrence data. 
Ecology, 84, 242–251. 
45. 
Peres(Neto, P.R., Legendre, P., Dray, S. & Borcard, D. (2006). Variation partitioning of 
species data matrices: estimation and comparison of fractions. Ecology, 87, 2614–
2625. 
46. 
Rao, C.R. (1982). Diversity and dissimilarity coefficients: a unified approach. Theor. Popul. 
Biol., 21, 24–43. 
47. 
Rao, C.R. (1995). A review of canonical coordinates and an alternative to correspondence 
analysis using Hellinger distance. Qüestiió (Quaderns d'Estadistica i Investivació 
Operativa), 19, 23–63. 
48. 
Ricotta, C. & Marignani, M. (2007). Computing Β(diversity with Rao's quadratic entropy: a 
change of perspective. Divers. Distrib., 13, 237–241. 
49. 
Simpson, G.G. (1943). Mammals and the nature of continents. Am. J. Sci., 241, 1–31.  
50. 
Stephenson, W., Williams, W.T. & Cook, S.D. (1972). Computer analyses of Petersen’s 
original data on bottom communities. Ecol. Monogr., 42, 387–415. 
51. 
Vellend, M. (2001). Do commonly used indices of beta(diversity measure species 
turnover? J. Veg. Sci., 12, 545–552.  
52. 
Verneaux, J. (1973). Cours d’eau de Franche(Comté (Massif du Jura). Recherches 
écologiques sur le réseau hydrographique du Doubs – Essai de biotypologie. Annales 
Scientifiques de l’Université de Franche-Comté, Biologie Animale, 3, 1–260. 
53. 
Wagner, H.H. (2003). Spatial covariance in plant communities: integrating ordination, 
variogram modeling, and variance testing. Ecology, 84, 1045–1057.  
54. 
Wagner, H.H. (2004). Direct multi(scale ordination with canonical correspondence analysis. 
Ecology, 85, 342–351.  
55. 
Whittaker, R.H. (1952). A study of summer foliage insect communities in the Great Smoky 
Mountains. Ecol. Monogr., 22, 1–44. 
56. 
Whittaker, R.H. (1960). Vegetation of the Siskiyou mountains, Oregon and California. Ecol. 
Monogr., 30, 279–338.  
57. 
Whittaker, R.H. (1972). Evolution and measurement of species diversity. Taxon, 21, 213–251. 
58. 
Wilson, M.V. & Shmida, A. (1984). Measuring beta diversity with presence(absence data. J. 
Ecol., 72, 1055–1064. 
59. 
Wishart, D. (1969). CLUSTAN 1a user manual. Computing Laboratory, University of St. 
 
Andrews, St. Andrews, Fife, Scotland. 
SUPPORTING INFORMATION 
Additional Supporting Information may be found in the online version of this article: 
Appendix S1   Details about property P8: Invariance to the number of species in each 
sampling unit. 
Appendix S2   Community composition data transformations. 
Appendix S3   The R function beta.div() computes estimates of total beta diversity as the 
total variance in a community data matrix Y, as well as the derived SCBD and LCBD 
statistics, for 17 dissimilarity coefficients or the raw data table. 

























 






