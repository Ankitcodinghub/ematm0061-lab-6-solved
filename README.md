# ematm0061-lab-6-solved
**TO GET THIS SOLUTION VISIT:** [EMATM0061 Lab 6 Solved](https://www.ankitcodinghub.com/product/ematm0061-lab-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93045&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EMATM0061 Lab 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This document describes your sixth assignment for Statistical Computing and Empirical Methods (Unit EMATM0061) on the MSc in Data Science. Before starting the assignment it is recommend that you first watch video lectures 13 and 14.

Begin by creating an Rmarkdown document with html output. You are not expected to hand in this piece of work, but it is a good idea to get used to using Rmarkdown.

β&gt;1

1 A Gaussian model for Red tailed hawks

In this question we will fit a Gaussian model to a Red-Tailed hawk data set. First load the Hawks data set as follows:

Now use your data wrangling skills to filter extract a subset of the Hawks data set so that every Hawk belongs to the “Red-Tailed” species, and extract the “Weight”, “Tail” and “Wing” columns. The returned output should be a data frame called “RedTailedDf” with three numerical columns and 577 examples.

Display the first five rows of the “RedTailedDf”. The resulting subset of the data frame should look as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>library(Stat2Data)
data("Hawks")
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##
## 1
## 2
## 3
## 4   1090  230  412
## 5    960  212  370
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Weight Tail Wing
   920  219  385
   930  221  376
   990  235  381
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
We now model the vector of tail lengths from “RedTailedDf” as a sequence X1, · · · , Xn ∼ N 􏰅μ0, σ02􏰆 consisting of independent and identically distributed with unknown population mean μ0 and population variance σ02.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The maximum likelihood estimates for μ0 is given by μˆMLE = n1 􏰖ni=1 Xi and the maximum likelihood estimate for σ2 is given by σˆ2 = 1 􏰖n (X − μˆ )2.

</div>
</div>
<div class="layoutArea">
<div class="column">
0 MLE n i=1 i MLE

Apply the maximum likelihood method to compute estimates mˆuMLE for μ0 and σˆ2 for σ02.

</div>
</div>
<div class="layoutArea">
<div class="column">
MLE

Next generate a plot which compares the probability density function for your fitted Gaussian model for the tail length of the Red-Tailed hawks with a kernel density plot. Your plot should look as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
0.03

0.02

0.01

0.00

</div>
<div class="column">
Estimator

MLE density

Kernel density

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Tail length (mm)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
150 200 250

tail

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
2 Location estimators with Gaussian data

In this question we compare two estimators for the population mean μ0 in a Gaussian setting in which we have independent and identically distributed data X1, · · · , Xn ∼ N 􏰅μ0, σ02􏰆.

What is the population median of a Gaussian random variable Xi ∼ N 􏰅μ0, σ02􏰆?

The following code generates a data frame consisting which estimates the mean squared error of the sample

median as an estimator of μ0.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>set.seed(0)
num_trials_per_sample_size&lt;-100
min_sample_size&lt;-5
max_sample_size&lt;-1000
sample_size_inc&lt;-5
mu_0&lt;-1
sigma_0&lt;-3
</pre>
<pre>simulation_df&lt;-crossing(trial=seq(num_trials_per_sample_size),
                      sample_size=seq(min_sample_size,
</pre>
max_sample_size,sample_size_inc))%&gt;% # create data frame of all pairs of sample_size and trial

<pre>  mutate(simulation=pmap(.l=list(trial,sample_size),
                         .f=~rnorm(.y,mean=mu_0,sd=sigma_0)))%&gt;%
</pre>
<pre>  # simulate sequences of Gaussian random variables
</pre>
mutate(sample_md=map_dbl(.x=simulation,.f=median))%&gt;% # compute the sample medians

group_by(sample_size)%&gt;%

<pre>    summarise(msq_error_md=mean((sample_md-mu_0)ˆ2))
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Modify the above code to include estimates of the mean square error of the sample mean.

Generate a plot which includes both the mean square error of the sample mean and the sample median as a function of the sample size. Your plot might look something like the following:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
0.3

0.2

0.1

0.0

</div>
</div>
<div class="layoutArea">
<div class="column">
100 200 300

Sample size

</div>
<div class="column">
400 500

</div>
</div>
<div class="layoutArea">
<div class="column">
Estimator Mean

Median

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Mean square error

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
3 Unbiased estimation of the population variance

In this question we consider samples X1, · · · , Xn ∼ N 􏰅μ0, σ02􏰆 consisting of independent and identically dis- tributed with unknown population mean μ0 and unknown population variance σ02.

Let X be the sample mean, let VˆMLE := 1 􏰖n 􏰅Xi −X􏰆2 and let VˆU := 1 􏰖n 􏰅Xi −X􏰆2. n i=1 n−1 i=1

Conduct a simulation study which compares the bias of VˆMLE as an estimator of the population variance σ02 with the bias of VˆU as an estimator for the population variance σ02.

Is 􏰝VˆU = 􏰙 1 􏰖n 􏰅Xi − X􏰆2 an unbiased estimator for σ0? n−1 i=1

As an optional extra, give an analytic formula for the bias of VˆMLE and VˆU as estimators of σ02.

4 Maximum likelihood estimators for the Gaussian distribution

Suppose that X1, · · · , Xn ∼ N 􏰅μ0, σ02􏰆 are independent and identically distributed with unknown population mean μ0 and unknown population standard deviation σ0.

</div>
</div>
<div class="layoutArea">
<div class="column">
Given an expression for the likelihood function l(μ, σ2) based upon a sample X1, . . . , Xn. Derive a formula for the derivative of the log-likelihood ∂ log l(λ).

</div>
</div>
<div class="layoutArea">
<div class="column">
∂λ

Show that X := n1 􏰖i=1 Xi is the maximum likelihood estimator for μ0 and S2 := n1 􏰖i=1(Xi − X)2 is the

</div>
</div>
<div class="layoutArea">
<div class="column">
maximum likelihood estimator for σ02.

What is the maximum likelihood estimator for σ0?

5 Maximum likelihood estimation with the Poisson distribution

In this question we shall consider the topic of maximum likelihood estimation for a an independent and identically distributed sample from a Poisson random variable. Recall that Poisson random variables are a family of discrete random variables with distributions supported on N0 := {0, 1, 2, 3, · · · }. Poisson random variables are frequently used to model the number of events which occur at a constant rate in situations where the occurrence of individual events are independent. For example, we might use the Poisson distribution to model the number of mutations of a given strand of DNA per time unit, or the number of customers who arrive at store over the course of a day. A classic example of statistical modelling based on a Poisson distribution is due to the statistician Ladislaus Josephovich Bortkiewicz. Bortkiewicz used the the Poisson distribution to model the number of fatalities due to horse-kick per year for each group of cavalary. We shall apply maximum likelihood estimation to Bortkiewicz’s data. First let’s explore maximum likelihood estimation for Poisson random variables.

A Poisson random variable has a probability mass function pλ : R → (0, ∞) with a single parameter λ &gt; 0. The probability mass function pλ : R → (0, ∞) is defined for x ∈ R by

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰕λxe−λ for x ∈ N0

</div>
</div>
<div class="layoutArea">
<div class="column">
pλ(x) = x! 0

</div>
</div>
<div class="layoutArea">
<div class="column">
for x ∈/ N0.

Suppose that you have a sample of independent and identically distributed random variables X1, . . . , Xn ∼ pλ0

i.e. X1, . . . , Xn are independent and each has probability mass function pλ0 . 4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Show that for a sample X1, . . . , Xn, the likelihood function l : (0, ∞) → (0, ∞) is given by 􏰚n1􏰛

</div>
</div>
<div class="layoutArea">
<div class="column">
l(λ):=e−n·λ ·λn·X · 􏰟 , i=1 Xi!

</div>
</div>
<div class="layoutArea">
<div class="column">
where X = n1 􏰖ni=1 Xi is the sample mean.

Derive a formula for the derivative of the log-likelihood ∂ log l(λ).

∂λ

Show that λ 􏰞→ log l(λ) reaches its maximum at the single point at which λ = X. Hence, the maximum likelihood estimate for the true parameter λ0 is λˆMLE.

Now conduct a simulation experiment which explores the behavior of λˆMLE on simulated data. You may wish to consider a setting in which λ0 = 0.5 and generate a plot of the mean squared error as a function of the sample size.

Now that we have explored maximum likelihood estimation with a Poisson distribution for simulated data we shall return to Poission modelling with real data. Let’s take a look at the famous horse-kick fatality data set explored by Ladislaus Josephovich Bortkiewicz. A csv file containing this data is available within Blackboard.

Download the csv file and load the file into an R data frame. You may wish to use the read.csv() function.

The count data for horse fatalities per year, per cavalary corps are given in the “fatalities” column. Model the values in this column as independent random variables X1,…,Xn from a Poisson distribution with parameter λ0 and compute the maximum likelihood estimate λˆMLE for λ0.

Use your fitted Poisson model to give an estimate for the probability that a single cavalry corps has no fatalities due to horse kicks in a single year. You may want to use the dpois function.

􏰃 ∂2 􏰄

As an optional extra give a formula for I(λ) := −E ∂λ2 log l(λ) . Next generate a simulation involving random

samples of size 1000 from a Poisson random variable with parameter λ0 = 0.5. Give a kernel density plot of 􏰝n·I(λ )􏰃λˆ −λ 􏰄.

</div>
</div>
<div class="layoutArea">
<div class="column">
0 MLE 0

</div>
</div>
<div class="layoutArea">
<div class="column">
6 Maximum likelihood estimation for the exponential distribution

Recall from Assignment 5 that given a positive real number λ &gt; 0, an exponential random variable X with parameter λ is a continuous random variable with density pλ : R → (0, ∞) defined by

􏰕0 if x &lt; 0 pλ(x) := λe−λx if x ≥ 0.

Suppose that X1, · · · , Xn is an i.i.d sample from the exponential distribution with an unknown parameter λ0 &gt; 0. What is the maximum likelihood estimate for λ0?

We shall now use the exponential distribution to model the differences in purchase times between customers at a large supermarket. In Blackboard you will find the “CustomerPurchase” csv file.

Download the “CustomerPurchase” csv file and load the file into an R data frame. You may wish to use the read.csv() function. The first column is the purchase time given in seconds since the store opens.

Add a new column in your data frame called “time_diffs” which gives the time in seconds until the next customer’s purchase. That is, letting Y1, Y2, . . . , Yn+1 denote the sequence of arrival times in seconds, the time_diffs

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
column contiains X1,…,Xn where Xi = Yi+1 − Yi for each i = 1,…,n. You may want to use the lead() function.

Model the sequence of differences in purchase times X1, . . . , Xn as independent and identically distributed expo- nential random variables. Compute the maximum likelihood estimate of the rate parameter λˆMLE.

Use your fitted exponential model to give an estimate of the probability of an arrival time in excess of one minute. You may wish to make use of the pexp() function.

7 (**) MLE for the capture and recapture model

As an optional extra we return to the capture and recapture model discussed in lecture 9.

Recall that in this example there are n0 squirrels living on an island. A conservationist captures t squirrels at random before tagging and releasing them. A week later, the conservationist captures k squirrels at random again, and counts how many have already been tagged. For simplicity we assume that the population of n squirrels is constant over the time period, and on both occasions the squirrels are selected purely at random.

We let Z be the random variable corresponding to the number of recaptured squirrels.

</div>
</div>
<div class="layoutArea">
<div class="column">
k−q (n0 )

l(n) =

for all n ∈ N. Give a formula for the maximum likelihood estimate nˆMLE of n0.

</div>
</div>
<div class="layoutArea">
<div class="column">
Inlecture9weshowedthatforq≤min{t,k}wehaveP(Z=q)= q Hence, the likelihood function l : N → [0, 1] is given by

</div>
<div class="column">
andP(Z=q)=0forq&gt;min{t,k}.

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰅t􏰆·􏰅n−t􏰆 Z k−Z

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰅n􏰆 , k

</div>
</div>
<div class="layoutArea">
<div class="column">
(t)·(n0−t)

</div>
</div>
<div class="layoutArea">
<div class="column">
k

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
