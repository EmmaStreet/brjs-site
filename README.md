# BladeRunnerJS Website and Documentation

## Website

The website is a simple [Jekyll](http://jekyllrb.com/) site.

### Prerequisites

The instructions assume that Ruby is installed and on your [PATH](http://en.wikipedia.org/wiki/PATH_\(variable\)). See the [ruby-lang.org downloads section](https://www.ruby-lang.org/en/downloads/) for more information.

### Running the website

To run the website locally:

    git clone git@github.com:BladeRunnerJS/brjs-site.git
    cd brjs-site
    gem install jekyll
    jekyll serve -w
    
Navigate to `localhost:4000` to see the site running.

## Docs

### Structure

The documentation is broken up into 3 high-level sections:

1. Concepts - overview of core concepts within BRJS
2. Use - documentation about using BRJS to build an application
3. Extend - docs on extending the BRJS toolkit functionality e.g. creating plugins

#### Concepts

The purpose of the concepts section is to provide enough basic detail for somebody to answer the following questions:

* What is it?
* Why would I need it?
* How do I use it?

The contents of the *How do I use it?* part shouldn't go into too much detail. Ideally, it should provide a brief example and then send the reader to the appropriate User Guide or Tutorial.

### Contribution

Because the documentation is open source we hope it's easy to submit improvements and fixes to them using pull requests. However, if you see a mistake and either can't fix it, or don't have time to, please [raise an issue](https://github.com/bladerunnerjs/brjs/issues).
