The question of the use of hedonic regression in the calculation of relativity is, I suspect, not breakfast table conversation for some of our readers even if it would appear that in the bars of Chelsea [they talk of nothing else](http://archive.spectator.co.uk/article/16th-june-1979/5/notebook). The Upper Tribunal's decision in Re: 47 Phillimore Gardens ([available](http://www.landstribunal.gov.uk/Aspx/view.aspx?id=1061) on the Upper Tribunal website) is all about exactly that topic and I think it is an important one. I will therefore try to unpack with my apologies to those readers for whom most of this is obvious.

The starting point is a house, 47 Phillimore Gardens. The appellants own a leasehold with 52.45 years left. They would like to own the freehold, which is owned by the respondent. The Leasehold Reform Act 1967 gives them a right to do so, by a process known as "enfranchisement", provided they pay some compensation to the freeholder in return.

It would be an understatement to say that the 1967 Act has been "hacked about a bit" and here is not the place to discuss how exactly the compensation is calculated, except that it includes an element known poetically as the "marriage value". The value of the house after merging the leasehold and freeholds is likely to be worth more than the sum of the value of each one individually and this extra value is known as the "marriage value". In the case of 47 Phillimore Gardens, the tenant would have to include half the marriage value in the compensation paid to the freeholder (see [section 9(1D)](http://www.legislation.gov.uk/ukpga/1967/88/section/9#section-9-1D)).

The conventional approach - and the one agreed by the parties before the Upper Tribunal - is to start with the value of the freehold with vacant possession and then work out what proportion of that value a leasehold of the length remaining at the time of valuation (i.e. in this case 52.45 years) would be. One would expect a very long lease to be worth almost as much as a freehold and a very short lease to be worth much less. This proportion is known as the "relativity" (alas nothing to do with Einstein).

For example in this case the appellants argued for a relativity of 87.04% and the respondents for 75.5%. Their positions are that way around because the appellants want to say that the leasehold is almost as valuable as the freehold and therefore having the freehold *as well* isn't really worth all that much more, in other words a high relativity leads to a low marriage value and less to pay to the freeholder in compensation. The freeholder wants to argue exactly the other way.

The 1967 Act throws in an extra complexity in the form of [section 9(1A)](http://www.legislation.gov.uk/ukpga/1967/88/section/9#section-9-1A) which says that the price payable:

> ... shall be the amount which at the relevant time the house and premises, if sold in the open market by a willing seller, might be expected to realise on the following assumptions ...
> (a) ... on the assumption that this Part of this Act conferred no right to acquire the freehold; or an extended lease

In other words, our valuation exercise has to imagine a situation where (contrary to the facts) the leaseholder has no right to enfranchise. 

Note that, for the purposes of the hearing, the Upper Tribunal assumed that the imaginary situation in 9(1A) is one where the leaseholder in question has no right to enfranchise but other leaseholders would do. This means that we assume that for some reason the 1967 Act does not apply to the property in question but that otherwise it applies normally. The appellant had thought of challenging that position but eventually conceded the point. 

The Upper Tribunal thought that was right and provisionally indicated that only the leaseholder trying to enfranchise is to be assumed not to have a right to do so. This means that the commonly used phrase "no Act world" for the imaginary situation is rather misleading.

The problem with imaginary worlds is that they are: imaginary. How does one work out what the relative value of a leasehold against a freehold would be in a world that doesn't exist? There are some leasehold properties for which there is (for various reasons) no right to enfranchise but sales of such properties are unusual and very difficult to compare with those of a normal leasehold property. We are left with inferring the relativity value somehow.

Enter Dr Philippe Bracke, a research economist. He had done extensive research using a technique known as "hedonic regression" to try to work out a graph of relativity values (plotted against length of lease).

Hedonic regression (not as exciting as it sounds) is a technique for working out the value of something for which there is no market. Suppose we want to work out the value of a house, we proceed very roughly as follows: first consider the kinds of thing that make a house valuable, eg number of rooms, size, number of bathrooms or state of repair. We would hope that there would be some mathematical function (call it the "price function") that took as input each of these factors and spat out at the end the value (or at least the likely average value) of a house with those properties.

Now if we take a large number of house sales of known value and for which we know the properties (such as number of rooms) we are using as input, then we try, using statistical techniques, to work out the price function. A family of such techniques are known, collectively, as "regression analysis". Hence "hedonic regression". 

In simple terms what the statistician is doing is trying to work out (1) how much each aspect of a house is "worth" on its own and (2) how much that contributes to the total value of the house when combined with other properties of the house. Having done that it should be simple enough to work out the value of another house with known properties because one simply combines them using (1) and (2) above. The "hedonic" (from a Greek word meaning delight or pleasure) comes because we are essentially trying to work out how much an extra storey/room/bathroom etc would "delight" a purchaser.

At this point you are permitted to be sceptical. What if there are significant aspects of a house that aren't included? What if the sample of house sales selected is skewed in some way? What if one property of a house if correlated with another - for example the number of storeys in a house may be correlated with whether the house is in a town or not - so as to skew the results. You can be sure that the respondent took many points on these lines.

But these kinds of objection are inevitable in any attempt to model the real world. Models are always simplifications. It is easy enough to pick holes in an analysis but what matters in the end is, how good is the model?

Dr Bracke's idea was to use a considerable body of data about leasehold sales from 1987 to 1991. At that time there was no right to enfranchise or extend the leases of leasehold flats (those rights came into force in 1993 with the passage of the [Leasehold Reform, Housing and Urban Development Act 1993](http://www.legislation.gov.uk/ukpga/1993/28/contents)) so there were plenty of unenfranchiseable leaseholds on sale. It was this data set that was used for the hedonic regression discussed above.

Both parties called academics as experts on Dr Bracke's methods. Both were professors at the University of Cambridge but in different departments so that the argument might be characterised as Economics v Land Economy. The result of that clash, and the Upper Tribunals' analysis, was that, in principle, Dr Bracke's technique was sound. There were however a number of serious problems with it.

One that seemed significant to me was that in order to produce a graph of relativity, Dr Bracke had to fit a line to a number of points. His data source was particularly rich in leaseholds of 55-65 years and 85-100 years, so 52.45 years required an extrapolation off the bottom end.

Now fitting a line to a set of points can be done "by eye" (just drawing a line that looks like it fits well) but this is clearly a highly subjective exercise and could result in rather different answers depending on the line drawn. 

It seems to me that Dr Bracke did not do much better than that. He used what is known as a polynomial to fit to the graph. Polynomials are generalisations of quadratics with higher powers of x. 

For the non-mathematician, they are essentially wiggly lines with the ends going off either indefinitely upwards or downwards. Obviously the more wiggles you put in, the closer fit you get because your line can wiggle between the points it wants to get close to. The disadvantage is that polynomials go a bit haywire at the end - either rising much faster than the rest of the curve, or falling much faster - and the more wiggles there are the more unnatural the curve can look. 

Dr Bracke used a curve with three wiggles in it (a "fourth-order polynomial curve"). But he could as easily have used one with more or fewer wiggles or for that matter have used something other than a polynomial. The resulting graph did some odd things - for example predicting that in some circumstances a freehold would be worth less than a leasehold or that 80 years and 50 years are worth roughly the same.

The Upper Tribunal's conclusion that this, along with numerous other more minor points, meant that Dr Bracke's relativity curve did give some qualitative information about the shape of relativity in the period 1987 - 1991, but that it was not much use quantitatively.

Despite this the Upper Tribunal thought that, on balance of probabilities, Dr Bracke's curve was not useful for modern relativity values. Things were very different then, for example interest rates meant people's attitude to investment was quite unlike it is now. There was no evidence that Dr Bracke's results could be carried forward to the present day.

Now this is important. It means that although Dr Bracke and hedonic regression failed to work in this case, if there were better (or indeed any) evidence that his results could be applied to today's relativity, things might be different. My impression is that the Upper Tribunal is open to considering a similar approach with the appropriate additional evidence. 

There are lots of very sensible and detailed criticisms of Dr Bracke's work which are well worth reading in the judgment that I haven't repeated here. But the other interesting thing about the decision is, what are the alternatives?

Suppose we don't use hedonic regression, what else can we do to work out relativity? We might:

* examine comparables and try to infer relativities from them - something that the respondent accepted was impossible in the present case and is likely to be difficult in general
* look at the value of settlements between leaseholder and freeholder - but this is problematic because of the "Delaforce effect" (the freeholder knows it will be cheaper for the leaseholder not to go via a tribunal process and hence includes some of that discount in the price)
* look at tribunal decisions - even more problematic because only a skewed sample come to tribunal.

In fact what almost everyone does is to look at a set of graphs "published" by RICS. The scare quotes are intentional. RICS does not endorse them, but merely publishes them for information. The Upper Tribunal noted that there are numerous problems with these graphs which include: some are based on very little data, some are based on old evidence (as old as Dr Bracke's) and often not updated, their methodology is often unclear, some are based on settlement rather than sales data and so on.

In my view it is likely that if we knew more about the way the graphs were prepared we could pick as many holes in them as we might in Dr Bracke's work. 

Despite this, the appellants offered an, in my view, rather cheeky argument in favour of the RICS graphs. The section 9(1A) hypothetical purchaser will, at least in prime central London (which is where 47 Phillimore Gardens is located), consult an expensive adviser who will almost certainly make use of the RICS graphs in deciding what to pay. 

In other words: even if the graphs are based on a wholly unreliable methodology, they are right because people will use them in deciding what relativity to use. In that sense they become predictive because they set the expectations they are purporting to predict. 

This sort of circularity is not unknown to the law but it seems to me a rather odd position for us to be in. One of the reasons the Upper Tribunal ended up there was that no valuation evidence whatsoever was put before them. Another application with valuation evidence might go a different way. Furthermore, if a new methodology (eg hedonic regression) becomes popular for some reason then exactly the same argument could be used for it and against the RICS graphs.

