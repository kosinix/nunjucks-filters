# Nunjucks Filters

Useful and reusable nunjucks filters.


## Install

Install latest from GitHub:

    npm install github:kosinix/nunjucks-filters

Tied to a specific version/release from GitHub:

    npm install github:kosinix/nunjucks-filters#1.0.0


## Usage:
    const nunjucksFilters = require('nunjucks-filters');
    
    // env comes from calling - new nunjucks.Environment(...);

    // Add filters to nunjucks environment var
    nunjucksFilters.extend(env)