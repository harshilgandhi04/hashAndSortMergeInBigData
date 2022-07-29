# Implementation of Hash Join and Sort Merge Join Algorithm for SPARQL Query Processing

The task is to implement two most popular join algorithms, namely Hash join and Sort-merge join
algorithms for a specific SPARQL query over an RDF dataset. The Waterloo SPARQL Diversity Test Suite
WatDiv dataset from University of Waterloo https://dsg.uwaterloo.ca/watdiv/ consists of diverse
RDF triple stores in different size. Based on two selected datasets from it, the SPARQL query of the form:
(?a)---follows--->(?b)---friendOf--->(?c)---likes--->(?d)---hasReview--->(?e)
is to be evaluated. In the query, (?a), (?b), (?c), (?d), (?e) are variables, and follows, friendOf,
likes, hasReview are properties. The answer of the query is the list of mapped values of all the variables
(?a), (?b), (?c), (?d), (?e).
The dataset consists of two triple WatDiv triple stores, one with the size of 100 thousand, and another
with 10 million triples
