
#Jedi Mind Tricks
##How Lean Methodologies Mitigate Biases, Uncertainty, and Risk in Product Development

<div class="notes">
I'm lauren, a PM at Labs

Here for about a year

Have worked for a variety of startups and enterprise organizations, including yipit and cafemom 

Have a lot of experience with lean

Here today to talk to you about how to use lean to mitigate some of the biggest challenges of product development: risk, biases, and uncertainty 
</div>


---

##Why Is Product Development So Hard?
- We are bad at predicting outcomes
- We are overconfident
- We are inherently biased

<div class="notes">
	
Why is product development so hard?

We're human! 

We have also have something called cognitive biases

Who among you would opt for surgery if the survival rate were 90%?

What if I said the mortality rate was 10%?

Look how many more of you accepted the positive framing of this surgery. 

This is known as a framing bias
</div>

---

##Biases Add Risk 
- We overestimate benefits
- We underestimate costs
- We underestimate time
- We are pervasive optimists

<div class="notes">
Among cognitive biases, one of the strongest is something called the planning fallacy

Tendency to overestimate benefits and underestimate costs of a project

We also tend to fear loss more than we value benefits

In 2002, a survey of Americans remodeling their kitchens revealed that they expected the job to cost $18,658 on average, but they ended up paying $38,769. 

We've all heard the addage about building software -- it's either twice the cost and 3x the price or 3x the price and twice the cost. 

As you can see, biases influence our thinking. They also add risk.

If you're interested in this stuff, read thinking fast and slow
</div>

---

##How To Outsmart Your Biases
- Accept that most opinions are assumptions
- Apply a methodology to validate assumptions
- When it doubt, fall back on our methodology

<div class="notes">
But there's a way to outsmart our biases
If you'll notice, this is pretty similar to the scientific method
</div>

---

##How to Outsmart Your Assumptions
- Test riskiest assumptions first
- Test assumptions quickly and cheaply
- Test assumptions with real users

<div class="notes">
We can also outsmart our assumptions

We tend to be risk averse as humans

We often leap before we look

In reality, we need a way to rein in our assumptions

He

I run relay races. My team runs 200 miles over 24 hours.

I'm usually the relay captain. That means I'm responsible for signing up my entire team and coordinating everything. 

This involves of planning. You need to amass 2 vans, 12 people crazy enough to do this, etc. 

It's really hard to coordinate all this stuff. THERE ARE A TON OF TO-DO's BUT NO CHECKLIST People have lives and jobs. They don't want to spend hours wondering what type of gatorade 12 people prefer.

Because it's so hard to coordinate, I've stopped being captain. As a result, our team hasn't run a relay in over a year. We used to do 3 a year.

I want Ragnar to make an app that helps captains organize their to-do list for the race.

It would let captains add people to their team.

It would let team members to sign the safety waiver

It would show a checklist of common food and drinks for a team of 12, as well as all the safety items needed.

It would let team members sign up for certain tasks (for example, finding vans)

In this fictional app, I made some big assumptions. 

Can anyone tell me what my riskiest assumption is?

That captains have so much trouble organizing their teams that they don't sign up for the race.

</div>


---

#What Is Lean?
##Your Words
- "Methodology for developing a product iteratively"
- "Try to get validation as quickly as possible"
- "Follow your KPI's, fail fast, don't be afraid to pivot"

---

#What Is Lean?
##My Words
- Methodology to mitigate risk, biases and uncertainty in product development
- TDD for Product

---

#What Is Lean?
##Eric Reis's Words
- Entrepreneurs are everywhere
- Entrepreneurship is management
- Validated Learning
- Build-Measure-Learn
- MVP

---

#How Lean Works
1. Make a hypothesis
2. Define success (qualitative and quantitative)
3. Do the minimum amount of work
4. Validate (or invalidate) the hypothesis
5. Rinse and repeat


---

#Make a Hypothesis
- We believe that [type of people] have a problem doing [x]
- We believe we can can fix it by building [y]
- We'll know we're right if [change in behavior or kpi]

---

#More On Hypotheses
- Defining your hypothesis is really hard
- Your statement must capture the core of your user value
- Be ruthless
 
<div class="notes">

If you don't capture the core user value, you're at the mercy of your biases. 

What's the difference between the following hypotheses: 

---
We believe that team captains have trouble planning races

We think we can fix it by building an app

We'll know we're right if more people sign up for the race and download the app
---
We believe that the prospect of coordinating a team is so overwhelming that team captains don't sign up for the race.

We believe we can fix it by building by building checklist of all the activities captains need to do before race day

We'll know we're right if captains that complete 25% of the checklist then sign up for the race

See how the first hypothesis could be dangerous? What's the app? How does downloading the app correlate to signing up?

Be ruthless with your hypotheses
</div>
---

#Define Success (Quantitative)
##We'll Know We're Right If:
- Set a baseline of the current behavior
- Set a goal you expect to hit after minimum amount of work
- This is a KPI (key performance indicator)

---

#Define Success (Quantitative)
##Best Practices:
- If doesn't represent a change in behavior, it's not a KPI
- If you're not embarrassed by it, it's not a KPI
- Focus on ratios (% of users who post on 1st day)
- Focus on how ratios change over time
- Don't focus on numbers that always go up (# of users, # of pageviews)

<div class="notes">

We'll know we're right if people download it and sign up for the race

(this isn't a change in behavior. it's also not a ratio)
Vs

We'll know we're right if captains that complete 25% of the checklist then sign up for the race

(this is a ratio. tightly tied to causality of our checklist. it can also change over time. )
</div>

---

#Define Success (Qualitative)
##We'll Know We're Right If:
- For new products, there's often no baseline
- Measure success by commitment (to share, to buy, etc)
- Measure success by net promoter scores (how likely are you to recommend this to a friend)
- Measure success by how users describe it to a friend

<div class="notes">
We understand success by talking to customers
We borrow practices from customer development
</div>
---

#Define Success (Qualitative)
##Best Practices:
- Metrics often don't tell the whole story
- Test with existing users or real potential users
- Ask non-leading questions
- Ask questions about past behavior

<div class="notes">
We'll know we're right if captains recommend this app to their team 
To other captains 
If they say it's saved them time 
If they say it's saved the anguish
</div>
---

#Do The Minimum Amount of Work
##To Validate or Invalidate a Hypothesis
- Consider things that aren't coded
- Consider things that aren't designed
- Consider things that don't scale
- Consider things that aren't on brand

<div class="notes">
What's the minimum thing Ragnar can build to validate this hypothesis?

A checklist 

A landing page for people interested in organizing a team

A way to track if captains that complete part of the checklist actually sign a team up for the race

NOT a web app 

NOT a photo sharing tool 

NOT a way to order cases of gatorade
</div>

---

##If you are not embarrassed about your product at the time you launch it, you’ve launched too late”
###- Guy Kawasaki

---

#Validate The Hypothesis
##(Or Invalidate the Hypothesis)
- Did you hit your goal?
- Why or why not?
- If yes, keep pushing
- If not, talk to your users
- If not, change your goal or change your problem statement


<div class="notes">
After 2 weeks, did people who filled out 25% of the checklist also sign up a team for the race?

If so, great -- it's time to build the next iteration of the product

If not, it's time to talk to their users. 

Maybe people that filled out 100% of the checklist never signed up for the race. Sounds like there's another problem there (money?)

</div>

---

#Lean Best Practices
- Test your riskiest assumptions first
- Test one assumption at a time
- Don't change goals mid-stream
- Document everything in a highly visible place

---

#Lean within Agile
- Focus one iteration on one hypothesis
- Include metrics stories in that iteration
- Use a validation board to keep track of hypotheses

---

# Lessons Learned
- Build something embarrassing
- Learning is *always* the primary goal
- Stand by your methodology 

---

# A Word on Viable
- "Viable" is a slippery slope to "just build it all"
- Make sure your hypotheses are solid 
- Make sure your test is solid 
- Defend yourself 

---

#Lean In Real Life

---

#Yipit (New Product)
##Make a Hypothesis
- We believe that users have a problem finding the best daily deals in their area
- We think we can fix it by emailing them all the deals

---

#Yipit
##Define Success
- We'll know we're right if we get more email signups than we have for our current product


---

#Yipit
##Do The Minimum Work:
- Landing page
- Email signup form
- Mailchimp email with hand-curated daily deals
- 3 days

---

#Yipit
##Validate or Invalidate
- 25k signups in one month

---

#Yipit
##Lessons Learned
- 6 Months: Search Every Manhattan Furniture Home & Lighting Store
- 3 Months: Search Every Sample Sale in NYC

---

#GTIO (Existing Product)
##Make a Hypothesis
- iPhone app that lets share pictures of their outfits and get realtime feedback
- We believe that users have a problem buying the clothing they see in their favorite looks
- We think we can fix it by building a way to shop the look

<div class="notes">
	GTIO was co-founded by Simon, one of our PM's
	He's currently on jury duty
	Unfortunately 
</div>
---

#GTIO
##Define Success
- 25% of users will click to shop the look
- 2 purchases per week from the email

---

#GTIO
##Do the Minimum Work:
- Build a "shop the look" link
- Email "community team with a link to the outfit
- Do our best to shop and email the user back
- Follow up to see if the user bought something

---

#GTIO
##Validate or Invalidate

---

#Lean in Enterprise
##Focus on Reducing Risk
- Test riskiest assumptions first
- Build off-brand apps with rough designs (skunkworks)
- Test in Canadian or Australian app store
- Roll out features to a small percentage users
- Curate a "product council" of your best users for feedback

---

#Questions?

---

#Shoutout
- Special thanks to Simon Holroyd for pairing on this presentation and exposing some old features

---

#Thanks!
- Lauren@pivotallabs.com
- @lgilchrist

---

#Resources
- The Lean Startup by Eric Reis
- Lean Analytics, by Ben Yoskowitz
- Use Lean Hypotheses to Define a Minimum Viable 

---
<script src="js/impressConsole.js"></script>
<script>
    impressConsole().init();
    // impressConsole().open(); // for console to open automatically
</script>
