Jasmine is a behavior-driven development framework for testing your JavaScript code \[Jasmine\].

This is an IntelliJ IDEA Live Template for the Jasmine JavaScript BDD Framework and Jasmine JQuery extention.

# About

This is are IntelliJ IDEA Live Templates for working with the Jasmine Framework. It contains two files. These files work with any JavaScript file as specified in the File Types.

##Jasmine.xml
This is the main template for the Jasmine Framework

##Jasmine_jquery.xml
This is the additional template for working with the Jasmine jquery extention. 

# Commands
The commands are delemited by <tab>. Hitting <tab> goes to the next $VALn$ where n is the number of tab presses until $END$ is reached. For instance typing in typing in ec<tab> will put you at $VAL0$ in `expect($VAL0$).toContain($VAL1$);$END$`. Hitting <tab> again will take you to $VAL1$ hitting <tab> one last time will take you to the $END$ from here tab becomes a tab character. 

## Jasmine Commands
### aft 
After each
`afterEach(function () {
	$END$
});`

### any 
any
`jasmine.jasmine.any($VAL0$);$END$`

### bef 
before each
`beforeEach(function () {
    $END$    
});`

### des 
describe jasmine
`describe("$VAL0$", function () {
    $END$
});`

### ec
expect to contain
`expect($VAL0$).toContain($VAL1$);$END$`

### ed
expect to be defined
`expect($VAL0$).toBeDefined();$END$`

### ee
expect to equal
`expect($VAL0$).toEqual($VAL1$);$END$`

### ef
expect to match
`expect($VAL0$).toBeFalsy();$END$`

### en
expect to be null
`expect($VAL0$).toBeNull();$END$`

### esc
expect was called
`expect($VAL0$).wasCalled();$END$`

### escw
expect was called with
`expect($VAL0$).wasCalledWith($VAL1$);$END$`

### et
expect to be truthy
`expect($VAL0$).toBeTruthy();$END$`

### ex
expect
`expect($VAL0$)$END$;`

### it
it
`it("$VAL0$", function () {
    $END$
});`

### notc
expect not to contain
`expect($VAL0$).not.toContain($VAL1$);$END$`

### notd
expect not to be defined
`expect($VAL0$).not.toBeDefined();$END$`

### note
expect not to equal
`expect($VAL0$).not.toEqual($VAL1$);$END$`

### notf
expect not to be falsy
`expect($VAL0$).not.toBeFalsy();$END$`

### notm
expect not to match
`expect($VAL0$).not.toMatch($VAL1$);$END$`

### notn
expect not to be null
`expect($VAL0$).not.toBeNull();$END$`

### notsc
expect was not called
`expect($VAL0$).wasNotCalled();$END$`

### notscw
expect was not called with
`expect($VAL0$).wasNotCalledWith($VAL1$);$END$`

### nott
expect not to be truthy
`expect($VAL0$).not.toBeTruthy();$END$`

### notx
expect not
`expect($VAL0$).not$END$;`

### runs
runs
`runs(function () {
    $END$
});`

### s
spy on
`spyOn($VAL0$, "$VAL1$")$END$;`

### scf
spy on and call fake
`spyOn($VAL0$, "$VAL1$").andCallFake($VAL2$);$END$`

### sct
spy on and call through
`spyOn($VAL0$, "$VAL1$").andCallThrough();$END$`

### sr
spy on and return
`spyOn($VAL0$, "$VAL1$").andReturn($VAL2$);$END$`

### st
spy on and throw
`spyOn($VAL0$, "$VAL1$").andThrow($VAL2$);$END$`

### wa
waits
`waits($VAL0$);$END$`

## Jasmine-Jquery

### eb
expect to be
`expect($VAL0$).toBe($VAL1$);$END$`

### ebc
expect to be checked
`expect($VAL0$).toBeChecked();$END$`

### lf
load fixutre
`loadFixtures($VAL0$);$END$`

### rf
read fixture
`readFixture($VAL0$);$END$`

### sf
set fixture
`setFixture($VAL0$);$END$`



# More

 * \[1\][Jasmine](http://github.com/pivotal/jasmine)
 * \[2\][Jasmine Text Mate bundle](https://github.com/pivotal/jasmine-tmbundle)
 * \[3\][Jasmine JQuery](https://github.com/velesin/jasmine-jquery)


# Live Template Installation
## Mac OS X
Copy the xml file to "~/Library/Preferences/IntelliJIdea11/templates/"

