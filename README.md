# Validic Coding Test
## Practical Problem

At Validic we help our customers by standarizing third party data.

The problem:

Please write an application that uses the [Github Jobs API](https://jobs.github.com/api) to help show jobs that are broken down by city and then by position type (full-time/part-time).  Please use Ruby, Java (or other JVM-based language) or Go.

The cities we care about are:

- Boston
- San Francisco
- Los Angeles
- Denver
- Boulder
- Chicago
- New York

Program guidelines:
- all work done in a git repository
- a readme with instructions on how to run the application
- a test suite

Ideal output:

```

Boston:
  - Python
    - full-time: 25%
    - part-time: 10%
    - unknown:  5%
  - Ruby:
    - full-time: 25%
    - part-time: 10%
    - unknown:  5%
San Francisco:
  - Node:
    - full-time: 25%
    - part-time: 10%
    - unknown:  5%
  - Scala:
    - full-time: 25%
    - part-time: 10%
    - unknown:  5%


Sourced: 1,123 job postings

```

That can be read as "In Boston, 25% of all current programming jobs are for Python and are full-time opportunities.".

The numbers above are made up but your program should be able to give us some indication of programming language trends across those cities.

### Please fork this repo.  Working from the 'backend' branch, please add your code and then perform a pull request.  Once we have your code, please remove your fork from public view or delete it entirely.
### Please include a ANSWERS.MD file in your repo that includes answers and thoughts to the following:
- challenges you ran into
- areas of the code you are most proud of
- areas of the code you are least proud of
- tradeoffs you were forced to make
- changes required to be production ready

This exercise should take you no more than 6 hours, if it does please just commit your work and send it over.
