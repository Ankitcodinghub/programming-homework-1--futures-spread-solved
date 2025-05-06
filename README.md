# programming-homework-1--futures-spread-solved
**TO GET THIS SOLUTION VISIT:** [Programming Homework 1- Futures Spread Solved](https://www.ankitcodinghub.com/product/programming-homework-1-futures-spread-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97952&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming Homework 1- Futures Spread Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Futures Spread Dynamics

Here we will practice obtaining data for spreads in futures markets, and characterizing their dynamics.

2 Data

Obtain second month quarterly 1 futures prices from the Quandl OWF database for two pair W, X; Y, Z (where W, X and Y and Z depend on your student ID number) for 3 Dec 2019 though 31 Aug 2021. Our defi- nition of second month is the contact where the number of days to futures expiration is the smallest available value greater than 302.

Form the spreads s(1), s(2) between these numbers as the difference s(1) = ttt

X − W and s(2) = Z − Y . ttttt

3 Analysis

Characterize the relative dynamics of s(i) in reasonable ways, using charts t

and statistics.

For example, compute the median and standard deviation of the difference

d(N) between s(i) and an N-day rolling average of s for some values of N. ttt

1Quarterly in this context means expiring in March, June, September, or December.

2In other words, for each date in the analysis date range, you have to grab all available futures contracts for that date. Then choose the one with lowest time to expiration so long as it is over 30 days. Note the OWF data set is not entirely fit for purpose and will sometimes be missing data for a futures contract just because the options have expired.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Examine more quantiles than just the median. Look at tails. Do the spreads correlate? How about their difference (d) values? Do spreads exhibit patterns over time?

3.1 Data

Futures pairs W, X; Y, Z (in order) are as given by the last two distinct digits3 of your student number as follows:

0. ICE B B ICE G G 0.1342281879194631 (1/7.45) 1. ICE B B ICE G G 0.1342281879194631 (1/7.45) 2. ICEBBICETT

3. ICE T T ICE G G 0.1342281879194631 (1/7.45) 4. CBTFVFVCBTTUTU

5. CBTFVFVCBTTYTY

6. CBTFVFVCBTUSUS

7. CBTTUTUCBTTYTY

8. CBTTUTUCBTUSUS

9. NYM RB RB ICE G G 0.003198489678291494 (100 /118.35 / 264.172)

The final number, where present, is a multiplier you should apply to X or Z before computing the spreads s.

When downloading from Quandl, you have to use the years and the quar- terly codes (H, M, U, Z) individually, there is no facility for Quandl to com- bine them itself.

Examples of st on various dates that you should be matching in your own data are as follows:

0. ICEBBICEGG

• 2021-02-08 6.606510

3So, if your student ID ends in 6222 then use 6 and 2. 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
• 2021-02-09 6.719866 1. ICEBBICETT

• 2021-01-19 -2.54 • 2021-01-20 -2.86

2. ICETTICEGG

• 2021-01-19 8.966309

• 2021-01-20 9.279866

3. CBTFVFVCBTTUTU

• 2021-02-18 -15.000000 • 2021-02-19 -14.496875

4. CBTFVFVCBTTYTY • 2021-02-18 10.382812

• 2021-02-19 9.375000

5. CBTFVFVCBTUSUS

• 2021-02-18 39.023438 • 2021-02-19 36.593750

6. CBTTUTUCBTTYTY • 2021-02-18 25.382812

• 2021-02-19 23.871875

7. CBTTUTUCBTUSUS

• 2021-02-18 54.023438 • 2021-02-19 51.090625

8. NYM RB RB ICE G G 0.003198489678291494 (100 /118.35 / 264.172)

</div>
</div>
<div class="layoutArea">
<div class="column">
• 2021-01-26 -0.124285 • 2021-01-27 -0.200692

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
