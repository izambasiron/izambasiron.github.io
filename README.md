# Random Number Simulation
A simple simulation of the proposed random number generation to examine how many tries it takes to complete the list.

## Parameters
- **Data** is the list of registered companies for balloting.
- **Step** is the gap between the next number to pick.
- **Multiplier** is the number of subsequent companies to pick. 

## Requirements
There are no special requirements to run, other than your browser. Simply run the `index.html` file in your browser.

### Development
For compiling the `index.haml` file, you will need ruby, bundler, sass and haml installed.
```bash
$ bundle install
$ haml src/index.haml > index.html
```
For managing JavaScript libraries, you need node, and bower set up. 
```bash
$ bower install
```
