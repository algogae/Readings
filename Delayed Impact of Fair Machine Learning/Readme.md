# Delayed Impact of Fair Machine Learning

## Abstract
Fairness in ML has been studied in static classification settings without concern of varying decision changes the underlying population over time. General belief on fairness criteria promote the well-being of the groups we aim to protect. There are bunch of known and studied fairness criteria, however by focusing on three criteria including unconstrained one, the belief can in fact frustrating. By completely characterizing the delayed impact of three standard criteria, we qualitatively explain the difference among them especially even in one-step feedback model. 

## 1. Introduction
From the lack of rigorous argument to the effect with respect to fairness criteria, we assume and formulate our problem setting. Running example is a hypothetical lending scenario in bank. There are two groups in the population with features described by a summary statistic, such as *credit score*, whose distribution differs between the groups. Impact of lending decision leads to either default event or successful lending. Former event leads to negative effect on both bank and borrower, while latter increases profit for the bank and credit score of the borrower that is desirable. 

Then, we come up with three specific criterias; *unconstrained*(`MaxUtil`), *equality in selection rate*(`DemParity`), and *equaility in opportunity*(`EqOpt`). Definitions are introduced in the later sections. Until then, let's get familiar with the basic building blocks of the settings. 
