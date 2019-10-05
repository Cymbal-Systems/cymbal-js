# Contributing to Cymbals

*Note: These may change at any time. Please be sure to revisit before contributing in the future.*

## The Basics

Cymbals is a Single-Page Application using ReactJS to render a user interface for a photography management system. This system allows for importing and exporting of CSV files containing data pertaining to school and student profiles and purchases.

Pull Requests: Create'em at will. We'll try to keep the MVP project up to date and create detailed issues to help guide the way.

## Development

Cymbals uses webpack to run a development server while the initial development process is building its foundation. Please visit the MVP Project and 

### Testing

Cymbals is heavily tested and is primarily developed in a Test-Driven style. Coverage reports are to be generated and will be verified before approving pull requests. 

#### Mocha, Chai, & Sinon

Call us old school, call us out-dated, call us what you will. Mocha, Chai, and Sinon run this ship and most likely always will. 

The focus of the unit tests should be on _what_ is expected, and not the _how_. For example, if an array of students is expected, we wouldn't verify that it used `Array.sort()`, but rather test that the returned array is properly sorted. This practice reduces tests (which bloats test suits), and allows for refactoring without failing tests.

