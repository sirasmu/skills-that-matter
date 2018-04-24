![great engineer][great]

[great]: https://github.com/sirasmu/skills-that-matter/blob/master/great.PNG?raw=true

Source: https://faculty.washington.edu/ajko/papers/Li2015GreatEngineers.pdf

# Logbook
Self improvement - Reflection and findings

Hi, I am not entirely sure what I want to do with this repo yet. Maybe throw in some cool diagrams, articles, my thoughts on my findings, cool code snippets. As I said I am not sure. However, I do think it is important that I write and document more, so the knowledge from today wont be lost by tomorrow.

https://faculty.washington.edu/ajko/papers/Li2015GreatEngineers.pdf

## Log 2017-12-12

So I was wondering what type of developer do I want to be? Which skills should I focus on? Currently I am learning Vim, but isn't that kind of an useless skill? Well it is not, because it is good to know a terminal based editor. I also see a benefit for writing notes in Markdown. Should I learn Emacs/Spacemacs? Well, I don't know. I think then I should consider which kind of workplace I would like to fit into and which languages I would like to use. Being a .NET developer it just makes sense to be using Visual Studio. However, I do not wish to be trapped within one environment. Do I care too much about tools? Probably yes. I should focus more on creating. Here are some languages that I have considered learning:

* C - I just really like C. I honestly don't really feel attracted to object oriented languges after I started working with C. There is minimal magic going on behind the scenes. It is just sort of beautiful and does not seem bloated.
* Python - Seems interesting. I have written a few small Python programs, but I do not feel like I am knowledgeable
* C# - A powerfull tool. I should become better at .NET
* Bash - Honestly I just want to learn more about shell scripts
* GO - I know nothing, but it seems interesting
* Rust - Heard well of it. Probably something I should look into when I am more experienced

Ok, so maybe it would be worth it for me to look into something like Spacemacs. Obviously not for C#. Also I quite like Atmel Studio for C and Assembly. I might also consider going into C++. I have been reading the book `Coders at Work` recently and no one seemed to like C++. I think beginners should start with object oriented languages so that they can form their mental model around that concept, but I am not sure that I actually would like to stay within the object oriented world. I should probably still become more well aquinted with C++. 

So far I have used Vim for Python and Bash. As such I think it might be worth it to learn Spacemacs. Today I saw a quite interesting video on the usage of git together with Spacemacs, which seemed very appealing to me. One of the reasons I wanted to learn Vim was so that I would not have to leave the terminal, which makes it more confortable to update git repositories right away after editing a file.

These are my muddied thoughts from today. I think I kind of care about the wrong things though, but it was great to try to sought out some my thoughts. For the next while I will probably mostly work with C# and Javascript, though. At least that is what I exspect that will be required of me. I don't think I like dynamic types, but maybe I will like Javascript once I have become more experienced. I just found the language to be kind of messy. That is maybe because it was one of the first languages I worked with and thus it troublesome that it was seemingly less structured.

## Log 2017-12-17

Lately, I have been reading about the Free Software Foundation. I read a bit about their coding standards and such. Then I started to look up cool Free Software. Findings:

- https://meet.jit.si
  * What: Web video conference, chat, screen sharing
  * Pros: You don't need to login; Easy screen sharing; Has shared documents
  * Cons: Seems imcomplete; I think the chat should be a more emphasized element; Doesn't seem like you can upload files

- https://puri.sm/shop/librem-5/
  * What: Phone with a GNU+Linux Operating System
  
 - Other cool stuff.....
 
 I think it is important as an engineer you consider the ethicality of what you build, so I find this really interesting.

## Log 2017-12-18

Talking about ethicality FSF / FOSS... Check this out

- https://librecmc.org/github.html
- https://gogs.io/

## Log 2017-12-19

### Todays reflection

I think to me it is important to have a clear conscience. Whether that is towards my employer or towards the people using the product. Now I have not yet been in a situation where I have to consider the ethicality of someone else using MY product. And I am not sure whether when it comes to it that I would actually care. However, I do know that I do not mind doing something against my own interest if that means I can go home and have a clear conciounce. Is this an important trait? Maybe less so, but I do think it is a trait I have and it would be nice if we had a world with less malicious intent.

When I look over the paper *What Makes A Great Software Engineer* I wonder whether I may some day be *great*. I do certainly try to improve myself. And I know I have improved immensely over just the past 2 years. Especially considering my starting point. I was an incredibly nervous person afraid of interacting with other people and were barely able to write a program. I have become more talkative, I volunteer to do presentations for people about technical subjects, I have stepped out of my comfort zone to take my life into the direction I would like, I have learned immensely and I was told that my code for a real-time embedded system was among the best my teachers had seen. I have been able to push myself when I did not believe in myself and yet come out with something pretty solid. I have been playing around with different technologies in my sparetime and gotten quicker at solving some technical issues. Well, this rant is really more for myself. As is this logbook. However, I do think I can feel proud of myself. 

I have never considered myself a passionate person. I always felt that was something I lacked. I think I do have my few pet subjects that I am passionate about. As for the passionateness descriped in *What Makes A Great Software Engineer*... It is about being passionate about ones job, being *intrinsically interested in the area they are working in, and not
just for extrinsic rewards such as money*. Well that is true for me. An important thing to keep in mind:

“I think that there are people who are great software engineers who are in the wrong place and aren't motivated and they end up not performing well.” -Principal Dev Lead, Dynamics

I think this is rather important as passion can vary. Not just about a subject/field, but also for the task at hand and one's workplace. I think it should be considered that having dispassionate employees is harmful. It may be they are truly passionate about the field, but just have no motivation regarding the task at hand. Something like that ought to be avoided as it would be in everyones interest to have happy and motivated employees. What would be important here is to figure out in which niche we each thrive.

Another quality mentioned in *What Makes A Great Software Engineer* is *open-minded*. To me the desciption of this sounds more like flexibility, foresight, being prepared to update your mental models and understandings according to keep it concurrent with the present world and the latest data. Also being willing to listen to others.

### Rust

I have started looking into Rust. It has my interest. I think I might be more interested in Rust that Python and Go. So far I really like the syntax of what I have seen and the description of the language sounded awesome! I compilled and ran a small program. Time to try out some more :) 

## Log 2018-01-06

Today I found yUML. Interesting UML tool.

![UML test][yUML-test]

[yUML-test]: http://yuml.me/diagram/class/[TestX]<>1-*>[TestY]

## Log 2018-04-17

Current goal is to learn CI/CD. For this I will be looking at Travis CI, TeamCity, Jenkins, Octopus Deploy + Tentacles and Resin.io. Current goal is to figure out how to keep values secret, but still have the correct ones upon deployment. I have to look into ENV variables. Currently I am working on a Python3 project with a Discord bot. I use Travis CI for it and it is the plan to try out Resin.io. The project is of now in a private git repository and I want to figure out how to use maybe ENV variables to see how I can make it public, but keep sensitive data hidden. Then I want to make a similar bot, but this time in Rust and with trying out Jenkins and Octopus Deploy instead. Just so that I get a broad familiarity with the tools and will be able to see what benefits they each have.

## Log 2018-04-22

### *Get your message across! Strengthen you personal power* with Natasha Swerdloff and Dorte Koch

This Friday I and the other students at my workplace was sent to a course about personal development. I found it quite interesting. There are a few things I want to go through so I can remember them for furture use and improvement. The course was divided into two parts.

**Part 1**
* Use Ethos to inspire trust in your audience. Establish why you they should listen to you. E.g. by your company or experience.
* Control your emotions by controling your breath
    * It is important to squeeze all the air you have in your lungs out, this well force you to take a deep breath which will have a calming effect. I have already used it a few times over the weekend and I feel like it really does work.
    * You can more easily breath well if you have a good posture, which is both good body language, but will also effect your mood. Don't pull your soldiers back, that is too much. Just imagine a straight line towards the ceiling.
* Speak loud and deep. This will make it more pleasant to listen to you and thus inspire trust
    * E.g. do an exercise where you say "HAAAMMMMAAAAA" and make sure to expand your throat/mouth area as much as possible
    * Imagine that you speak towards the far end of the room. Don't speak to your toes!
* People usually only keep the Speaker, Topic and Verbalisation/Visualisation in mind. You should also remember the Audience and the Context!

**Part 2**

* Do not dwell on why you do not feel well
* Do not blame others for how you feel / People do not effect your emotions - Your thoughts do
* The Cognitive Diamond gives a model for how what you do and what state you are in has an effect. Maybe you don't know how to think positive thought, but you can indirectly effect your thoughts with your behaviour and vice versa.

        Thoughts
        /       \
 Behaviour      Feelings
        \       /
           Body
           
*Learning styles (lowest score 24, highest score 48)*

* Logical (40 points)
    * What is wrong? Quality. Optimizing. Why waste time. Get to the point. Organizes meaning internally and sees how it is applicable in other situations. Sequential thinking. Learn systematically to keep track of information. Short precise sentences. Needs clear introductions. Asks questions till subject is understood. Use metaphors and listicles. Does not like long stories and prefers precise summaries. Speaks in short/curt sentences. Use the fish structure when presenting (head, body, tail).
* Visual (30 points)
    * I got it. Impatient. Color attentive. Aesthetics. Breathes shallowly and fast. Talks fast in short sentences with a high tone. Quickly gets an overview. Use diagrams.
* Auditory (26 points)
    * Ask them questions. They will also ask you questions. They like stories. Good at remembering what they were told word by word, but might not necessarily understand it. Thinks by talking internally/externally. Disturbed by noise. Abdominal breathing. Talks in long sentences and monotone. Learns well with verbal instructions. Use word play.
* Kinesthetic (24 points)
    * RTFM! Yeah nope not gonna do that. Does it feel right? Do I trust this person? Likes side stories. Wants to practise and do exercises. Offended by people who are being short and concise. Inspire trust e.g. by giving food or be entertaining. Responds well to touch. Breathes deeply. Speaks slowly in a deep tone of voice. Learns by doing and touching.

This seems explain really well why I prefer some teaching styles. T hat people learn differently should always be kept in mind when teaching someone else. This model also makes a lot of sense to me. I have always seen myself as a visual person, but I am actually not that visual. I make some sort of connections in my head that I am not quite sure how to descripe. I use visual aids a lot to make connections and understand how something works, but it is somehow more about how it relates to something else. 
