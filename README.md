Was getting help from the question center and the mentor told me to submit this problem. Thanks!

# Intro-to-Functions-Lab-problem
origin  git@github.com:lorenzocovarrubiasjr/javascript-intro-to-functions-lab-bootcamp-prep-000.git (fetch)   origin  git@github.com:lorenzocovarrubiasjr/javascript-intro-to-functions-lab-bootcamp-prep-000.git (push) 


/*Problem #5 */
function sayHiToGrandma(string) {
  var lowercase = string.toLowerCase
  string = lowercase
  return "I can't hear you!";

  var uppercase = string.toUpperCase
  string = uppercase
  return "YES INDEED!";

  string = "I love you, Grandma."
  return "I love you, too."
}


/* Learn IDE Response */
5 passing (780ms)                                                                                          
  2 failing                                                                                                  
                                                                                                             
  1) sayHiToGrandma(string) returns "YES INDEED!" if `string` is uppercase:                                  
                                                                                                             
      Error: Expected 'I can\'t hear you!' to equal 'YES INDEED!'                                            
      + expected - actual                                                                                    
                                                                                                             
      -I can't hear you!                                                                                     
      +YES INDEED!                                                                                           
                                                                                                             
      at assert (node_modules/expect/lib/assert.js:29:9)                                                     
      at Expectation.toEqual (node_modules/expect/lib/Expectation.js:81:30)                                  
      at Context.<anonymous> (test/index-test.js:44:37)

 2) sayHiToGrandma(string) returns "I love you, too." if `string` is "I love you, Grandma."`:               
                                                                                                             
      Error: Expected 'I can\'t hear you!' to equal 'I love you, too.'                                       
      + expected - actual                                                                                    
                                                                                                             
      -I can't hear you!                                                                                     
      +I love you, too.     
      
       at assert (node_modules/expect/lib/assert.js:29:9)                                                     
      at Expectation.toEqual (node_modules/expect/lib/Expectation.js:81:30)                                  
      at Context.<anonymous> (test/index-test.js:48:52) 
                          
