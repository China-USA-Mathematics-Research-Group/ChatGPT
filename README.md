# The future of mathematics? 
Link: https://www.ma.imperial.ac.uk/~buzzard/one_off_lectures/msr.pdf (Research slideshow)

# How will AI change mathematics? Rise of chatbots highlights discussion (Nature article)
Link: https://www.nature.com/articles/d41586-023-00487-2

# Theorem Proving in Lean
Link: https://leanprover.github.io/theorem_proving_in_lean/
PDF Version

# Using Lean for teaching
In the 2018–19 academic year, I taught Imperial’s introduction to proof course again, this time using Lean live in the lectures for some of the proofs. For example, I proved that a composite of surjective functions was surjective in Lean, I proved various results about equivalence relations in Lean, and I proved Cantor’s diagonal argument in Lean. I wrote the code live during the lectures, projecting my laptop onto the screen, but I also circulated “traditional” proofs in the course notes afterwards. All of this was done under the watchful eye of Athina Thoma, a specialist in mathematical education, who interviewed and surveyed the students and is writing up her conclusions for a forthcoming publication with Paola Iannone, another such specialist based in Loughborough. This approach was completely new to both me and the students, and I note with interest that their performance on the (conceptually complicated) question about binary relations on the end of year exam was done very well. Of course one has to be careful here; not all the students will want to see mathematics being done with computers, and of course these students should not be disadvantaged by such an approach. However I did think it was important that the students learnt, as early as possible, what a logical argument looked like, and how a logical argument is something which can be explicitly checked by an algorithm. This is not how mathematics is taught in schools but it seems to me to be a crucial message which an introduction to proof course in a mathe- matics department should convey. Patrick Massot is also using Lean in the mathematics department at Orsay, in his introduction to proof course.

On Thursday evenings during term time I run a Lean club at Imperial called the Xena Project (with asso- ciated blog at xenaproject.wordpress.com), where undergraduates learn to formalize the mathematics which they are learning in lectures, and any other mathematics of interest to them. One purpose of the project is to make knowledge of formalisation more prevalent amongst the undergraduate community, just as knowledge of LaTeX now is. Another purpose is an ongoing project to completely digitise the pure mathematics part of Imperial’s undergraduate curriculum.

I have also used Lean for outreach, showing schoolkids how to prove things like 2 + 2 = 4 from the axioms of Peano arithmetic and then raising the question of how much more mathematics can be done like this.

# Using Lean to help with research?
Currently, the only thing that Lean can offer the researcher is a “certificate” that any theorem they have formalized in Lean is indeed correct. Many humans feel that they do not need this certificate. I find it interesting that more and more mathematics relies on unpublished work; talk to any pure mathematician in any big area and they will know of some theorems which rely on results in the “grey literature” (a letter or an email from X to Y) or even results which are not in the literature at all (“a forthcoming paper”, sometimes announced years ago and which never came forth). 

Humans are good at forgetting to go back and fill in these details. Lean will not let you forget. The computer-generated red squiggly line underneath your theorem reminds you that your proof is not complete, even if your work relies on results announced by others and hence “it is not your job to complete it”. During our work formalizing perfectoid spaces, it got to the point where I knew “we had done it”, but until the definition compiled we knew we had not convinced Lean. Another issue is the fact that formalising the proof of a big theorem like Fermat’s Last Theorem, given the state of the art, would surely take more than 100 person-years. Getting money for this would involve a grant proposal which no grant agency would fund, and which would yield a result which no mathematician would care about anyway — we all know Fermat’s Last Theorem is true, because we know the experts have accepted the result.

Because Lean is offering something that pure mathematics researchers do not generally want (a fully formalized verification of their theorems) at a price which researchers generally will not pay (the time taken to learn how to use the software, and then the time taken to formalize their own proofs), in practice one has to rule this out as a viable practical application of these tools at this point in time. Things might change in the future, but rather than speculate on how good computers can or will become at understanding natural language (i.e., arXiv preprints), let me simply observe that currently they are nowhere near good enough, and instead turn to other things.

Already computer scientists are trying to develop tools which can actually do mathematics better than humans. They want to train their AI on databases — but these databases are few and far between, and several of the databases which are used in practice are databases of solutions to gigantic logic puzzles which bear no relation to modern mathematics. I believe that it is up to us as a community to explain to computer scientists what we are actually doing, in a format which is more useful to them than tens of thousands of arXiv preprints where we use words like “normal” and “complete” to mean five different things and where we write in the idiomatic and bizarre English language, thus adding another layer of obfuscation to the material. Formalisation solves this problem — it makes us say what we mean in a clear and coherent manner. This is what these people need to make tools for us — and we are not giving it to them. Mathematicians do not seem to have any desire to formalise a proof of Fermat’s Last Theorem, however computer scientists are desperate to train their AI’s on a formalised proof, to see how much further they can take things. If any mathematician reading this decides that they would be interested in taking up the challenge of formalising the statement of one of their theorems in Lean, then they can find me at the Zulip lean chat.

Computer scientists do not understand a lot of what we as mathematical researchers do, or how we do it. Let’s tell them in their own language, and see what happens next. Computer scientists have developed tools which can eat mathematics, but until these tools get more self-sufficient they will need to be hand-fed. It will be very interesting to see what these tools become as they grow.

# FURTHER READING
[1] H. Bender and G. Glauberman, Local Analysis for the Odd Order Theorem, Cambridge University Press, 1994.

[2] S. Gouezel and V. Shchur, A corrected quanti- tative version of the Morse lemma, J. Funct. Anal. 277 (2019) 1248–1258.

[3] T. Peterfalvi, Character Theory for the Odd Or- der Theorem, Cambridge University Press, 2000.

# Exploring the Potential of AI in Education: Thoughts on “Open Book, Open AI” Examinations
Link: https://www.zinkerz.com/2023/01/27/exploring-the-potential-of-ai-in-education/

# How Will AI Change Mathematics? (Castelvecchi---March 2, 2023)
AI tools already help formulate new theories and solve problems. But they’re set to shake up maths even more.
Link: https://github.com/China-USA-Mathematics-Research-Group/ChatGPT/blob/d18bad32a48d0d2cf062f709e1bf26e4e4248673/How%20Will%20AI%20Change%20Mathematics.pdf

# CHATGPT+GeoGebra Video
Rather than generating GeoGebra code with ChatGPT, I think a more realistic use of the software is to open GeoGebra next to ChatGPT and ask ChatGPT to provide GeoGebra steps to help explain concepts. For instance, I had a very engaging time tonight asking ChatGPT to explain slope to me using GeoGebra. As I use the tool, I can't help feeling that I'm talking to a precocious child who needs help explaining. We literally need to teach ChatGPT how to talk to students ("slow down!" "One step at a time, please."). Fascinating stuff.

Youtube link: https://www.youtube.com/watch?v=n8P0SaOvKhM (loads fast, but might require VPN)

Local link: https://user-images.githubusercontent.com/124541337/223581286-c4542f9b-ab4d-47b2-85bb-ff9ff320ed99.mp4 (loads SLOWLY)

# DRAFT PROPOSAL FOR AMS REGIONAL---FRESNO, CA
Title: ChatGPT or ChatGPA? Exploring the role of AI in problem-solving and posing

In the following session, an algebraist (Zheng Yang) and a mathematics educator (Todd Edwards) explore classic recreational mathematics tasks (e.g., Lewis Carroll's Cats and Rats Problem) using ChatGPT and GeoGebra. 

As others have noted, ChatGPT is a language tool, not a computational engine. As such, ChatGPT generates genuinely interesting results when asked to solve mathematical tasks. "ChatGPT sometimes delivers insightful answers that would be a credit to an excellent Ph.D. student. Other times, however, it makes idiotic and obnoxious mistakes" (Thagard, 2023). Drawing on a vast collection of writing samples, ChatGPT relies on pattern recognition to predict what utterances are most probable. These writing samples include incorrect results that are, in turn, reflected in ChatGPT responses. 

Critics of ChatGPT (and AI, in general) point to faulty responses as evidence that ChatGPT has no place in learning classrooms. Such criticisms mistake ChatGPT as an answer generator (i.e., "ChatGPA") rather than as a learning partner---one that requires a human capable of asking useful questions in order to generate productive responses. Herein lies our challenge---First, to empower our students to ask more and better questions; and, Secondly, to help students learn how to communicate productively with the AI.

In our interactive session, we'll wrestle with these ideas as we engage ChatGPT as a learning partner. We'll ask ChatGPT to respond to audience-generated questions. We'll generate code and incorporate it in sample GeoGebra sketches. Moreover, we'll brainstorm ways to help our students learn how to communicate with AI productively, in order to build conceptual understanding of the mathematics they are studying. At the end of the session, participants will have: (1) a better understanding of ChatGPT, including its strengths and limitations; (2) a better sense of how to engage ChatGPT to generate productive output; and (3) ideas for incorporating ChatGPT with students in their own classrooms. 

# ChatGPT
This repository contains prompts for use with ChatGPT when exploring mathematics content.
We want to look for ways to use GPT and its variants to help us better understand mathematics.
