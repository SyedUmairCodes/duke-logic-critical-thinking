# categorical Logic

Welcome to week five of our course. The week on categorical logic. [NOISE] Remember last week was on a part of deductive logic that we called propositional logic. Last week, we tried to understand why certain inferences, certain arguments that use propositional connectives were valid, because of the truth tables for the propositional connectives that they use.
Play video starting at ::36 and follow transcript0:36
This week, we're going to be looking at arguments that are valid not because of the propositional connectives that they use. In fact, a lot of the arguments that we'll be looking at this week have no propositional connectives at all. We'll be looking at arguments that are valid for a different reason. We'll try to understand what that different reason is.
Play video starting at ::55 and follow transcript0:55
But first, to review in more detail what we did last week, let's consider an example of a deductive argument that propositional logic can help us to understand.
Play video starting at :1:8 and follow transcript1:08
So let's look at this.
Play video starting at :1:12 and follow transcript1:12
Consider the following argument. Premise one, Jill is riding her bicycle if, and only if, John is walking to the park. You can imagine, let's say, that Jill has a bicycle, but the only time she ever rides her bicycle is to meet John at the park. And the only way John ever gets to the park is by walking there. Let's say he lives just a block down from the park, so it doesn't make sense for him to get there any other way, so he only goes to the park by walking there. And Jill only rides her bicycle when she's meeting him at the park. So, according to Premise 1, Jill is riding her bicycle if, and only if, John is walking to the park.
Play video starting at :1:52 and follow transcript1:52
Premise two, John is walking to the park, if, and only if, premise one is true.
Play video starting at :2:4 and follow transcript2:04
And the conclusion of the argument is, therefore, Jill is riding her bicycle.
Play video starting at :2:11 and follow transcript2:11
Now let me ask you, is that argument valid?
Play video starting at :2:15 and follow transcript2:15
Is there any possible way for the premises to be true, while the conclusion is false?
Play video starting at :2:22 and follow transcript2:22
Well, that's not obvious, is it?
Play video starting at :2:24 and follow transcript2:24
It takes a while to see that in fact that argument is valid
Play video starting at :2:30 and follow transcript2:30
and the way to see it is by using the truth table for the biconditional, expressed in English by if and only if.
Play video starting at :2:39 and follow transcript2:39
We can use the truth table for the biconditional to see that that argument really is valid. Here, let me show you what I have in mind.
Play video starting at :2:50 and follow transcript2:50
So look here. There's the proposition Jill is riding her bicycle. Now, that proposition could be either true or false. Then there's the proposition John is walking to the park. And of course, that proposition could either be true or false. So there are four possible combinations. Either Jill is riding her bicycle is true and John is walking to the park is true, Jill is riding her bicycle is true, and John is walking to the park is false. Jill is riding her bicycle is false, and John is walking to the park is true, or both of those propositions are false. Those are the four possible scenarios.
Play video starting at :3:21 and follow transcript3:21
Now, according to premise one, Jill is riding her bicycle if, and only if, John is walking to the park.
Play video starting at :3:30 and follow transcript3:30
So if premise one is true, that shows us that we're either in the first of those four scenarios, or the last of those four scenarios. We're either in a scenario where it's true that Jill is riding her bicycle and it's true that John is walking to the park, or else we're in a scenario where it's false that Jill is riding her bicycle and it's false that John is walking to the park.
Play video starting at :3:52 and follow transcript3:52
Okay, now consider the proposition John is walking to the park if, and only if, that last statement, the statement to the left, that Jill is riding her bicycle if, and only if, John is walking to the park. John is walking to the park if, and only if, that statement is true.
Play video starting at :4:11 and follow transcript4:11
Now, what's the truth table for that going to be?
Play video starting at :4:16 and follow transcript4:16
Well, the truth table for that is going to be as follows. It's going to be true whenever it's true that John is walking to the park and it's also true that Jill is riding her bicycle if, and only if, John is walking to the park. It's also going to be true whenever it's false that John is walking to the park and it's false that Jill is riding her bicycle if, and only if, John is walking to the park.
Play video starting at :4:39 and follow transcript4:39
So that means that last biconditional that John is walking to the park if, and only if, premise one is true. That's going to be true in the first two of our scenarios. It's going to be true when it's true that Jill is riding her bicycle and true that John is walking to the park. It's also going to be true when it's true that Jill is riding her bicycle and false that John is walking to the park.
Play video starting at :5:4 and follow transcript5:04
Okay, so now, under what conditions will premise one and premise two of our argument be both true. Remember, premise one says Jill is riding her bicycle if, and only if, John is walking to the park. Premise two says John is walking to the park if, and only if, premise one is true. So under what conditions will those two premises be true? Well, those two premises will be true only in the first of our four scenarios. Because in the first of our four scenarios, it'll be true that Jill is riding her bicycle if, and only if, John is walking to the park. And in the first of our four scenarios, it will also be true that John is walking to the park if, and only if, that last statement, premise one is also true.
Play video starting at :5:53 and follow transcript5:53
So that's the only scenario under which both of those premises are true. But now notice in that scenario, when both of those premises are true, Jill is riding her bicycle.
Play video starting at :6:7 and follow transcript6:07
And so, the argument that we just looked at is going to be valid. Because in any situation in which the two premises are true, the conclusion is going to have to be true. And we learn that by looking at the truth table for the biconditional.
Play video starting at :6:24 and follow transcript6:24
Now, you see, that's an example of how we can use the truth table for propositional connective like the biconditional to discover that a particularly tricky argument is valid.
Play video starting at :6:38 and follow transcript6:38
Right, we have a tricky deductive argument right here. It's not obvious whether or not it's valid, but we can use the truth table for the biconditional to discover that the argument is valid. But remember I said we don't just use truth tables to discover when arguments are valid or that they're valid. We can also use truth tables to explain why they're valid, even in cases where they're obviously valid. Right, so last week we looked at lots of examples of arguments that were obviously valid, and in some cases obviously invalid. And we used the truth table not to figure out that they were valid or invalid, it was already obvious that they were valid or invalid as the case may be, we use the truth table to understand why they were invalid or valid.
Play video starting at :7:23 and follow transcript7:23
That's what the truth table was for in those cases.
Play video starting at :7:29 and follow transcript7:29
Now, this week in our study of categorical logic, we want to find a method that can function like the method of truth tables to help us discover whether particular inferences are valid. And why particular inferences are valid.
Play video starting at :7:48 and follow transcript7:48
But it's not going to be the same as the method of truth tables because truth tables only work for inferences or arguments that uses truth functional connectives. But not every valid argument uses a truth functional connective.
Play video starting at :8:3 and follow transcript8:03
Consider a couple of the examples we looked at last week. Consider this argument from a week ago.
Play video starting at :8:12 and follow transcript8:12
No fish have wings.
Play video starting at :8:14 and follow transcript8:14
All birds have wings.
Play video starting at :8:17 and follow transcript8:17
All animals with gills are fish.
Play video starting at :8:20 and follow transcript8:20
Therefore, no birds have gills.
Play video starting at :8:24 and follow transcript8:24
Is that argument valid?
Play video starting at :8:28 and follow transcript8:28
It's not immediately obvious whether or not it's valid. But it turns out that it is valid, and we have a method for proving that it's valid, and this method is what we'll be talking about this week. It's the central method of categorical logic.
Play video starting at :8:46 and follow transcript8:46
Notice also that there are other inferences, which are obviously valid. But, the validity of which, truth tables don't help us to understand. Consider, for instance, this example, Mary has a child who is pregnant. Only daughters can become pregnant. Therefore, Mary has at least one daughter. Now that argument is pretty obviously valid.
Play video starting at :9:7 and follow transcript9:07
But why?
Play video starting at :9:9 and follow transcript9:09
What is it about the argument that makes it valid? I said at the beginning of week four that there's something about the form of the argument. Something about the use of the terms only and at least that makes that argument valid. And any argument no matter what it's about that uses the terms only and at least in the way that this argument does is also going to be valid. But what is it about the use of those terms that makes this argument valid? Well, this week in our study of categorical logic, we're going to discover a way of understanding what's going on with that use of those terms only and at least, those terms that we call quantifiers. We're going to discover a method of understanding quantifiers that can help us to understand why this particular argument and others that are of the same form are valid.
Play video starting at :10: and follow transcript10:00
Okay, so that's what we'll be doing this week in categorical logic. We'll be understanding how quantifiers work, but what are quantifiers? And, after all, if the central words that we're going to be concerned about this week, the central concept this week is the concept of a quantifier, why is this called categorical logic anyway? Why not quantifier logic? Categorical logic is the logic of categories. Quantifiers are words like all, some, none, only, at least, and so forth.

# Categories and Quantifiers
In the last lecture, I raised the question, why it is that we call the subject that we're going to study this week categorical logic, the logic of categories, when, really, what we're going to be doing is learning about quantifiers. Quantifiers like all, some, none, only, at least, and so forth. What do categories and quantifiers have to do with each other? That's the topic of today's lecture.
Play video starting at ::33 and follow transcript0:33
So first, let me talk a bit about categories, and what role they can play in arguments. Now, frequently we give arguments that make use of categories of kinds of thing. Consider the following argument. Brazilians speak Portuguese. Portuguese speakers understand Spanish. And therefore Brazilians understand Spanish.
Play video starting at ::58 and follow transcript0:58
Now there's an argument with two premises and a conclusion, and it's an argument that talks about various categories of thing. One category of thing it talks about is Brazilians. Another category is Portuguese speakers, people who speak Portuguese. And a third category is people who understand Spanish.
Play video starting at :1:18 and follow transcript1:18
The argument brings those three categories into relation with each other.
Play video starting at :1:24 and follow transcript1:24
But how does it do that exactly? What, precisely is it that the argument is telling us?
Play video starting at :1:32 and follow transcript1:32
Well, here's one interpretation of the argument. You could understand the argument as saying that some Brazilians speak Portuguese, certainly that's true. Maybe not all Brazilians speak Portuguese, and maybe there are some Brazilian citizens should've only recently acquired citizenship, and have never learned to speak Portuguese. So, some Brazilians speak Portuguese, that much at least is true. And some Portuguese speakers understand Spanish, of course, that's true.
Play video starting at :2:5 and follow transcript2:05
But suppose the argument concludes from those two premises that some Brazilians understand Spanish.
Play video starting at :2:12 and follow transcript2:12
Would that be a valid argument?
Play video starting at :2:14 and follow transcript2:14
Well, although I'm confident that the conclusion of that argument is true, the argument itself wouldn't be valid. Because there is a way for both premises of the argument to be true while the conclusion is false. Just imagine this, while it's true that some Brazilians speak Portuguese and some Portuguese speakers understand Spanish you could imagine that all of the Portuguese speakers who do understand Spanish or in Portugal not in Brazil. Or in any case are in some other part of the world than Brazil. And that none of the Brazilian's who speak Portuguese are among the Portuguese speakers who understand Spanish.
Play video starting at :2:52 and follow transcript2:52
In that circumstance, the premises could both be true, while the conclusion, that some Brazilians understand Spanish, would be false.
Play video starting at :3:3 and follow transcript3:03
So the argument even if it's conclusion is true, the argument is not valid.
Play video starting at :3:10 and follow transcript3:10
But maybe that's not how to understand the argument that we just considered a moment ago, the argument from Brazilian speak Portuguese and Portuguese speakers understand Spanish. Do Brazilians understand Spanish? Maybe there's a different way to understand the argument. Maybe the right way to understand the argument is by saying this. Most Brazilians speak Portuguese. Certainly that's true.
Play video starting at :3:32 and follow transcript3:32
And maybe the argument says, is supposed to say also that most Portuguese speakers understand Spanish.
Play video starting at :3:41 and follow transcript3:41
I don't know if that's true, but I gathered from people that it's probably true.
Play video starting at :3:46 and follow transcript3:46
And maybe the argument intends to draw the conclusion from those two premises that most Brazilians understand Spanish.
Play video starting at :3:56 and follow transcript3:56
Now would that argument be valid?
Play video starting at :4: and follow transcript4:00
Well, no, it wouldn't.
Play video starting at :4:3 and follow transcript4:03
Because even if the conclusion of the argument is true, there's still a possible scenario in which, the premises are true while the conclusion is false. I could describe such a scenario to you. Suppose that while most Brazilians do speak Portuguese and most Portuguese speakers do understand Spanish, most Portuguese speakers, let's suppose, live outside Brazil.
Play video starting at :4:29 and follow transcript4:29
And the Portuguese speakers who understand Spanish are just those Portuguese speakers who live outside Brazil.
Play video starting at :4:41 and follow transcript4:41
So while then it would be true that most Brazilians speak Portuguese, and most Portuguese speakers understand Spanish. It might not be true that most Brazilians understand Spanish, because maybe that minority of Portuguese speakers who live in Brazil don't understand Spanish. The only Portuguese speakers who understand Spanish, we could suppose are that majority of Portuguese speaker who live outside Brazil.
Play video starting at :5:7 and follow transcript5:07
Now, of course, that isn't the actual scenario, but it's a possible scenario. And since it's a possible scenario, there's a possible scenario in which the premises of the argument are true, and the conclusion false, and so the argument is not valid.
Play video starting at :5:26 and follow transcript5:26
But maybe that's not even the correct way to understand our original argument about Brazilians. Maybe the correct way to understand our original argument is like this, maybe the argument was intended to say all Brazilians speak Portuguese and all Portuguese speakers understand Spanish. Therefore, all Brazilians understand Spanish.
Play video starting at :5:50 and follow transcript5:50
Now, one thing that this argument has to its credit is that it is valid. If the premises of this argument are true, if it's true that all Brazilians speak Portuguese, and it's true that all Portuguese speakers understand Spanish, then it's got to be true that all Brazilians understand Spanish. So this argument, in contrast to the last two arguments that we looked at, this argument is valid.
Play video starting at :6:19 and follow transcript6:19
Unfortunately, it's not sound, because it's almost certainly not the case that the two premises are both true.
Play video starting at :6:28 and follow transcript6:28
Be that as it may though, the argument is valid.
Play video starting at :6:32 and follow transcript6:32
Now notice what we did. We started off with an initial argument that used three categories in the argument, the category of Brazilian, the category of the Portuguese speaker, and the category of a person who understands Spanish.
Play video starting at :6:48 and follow transcript6:48
Then we saw that by the use of certain modifiers, the modifier some, most or all, we could make that original argument about Brazilians understanding Spanish. We could make that original argument more precise.
Play video starting at :7:4 and follow transcript7:04
And once we made it more precise, we could test whether or not it was valid.
Play video starting at :7:13 and follow transcript7:13
Now, what I want to introduce is a way of testing whether or not an argument is valid when the argument is one that uses categories and quantifiers to modify those categories.
Play video starting at :7:27 and follow transcript7:27
The method involves the use of what we'll call Venn diagrams. A Venn diagram is a diagram that represents a number of different categories. In this simple Venn diagram, we have a representation of the category of Brazilians, and we have a representation of the category of Portuguese speakers.
Play video starting at :7:46 and follow transcript7:46
Premise one of our original argument stated a relation between Brazilians and Portuguese speakers. But what relation did it state? Well, that was left vague by the original statement of the argument, but then when we looked at three different ways of making the argument more precise, we saw three different relations that could be stated.
Play video starting at :8:6 and follow transcript8:06
It could have said that some Brazilians are Portuguese speakers. The way of representing that would be by drawing an X right here,
Play video starting at :8:16 and follow transcript8:16
to show that there is something.
Play video starting at :8:21 and follow transcript8:21
There is someone who is both a Brazilian and a Portuguese speaker.
Play video starting at :8:28 and follow transcript8:28
The second modification we made of the statement, said most Brazilians are Portuguese speakers. Now, this week we're not going to discuss a way of representing the quantifier most in Venn diagrams. I just call it to your attention as a quantifier that can be used and frequently is used to modify categories and argument. But the third way that we interpreted our original argument about Brazilians understanding Spanish. The third way was as an argument that began by stating that all Brazilians speak Portuguese. Now how would we represent the fact that all Brazilians speak Portuguese? Well, what are you saying when you are say that all Brazilians speak Portuguese? Well, you're saying that there is no Brazilian who falls outside the category of Portuguese speakers. This circle right here, represents the category of Portuguese speakers. And when you say all Brazilians speak Portuguese, what you're saying is that whatever Brazilians there are, they have to be inside this circle. They can't be outside the circle, they've gotta be inside the circle of Portuguese speakers.
Play video starting at :9:48 and follow transcript9:48
So the way to represent that is to shade out the portion of the Brazilian circle that's outside the Portuguese speaker circle. There, you're indicating that there isn't anything, in the Brazilian circle there isn't anything the category of Brazilians
Play video starting at :10:6 and follow transcript10:06
that falls outside the category of Portuguese speakers. In other words, all Brazilians speak Portuguese.
Play video starting at :10:15 and follow transcript10:15
That's how you could represent that. And that's what we're going to do to represent the statement all Brazilians speak Portuguese. We simply shade out the part of the Brazilian circle that's outside the Portuguese speakers circle. And to represent some Brazilians speak Portuguese, we put an X in the Brazilian circle that's also inside the Portuguese speakers circle.
Play video starting at :10:41 and follow transcript10:41
Now we used a Venn diagram to represent the information contained in the first premise of the argument about Brazilians but how could we use the Venn diagram to represent the information contained in both premises and the conclusion. Well, here's how.
Play video starting at :11:1 and follow transcript11:01
So here are three circles corresponding to the categories of Brazilians, Portuguese speakers, and those who understand Spanish.
Play video starting at :11:14 and follow transcript11:14
Now suppose we interpret the first premise of our argument, Brazilians speak Portuguese. As saying that some Brazilians speak Portuguese, well as we saw already the way to represent that is with an X right here that's both in the circle of Brazilians and in the circle of Portuguese speakers. That represents that there is something that X that is both a Brazilian and a Portuguese speaker.
Play video starting at :11:42 and follow transcript11:42
Now, how would we represent the information that some Portuguese speakers understand Spanish? Again, we could do that with an X that is both in the circle of Portuguese speakers and in the circle of those who understand Spanish.
Play video starting at :11:59 and follow transcript11:59
So that represents that there is something that is both a Portuguese speaker and an understand of Spanish.
Play video starting at :12:8 and follow transcript12:08
But, now notice we've represented the information that some Brazilians speak Portuguese and some Portuguese speakers understand Spanish.
Play video starting at :12:17 and follow transcript12:17
Now, does that information imply that some Brazilians understand Spanish?
Play video starting at :12:27 and follow transcript12:27
If the information that some Brazilians are Portuguese speakers and some Portuguese speakers understand Spanish, if that information is true, does it follow from that that some Brazilians understand Spanish?
Play video starting at :12:38 and follow transcript12:38
Well, one look at this diagram should tell us that, no, it doesn't follow. Because look here, you have a thing that is a Brazilian and a Portuguese speaker, representing the fact that some Brazilians speak Portuguese. Then you have a thing that is a Portuguese speaker and understands Spanish representing the fact that some Portuguese speakers understand Spanish, but do you have anything that is both a Brazilian, and something that understands Spanish? No, not necessarily.
Play video starting at :13:9 and follow transcript13:09
So, this diagram right here shows you that if the premises of our argument are some Brazilians are Portuguese speakers and some Portuguese speakers understand Spanish, from those premises it doesn't follow that some Brazilians understand Spanish.
Play video starting at :13:26 and follow transcript13:26
If you want to conclude that some Brazilians understand Spanish your argument is not going to be valid. There's going to be a possible scenario in which the premises of your argument are true and the conclusion is false. And so, we can say, about this argument right here, that this argument is not valid. And we can understand why it's not valid by looking at this Venn Diagram. Right here.
Play video starting at :13:54 and follow transcript13:54
That shows why our argument about some Brazilians being Portuguese speakers, while that argument is not valid.
Play video starting at :14:5 and follow transcript14:05
But now, let's consider not the argument to the effect that some Brazilians speak Portuguese, let's consider the argument to the effect that all Brazilians speak Portuguese. How would we represent the information in those premises and that conclusion? Well, if all Brazilians speak Portuguese, what that means is that all of the Brazilians must be inside the category of Portuguese speakers. So there can't be any Brazilians outside that category.
Play video starting at :14:35 and follow transcript14:35
So we can shade out the portion of the Brazilian circle that's outside the category of Portuguese speakers. We know there's nothing in there because all the Brazilians there are, are inside the category of Portuguese speaker according to premise one of this new argument.
Play video starting at :14:52 and follow transcript14:52
According to premise one all Brazilians are Portuguese speakers, according to that premise all the Brazilians there are have to be in here.
Play video starting at :15:3 and follow transcript15:03
Premise two says, all Portuguese speakers understand Spanish.
Play video starting at :15:10 and follow transcript15:10
Well, if all Portuguese speakers understand Spanish then there cannot be any Portuguese speakers who are outside the category of those who understand Spanish. Here's the category of those who understand Spanish and all the Portuguese speakers, according to premise two, have to be inside that circle. So that means that we can shade out the portion of the Portuguese speaker circle that's outside the understands Spanish circle.
Play video starting at :15:43 and follow transcript15:43
There are no Portuguese speakers that fall outside the category of understanders of Spanish according to premise two of this argument. That all Portuguese speakers understand Spanish. So now we can represent that information that way.
Play video starting at :15:59 and follow transcript15:59
Now that we've represented the information contained in those two premises, all Brazilians speak Portuguese, and all Portuguese speakers understand Spanish, let's ask, does if follow from those two premises that all Brazilians understand Spanish? Well, let's see, yes, it does. What Brazilians can there be? There can't be any out here. And there can't be any in here. And of course, there can't be any in here either. The only Brazilians there can be are these in here.
Play video starting at :16:36 and follow transcript16:36
That's the only part of the Brazilian circle that is left unshaded.
Play video starting at :16:42 and follow transcript16:42
Once we shade it in, the circles that we had to shade in to represent the first two premises of the argument. Once we shaded in, the part of the Brazilian circle that we had to shade in in order to represent the premise that all Brazilians were Portuguese speakers. And then we also shaded in the Portuguese speaker circle outside the understanders of Spanish circle. The only part of the Brazilian circle that's left unshaded is this, which means that whatever Brazilians there are have to be in here.
Play video starting at :17:15 and follow transcript17:15
So if there are any Brazilians at all, they've got to understand Spanish because they're in the circle of things that understand Spanish. Therefore, all Brazilians understand Spanish and we've just used this Venn diagram to prove visually that our argument is valid. This argument back here is valid.
Play video starting at :17:39 and follow transcript17:39
And our three circle Venn diagram shows that it's valid.

# How Quantifiers Modify Categories
In the last lecture, I said that quantifiers modify categories. That's how quantifiers and categories are related to each other. Categories are kinds of things and quantifiers modify categories. They can modify them in different ways. There are different kinds of quantifiers. In today's lecture, we'll talk about some of the different kinds of quantifiers and how they modify categories. We'll also talk about how the representation of these different quantifiers differs both verbally and visually, using the Venn diagram.
Play video starting at ::37 and follow transcript0:37
Okay, so what are the different kinds of quantifiers? Well, here are some of the different kinds of quantifiers.
Play video starting at ::44 and follow transcript0:44
There's the quantifier "all", and we can apply this to categories. Notice, by the way, in this slide I'm using an upper case F and an upper case G to represent any category at all. So in a statement of the form all Fs are Gs, that's the claim that all things that fall into one category, never mind exactly what that category is, let's just call it F, also fall into a second category. Again, never mind what that category is, we can just call it G.
Play video starting at :1:22 and follow transcript1:22
There are lots of examples of this kind of claim. When you say all things of one category also fall into a second category.
Play video starting at :1:30 and follow transcript1:30
For instance, all dogs are mammals. All squares are rectangles. All Coursera students are human, and so on. In all of these cases, you're making a claim of the form that all things that fall into one category, the F category, also fall into the G category.
Play video starting at :1:51 and follow transcript1:51
So, all is one kind of quantifier. And any statement of the form all Fs or Gs, we're going to call a statement of type A, a proposition of type A.
Play video starting at :2:1 and follow transcript2:01
Then there's the quantifier "no",
Play video starting at :2:4 and follow transcript2:04
which we can use in the statement of the form no Fs are Gs. No things of one category also fall into a second category.
Play video starting at :2:15 and follow transcript2:15
So for instance, you might say no humans are reptile, no Coursera students are trees, no democracies are at war.
Play video starting at :2:29 and follow transcript2:29
So, there are examples of statements of the form we're going to call E. An E statement is a statement to the effect that no things that fall into one category also fall into a second category.
Play video starting at :2:45 and follow transcript2:45
Then there's the quantifier "some".
Play video starting at :2:47 and follow transcript2:47
Now, the quantifier some can be used to make statements of two very different kinds. You could say that some things that fall into one category also fall into a second category.
Play video starting at :2:59 and follow transcript2:59
So if you'd said, some humans are female. Some Coursera students are American.
Play video starting at :3:8 and follow transcript3:08
Some Americans speak Spanish.
Play video starting at :3:13 and follow transcript3:13
Those are statements to the effect that some things falling into one category, the F's, also fall into a second category, the G's. Some F's are G's.
Play video starting at :3:25 and follow transcript3:25
Propositions of that form we'll call I propositions.
Play video starting at :3:30 and follow transcript3:30
Finally, we can also use the quantifier some to make a different kind of statement, a statement to the effect that some things that fall into one category don't fall into a second category. Some humans are not female.
Play video starting at :3:44 and follow transcript3:44
Some Coursera students are not American. Some Americans are not Spanish speakers.
Play video starting at :3:51 and follow transcript3:51
Statements of that form we'll call O statements or O propositions. They say that some things that fall into one category don't fall into a second category. Some Fs are not Gs.
Play video starting at :4:5 and follow transcript4:05
So those are the four kinds of statements that we're going to focus on in this week on categorical logic. We'll consider other kinds of statements as well, and we'll mention some other kinds of quantifiers, but those are the ones that are going to be of primary interest to us.
Play video starting at :4:21 and follow transcript4:21
Now, I've talked about these different quantifiers and how they can be used to make statements of very different kinds.
Play video starting at :4:29 and follow transcript4:29
But now we can visually represent the differences in the information provided in these four different kinds of statements. So consider, how would we visually represent a statement of the form that all F's are G's? All things that fall into one category also fall into a second category.
Play video starting at :4:51 and follow transcript4:51
Well, if you wanted to say all F's are G's, let's see, how would you do that? You'd be saying that all of the F's that there are fall into the G circle.
Play video starting at :5:1 and follow transcript5:01
But if all the F's that there are fall into the G circle, then there can't be any F's outside the G circle, right? So the Venn diagram for all F's are Gs would look like that.
Play video starting at :5:15 and follow transcript5:15
You'd be saying whatever F's there are, they've got to be in here.
Play video starting at :5:24 and follow transcript5:24
There can't be any outside there. So that would be the Venn diagram for all F's are G's, or a proposition of the A form.
Play video starting at :5:38 and follow transcript5:38
Next, there are propositions of the E form. Now, how would we represent those? Well, let's see.
Play video starting at :5:46 and follow transcript5:46
Here's the Venn diagram for no F's are G's. When you say no F's are G's, you're saying if there are any F's at all, they can't be inside the G circle, so you've gotta shade out that portion of the F circle that's inside the G circle. The shading implies that there's nothing there.
Play video starting at :6:5 and follow transcript6:05
So, there are no F's inside the G circle. And that's how you represent no F's are G's.
Play video starting at :6:14 and follow transcript6:14
Next, there are statements of the I form, some F's are G's. How would you represent those? Some F's are G's. You use an X mark to represent that there is a thing. So use an X to represent that there is a thing that's in the F circle and that's also in the G circle. So there's a thing right there, it's in the F circle so it is an F, but it's also a G. So some F's are G's.
Play video starting at :6:46 and follow transcript6:46
That's how you'd visually represent a statement of the I form. Finally, how about a statement of the O form, some F's are not G's. How would you visually represent that?
Play video starting at :6:58 and follow transcript6:58
Well, you'd have to make an X to indicate that there is an F, right? There is a thing that is F but it's not G. If it's not G, then it's gotta be outside the G circle. So it's inside the F circle, but outside the G circle.
Play video starting at :7:18 and follow transcript7:18
And that's how you'd indicate visually some F's are not G's.
Play video starting at :7:24 and follow transcript7:24
Now, I'd like you to notice something.
Play video starting at :7:27 and follow transcript7:27
We've just gone over theVenn diagrams for propositions of the A, E, I, and O forms.
Play video starting at :7:35 and follow transcript7:35
But what I'd like you to notice, let's go back to those forms.
Play video starting at :7:40 and follow transcript7:40
Propositions of the A form, all F's are G's, are negations of propositions of the O form, some F's are not G's, right? If all F's are G's, then it's not going to be true that some F's are not G's. And if some F's are not G's, then it's not going to be true that all F's are G's.
Play video starting at :8:4 and follow transcript8:04
All F's are G's, in other words, is going to be true when and only when some F's are not G's is not true.
Play video starting at :8:14 and follow transcript8:14
And similarly propositions of the E form are going to be negations of propositions of the I form. When is it going to be true that no F's are G's? It's going to be true that no F's are G's when and only when it's not true that some F's are G's. If some F's are G's, then it's going to be true that no F's are G's. And if no F's are G's, then it's not going to be true that some F's are G's.
Play video starting at :8:36 and follow transcript8:36
So, propositions of the A and O form are negations of each other, and propositions of the E and I form are negations of each other. Those relationships are represented visually on the Venn diagrams that we just drew.
Play video starting at :8:51 and follow transcript8:51
Consider again the Venn diagram for propositions of the A form.
Play video starting at :8:56 and follow transcript8:56
Propositions of the A form, the Venn diagram is going to have shading in here.
Play video starting at :9:2 and follow transcript9:02
But in propositions of the O form, the Venn diagram is going to have an X in here, in the precisely the place where propositions of the A form had shading.
Play video starting at :9:15 and follow transcript9:15
Propositions of the E form are going to have shading in here, where propositions of the I form are going to have an X in here.
Play video starting at :9:24 and follow transcript9:24
So the way that we represent negation using Venn diagrams is one proposition's going to be the negation of another just in case the first has shading wherever the second has on X or vice versa.
Play video starting at :9:39 and follow transcript9:39
If one proposition has an X wherever the other has shading or it has shading wherever the other has an X, then the two propositions are going to be the negations of each other. That's how the relation of negation is visually represented in Venn diagrams.

# Immediate Categorical Inferences

In the last lecture, we learned about propositions of the forms that we labeled a, e, i, and o.
Play video starting at ::11 and follow transcript0:11
We learned how to represent these propositions verbally and also how to represent them visually using Venn diagrams. Today, I want to apply those lessons to study a kind of argument that we are going to call an immediate categorical inference.
Play video starting at ::26 and follow transcript0:26
So what's an immediate categorical inference? An immediate categorical inference is an inference with just one premise and, of course, one conclusion where each of those two statements, both the premise and the conclusion are of the form A, E, I or O. They needn't be of the same form. One of them could be, let's say of the E form and the other one of the O form or whatever. They needn't be of the same form, but they're each of one of those four forms.
Play video starting at ::59 and follow transcript0:59
Now, these are very simple inferences, but we're going to study them today because we're going to see how we can use Venn diagrams to show that some of these inferences are valid and others aren't.
Play video starting at :1:15 and follow transcript1:15
Now, before we do that, let me say something about the kinds of propositions that are involved with inferences, the A, E, I, and O propositions. Remember what those letter stand for. The A proposition is a propositions in the form all F's are Gs. All things that fall into one category also fall into a second category. An E proposition is a proposition of the form no Fs are Gs. Nothing that falls into the first category also falls into the second category. An I proposition is a proposition of the form some Fs are Gs. That's to say some thing that falls into the first category falls into the second category. And an O proposition is a proposition of the form some Fs are not Gs, right? Some thing that falls into the first category does not fall into the second category. Now notice, in each of those propositions, there's one category that I'm indicating by use of the schematic letter F. There's one category that gets directly modified by the quantifier, right? The F category, right? I'm talking about, in the A proposition, I'm talking about all things that fall into that category. In the E proposition, I'm talking about no things that fall into that category. In the I or the O proposition, I'm talking about some things that fall into that category. So there's a category that gets directly modified by the quantifier, and then there's another category that doesn't. Okay. Let's introduce terminology to distinguish these two categories. We'll talk about the two categories as the subject term and the predicate term.
Play video starting at :2:50 and follow transcript2:50
So that category that gets directly modified by the quantifier, the F category, is what we're going to call the subject term. And the category that doesn't get directly modified by the quantifier is what we're going to call the predicate term. You'll see in our later lecture about syllogisms why this terminology is going to be useful. It's not going to be obvious today why it's useful, but it'll eventually become useful.
Play video starting at :3:15 and follow transcript3:15
Okay. So, Fs are subject terms, Gs are predicate terms.
Play video starting at :3:22 and follow transcript3:22
And immediate categorical inferences are inferences that have one premise with a subject term and a predicate term, and one conclusion with a subject term and a predicate term. All right.
Play video starting at :3:37 and follow transcript3:37
What kinds of immediate categorical inferences are there? Well, there are lots. But the most common kind of immediate categorical inference is one that we'll call conversion. A conversion inference is an inference in which the conclusion just switches the subject term and predicate term as they occur in the premise.
Play video starting at :3:58 and follow transcript3:58
So, if the premise is of the form no Fs are Gs, let's say no Duke students are NFL football players. Then, the conclusion would be in the form of no Gs are Fs.
Play video starting at :4:17 and follow transcript4:17
No NFL football players are Duke students.
Play video starting at :4:21 and follow transcript4:21
That's an example of an immediate categorical inference that's a conversion inference. It converts one E proposition to another E proposition.
Play video starting at :4:33 and follow transcript4:33
You could do it for other forms of propositions. So, for instance, consider the conversion inference from an A proposition to another A proposition. Consider the inference from all Duke students are NFL football players to the conclusion all NFL football players are Duke students. Now, notice the first of those two conversion influences is plausibly valid, whereas the second one isn't.
Play video starting at :5:6 and follow transcript5:06
Why is that? Well, we can see why that is if we use Venn diagrams to visually represent the information contained in the premises of those inferences. More generally, I can say right now that conversion inferences are valid for propositions of the E and I form, but they're not valid for propositions of the A or O form.
Play video starting at :5:35 and follow transcript5:35
We can understand why that is using Venn Diagrams, right? So, why is it that conversion inferences from the A form to the A form are not valid? Why are they not valid? Well, let's consider.
Play video starting at :5:51 and follow transcript5:51
What are you saying when you say all Fs are Gs? Well, you're saying that whatever Fs there are, they're not outside the G circle. They're all in the G circle.
Play video starting at :6:2 and follow transcript6:02
So, you represent that information by shading in the portion of the F circle that's outside the G circle, in order to indicate that there's nothing there. Okay. But now, once you've shaded in that portion of the F circle,
Play video starting at :6:15 and follow transcript6:15
does that tell you that all Gs are Fs? No. Of course, it leaves open that all Gs are Fs. I mean, it could be that all the Gs there are, are in here.
Play video starting at :6:28 and follow transcript6:28
But shading in the portion of the F circle that's outside the G circle also leaves it open that there are plenty of Gs out here.
Play video starting at :6:38 and follow transcript6:38
So, once we look at the Venn diagram from the inference for all Fs or Gs to all Gs or Fs, we understand why that inference is not valid. All right, shading in the portion of the F circle outside the G circle leaves open that there are plenty of Gs that are outside the F circle.
Play video starting at :6:59 and follow transcript6:59
Okay. What about the second kind of conversion inference for propositions of the E form, from no F's are G's to no G's are F's?
Play video starting at :7:7 and follow transcript7:07
Well, let's see, how would we represent no F's are G's?
Play video starting at :7:11 and follow transcript7:11
Well, we do that by shading in the portion of the F circle that's inside the G circle. All right? So, that shows that no F's are in G the circle. No F's are G's. But now look, if no F's are G's, then we can just read off from that that no G's are F's. Right? If there are any G's, they can't be in the area that's shaded in, right? because what it means to shade in the area is that there's nothing there. So whatever G's there are, they can't be inside the F circle. They've got to be outside the F circle. So, if it's true that no Fs are Gs, then it's got to be true that no Gs are Fs. The Venn diagram for no Fs are Gs shows us that.
Play video starting at :7:55 and follow transcript7:55
So, conversion inferences are invalid for A propositions, but they're valid for E propositions. What about I propositions? Well, lets see. I propositions have the form some Fs are Gs. Well, how would we represent some Fs are Gs? We would indicate that there is something that's inside the F circle, it's an F, but it's also a G. It's in the G circle. We indicate it with an x. Okay. But notice, once we indicate by means of that x that there's something inside the F circle that's also inside the G circle, you can just read off from that that there's something inside the G circle that's also inside the F circle. In other words, some G's are F's. So, once again, from the Venn Diagram, you can see that if some Fs are Gs is true, then some Gs are Fs has gotta be true. In other words, the conversion inference for an I proposition has got to be valid.
Play video starting at :8:53 and follow transcript8:53
Okay. Finally, what about O propositions? Some Fs are not Gs. Well, let's see. Some Fs are not Gs. How would you diagram that? Well, some Fs, so you want to use an x to indicate that there is an F, but it's not a G. So it's gotta be outside the G circle. So, there. You draw an x that's inside the F circle to show that it is an F, but it's outside the G circle. So, it's not a G. That's how you represent that some Fs are not Gs.
Play video starting at :9:25 and follow transcript9:25
Okay. Now, does that imply that some Gs are not F?
Play video starting at :9:31 and follow transcript9:31
No.
Play video starting at :9:32 and follow transcript9:32
Maybe there are no G's at all for all that you've just been told. Right? You're told that some F's are not G. That doesn't tell you that there are any G's. Or if there are any G's, maybe all the G's are in here. You don't know whether there are any G's in here.
Play video starting at :9:51 and follow transcript9:51
So, from the premise that some Fs are not Gs, you can't infer that some Gs are not F. It doesn't follow that some Gs are not F. And the Venn Diagram shows us why.
Play video starting at :10:4 and follow transcript10:04
So, this last conversion inference on propositions of the O form is not valid. And, once again, you can see that from the Venn diagram for propositions of the O form.
Play video starting at :10:18 and follow transcript10:18
So, this shows how Venn diagrams, simple, two circle Venn diagrams, can be used to establish the validity or invalidity of immediate categorical inferences. Okay. Next time, we'll consider inferences of a more complicated kind. See you next time.

# Syllogisms
In the last class we talked about immediate categorical inferences, which are inference that have a single premise and a conclusion, where each of those two propositions is of the A, E, I, or O form.
Play video starting at ::16 and follow transcript0:16
Today we're going to talk about a new kind of inference called a syllogism.
Play video starting at ::21 and follow transcript0:21
So what's a syllogism?
Play video starting at ::24 and follow transcript0:24
Here's a definition.
Play video starting at ::26 and follow transcript0:26
A syllogism is an argument that has two premises and a conclusion, where all three of those propositions are of the form A, E, I, or O. Now, the conclusion is going to have two categories in it, one category that's modified by a quantifier, and we're going to call that the subject category. The other category is not modified by a quantifier, we're going to call that the predicate category. Now the subject category is what we call the subject term of the syllogism. The predicate category, the category that's not modified by a quantifier in the conclusion, that's what we're going to call the predicate term of the syllogism. Now every syllogism is going to have a premise that includes the subject term and another premise that includes the predicate term.
Play video starting at :1:20 and follow transcript1:20
Now the premise that includes the subject term is what we're going to call the minor premise of the syllogism. And the premise that includes the predicate term is what we're going to call the major premise of the syllogism. So every syllogism is going to have two premises where one premise is the minor premise. And it's going to include the subject term of the syllogism, which is the category that's modified by the quantifier in the conclusion of the syllogism. And the other premise is the major premise of the syllogism. It includes the predicate term of the syllogism, which is the category that's not modified by a quantifier in the conclusion of the syllogism.
Play video starting at :1:59 and follow transcript1:59
Okay, now let's look at how we can use Venn diagrams to represent the information that's carried by syllogisms, and so to assess whether or not a particular syllogism is valid. In order to visually represent the information that's given in the syllogism, we need to use a Venn diagram with three circles, not just two circles because in a syllogism we have three categories. We have the subject category, the middle term, the Gs, and the predicate term, the Hs. So, we need to get a Venn diagram with all three of those circles to represent the information contained in the syllogism.
Play video starting at :2:39 and follow transcript2:39
Now I've described all this very abstractly. Let me give some examples so you can see how this works and how we can use Venn diagrams like this to figure out whether or not syllogisms are valid and to explain why they're valid. Okay, so consider this syllogism. All Duke students are humans, all humans are animals, therefore all Duke students are animals. Okay, valid or not?
Play video starting at :3:9 and follow transcript3:09
Well, pretty obviously it is valid.
Play video starting at :3:13 and follow transcript3:13
But a Venn diagram could help us to understand why it's valid.
Play video starting at :3:17 and follow transcript3:17
So let's diagram the information contained in the premises. So the first premise, recall, was that all Duke students are humans. Well, if we want to show that all Duke students are humans, that's to say that whatever Duke students there are have got to be inside the circle of the humans. So this region of the Duke student circle, this region of the circle that's outside the circle of the humans, we can shade that in to indicate there is nothing there, right? Nothing here because whatever Duke students there are have got to be in this region.
Play video starting at :3:50 and follow transcript3:50
Okay, the second premise said that all humans are animals. Well, if all humans are animals, then what that tells us is that whatever humans there are have gotta be inside the circle of the animals. So we can shade in the portion of the humans circle that's outside the animals circle, right? Because there aren't any humans out there. So shade that in.
Play video starting at :4:14 and follow transcript4:14
Okay, but now we look at the diagram with those regions shaded in and what can we conclude? Well, we can conclude that whatever Duke students there are have got to be in this region right here. That's the only region where there could be any Duke students given the two premises of our argument. In other words, all Duke students are animals.
Play video starting at :4:43 and follow transcript4:43
And that's just the conclusion of our syllogism, remember? All Duke students are animals.
Play video starting at :4:50 and follow transcript4:50
So we just used the Venn diagram to explain why this syllogism, which is obviously valid, is valid. We explained why it is valid. It is valid because when you shade in the portion of the Duke students circle that's outside the humans circle and you shade in the portion of the humans circle that's outside the animals circle, the only place left over in the Duke students circle for there to be any Duke students is inside the animals circle. And so all Duke students are animals, as we all know. Now here's a second syllogism. Let's consider this one. Some Duke students are humans, all humans are animals. Therefore, some Duke students are animals.
Play video starting at :5:38 and follow transcript5:38
Valid, or not? Well, let's see. So, some Duke students are humans. How would we represent that information? Some Duke students are humans, what that means is that there's got to be something in this part of the circle of Duke students that's also in the circle of humans.
Play video starting at :6:3 and follow transcript6:03
But the first premise doesn't tell us where that thing would be. Would it be here, or would it be here?
Play video starting at :6:11 and follow transcript6:11
Well, let's hedge our bets and draw it right here since we don't know. We'll draw it on the borderline of the animals circle since the first premise doesn't tell us whether it's here or here, okay.
Play video starting at :6:26 and follow transcript6:26
The second premise said, all humans are animals.
Play video starting at :6:30 and follow transcript6:30
Okay, well, if all humans are animals, what that tells us is that there aren't any humans outside the animals circle. So we can just shade in the part of the humans circle that's outside the animals circle. All right, shade it in right there. But then notice, remember we have to have an x inside our Duke students circle and our humans circle inside the intersection. Well, it can't be in here because this is shaded in, which means there's nothing there. So this only place it can be is right there.
Play video starting at :7:6 and follow transcript7:06
So now we know that the x had to be over here. But once we've put the x over there, which we have to given the information in the two premises of our syllogism, what can we conclude? We can conclude that some Duke students are animals. And that's exactly what the conclusion of the syllogism is, is that some Duke students are animals.
Play video starting at :7:31 and follow transcript7:31
Finally, that should say example three, not example one. Finally, consider this syllogism. No Duke students are humans, all humans are animals. Therefore, no Duke students are animals.
Play video starting at :7:45 and follow transcript7:45
Okay, now how would we represent that using the Venn diagram? Well, no Duke students are humans.
Play video starting at :7:51 and follow transcript7:51
So that means that we have to shade in the portion of the Duke students circle that's inside the humans circle to show that there's nothing in there, right? None of the Duke students are humans.
Play video starting at :8:6 and follow transcript8:06
Okay, all humans are animals, so that means we have to shade in the portion of the humans circle that's outside the animals circle, all right?
Play video starting at :8:18 and follow transcript8:18
Because there are no humans out there. All humans are animals, all right?
Play video starting at :8:27 and follow transcript8:27
And the conclusion was that no Duke students are animals.
Play video starting at :8:32 and follow transcript8:32
But wait a second, you can't read that off the diagram. There could be lots of Duke students over here who are animals. There could be all sorts of Duke students who are animals right there. They wouldn't be human, but there could still be plenty of Duke students that are animals.
Play video starting at :8:52 and follow transcript8:52
In other words, this third syllogism is not valid. And it's not valid for reasons made clear by the Venn diagram that we just looked at. The Venn diagram shows us that and explains why the inference, the syllogism, is not valid. Just because no Duke students are human and all the humans are animals, it doesn't follow that no Duke students are animals. Those premises leave it open that there are plenty of animal Duke students. They just wouldn't be the humans.
Play video starting at :9:24 and follow transcript9:24
So, in this lecture, I've tried to show how we can use Venn diagrams to predict that and to explain why syllogisms are valid or invalid, as the case may be.
Play video starting at :9:39 and follow transcript9:39
Next time we'll apply these lessons to some examples that we've already looked at before, but that we weren't treating as syllogisms when we looked at them before.

# Categories, Individuals, and Language
In the last few lectures, we've been seeing how we can use Venn diagrams to predict that and to show why, explain why certain immediate categorical inferences and certain syllogisms are valid or invalid. Now, I'd like to make a point today about categorical logic, about categories in general. It might seem that the application of the method of Venn diagrams is really quite limited, because a lot of our statements aren't really about categories at all. They're about individuals, not categories.
Play video starting at ::43 and follow transcript0:43
But I want to say that this is an example of how ordinary language can mislead us.
Play video starting at ::50 and follow transcript0:50
If we think about precisely what it is that we're saying in a lot of the ordinary statements that appear to be about individuals, we'll see that, in fact, those ordinary statements really are about categories and not just about individuals. Let me give you an example to illustrate this point.
Play video starting at :1:10 and follow transcript1:10
Consider the statement, Mary owns a Ferrari. Now, that statement appears to be just about individuals, it doesn't appear to involve any categories, right? There's Mary, who let's suppose is a particular person that I'm talking about, like a co-worker of mine. Not that any of my co-workers would own a Ferrari, but suppose that Mary is a particular person. And we're talking about Mary's Ferrari, which is a particular car, and It seems that that statement is just claiming that the person, the particular person I'm talking about owns that particular car, right? There don't seem to be any categories involved at all.
Play video starting at :1:53 and follow transcript1:53
But wait a second.
Play video starting at :1:57 and follow transcript1:57
Compare the statement Mary owns a Ferrari to the statement some of Mary's possessions are Ferrari cars.
Play video starting at :2:6 and follow transcript2:06
Now, that second statement, notice, is of the I form. It's of the form some Fs Are Gs. You're saying some things that fall into one category, the category of Mary's possessions, also fall into a second category, the category of Ferrari cars.
Play video starting at :2:30 and follow transcript2:30
Now, these two statements seem to amount to the same thing. When I say, Mary owns a Ferrari, what I'm saying is true if, and only if, some of Mary's possessions are Ferrari cars. The information carried by one of those statements seems to be the same as the information carried by the other.
Play video starting at :2:58 and follow transcript2:58
So here's a case where
Play video starting at :3: and follow transcript3:00
to look at the language we were using when we said Mary owns a Ferrari, you would have thought, well, we're not talking about any categories there. So the method of Venn diagrams, and all of this stuff about categorical logic, is completely irrelevant to any argument we might make that uses the statement, Mary owns a Ferrari, used either as a premise or as a conclusion.
Play video starting at :3:23 and follow transcript3:23
But in fact, that's not true.
Play video starting at :3:25 and follow transcript3:25
In fact, the statement that Mary owns a Ferrari is equivalent to the statement, some of Mary's possessions are Ferrari cars, which is a statement of the I form, some Fs are Gs.
Play video starting at :3:38 and follow transcript3:38
And so the categorical logic that we've been developing this week in the method of Venn diagrams actually can be used to study the validity of arguments where the statement, Mary owns a Ferrari, is included as one of the premises or is the conclusion.
Play video starting at :3:56 and follow transcript3:56
Because the statement, Mary owns a Ferrari, is just equivalent to the statement of the I form, some of Mary's possessions are Ferrari cars. I want to say this phenomenon is very general. Not every statement is of the A E I or O forms, but lots and lots of ordinary statements that we make are of one of those forms,
Play video starting at :4:21 and follow transcript4:21
many more than ordinary language would suggest. So with that in mind, I want now to show how we can apply the categorical logic, how we can apply the lessons we learned concerning the validity of syllogisms and how we can use Venn diagrams to predict and explain the validity of syllogisms. How we can now apply those lessons to arguments that
Play video starting at :4:48 and follow transcript4:48
are syllogisms, but you wouldn't think that they are just to look at the language in which they expressed. Okay, see you next time.

# Venn Diagrams and Validity
Today we're going to talk about how you can use Venn Diagrams to show that a particular inference is valid and to explain why it's valid. >> [SOUND] >> We're going to do that by considering the particular inferences, the particular arguments that we looked at at the beginning of last week, when we were starting our unit on deductive logic. So let's look at those inferences right now. Remember the first one was the example of Walter gave back in week three, our argument about Mary. Premise one was Mary has a child who is pregnant. Premise two was only daughters can become pregnant. And so the conclusion of those two premises was therefore, Mary has at least one daughter.
Play video starting at ::54 and follow transcript0:54
Okay now how do we represent the information contained In the premises of this inference using a Venn diagram. Well let's begin by asking what are the categories that this inference that this argument brings into relation with each other. Is Mary one of the categories?
Play video starting at :1:17 and follow transcript1:17
Well no, because Mary's not a category. Mary is an object. Mary is a thing. She's a particular thing. She's not a category.
Play video starting at :1:26 and follow transcript1:26
What is a category though that's mentioned in this argument is Mary's children.
Play video starting at :1:34 and follow transcript1:34
And the information in the first premise is that the category of Mary's children includes something that is also in the category of pregnant people, or pregnant beings. So we can visually represent that information as follows. The category of Mary's children includes something that's in the category of pregnant people. Right, so we don't know whether or not the category of Mary's children includes anything out here, but whether or not it includes anything out here, it's got to include something that's in this region.
Play video starting at :2:24 and follow transcript2:24
So do we draw an X?
Play video starting at :2:27 and follow transcript2:27
Well, let's wait a minute. Let's ask, where would we draw that X? Would we draw it here or would we draw it here?
Play video starting at :2:36 and follow transcript2:36
That's going to make a difference.
Play video starting at :2:38 and follow transcript2:38
That's going to make a difference where we draw it. So we don't yet know whether to draw the x in here or in here.
Play video starting at :2:46 and follow transcript2:46
We know though, that the x is supposed to go somewhere in this
Play video starting at :2:52 and follow transcript2:52
football shaped region, that's in the intersection of the category of Mary's children and the category of pregnant people.
Play video starting at :3:1 and follow transcript3:01
Maybe premise two will help us figure out where to draw that x. Let's see.
Play video starting at :3:8 and follow transcript3:08
So premise two says only daughters can become pregnant.
Play video starting at :3:12 and follow transcript3:12
So how do we visually represent the information that only daughters can become pregnant? Well only daughters can become pregnant means that there can't be any pregnant people who are not daughters. So we have to shade out the circle, the portion of the circle of pregnant people that's outside the circle of daughters.
Play video starting at :3:37 and follow transcript3:37
Right? There can't be any pregnant people who are outside this circle.
Play video starting at :3:44 and follow transcript3:44
All the pregnant people are inside this circle. Okay, but remember what did premise one tell us. Premise one told us that Mary has a child who is inside this circle. So here is what we know. Mary has a child who is inside the circle off pregnant people.
Play video starting at :4:3 and follow transcript4:03
And anyone who's inside the circle or pregnant people must also be inside the circle of daughters. Well so Mary's child who's inside the pregnant people circle, must be right here.
Play video starting at :4:17 and follow transcript4:17
So that's where the X goes.
Play video starting at :4:19 and follow transcript4:19
So what we can figure out, from just the first two premises. Remember I haven't relied on any information here other than the information given in premises one and two. What premises one and two tell us is that there's an x and it goes right here.
Play video starting at :4:37 and follow transcript4:37
Okay but if the x goes right there, then what does that tell us? That tells us that at least one of Mary's children is a daughter.
Play video starting at :4:48 and follow transcript4:48
Mary has at least one daughter.
Play video starting at :4:52 and follow transcript4:52
Maybe she has more than one daughter, but we know based on the information contained in premises one and two, we can conclude that she has at least one daughter. We know that for sure based on the information contained in premises one and two.
Play video starting at :5:7 and follow transcript5:07
So if the information contained in premises one and two is correct, then Mary must have at least one daughter, and so the argument is valid. And the Venn diagram shows us that the argument is valid, because once we visually represent the information contained in premises one and two, then we can simply read off the diagram that the conclusion is true. We can read off the diagram that Mary has at least one daughter.
Play video starting at :5:33 and follow transcript5:33
Okay, now let's see if we can apply this technique to the other arguments of the same form that we considered at the beginning of last week. Remember, we considered an argument concerning Terry. Premise one was Terry has a job in which she arrests people.
Play video starting at :5:52 and follow transcript5:52
Premise two was only police officers can arrest people.
Play video starting at :5:57 and follow transcript5:57
And the conclusion of those two premises was therefore at least one of Terry's job is as a police officer.
Play video starting at :6:4 and follow transcript6:04
Now, how would we visually represent the information contained in the premises. Well, Let's consider. Premise one tells us that Terry's jobs includes a job in which she arrests people.
Play video starting at :6:26 and follow transcript6:26
Right? So at least one of Terry's jobs has to be in this circle, because whatever else it is that Terry does she has a job in which she arrests people, so at least one of here jobs must be in this circle. And of course it has to be in this circle because that's the circle of Terry's jobs. So, at least one of Terry's jobs must be in this football shaped region right here, in this intersection of the category of Terry's jobs and professionals who arrest people.
Play video starting at :6:58 and follow transcript6:58
That's what premise one tells us. But again, it doesn't tell us where that particular job of Terry's would be. Is it here? Or is it here?
Play video starting at :7:10 and follow transcript7:10
Premise one doesn't give us that information.
Play video starting at :7:14 and follow transcript7:14
What does premise two tell us? Remember, premise two tells us that only police officers can arrest people, so how would we visually represent that? Only police officers can arrest people. That means that in the circle of professionals who arrest people, we have to shade in this part because there are no professionals who arrest people other than police officers. Only police officers arrest people, so we shade in that portion of the Professionals who arrest people circle. Now remember what we learned from premise one, was that Terry has a job in which he arrests people. So somewhere in this football shaped region, there has to be an x, but we know now that it can't be here. So the x must be here.
Play video starting at :8:14 and follow transcript8:14
So that's the information that we get from premises one and two. But notice once we visually represent that information in our Venn diagram then we can simply read off the Venn diagram. That Terry has a job, at least one job in which she's a police officer. So at least one of Terry's jobs is as a police officer.
Play video starting at :8:40 and follow transcript8:40
And we can just read that off the Venn diagram once we've used the Venn diagram to represent the information contained in premises one and two. So the Venn diagram again can be used to represent the validity of the inference.
Play video starting at :8:54 and follow transcript8:54
And not only that, notice also that the Venn diagram for this inference, is the same in the placement of its shading and its X's, as the Venn diagram for the previous inference about Mary. Well, what does that tell us? That tells us that the two inferences, the two arguments are of the same form.
Play video starting at :9:19 and follow transcript9:19
They're of the same form, and you can see that by seeing that their Venn diagrams look the same. The only difference between the two Venn diagrams is the labeling of the circles, is the categories, the specific categories involved in the argument. Other than the specific categories involved in the arguments, the labeling of the circles, everything else is the same. The shading is in the same place, the X is in the same place.
Play video starting at :9:47 and follow transcript9:47
Okay, now. Can we apply this to our third argument about Robert? You'll remember this third argument that we considered of the same form. At the beginning of week four, at the beginning of our unit on deductive logic. Remember, we considered an argument that went like this. Premise one, Robert has a pet who is canine.
Play video starting at :10:6 and follow transcript10:06
Premise two, only mammals are canine. Conclusion, therefore at least one of Robert's pets is mammal. Okay, well how would we visually represent the information contained in premises one and two of this argument? Here's how. At least one of Robert's pets is canine so that means that whatever other pets Robert has, right? Maybe Robert has some non-canine pets. But at least one of Robert's pets must be in this circle.
Play video starting at :10:37 and follow transcript10:37
Well, that particular pet that we're talking about has to be in this circle, but of course, it also has to be in this circle because this is the circle of Robert's pets. So the pet must be in this football-shaped region right here, the intersection of Robert's pets and canines.
Play video starting at :10:55 and follow transcript10:55
But where is it? Is is here or is it here?
Play video starting at :10:58 and follow transcript10:58
Well, now, let's look at premise two. What do we find out from premise two? What we find out from premise two is that only mammals are canine. Okay, well, if only mammals are canine, then that means
Play video starting at :11:11 and follow transcript11:11
that there can't be any canines outside the circle of mammals. Right, all the canines. Whatever canines there are, are in this region right here.
Play video starting at :11:26 and follow transcript11:26
There aren't any canines outside the mammal circle.
Play video starting at :11:30 and follow transcript11:30
So we know that whatever canines there are have to be in this intersection right here, the circle of canines and the circle of mammals. And we also know that Robert has at least one pet in the circle of canines. If Robert has a pet in the circle of canines, and we also know that there's nothing in the circle of canines that's over here, then we know that Robert's pet which has to be in this circle, right this is the circle of Robert's pets. Robert's pet has got to be in here. Right, the pet that we're talking about, the pet that's canine has got to be in there.
Play video starting at :12:13 and follow transcript12:13
Okay so that's a way of visually representing the information contained in the two premises of our argument. But once we visually represent that information we can just look at the diagram and read off the fact that at least one of Robert's pets is mammal.
Play video starting at :12:32 and follow transcript12:32
because at least one of the Robert's pets is inside the circle of mammals. Right? Inside this circle, which means that at least one of Robert's pets is mammal.
Play video starting at :12:41 and follow transcript12:41
But that's exactly what the conclusion says.
Play video starting at :12:45 and follow transcript12:45
And so this Venn diagram shows us that this argument about Robert is valid just as the arguments about Mary and Terry were valid. Furthermore, this argument about Robert is valid, for the same reason as the arguments about Mary and Terry were valid. They're valid not because of their subject matter, right. The three arguments have completely different subject-matters. They're valid because of their form. And their form is what's revealed by the Venn diagram. The form is what's in common to the three Venn diagrams. The placement of shading and X's in the Venn diagrams is their common form and that's what explains why all three of the arguments are valid.

# Other Ways of Expressing A, E, I, or O Propositions
In the last few lectures, we've seen how we can use Venn diagrams to visually represent the information that's conveyed in A,E,I, or O propositions. And we've also seen how there are different ways in ordinary language of expressing such propositions. Sometimes such propositions are expressed even by sentences that use individuals name. And don't explicitly mention categories. Today I want to talk a bit more about that. I want to talk about the various ways in which, in English at least, and in many other natural languages, we can represent the information conveyed by A, E, I or O propositions using forms of language that we haven't yet discussed.
Play video starting at ::51 and follow transcript0:51
So let's consider some examples. So consider propositions of the form, not all Fs or Gs. We haven't talked about not all before. When you say not all Fs or Gs. What exactly are you saying? Usually when you say not all Fs or Gs, what you mean to be saying is that there are some Fs that are not Gs. In short, what you mean to be saying when you say not all Fs or Gs, is usually a proposition of the O-form.
Play video starting at :1:28 and follow transcript1:28
So, how would you represent not all Fs or Gs? Well, all Fs or Gs, remember, would be represented by shading this out. That would be all Fs or Gs. But you're saying not all Fs or Gs. In other words, some Fs are not G. So instead of shade there what would you do is put an x right there. There's some F, something out there, that's not a G, it's outside the category of the G's.
Play video starting at :1:59 and follow transcript1:59
And for some examples you might say, not all geniuses take Coursera courses. In other words, some geniuses don't take Coursera courses.
Play video starting at :2:12 and follow transcript2:12
Or you might say not everything that Pat does is intended to annoy Chris.
Play video starting at :2:18 and follow transcript2:18
In other words, some of the things that Pat does, some of the things that fall into the category. Things that Pat does are intended to annoy Chris. That is to say, they do fall into the category of things that are intended to annoy Chris.
Play video starting at :2:37 and follow transcript2:37
So those are both examples of statements of the form not all Fs are Gs, and they're both equivalent to a statement of the form some Fs are not Gs.
Play video starting at :2:51 and follow transcript2:51
Now consider statements of the form all Fs are not Gs.
Play video starting at :2:57 and follow transcript2:57
Well, when you say something of the form all Fs are not Gs, that's usually intended to convey that no Fs are Gs. In other words, it's usually intended to convey a proposition of the E form.
Play video starting at :3:11 and follow transcript3:11
So whenyou say no Fs or Gs. How do you represent that? Well, you represent it by shading in the intersection of the Fs and the Gs. And that's just to say that all Fs are not Gs. Right? If there are any Fs at all they've got to be out here. They've got to be outside the category of the Gs.
Play video starting at :3:29 and follow transcript3:29
Some examples of statements like that.
Play video starting at :3:32 and follow transcript3:32
All Nobel Prize winners are not alcoholics.
Play video starting at :3:37 and follow transcript3:37
You're saying, if there are any Nobel prize winners, they're outside the category of the alcoholics.
Play video starting at :3:45 and follow transcript3:45
Everything that Pat does is not designed to achieve victory.
Play video starting at :3:51 and follow transcript3:51
Again, you're saying that whatever falls into the category of things that Pat does,
Play video starting at :3:58 and follow transcript3:58
it is outside the category of things designed to achieve victory.
Play video starting at :4:5 and follow transcript4:05
All right, so if this is the category of Pat's actions. And this is the category of things designed to achieve victory.
Play video starting at :4:25 and follow transcript4:25
Then when you say everything that Pat does is not designed to achieve victory, you're saying there's nothing in this intersection. Whatever Pat's actions are, they've gotta be out here.
Play video starting at :4:37 and follow transcript4:37
Okay, finally, let's consider a statement of the form some Fs are both Gs and Hs. If you say some Fs are both Gs and Hs, what are you saying?
Play video starting at :4:50 and follow transcript4:50
Well are you saying that there are some Fs that are Gs, and some Fs that are Hs.
Play video starting at :4:59 and follow transcript4:59
Well, that's something you could say of course. You could say some Fs are Gs, and some Fs are Hs, right? Some, you could say some men are tall, and some men are short.
Play video starting at :5:9 and follow transcript5:09
But when you say some Fs are both Gs and Hs you're not saying that, you're saying that some Fs are in this intersection of Gs and Hs, right? So, some Fs have going to be here, that's what you're saying when you say some Fs are both Gs and Hs, right? That's why you couldn't truthfully say some men are both tall and short, right? There is no man who is both tall and short. But you could say there's some men who are both wealthy and happy.
Play video starting at :5:44 and follow transcript5:44
There a man who is wealthy and who is happy. Other examples, some philosophers are both robotic and monotone, right? It's not just that there's some philosophers who are robotic and some philosophers who are monotone. There are actually some philosophers who are both robotic and monotone.
Play video starting at :6:4 and follow transcript6:04
Some of the things that Pat does are both intended to amuse and to provoke, right? It's not just that some of the things she does are intended to amuse and some of the things she does are intended to provoke. It's that some of the things she does are intended to do both amuse and to provoke. So, if these are Pat's actions right here. And this is the category of things intended to amuse, and this is the category of things intended to provoke. Then this last statement, some of the thing that Pat does are both intended to amuse and to provoke. It's saying that some of Pat's actions fall into this area right here. This intersection of things designed to amuse and things designed to provoke. But of course since they're Pat's actions, they have to fall into this portion of the area right here.
Play video starting at :7:1 and follow transcript7:01
Okay. I hope I've given you a sense of the various ways in which ordinary language can express ideas that we can represent visually using Venn diagrams.
