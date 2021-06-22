# Codewars

[Codewars](https://www.codewars.com) is a site that has thousands of programming problems you can use to practice what you’ve learned in class.

On Codewars these problems are called Kata. A Kata is a little workout. Solving lots of kata gives you lots of practice in:

* writing JavaScript 💻
* breaking down problems 🧩
* recognising common questions 🕵️‍♀️
* building up your JavaScript muscles 💪

## Setup Codewars

### 1. Sign Up

To sign up to Codewars visit this link and complete their simple tutorial

[https://www.codewars.com/join](https://www.codewars.com/join)

### 2. Setup Account

After you've signed in you'll want to go to "Account Settings" at the top right of the screen. 

![](../../.gitbook/assets/image%20%282%29.png)

### 3. Join Our Clan

Codewars Clans are teams so that we can track how many challenges we've completed compared to other people. It also helps us share our solutions when we've completed them. 

To join the CodeYourFuture clan you should enter "CodeYourFuture" as you see in the screenshot below

![](../../.gitbook/assets/image%20%283%29.png)

Make sure you scroll to the bottom of the page and click "Update" to save.

### 4. Join the Slack Channel

We've got a community of other CYF Trainees also working on Codewars exercises. You can find them at

[\#cyf-codewars](https://codeyourfuture.slack.com/archives/C019GDCRA2J) on Slack

Join the channel now!

## CodeYourFuture Collections

We’ve made collections of kata and synced them to the Syllabus. 

Here are the CYF collections:

[https://www.codewars.com/users/CodeYourFuture/authored\_collections](https://www.codewars.com/users/CodeYourFuture/authored_collections)

To edit these collections please speak to your City Coordinator, Syllabus Team or Education Director.

![](https://lh5.googleusercontent.com/gXMA6mT6aUjcJ1Ma6sQZOOWjAT9yVbq1woKfqr8gIBa5FQ1IqovN-zqbYeuOuCy_4iKue7ldwB57fbL7V-vjRw6S4BDgx2ZjZaBAg1dU2UBcYbynT4vLYkP3WaLTDfK3mm-GsU57)

## How To Use Kata

First, click this [link to view all of the CodeYourFuture collections.](https://www.codewars.com/users/CodeYourFuture/authored_collections)

Choose a collection by clicking the title. You will see the collection view. If you click the green button marked ‘Train Now’, you’ll cycle through all the kata in this collection. Or you can go right to one you find interesting by clicking the title.

The first thing you’ll see is the details page - it will describe the problem. Sometimes these descriptions are very clear, but more often you will have to figure out what the kata wants by progressively working through with tests. **And that’s what we want you to do**. 

You can read the description before you go into the kata to decide if you want to attempt it. 

### **1. Read the description**

![](https://lh5.googleusercontent.com/3MLG8PLGw5MB6COJUEQ5eAOpIEV-4pS62EHduDP89kUqLOVsx5YIftBC6k7-lGrDJlkfkoJAE3euTDSHz2zY7snlYI3SJY32hwURKAaLMNyZK2r-wbkt9QA1rtTT9wwuzbjcw7kF)

Okay, so this one wants us to calculate the number of milliseconds given in hours, minutes and seconds.

What else does this kata description give us? They don’t all give you the same things, but here are some common clues you might get.

![Input constraints](https://lh4.googleusercontent.com/NesGsI-ZBB67N8XHU24U3VdHaRdHItCbfDPY1xNdGTYbCvQg1mFUHp_aauzdXnJV1HI_7r_zUODgSP8-gCdtNfyimReqeaSaoI5_Uqy6d5WlcIHw9juJ0JTIurt0Xvhyo9kDmXh6)

**Input constraints / limits of each value** 

 They are saying that there aren’t 61 minutes, or 135 minutes in an hour, or a million hours in a day. We don’t need to handle those kinds of values in this kata. We can be sure it’s always going to follow the rules of the 24 hour clock.

![A test case shows inputs and expected result](https://lh6.googleusercontent.com/re-3U15uquZk65F_QliOIqG0PAIG6WDBu_rE-YF5IoZinTfcjVRBaOv6zthK6qvnJ_IJaETvcOE8lxl0Sgk5C-8RF9mNYxII__pjNeUUwGyKJe4MSJgkUk0KbDphhv1urWt7EaCr)

And here it gives us a test case -- here are inputs \(**h**, **m**, **s**\) and outputs \(**result**\) given. Let’s go into the kata by hitting Train.

### **2. Read the tests**

And  look, we can see the same values over here, in the tests panel. 

![](https://lh3.googleusercontent.com/eExx2-au1LgE43ntkF3OUVU0S_olXLZWcsdRv0KAcbNChgIZohehGKOJTP-My-YfeZ20U6h5jpkP3a2ISZdLyjSzioN5rbebl7xOQHaUhfYUs3joT38DWSoPpDWVR0PZLKf4ngCO)

The tests are showing inputs on the left and the expected output on the right. It’s saying the return value of the function past\(\), when given those inputs, must be equal to the value given after the comma.

The function **past\(0,1,1\)** must return the value **61000** for the test to pass.

So we could copy these answers into our code and just give the right outputs for the right inputs. We could even delete these other tests. 

![](https://lh6.googleusercontent.com/s_YM5EyQIBP1glKG9vszdK_55RZN9ukTDb3CbzCsMPYbsI8sWI-mzKK6ab2W3NYGVqH_MROQ3x-xHl4RIN6eftkBdep7a2fbt8hWMeQp0loWlNmz-rnBXJ9_A3aDCzPye-jkqaju)

And look, green! But, would that solve the kata? **No**. If we change the inputs then the answers will be wrong. And the kata will do that for you. If you hit the blue “Attempt” button, it will run through loads more tests and look, now our answer doesn’t work any more. 

![](https://lh5.googleusercontent.com/FhtDmTYdbYuwOz2SuhdtCrDuFP-RmUG0pAAx5OxOlmnHYyxJ2nFAxmhfpGn6mbgedyFfcO4O6bWolioJ9HFTXwgyWu2zHZV9LJ-3hAsNyOnKdvu3jN-004zQzWtWDzTaLKXnwyFL)

So we can’t rewrite the tests to pass the code. **We’ve got to rewrite the code to pass the tests.**

Let’s work this problem

### **3. Read the test results**

So I will reset by hitting the reset button and run the kata tests again.

Now my test is failing as undefined, because I’m not returning anything at all right now. I definitely need to return a value, so I’m going to write a return in.  What other piece of information do I need?

1. I need to figure out how many milliseconds there are in each of these values
2. Convert the values to that number
3. Then add them together. 

How many milliseconds are there in an hour, anyway? I’m gonna google that.  


![](https://lh6.googleusercontent.com/Nto7oAm5psoZupQrQGzR0ZSbB4PYccr_drMeab9_WEtI9_rAxEjZuFuG8Yk_30qUX3lfG5f9H36wxQsQoRNBC6JBLLgdR-mf2-rDTl_iyNOpOPCKw_eeuOvkzbc4BWXGdokBSuhk)

Oh look at that - google has a converter right there. Wow, that’s a big number! I’m going to copy and paste that and then hit test. Test often.

![](https://lh6.googleusercontent.com/lVWkyoBHfLJFQt_mnhH3-9C1M3ukhlS_LGZXuzYHDtxiH3fcTrINBm5k6canJYtJqHtAlUeWvaXX6D0RIXsCRq_Mu1l9wOVFEhsxBSjSCL7LyC5Zl9-OLV8-CiWAK2yV5b6WPN4H)

Hm, not right yet -- I guess I need to try doing the same thing for the minutes and the seconds and then adding them all together. 

![](https://lh3.googleusercontent.com/3sohLqEZR1MGu8Y2JFpawUt4x4w6CIYnCOdvTGTnc0EXZUl3vXBW8smrFkl_XBgZw29HetY2dGQuqG_ZC696h2RcfTQ_9lkGGBCH3tqAzEeXZC8zpBkqyEORkD0esjJzGyX6kjgu)

![](https://lh3.googleusercontent.com/91Xf1wxchC6Je2VS472VBwMCRiE8sCyH3RF1-fL6qw2sLlGFonQemRf35nHTE3ocTUTmvySsoZSzXiacJaJ4wvMFjXwYm17MLMMI9DLsXpEAq0kvhArBudqfxmthuHrGHoj3VVdJ)

Oh look, success! But this is only a limited number of tests. 

![](https://lh5.googleusercontent.com/KCdiJh1Qx9jI1bbSjE5OCGMBsZfuxo3jgp5IkJCKZsEKHAMpizTfbrk63TqQxrxkFW7smcz7tMpwme4lVxqY0PQa9J2kz2yT9ldSLEII7UbNYumN9qpa3dgv1MkG8iWeXW35rcxH)

I’ll hit the blue attempt button \(you can attempt over and over, _and you should_\).

![](https://lh4.googleusercontent.com/2tmUkuIfjJZXedur-8BYB_8BVZmHqWNJMCUVbTBQp71zRsGNWDfee4ovsH1Z8m4H326graTbJev-NDHyB56HmaLeSfFmiUlHxXHSbz91BrXQ1AgGp3Wa9HSOEK1PUDgbETl22mgq)

### **4. Refactor**

Now I’ve passed all my tests I can refactor and make it all tidy. Maybe I’ll make it a fat arrow function… 

![](https://lh5.googleusercontent.com/GWYcCKp-2Ybtp5y2aIprRm2qcH00FlYwXKf4NaF9Di88IA7mU50BRCsr2Xh8y8J_Ar-yaQyZwV7OXEpu1C2DrhW4pzGwjqJYOK2EGnf91xrziEzbe-38JgKZurHhrTNNq866-0IG)

But look, it seems like I’ve solved this kata before so I’ve got my old solutions right here in this tab. What did I say?

![](https://lh6.googleusercontent.com/QA4fyWc0rAtsast5NVzMfKuf1bF8XxaXaUhc34H4_rD5GLIvovmSvfCkqQxruhZAjCzrMU_pWFBy0pYLTqEXa50GIjfJNeM1yFpmJkY5pSjBT4UIVkcfTaEAcCWRhtd_nYc2sI7J)

That’s a pretty good point.  I could one line this, and if I am practising one liners that is what I should do. But when I come back to this kata, I’m not convinced that I would know what these numbers mean. I wouldn’t know what 3.6e+6 meant, for sure. So maybe I should identify these values. I could do it the way I did last time, except I would spell milliseconds correctly. Hit submit.

### **5. Compare**

And now we get to go and see how other people solved it. Click around the different filters. Look at all these different answers!   


![](https://lh3.googleusercontent.com/4bBGC3jaZJxw1Bk2LjQzBdEea_XZq3bNvH5oLJpSPPMR2aUfQnBPEjVDUMAYiPUP2MueiC46TRhd3jFXoSq16nVDDr16SjiGBg5-PdZH7t7a8za0Y7Bq64C_VYQJiBW04cIQxor-)

Take the “best practices” with a pinch of salt - especially at beginner levels where the people voting are just learning. But it’s interesting to see all the different ways to approach the problem - and there are always many many solutions.   


\(It’s worth repeating kata after a break - go back and train again on kata you’ve already done, a few weeks or months later and see how differently you approach things.\)  


## Recap

So you need to:

* Read the description
* Run the tests
* Read the test output
* Google well and often
* Test and test again
* Refactor at the end
* Read others solutions

So that’s Codewars. [Join the CodeYourFuture clan](https://www.codewars.com/users/edit). Join the slack channel. Find the collections, and get some exercise.  


Clan name: **CodeYourFuture**  
__Slack Channel: **\#cyf-codewars**  
Collections: ****[**CYF Modules**](https://www.codewars.com/users/CodeYourFuture/authored_collections)\*\*\*\*

  
  
  


