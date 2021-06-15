---
layout: tutorial
title: "Gaussian Mixture Models"
complexity: 17
pdf: "/assets/tutorials/gmm14.pdf"
---
Gaussian Mixture Models (GMMs) are among the most statistically mature methods for clustering (though they are also used intensively for density estimation). In this tutorial, we introduce the concept of clustering, and see how one form of clustering...in which we assume that individual datapoints are generated by first choosing one of a set of multivariate Gaussians and then sampling from them...can be a well-defined computational operation. We then see how to learn such a thing from data, and we discover that an optimization approach not used in any of the previous Andrew Tutorials can help considerably here. This optimization method is called Expectation Maximization (EM). We'll spend some time giving a few high level explanations and demonstrations of EM, which turns out to be valuable for many other algorithms beyond Gaussian Mixture Models (we'll meet EM again in the later Andrew Tutorial on Hidden Markov Models). The wild'n'crazy algebra mentioned in the text can be found (hand-written) <a href="/resources/tutorials/gaussian-mixture-models/gmm-algebra.pdf">here</a>.